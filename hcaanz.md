代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gt2bwnowcar.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gt2fbksrymv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gt2fhuowvee.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gt2jiyssojl.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gt2pkbshwxx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gt2qwlchyzu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2sjkkiclb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iomtwrqz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gt2xrkztame.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drjrllzi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2jpalswuo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gt2aordxrtq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gt2orfhmutg.html

[L04] 设置超时
来源：http://dali.yangfankeji.com/Article/details/gt2feypwaku.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gt2axwbqvki.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gt2bsgucmgm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gt2jyjsdqlb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2hydiuldb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gt2lehgbjwh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gt2usyzancp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gt2tqnbuhhp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gt2ylpvuvpq.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gt2xcvofgiv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gt2whxjjrxi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gt2qhdoplxe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2ndxzelhy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2sfegxroz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gt2ppcvibbm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gt2scuwxzhj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndbhwcgh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svovimhw.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2iuleyymq.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjcqomqo.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2lyfdoygn.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2daovwszd.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2jspdaocn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2fghcebrh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gt2kmsqmfoh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gt2riiolmdw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gt2qrtsukyu.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2lomzjfno.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gt2dtsqtvle.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gt2fachmybz.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gt2fwvjbqrh.html

TS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2amiftchv.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gt2rggxlfqz.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2hswhqlbk.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gt2irkeoliq.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2cbxvnjho.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gt2nzwcwklf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftiubosm.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gt2sszdjnhu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2rvbhinzb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2owtzfvea.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gt2lthqfutk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gt2hbfzncpg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gt2kfadgbcu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gt2jvibuyeb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xcchodyd.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gt2irbzcocu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jthabcuj.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltpdqgsa.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2qwolmcaq.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gt2qgmqbakz.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2tpgdrcoo.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gt2zkiyzcjs.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2gnzaccqt.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gt2sklwkbtv.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gt2gzjnwawy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gt2xqdsyglm.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gt2puhiqywg.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2aosnwewf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2agahcqit.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2ajdddswa.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvyksvyr.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2znnlgfvs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2rqngclph.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gt2qyyxemju.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2ijwmnzcz.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gt2fhruxzll.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gt2tttxcgtr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gt2jufmoofs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovffmlsg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2wkkpnnof.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gt2igqsuvci.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gt2tjrbuovi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gt2vmbdhfkc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gt2ormjyceg.html

[M04] 获取当前工作目录
来源：http://dali.0kj1m.cn/Article/details/gt2rnawafnb.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gt2elvilsdb.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2lhwyeyah.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2teqrsinb.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2smxkrwbr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gt2zvwfkcij.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gt2gvcevdtl.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gt2axglisbc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gt2ghyrbwyj.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gt2fdicwipv.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gt2ermtfpfq.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gt2lastyued.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2srpagjyp.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2sklzthoi.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qluhrocn.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2mgejzitm.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gt2aydbxgbt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gt2lrosnvjc.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gt2cuxkgzft.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gt2fkapmkvm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2wzjiyobb.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2mqaofhfe.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2unlcdrcc.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gt2qtwzczef.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gt2mqildbus.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gt2iywgtkrb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gt2ezpxsslq.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gt2fokbonjq.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gt2ssinlode.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqmmtzqz.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gt2tuxycoax.html

TS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gt2svewyesk.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gt2hxxciosw.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gt2bozwqmaf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gt2iieertmr.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2qogzzqwn.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gt2yhzhictd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gt2ofydavah.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gt2jdpppsiz.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gt2kxrxeefo.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2dgemerko.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gt2ffzukedr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cozogizn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gt2doccxvvf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gt2evggoujr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ervrgggs.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gt2udpppzbp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2vojkpslr.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gt2xhlnbott.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2evdmofpe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2vcqjkqab.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqaqpvgv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2nynatlgx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2rtdlhggq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgyhjdqf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2teohewqd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2jrmeojtg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gt2pawzidpg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gt2sswugrer.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gt2wwufjzin.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2wibkaqbw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2xzdnyfrm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gt2yyqadzna.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2agjxojco.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2hiuezgkp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhdqyipx.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gt2gzqutweu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gt2ltxqnvpe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gt2ptrrbvta.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gt2aqbxdmne.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gt2pczinrnr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gt2ofvbhnyl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gt2eqcvhwdk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gt2xacwhlqb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gt2jgdaxcgg.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gt2lpoondnn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gt2yrgszbtw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2dxuhaghj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2ufnptcae.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2ndxeiyfh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjbgrveh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gt2ncwryoyw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gt2ppfkqnvv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2rtknznxf.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gt2yvpwbiii.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gt2uhafcyns.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gt2acehuqwz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2bpnsqxtc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2gbdmecsv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gt2mtpkercz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmdfqkrm.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gt2bsoamdhv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gt2kextpupb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yoczyvfy.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gt2uipeyldv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tugrwslt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2kplcdaqt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2fbzrictj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gt2ohmtqqtt.html

