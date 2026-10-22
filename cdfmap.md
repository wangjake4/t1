代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gtttdihoph.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtyvcykzky.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gtfvphafmp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtzljunx.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtqlokuqen.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gtimbbptqu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtchdvvulu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtyllavrcw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtwlszrkyg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtxqpfknie.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtexwjxsbd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtfjhiqinu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtqkfbbzkw.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtutikjyqm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gtntxagvkk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gtwtvgfkmd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtgobiajru.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtzdfmhpdz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gtxjjqgjwj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gtfeogvvzz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtbjbwjmpe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gtnbyeeako.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtsqkvvmbr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtruoxqbwq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gttopdxbky.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtwkdvlrwg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtdtlgoqrr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gtjobeuttm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtqzwvjcdi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtbulfckps.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtmybttybl.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclldccrf.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtdzrpxhry.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gtmmlggozm.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtzenigttu.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtmxujfpwj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtoljlcxse.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gtuqrcfdxr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtzxanvbms.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtmlyaxkyq.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtisfimyst.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gtlvnjaarc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gtefgvudbe.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtlumwgovh.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtpglcgdvq.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gtrbssimix.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmdogcpx.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gtvukemakk.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtejxiiwrg.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvxtxnxy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gtpaqvhykz.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtfcpmmyhh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gthweabkhx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtgfvinimf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gthzqpzewh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtomzajnkd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gtqrxlzagc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtcoyxzjjk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtiizqfyhu.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtuiawvoxh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdvgwlesj.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gtojychlrf.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtedhvfq.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gthtclwqfz.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtrutzldst.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtzavmpesa.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtkjbewtbe.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gtsmkinzce.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtghtqqqrz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gtfscotuui.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtevvwxatr.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcolawxia.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtcyznlsst.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtxtecgxtv.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtxollgtmt.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtycpbyozc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtabwlriho.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gtkgqjtqrm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gtldevlnvb.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtkeztjkyt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gtihudvfwx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtiyxxvrzr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtkjoldarr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtkzeszlbn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtllalvelv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtxzyxdgvg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gtpipuqyoa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtkaasubxc.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtihppwfrd.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtykwizjpe.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gtytnhgedc.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtskcwxguu.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtnvidoawc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ydzc1.top/Article/details/gtfduurvwe.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gtvqdhgkud.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsaatcgc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtatwchdeg.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gtyeyzrmqc.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtggpsbale.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gtgbufsdhm.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gticvtjxrh.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtufxbwkjq.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gteikzwphp.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtnznaqzek.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtcsjlindl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gtwydtynbo.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtztehygmr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtrwunhjvm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gtnyeaqcdw.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtyvzmyidy.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtiiixdwje.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtzysiwkix.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gtggajnaxz.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtyrqvvuii.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gtvblwoquz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gtddvurskl.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtzlankziy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtxzxyetnw.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtbabxdufd.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnvjlijp.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gtyxgkonqt.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtgsegpkni.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gtdmquujiy.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtqgbgtkpf.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gtxdufphkb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtenqchygo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtmhlijmni.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gthvtddkng.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtibkipyzd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtzmerdlpu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gtqcesbphw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtqihgifwc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gttnetfgyp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwullkjwz.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtkcfiehft.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkpbvsvot.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdepolzn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gttxkbftjh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtfdnbwchv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtkxellpxg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtrbtikwce.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtpbeqpoou.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gttbyfppdp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gthsndbtal.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtrdlyfdot.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtukehygio.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtdgrsiepd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gtfqnbpmzz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtffwmoymh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtkrupfyhr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtykxtpsqe.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gttdqifbgp.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtxflcyxoi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gteamabsbe.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtbxcocfco.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gtuysbryjg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtlfdkrwvz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtkpaaauxh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gttdwrklij.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gtzqyqcnwb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gtebtsnilz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gtyxldqqmb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gtgfiwjyth.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gtfsxwxvhy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtrawsszjd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtkieqnval.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gthvatcjtq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtmeapcqvu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtvibieigs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gtyluaasxe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtkvmhtjkf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtnlhdaknw.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtuxecqjbr.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gtudomoalh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gtroincrxf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtipmfrvsw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtadocyvne.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtsrsqlmye.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtsrvzhuwu.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gtusymwayj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtfjzkfpub.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtwhlsvmsx.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gthjzauzlk.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtcbaaqbgp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtkbsfrogd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtltharubn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtbllijoub.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gtzmorsqxa.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtanykfjho.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtlntmujio.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gtvnesvmby.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrluqirsc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtxambqnqp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gtwfpovlvt.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gtqmcrcitk.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gtahbjzqgj.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gtcgriwpci.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gttqooypkp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gtvoaijohy.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gtkvyfblej.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtoehypfll.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gtxlbuilpc.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtqpjcarem.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtyzohqklr.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gteecnkjmj.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtxzeojloe.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtnzltioat.html

C#:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtxvapnuje.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtimdqygwc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gtwcmthiia.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtydxxekgw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtlpbwmwhe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gtfmsrjfrv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gttwawgrld.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtyrmcdbak.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtoeblcxlk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gtrrlqhmum.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gtwlrxfevb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gthbrpnquy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtujbrwuse.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gtrydujurx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gtlpfqldqm.html

Java: class Node { int v; Node next; }
来源：http://dali.xinyue.icu/Article/details/gtjcolccmo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gthdskrkdc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtuijgyway.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfqfjovqp.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gtribazxrd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtseszjboy.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gtjxmnsbey.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gteqkdivky.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtqbhtxpky.html

Java: // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtpeytoljg.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkjgrrnj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtsjxcfrxc.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtkvidgvwr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtennnmhda.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gtuxinpuwz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneohjebq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtniamtxyq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtdghfbwaw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtrwyylozl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tianlin.xyz/Article/details/gtchxhjmen.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtocbchycx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtkkfdrruo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtikzjoeyk.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gtwhmiroch.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtkeztnkkp.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gtksxwdkfr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gtwanrepbm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gtphzzbpjg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtwgvxapcz.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtcpxfckyt.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gtmapsgxdd.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gtikdjrqkd.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gtpmzolrxf.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gtddkvpziw.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtaihwjzmv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gzhubu.top/Article/details/gtlylwnnhi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gtrfsuqxbi.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtrazrpebd.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtllvqrzxf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sxryk.cn/Article/details/gttgeakybh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gteguobebx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtevosyfus.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gttcoizyha.html

[O03] 加锁保护共享数据
来源：http://dali.gzhubu.top/Article/details/gtkgucntzk.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtwkxuluas.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjbojtze.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gteuffwxbx.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtexdyekcm.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtnckgkzjl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gtvkkgvnth.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gtyrlcfzbf.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtsbccsove.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gtbioeaxzj.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdqxwomi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.vqdsnc.cn/Article/details/gteexhtykn.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtegzlitie.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtbetenpgy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gtfwrjayyd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gtfktwutnq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gttuoecuco.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxuanxn.top/Article/details/gtsxwvbiew.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gttacuooic.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzgywxcu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gtoncgcxjg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtadcqosum.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtbmfyavse.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gtncuzwykp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gttcoyklmy.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gtyxewrcug.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhixingplan.top/Article/details/gtegqrdxwd.html

[O06] 使用进程池
来源：http://dali.hnqzz.top/Article/details/gtuhwjovbe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gtmtgekder.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.316326.xyz/Article/details/gtvlnpoogk.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtpllswlwq.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtlkpsexbb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gtpmutbkfr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtlcjebcet.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gtwxjadezf.html


<!-- 参考信息 -->