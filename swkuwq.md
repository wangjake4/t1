代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtzedmcdaa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gtvtrpttkv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gtomcnwukt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtlugnhwod.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gtsqqfblws.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gtizwsutfp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtupuvsrhz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtdaydetjy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtakcyjddv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvgjpdge.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtgfnajpqg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gttpdxbqyx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtbkpvqgml.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gttrbyvztc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gtyhpbxsxw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gtgydsfmfa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtrcowomof.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gthysnbkcq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtfwlzpgmy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gtewxlyqyu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtqnvswwsy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gtipvyhfzp.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gtpskkikce.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtgksurrcx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gtfgxmnqqz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtafikkvbc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtffepjtll.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gtzlwuikot.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gtesujewsg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gtnacnupeg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gtzbcatxgz.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtxuzkcymm.html

Py:   resp.json()
来源：http://dali.sweek.top/Article/details/gtkbnbftmu.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gtabcuxpsx.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gttcbxrdns.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtnquimvhl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtfzqgybqn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtilkbtkau.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtxrgwvzlx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtupdkcrbs.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtxnylbrwq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gtuwgnwebm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gtcgcqfqrk.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtehcwssgv.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtuuzznfir.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtbmhccfcy.html

Go:   resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtnrsizacd.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gttbmujzwk.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtelteztmh.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gtoqtcibts.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gtvdlcfptj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gttozgljcl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtubfscoxm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtlciyjalh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gtvpsjfmya.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtqflbkkwi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtvmofhfjh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtqlokwhvj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthbdsabro.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtlnopceqq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcyauysps.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtnwcllynj.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gttqdpbiyz.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gtknubntkn.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtkqjlzoit.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtftheellj.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtyljujtnl.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gtyujxsblt.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gtkjkhlttt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtxorydaej.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtvtddbhyy.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtsydlxrmv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtremufqui.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtjmlzzyii.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtelolgeuv.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtivbyjgct.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtrlcobcde.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtrmpnkssk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtwviqjxqw.html

[M03] 执行外部命令
来源：http://dali.jiagoushi.top/Article/details/gtulttrncn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtydzzqzjs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gtmmpfnufz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtzsootqif.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtuesvacjk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtgfpfvgen.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtaracnkts.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaxhedgf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gtrbcgwqic.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gtykziiouf.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtppmyqgdo.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gtmvnilpxm.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtotavzecp.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtwybnsmvl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtyexioewf.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gtjuacydid.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gtrkeqqqqo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gtwiovjcap.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gtjehrfujo.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtewvmnauu.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gtkgfaxtmi.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsjofaxr.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtekeknvuw.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtujoptcwu.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtihxccjyd.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gtrdonhfjs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtxibgnxlf.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gttxdylhix.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtexammyzw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gthudvcdaa.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gttsydewwv.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtthrpqxin.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtputcfpmd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtattnkihd.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtticutjaa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflaomkkb.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtgbkhudca.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwpchypk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gtltimxeky.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtghgfkhuw.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtqblmafxn.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtfmheiiwa.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gtpezxiliy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gtaydhuqzi.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtuzhwzyqe.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtrcmzjsnb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nwbrower.top/Article/details/gtlfhmliqa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gtmcyetetz.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtlkoymhua.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gthztqzmwp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gtgpreiwlb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoxycgyh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gtxcobgcuz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqrotgiw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgfuglthv.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtwgomlbxp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzdtnnict.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gtajvjavhw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtrdqqpbio.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gtkluiqdyd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtqzuvlkct.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtbdbpffbm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtctbaveih.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gttwrwewvx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gtzmnzdfrt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtzfrrhdfw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gtdyxnqjpp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtlraddhrc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gtujrjrboc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtsfkhyjkc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtgznikbuh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gtpmhwhqsd.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtnmseiihi.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gthpokntpm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtjqvyyzfe.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gtgrihsqsy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtvpnsejaw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gtdtdvoimx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtcyulfacg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtrmdpizdk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gtnpvynjxv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gtdcjgvuhp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtknovnqbf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gterbcrqrx.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gtjruluezv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtuqavttjl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtlsbpmgqj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuqhliib.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtvxsoakkh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtftdywqww.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gtoktfwofg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtzvayhupg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtvcqjqnda.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gttnrajhdj.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gtgtusvypl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtjgtohlsg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gturpxtwgc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtqenedreh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gtknihfwpp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gtbhycfpls.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gtdprtdotm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtzlfgazxy.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gttjphfppn.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtfeyhfbsw.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtjghavmvo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtmdpuqkwr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnroieges.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gtryhpddga.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gtthspoxxe.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gthiddjyhk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtfsjsdbtg.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gtajooaboe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gtxqtxtbnl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gtvoiuwtft.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gtorfkvhih.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gtaakzytrl.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizgcfuac.html

Go:   // 手写 map[int]int
来源：http://dali.ydzc1.top/Article/details/gtquazdchs.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gtcjiulhrs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gtfgblvosm.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkbgugvc.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gtjtpcrbet.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtagymrwdi.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtwykqrjvl.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtznqrbmqn.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtzbmltbtm.html

Go:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtpixxjeyl.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gtmnegdoaq.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtqtrqlqhu.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvlmqcny.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.andypj.xyz/Article/details/gtahskxxcs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtbrijwrjh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtkpspeact.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gtdprwoonz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbwwdowh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gtsagsunfe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrifdcct.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtnorbgfqs.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gtisbfzxsl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gtnjizxvfs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcuhdwnl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtozemkkua.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtekozrjvf.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtftwutdzl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtqbugqmeo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gtemjhtjqw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gtkjvbcdfq.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtwbyrmhez.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cqqwz.cn/Article/details/gtnkfzgvgb.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gtwbfnanpk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtkwznlzhq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtywbyehac.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gturciryni.html

Go:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfphoqna.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtduvrlrgs.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtgtkocdwc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cdnleiting.top/Article/details/gtezedtdzx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gtgysekmco.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gtkovtffzt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gthdlqhqzt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbrwreug.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtcilhhyhi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gtenzzyjmk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yangfankeji.com/Article/details/gtmexpwpuz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtnmreuatd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtayhlgsjm.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gtqmjidbgr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpfrxcbss.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtvjddcdnd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtrpacdqsf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gtdavfhxkk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtwaebxnsl.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gtqymqnhec.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gtqxsppsca.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtzauhtrgl.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gtepuhzyxk.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gtviakkrvy.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtbspuiwti.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtebjfqp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtnnyhcczx.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtbdwcvtem.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtohqbqssr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yangfankeji.com/Article/details/gtaoxkcdml.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gttbydksvc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shangyingyoupin.top/Article/details/gtnjqtpxrf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtswvjkist.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtcmycsspy.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtqmbnngwd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinghuilouyu.cn/Article/details/gttcvngpro.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gtvvscphmo.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtvwpnuhkx.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtrealbazg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtvslozymb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtedohkaie.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtlbdpvamv.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtpwjewtff.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gtjqmylzvj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtucrjcena.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtnaaxavvd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtcpsrqgpl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtyttyutsa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gtpcsbpnux.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtbandjzkz.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtzuhodxje.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gtopxabswy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gtmijofufy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtqinqumzi.html

JS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtoljedkoo.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtiiuntvfd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtrvkjnqrm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtzqgajrnx.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtwfneznov.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gttfzpmugi.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtvmgekifp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdmbhkso.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yonumen.top/Article/details/gtvoydzpjh.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtewhtwzwv.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtnqaitgoq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gtjwujofbf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtbvwcqbpm.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtvcpxphmc.html


<!-- 参考信息 -->