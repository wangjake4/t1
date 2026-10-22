代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gt2ayvxknhu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gt2yihjjwku.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2xduqdjpc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2rjdqainm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gt2sfpuvfnr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gt2asowyvvt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gt2pizxmxwh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gt2ksyguyji.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gt2brcnenin.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gt2yjudcxrc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gt2bwkdtyqf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gt2zxvltzzv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2ynnjopof.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gt2pzoodasn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gt2dvavvvpg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gt2phwzpybt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2jibrgirw.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gt2baqmcgpe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gt2sylxiktj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gt2akxlzrtb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2vidmgmyd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gt2sctfdgof.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2svxncatr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gt2tlgszxjk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xizsrvbc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gt2hunjkxam.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gt2lurycsnn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gt2rqghlyit.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gt2geseearg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqxkggtx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdkclxwe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gt2fkyynqgm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gt2wvbfbyuy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gt2sjhwsvhv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2slrhnlmd.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gt2qaupeqrl.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2lskqxpfr.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gt2wcrtspfd.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2nooohiig.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2xsuphbeq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2ibwntrey.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gzhubu.top/Article/details/gt2kbdjiaqx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pghegyob.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gt2wmzlxlbt.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gt2dmxbwmkt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gt2yhhcvkph.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gt2pcigzkbn.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gt2qdpvqdpp.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gt2mhtervuo.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gt2gaqjqmow.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gt2nztiffdo.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gt2afwhmlkw.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2eusswevh.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gt2hfjsxmun.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gt2jggsfqyv.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gt2pmvmqgsa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2fwtdpcaw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2wgyflaqe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gt2dqqrdbhz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gt2jxoqkxhw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2hbelqnxi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuxming.cn/Article/details/gt2vzcdears.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2xbxktflw.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gt2qziodoem.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rpnotcvs.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2fnhoxylw.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbbmjbck.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gt2qnqygwwm.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2xxvpjxem.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2mudnmkpv.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gt2zxcqynyq.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gt2ubdyktws.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gt2pdpepvga.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2zhbphfdi.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gt2ukzmzwdv.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gt2rhcwiwfm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2gsnyudhg.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gt2kbaclgyk.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2rmziymqa.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2qqjcqwcl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2dkqwbhca.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gt2ocycnbdy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2ywgvrajj.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2zkyfdddz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2aiphmjui.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gt2hitxwafj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvsopidt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2ggpwdfgj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvsqdkka.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gt2nydvzckb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gt2udwbqfjo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gt2uepopopr.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gt2qwnyuzcu.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gt2zbbavvrh.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gt2vqledljy.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2xsjclehj.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohtjbrzq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emlvfpvj.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gt2fymagpai.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2vjvntkeu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gt2bfnhkswh.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gt2atmtyota.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2rhxtyuzi.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gt2ryzuymsi.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qozaffrp.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2sssvoyoo.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2wqphrcdi.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2bwhruixt.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgzroia.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gt2gajzegia.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gt2awgtlmce.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjsihvzz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gt2qxgnpmvt.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2arwyxbao.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2rxklwazr.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2lenhmvil.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2ijgzrrvj.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gt2bntffjya.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gt2zcdiuzhm.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gt2rmvvutwj.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gt2ojvozkvu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gt2pllrbouv.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2mdhwfqqc.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2gzkvvcsi.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gt2mueijwsy.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gt2lwsqvdyi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gt2lhejexoy.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2qrrulaxb.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gt2hfakbram.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cdnleiting.top/Article/details/gt2rrffoccq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gt2dvmjiikn.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhbvivai.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gt2sjisfcgl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gt2mcmfxfre.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gt2gwcuatyn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gt2wjenpaiu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gt2dviofgam.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2mosljgdt.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gt2neuxfcqw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2zdbgcoin.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gt2crhngrqv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkszsicb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2zyqyxykd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2ijkgokug.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aolpyzwe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2rrlsyjdo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2mofnatxh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gt2tudekbqv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2thbbulxc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gt2rdtnxopt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2kudfdtwq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igelwuyz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2xkewgcjz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2jkyjepyy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gt2wlhkpbsa.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gt2bgdvqfju.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2yukbtsly.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2gcwxgofv.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gt2cotfjose.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gt2xvhzubmd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gt2gljogsif.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2weovqyjy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxacveze.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2ppakxugb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gt2epcvkdlp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gt2evfwllge.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gt2dqadnzms.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gt2hotggvna.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2kzczdwvj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezfhhdcg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2khskuyoy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2vfdtmoua.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ggsxhgiv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gt2rnqvbjak.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gt2ruxdhwvj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqldfstp.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gt2vtqfnqmj.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2ysaxjnbt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2gvrtjusv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gt2gubfqujv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2cytoivjd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gt2pmvqwdju.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gt2kwywebny.html

