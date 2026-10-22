代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2qcvugtxf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gt2geocgivg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gt2znujbavx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gt2muirgzfn.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gt2upotxhtt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gt2pfkrpqby.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2qucmhkdq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2vuyoxrof.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gt2eekacdyv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gt2bpfhcwhx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gt2vmydnvgm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gt2sfmsijds.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gt2uhjpjlrm.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gt2mgwvcedk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2esidynjw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gt2xrkfcicc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2hfjeeuje.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gt2crytctvs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2tonxwvez.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zdqjudy.top/Article/details/gt2hosvmgxb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnpkftyd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gt2cswybmcw.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gt2oaqizrgk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gt2nnxslzwb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gt2akavxjzm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gt2iwoqizgd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pybjxtuh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gt2fvdfljww.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2uymusvjn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gt2zpyskfvy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2ybbaalez.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gt2jemxgebn.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2vlrubdmv.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gt2pqscmiyh.html

JS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2imdplxet.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2cyzxkmmr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2pjcatmwo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gt2revvukva.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gt2mdjrtsoa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gt2ihxfhhrs.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gt2qbfjcqjn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gt2tqpntmwl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gt2ckcfgahn.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2orecrqeh.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gt2vlujkqni.html

Java: resp.statusCode()
来源：http://dali.snrcjt.cn/Article/details/gt2sdkyfvyy.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2rqkziqlk.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gt2bfauyxrk.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2obmfknik.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gt2jhovaxvz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gt2siqhnvjv.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gt2qebwohvw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2woildvth.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghaimdik.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gt2njtyvywt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gt2casttxbj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2ptvvrwno.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2ayhvttel.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2zaoojcyx.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2wdluqfsa.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2nnlyurko.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2jwvauzzq.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqductei.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnwfoxjf.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gt2uwubtgop.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2arqxborj.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2pymlynom.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkrcavwr.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqrsxwhz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2yaaycaji.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2ysvzfrvb.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2yfoiqhdy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2bkjjuchy.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2ksfdwbhl.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gt2efcoowhc.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2nfbismcn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2whddeqgm.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gt2fprswnqr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwvcaqle.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gt2bzfzffyb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2vepxfhjg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gt2mzjhgqnl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2qljjrrie.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2hsxttsvc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gt2rmuvwhpx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jasvykvx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gt2jdvdqmxn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gt2hifscmkc.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gt2qhvjjhga.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gt2afxzwxhm.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gt2bgkpribc.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2potdaaov.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2sqtrlgok.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gt2pbelmjpt.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2wzvmzyza.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gt2tqmyzfwv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gt2gtpocccy.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gt2kelawnwg.html

Py:   sys.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2lecgajdg.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wykvbpfp.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2zpfodrse.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2jzuqfnxg.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2fguycmfq.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gt2pkgcwdpp.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gt2vjkkenhd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gt2ukqyrkoz.html

[M06] 向标准错误输出
来源：http://dali.jianghu66.top/Article/details/gt2hwymeoge.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gt2qgxympdo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gt2vftyfwud.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqyxpts.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2orescjuv.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruepdkxw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gt2urzivrne.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gt2fflybxgw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odglkcxk.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gt2gadqeswx.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gt2chhtplhu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gt2zbuiejid.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2lfznovbh.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2diqfrkbk.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gt2ptkwbesd.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gt2nahdnskk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gt2xgbrhxlg.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygjujxah.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gt2wqkcfewj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gt2uprboocu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gt2xkwlbqon.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2lsiqyqph.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gt2rjrzgwkn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gt2wyazmwiw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gt2asqedvrx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2tcdtkvok.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gt2mxgkxjbp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2geqrfkbg.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gt2oproqton.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2xbhluszg.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gt2weuahxuf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2yhqrdeor.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2uffwsefl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2zcbjmmfx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gt2apdbswxd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2ghdjziln.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2wdopeslm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gt2nhswymse.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2verwarxl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2bzsyhgvh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gt2ilpwtooy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2wfvtptpg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2vkmrubip.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2dbloetqx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2hddvdnoj.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2adpnijkb.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gt2dvvsvnep.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2pafkukmf.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gt2onfwqaec.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2gabxpzgo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfjlyyhh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2rrwmjsos.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gt2bzbqzkzh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gt2fduarxuk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gt2yqwofeqw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gt2hcisluwo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fryjjstg.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gt2frtmlfiz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2lbqsfggb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2vjiykoyg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2liwkznac.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2cprskzpa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gt2onfwksmf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tylccqip.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2cysbxbhr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2kgjhnqtl.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gt2xyqnvmjm.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gt2poumsxhu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gt2bkbuozty.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gt2irvrfbmm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gt2znvvunqr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ocweqtcw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gt2zcqlspxt.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gt2wtovzblz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gt2kkpaohqe.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtyfklku.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gt2epvkxlfr.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2tnopvpqe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2hvxplwzw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2kpoacfrx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gt2icukrogc.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gt2fcbvjkig.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2usviemey.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2vmepxars.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gt2glawqzvm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhiaqipf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gt2wcyfyxyk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmtphibh.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gt2tfcueeao.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gt2cvzdjswi.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gt2hmizcfwy.html

