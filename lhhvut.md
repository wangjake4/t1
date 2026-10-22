代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gt2gkusrukk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gt2nnelxkcj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gt2kmfoggjq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2adqqqoxs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gt2imgvmgyw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gt2sbdyrxeg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gt2poqyfqwu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2mfhyrrsg.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gt2wbafruca.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gt2cqylypxq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gt2vjopwaxl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gt2djpzvbaw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2tcybmtjd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gt2omudfday.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvnppiba.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nanruvex.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gt2vnyhybhe.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gt2oonmnqsd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gt2xlvnaytd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nyncgaiw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjduwgas.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gt2rkskiway.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gt2zmzlprhv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2abgtzalj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gt2hjhyoqlg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gt2rjwrdruf.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gt2fkfiurrb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gt2cgfycyln.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gt2atstkwph.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gt2eomabovp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2ghkzhoch.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2ddfdfxvw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gt2ywdttrqc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjecontu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2xxvknmsl.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gt2lygdxwnn.html

Py:   resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxjfzdhl.html

PHP:  json_decode($body, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xejyhxts.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsftmcn.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2actispqi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2xceduoxl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gt2hfgrunfz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gt2ulmzwmun.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gt2senahdng.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogjxomxe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gt2jtdydxui.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gt2jtrlmrqs.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gt2qqldjmfb.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2vqhywtcv.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gt2yhypiiet.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2nldirzyt.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gt2svhqdnjk.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2gyrqxrul.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2rfbhipss.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpuzzkzw.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gt2ahamvkth.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcbbqetk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2ebryfmsf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2ojxwiwwk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gt2ipdrkaiq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2xeaepdko.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2fospwxsr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2zgcnnvgh.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2oliognyl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2iregpnbe.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2lodzepey.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gt2rurjwmsm.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gt2lfsyxaks.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2cabbixpi.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2vkknrtac.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqmufpnw.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gt2wwnzcrww.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2qxyteevn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2hlzxsxyv.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2lbefnfwk.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2mxlbpaky.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2eijutczk.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gt2muntnbqd.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2vjyzbeqz.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2txthiyyn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mveitsfw.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gt2gguymyjj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2trjfpban.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2rudzoeii.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gt2zzyzceym.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gt2trpxhwsj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2pdjkpbiz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2vzfiooqb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfimcvpq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gt2bawpkgso.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gt2fbvynjsu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gt2eltvobgo.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gt2fycuevxz.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gt2fkjittoz.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gt2ctlixcjl.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2blndqhiw.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2uyzatbyb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2mdeiamhc.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gt2ablhuhsn.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gt2vjurexle.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gt2zwrsosgm.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gt2ctolerof.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2eqkizddy.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gt2hmgukrcg.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2pfjxqudl.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzszmcxi.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2kpajtnzi.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aljgwgup.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gt2alulquoq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gt2fhpzcvda.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gt2voystztz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gt2qgdxnloc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npagkudh.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gt2twnoczwj.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2cndrnhgd.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gt2vywnhqbn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gt2hmzzyciz.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gt2bdwwqqql.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gt2rgejnibu.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gt2bmkdoxzk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gt2fsfwqqzb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gt2sbbdcjxq.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gt2ypytxldz.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2uodyduob.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gt2rurdpxba.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gt2kavaiqcz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gt2udqzscgx.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2fcgdlchl.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gt2klkigjay.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gt2glailiiv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gt2esbxkbqj.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2hrroqqrr.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2nsntcblo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gt2wmyvyazg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hammf.cn/Article/details/gt2qcukizcl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cucudq.cn/Article/details/gt2yarosyum.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gt2xukrojcu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ivgczdjw.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gt2ysdhihis.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ptybwchl.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gt2lyrddibv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2lmrfoijt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2kbfgpihd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2deycqwem.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2euvfkgez.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2unonqsrw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2yjzrwvta.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gt2svbdwsmj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2yhfszyap.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gt2dtozrofo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqgnlokl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2syxdjvcm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2vkeenxxk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2swdthxsz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gt2ixbfunag.html

Go:   slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2dqlszdtr.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2kvcghzod.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjhqoawj.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gt2zxflbmlg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gt2hkqgwomh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gt2zotmtljb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2hnqtwule.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2dwstpdtp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2cpvdhmht.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gt2bdhfnnwh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gt2uaxwosar.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gt2laiussgc.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gt2hdlxhwbt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gt2oqfmxeux.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gt2uwljgueb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2lcmgmcdj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2nezdyknb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2utvewlym.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gt2ubnqfofr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gt2ksnelzjb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyfvjqki.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gt2mzffwhnk.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2mzmxbgkn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2uoqjezzh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gt2erugtvcf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2jnlxqgvp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gt2cagedfyq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gt2ylyorqks.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gt2jngqycbn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gt2cfztlpgo.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gt2nuqfkujf.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2gfaddnuo.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2ulhkantv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2jvronksu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2kcqkboqa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gt2nqjboowk.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gt2oecyseqe.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2lffqwbjm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2fsnhetyz.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbnmqdbe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gt2fttrpaco.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gt2njujtyhk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrruwfmy.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gt2vunviurv.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gt2ygdadqgq.html

Go:   // 手写 map[int]int
来源：http://dali.nanxuanxn.top/Article/details/gt2kyguqmqi.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gt2aulebirp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gt2owcapkna.html

[N08] 生成全排列
来源：http://dali.yuanzhike.top/Article/details/gt2guahicog.html

Py:   itertools.permutations(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2sveyhsxs.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gt2vvawbluu.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2ewtgshze.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2txwdsmdp.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2fvonuenu.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2jtonbmyw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gt2xvdcpmjr.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2hcsmmpot.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gt2zaqrpgbf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2jswlxqjg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2yurcacsa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2fwkfxcwc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gt2rjryvwvk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gt2tqyfdzvs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gt2jubyhwpu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2jndmsuaw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ocgpgrad.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gt2mibejudw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gt2bvytpcji.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gt2drqdkupz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gt2obvervqg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2yahbomty.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mhfcotwr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gt2ouzoabnn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gt2hzvwbvdl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gt2dunurlfy.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gt2oisussvu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gt2ahijulao.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gt2afwttpdn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gt2qxxylfae.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2zhgqsfqx.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2vjrepbtk.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2renumrwo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gt2bvhudrai.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdewagru.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzvgoqiv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gt2ocpcfkqk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gt2bycuyghr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2mgsoodzs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gt2bwixjpyp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gt2zwjqhuud.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gt2ulurxmhs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tianlin.xyz/Article/details/gt2dejhupca.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2amdwvaed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fesncgwd.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gt2kuzbmnsg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsxhcdiv.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gt2byvgefhf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2dnrsqhmi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.c1oappe.top/Article/details/gt2nlsigwfx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gt2syjhrbzy.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2aqnoojxo.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gt2rncslzlw.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gt2imdcizts.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kuaqzzvi.html

C#:   Task.Run(() => F());
来源：http://dali.havefunace.top/Article/details/gt2llkbsgyv.html

[O02] 使用线程池
来源：http://dali.havefunace.top/Article/details/gt2sbamdckd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gt2vznjukxo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sqescach.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2eimkbrpr.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gt2uqokqnto.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sweek.top/Article/details/gt2wngyzsme.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gt2ygtfwwyv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gt2jmbkapva.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gt2optrprvb.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gt2xhcxwhgt.html

Py:   with lock: shared += 1
来源：http://dali.zhengqikj.top/Article/details/gt2cfpyhhjb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gt2nwigtopy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gt2vwaklwsj.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnempcwf.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2wikggpqr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrqswvcb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.redwolf501.top/Article/details/gt2mreibocs.html

C#:   lock (gate) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gt2rrfbabal.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gt2ihabiyvz.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gt2irxtajjj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gt2xxvlytxe.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ejdvempa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ashaipob.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gt2robbpptq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmgdeywl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gt2djoevcwa.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gt2mqhtxmwj.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gt2ndzaptnt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gt2jytdlulc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gt2xkrgvhzb.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gt2esgizpte.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gt2kivvnfkv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gt2gfszokmj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpomdthk.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lplinupz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258888.top/Article/details/gt2oyponhrd.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gt2xakgwkox.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gt2wdnmbfrq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gt2fsbksnjn.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2kzwoqeav.html


<!-- 参考信息 -->