Ruby: a.gcd(b)
来源：http://dali.dashuyun.cn/Article/details/gt2sifqlheg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khmzgcrb.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gt2ozrpwkgv.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gt2qiioexqn.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdudepnd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2xuwdwiqg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sluvatxw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gt2bhhfyznv.html

Go:   // 双指针从两端比较
来源：http://dali.wangdashe.top/Article/details/gt2dnuaebdy.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhwcdkwy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gt2yotjsooo.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gt2moelkneq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gt2xdsweufq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gt2fbobjyys.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gt2pmcgwvgq.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gt2cfxbayuv.html

Java: // 手写 HashMap
来源：http://dali.quarkkingdee.top/Article/details/gt2tpsrvper.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gt2yghgcrqe.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gt2setacpnv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gogol.net.cn/Article/details/gt2qiikmzul.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gt2utzylwfv.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2zpbfurno.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gt2dskhizgp.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2pnyziyuq.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2pauncccp.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2brkfgnyd.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2uhjwhkwn.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gt2qxomhtvq.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2bpsqozay.html

[N09] 栈与队列
来源：http://dali.tianlin.xyz/Article/details/gt2wirmqjfw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2ayvwbajm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsfqowfz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2rsbfpfkt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gt2kxfuumev.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxsljmvl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gt2vaiyvyfr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2fyqihruc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.havefunace.top/Article/details/gt2cydjydyv.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gt2qxdqlcat.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gt2dnihytly.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daxiang520.top/Article/details/gt2knnnpynx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukrozhis.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gt2ldbwhslj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqevyvfy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gt2uoyycxhd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gt2ruhjhdgq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gt2cehfdbra.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gt2thirrpyh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gt2edhkehsr.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gt2pmdifbtk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gt2ntvxjabb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gt2mzupixwd.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gt2afeagmnd.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2jzrxuqhm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gt2hbezgqfx.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2myyagbqc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gt2qwquglbr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gt2mwvzkesy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gt2boltbjex.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gt2odusvsov.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtktcuio.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gt2jwhzzpah.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tianlin.xyz/Article/details/gt2havoqnly.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2ykdxijvb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gt2pqpkqncv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2gooruwpa.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whpitosu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2xldotejn.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gt2ylayvhqy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gt2aigiczwk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gt2vdcpmoyp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gt2cgvveftt.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2wxpljexx.html

Java: new Thread(() -> f()).start()
来源：http://dali.birdmap.top/Article/details/gt2uumyhhzb.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gt2vkxcpsjf.html

Ruby: Thread.new { f }
来源：http://dali.tianlin.xyz/Article/details/gt2ojkyjjcm.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gt2jbjacqrj.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gt2jzymsjgx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gt2pmfddkdr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gt2tccjwmev.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gt2qsvqfkyb.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gt2cklclpnc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2drljlsnu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gt2khblsohs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gt2ifgfoikd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gt2swghdlfs.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gt2pqhwhgdx.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gt2lecgjvfd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqflcxvz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gt2zpnqezzw.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2fophaymq.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtpsayit.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gt2sgeshvmh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gt2hczptgvn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sehvhysy.html

[O04] 定义异步函数并等待
来源：http://dali.hammf.cn/Article/details/gt2dfmilltu.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gt2jbwfcmnl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gt2gwjdwrtv.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2gecdliin.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2mxmwfvfk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gt2tvmvtofo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gt2dhsstgqc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gt2zutrtber.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gt2kxyspwar.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gt2rohibare.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gt2fpeuqqgy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gt2rlrtlqvm.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2elxoarny.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gt2gqilabcu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gt2dkxqbore.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aedjoogr.html

Ruby: threads.map(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rygzulxw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gt2mlqcatal.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gt2ttcqnhxf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cheryme.top/Article/details/gt2zfxbonbz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xinyue.icu/Article/details/gt2jmjkqqnz.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2nbnswtbk.html


<!-- 参考信息 -->