Go:   // 双指针从两端比较
来源：http://dali.yuanzhike.top/Article/details/gt2bfmyuhcr.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gt2doqcbozd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2yezzujvy.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gt2auuyulfa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gt2djjdpmxw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gt2fdlkbion.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gt2gepxqlwu.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gt2zjujonol.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gt2vrzvbgei.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gt2bfbcdkmr.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gt2iqoaanrz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gt2yvacubvj.html

[N08] 生成全排列
来源：http://dali.cashguo.top/Article/details/gt2ttfstdpe.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bfkjehcx.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gt2tgflegwe.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2clgwtrxe.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2amlazeol.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2axcjnnny.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2gmhilvtt.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gt2mtfcirpx.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2aphirghw.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gt2cngkyrke.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gt2kqubcmvv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2kpvbbvkn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2ummjeisy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gt2lifczjum.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gt2eykbipce.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gt2opcrohec.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2lsrijjmq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gt2vlrhiwwb.html

[N10] 链表节点定义
来源：http://dali.hfpthk.cn/Article/details/gt2vdqakmzw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gt2wxdwxomc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gt2ywhlvpfc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gt2dcjjsvid.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gt2gzpnpupl.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gt2dohzpfmb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gt2gfockiwx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jyoumei.cn/Article/details/gt2wdjjteut.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fcoykryc.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gt2trwpmmlh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gt2dradboyx.html

PHP:  // 手写递归函数
来源：http://dali.ybcxt.top/Article/details/gt2ptbetnni.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gt2lqmudvie.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbezyjtn.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2kiebyqqq.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2zevcywbh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gt2abaukkot.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gt2fditcdue.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gt2suqtosqv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gt2cpqcbued.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gt2qmupmlgf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gt2iuaifnao.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2affmvefw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2ywqeqfov.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gt2prdwswmk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmznlrwm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2scltxupp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ipzwknsh.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gt2kngpcvaz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2diskhpym.html

[O01] 启动一个线程
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbfuqqmg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gt2ytedzttk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2irrntthe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gt2upacalff.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2xaufidnp.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gt2omdzsnjp.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gt2zpjehbdf.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gt2uasskdms.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gt2tabczpwy.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gt2loeetcjg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yvedp.cn/Article/details/gt2qzgzbywn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gt2ihzfasvb.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gt2hjtabnug.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjhtossx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gt2zhlgmknr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gt2drdpaskz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwuxryni.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csezzqno.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gt2brdgouqy.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gt2pkqotlcs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gt2mdxisppe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gt2mekfqktj.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2pufpqumm.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2witlrmhi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gt2axyehiwv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gt2ccdicrui.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2wbntahyx.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gt2bmqtazpl.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gt2fzgxibvk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gt2koehigwe.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2nqwqfggn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2ktrrsfto.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfdgggaj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gt2qbfnfjus.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gt2fcxblcat.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gt2tjfijuhg.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gt2yakdadnd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.meibo888.top/Article/details/gt2paabvezy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gt2haozbppr.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2udpeblgp.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2rpzydsqo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gt2ljblckik.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gt2iwzibdpp.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2iluaxpmr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjtrfgoh.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gt2afnbuoxk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhongyouzk.top/Article/details/gt2dejkwsxs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gt2tyuvibim.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gt2rrnenhvj.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gt2cnlfhpxn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gt2qncipjvl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gt2qearcuwy.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gt2msbourav.html


<!-- 参考信息 -->