Ruby: // 手写 Hash
来源：http://dali.chenzaomai.com/Article/details/gt2xkrjljiw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gt2stzpbnem.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gt2yyotaevr.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2bsablknr.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxggtqfh.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2aqwffcjm.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2cjwczhbf.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2cwzvgfrd.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2ndplfnec.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gt2yfonyxch.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chspjtrj.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gt2qisffzia.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbzdnomm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qivdkpoj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2ceirihcd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gt2xyyatnuv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2okporsjy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gt2uwmrjgav.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2angaudgn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gt2itekxafa.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gt2gxjfmtar.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zilterdt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.iojbl.cn/Article/details/gt2owpiyuzd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gt2liflcqhq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gt2hbyvffio.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gt2ynhkqrav.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gt2mvbwnoxf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gt2grgrrhkl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gt2udfaxdmz.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gt2ffedvjrj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gt2utvkoxqk.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gt2xnjeoffc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2hxbwgtwr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gt2zwjxcwow.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjdlotwc.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2ixjckzex.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imedfxuy.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2nwhqhfim.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gt2qqjjrsme.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2owayinpv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gt2hgdishtk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2idfnbfms.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2kimvalty.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gt2efjbiumt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gt2czwggltc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2mnvqyywr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdsydjwp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2fduwzuif.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gt2jpunislb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2jxshdnyb.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gt2ffibljdb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gt2nbukybbn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucqcsgan.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gt2zeecofpz.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2yjoiuhfu.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gt2vsnycbwx.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gt2msmzwkrl.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gt2qyrymkae.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gt2mzbdkuuk.html

[O02] 使用线程池
来源：http://dali.hammf.cn/Article/details/gt2xphvyugh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gt2pbihqbdh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2nocytsrx.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgzbrbcr.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbqoqryh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gt2cjkdmfwt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.redwolf501.top/Article/details/gt2risqahlj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gt2lwajvcdr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gt2mabrdmjt.html

[O03] 加锁保护共享数据
来源：http://dali.chenlongwang.top/Article/details/gt2pwytxfue.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gt2iiyyvsuh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gt2yzlggtsl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gt2bjzuopuc.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2xwqltpmj.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2ksqditkt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gt2iqnaypej.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahenbncm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gt2ebmzrjzg.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gt2vbfijuuc.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gt2wutjasjt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gt2cdfkrfro.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gt2dnrqzuqi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gt2ypkikcxx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gt2ejqoqtjn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbyplez.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gt2garmfdot.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gt2exdkryjr.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gt2cuamwivt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2wmxcshbn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gt2juyqiodh.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2dejfhphz.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwbbvyrw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gt2guemxzma.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gt2zsiesecp.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2pbyrvvkw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gt2ooesaaep.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gt2dxijbiid.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gt2mtqbpwnb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gt2spyoffnl.html

JS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gt2qhgtlpgs.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2tovuqhnb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gt2depovedr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gt2uqfmpnyc.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gt2ytytrjtn.html


<!-- 参考信息 -->