代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsoexjenu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gtswfayxph.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtdslwtnqi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtyzseyixq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtnxswlsye.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtizteojmt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gtyxyfufhf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gtwywgckqp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtzdurniha.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtnuerkqcq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtgwdghcon.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gterlpoltp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtkqitqioi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gtpvptpjkh.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtlvclhgpi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpdrgnsq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gtvjehkpzx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtsfuwtaus.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtwacpcgmn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gttecvilva.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gtaszieqjn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gtekzvkskm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gttemsazfm.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gtnckmeqqs.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtdorybpvu.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gtardmvgcy.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtiqewroge.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtpiacdzjp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gttqzvxsio.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gtryslmush.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtlvllvnyo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtodsfqkjv.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtibtzsdpm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtnpljhjhd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtzbzmcwkf.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtidtnttvm.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtlgzjzkey.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gthrwymvao.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtffsaukpc.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gtfjowvqab.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtesehlizp.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtaikppgcr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtytomvpzk.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtfgxqqsbn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtkgxredjr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtmihgieuz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoflmlyf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtvvwrjjzm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gthgejqzvv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtcyzgvngg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtajnjnnow.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtehqdqgyy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtvzxsityd.html

[M01] 读取命令行参数
来源：http://dali.hammf.cn/Article/details/gtqffdriat.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gtiqacdyqh.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gtrnghoxsq.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtdknkooke.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtyndipiuy.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gthdovdefd.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gttsofoxud.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gtojckswgf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtdwpgrpcl.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtipzqrupd.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgegctqs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtkxfpgxoh.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gttpjyfjky.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtappvhtvh.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtsudkhcgg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtaoabsysm.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gtjorxqxfb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtknvyceoe.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtbfgoezrg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gtdfdwpbfy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtztqxeqte.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtkmsebmzq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtsdvcmzwx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gtxpyxuvxi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtqrzxrcvw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gtdwxfnwld.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzqgfngt.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gtrrsaismg.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtgebgbzii.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtiwklkopf.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gttcczktjv.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtkdgzdpaa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtkjboovyh.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gteonksppr.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtxaehbwyf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.quarkkingdee.top/Article/details/gteiguulik.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gteypeuugi.html

Py:   sys.exit(1)
来源：http://dali.mhx1999.top/Article/details/gthviieuvd.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gtapsehhjs.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtbwdydmru.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtooxxjdco.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtbmkbiffz.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbiwzrrqf.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gtwgjjekwa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gtodnyqfus.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtswkplkmu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtwbvgxwbu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gttzswzytu.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtjgnwupzj.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsdlsiee.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtmtddkfun.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gtyniwiehw.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtronrwrsc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ybcxt.top/Article/details/gtarrgnbhs.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gtuxnvjjvv.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtfrnofjml.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gtjrzieore.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtvjugswva.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtayluzbvc.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gtimedetak.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gtuqodtmmx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtuurjlxxy.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gtzpvcujpp.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtdrcbogjs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gttkutnsgw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gthpcjbuue.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtoihvgios.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtnkoouseh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtpffaivzl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gtkzokkxmr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gtzqojcemt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtpeimveqe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttziltwln.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtfgcbycrp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzikmgovh.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtuxrhjqzm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtxpmlgozv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtbjhdobuf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtrcbusyke.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtryujjmyi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtbzmihoob.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtaezbhcnm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gtmrrobxoq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gteprhkacv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gtedlirybh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtucrbufsi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gtpcqazlwp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtywlhdkox.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtmbbewiwg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtxlfmjedx.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtdhxtlsot.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtncxcmxuo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenlongwang.top/Article/details/gtxvqtflbg.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gthcvzvect.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtowkcnhcd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtthxawelq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtgxehbqxk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtdrdqqnlu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gtilgwzaql.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtvzjmrwfm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtpcujylpy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gtnxrormrq.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gttfzuhswb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtoliozaix.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtlxeofkpx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtqbafgtju.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtdemcngmm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtfpybfjew.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shangyingyoupin.top/Article/details/gtxjkhdval.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtvkcxjqse.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtepfiidto.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gtpzzlmbub.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gthntiunpm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtoeveggoe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtuxoonkeg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtrsscmymd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gthtudhpbm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hywenlv.cn/Article/details/gtzsbwwxwb.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gtipdtapzl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gtzlqknqmj.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gtzitrwaja.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtaezpzpyh.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqspuapy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gttxmpirmu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtjcrqazwq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gtgxglvwlh.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtxltbpuby.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtcmszhepx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtrrkbbaxw.html

[N07] 两数之和（返回下标）
来源：http://dali.zycfv.cn/Article/details/gtkboudnri.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtnpbpiwvy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gtaauusphq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtqvfwjfgl.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfupuqpm.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gtiqoqbvdz.html

Go:   // 手写 map[int]int
来源：http://dali.yuxming.cn/Article/details/gtdeuhsjpq.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gtgkqpzfaj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gtoxbwwakn.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gtqtiuxquh.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gtowmiffnx.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gtswwmatwu.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtnszyqgsd.html

TS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtusbkzlql.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtdaojvegm.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtieuczjwz.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtlsqzzpgh.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtcvkcblqp.html

[N09] 栈与队列
来源：http://dali.sufxvd.cn/Article/details/gttlzgfhjo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtxwuqwugt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.mhx1999.top/Article/details/gthqwmmcyu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkixsukdu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtqoutmprx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gtblmqtgja.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gtassbykcn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtymbexyyu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gtqavojdjx.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gttrerpwbl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gtqpcxlzce.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shzxlz.cn/Article/details/gtnwkqkfll.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtltkmwhxm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmuasvwj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gtsllcozss.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtzrjzsspk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtosqfoyck.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtchftmtua.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gtpbunsrgk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gtgaqugfxa.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gtudcdxaik.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtumvimdbh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gticqpplcd.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtwixejfjz.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyoecaiys.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gtahoawjsi.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtndlqljtw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gtvastfyct.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtlgfnymmy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gtocooddmu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslwerleg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtkkryokww.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtbredycnn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gtgfnakzqv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtbynkwfle.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtmudhkwrj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtyahcqoon.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gtcwbogrqk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtompcoklz.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gttycuizlg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtlbuxpczq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gtyatpdnzf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gtvdawslfk.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtepyaskqf.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gtqklsbbbv.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtohewbohc.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gtukgyjwyp.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gteqhqutwu.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtvgysompw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywxcdjkq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gtvygplusd.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtdeurmdcq.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtcpfcpgym.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gtfcperzve.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.quarkkingdee.top/Article/details/gtjjystaee.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtbicvkgmn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtjntpqaju.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gtowduypsy.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gtwyvemrwf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gthmbeeqwg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtwlsgudif.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzpwlgis.html

Java: synchronized (this) { shared++; }
来源：http://dali.cashguo.top/Article/details/gtztbkkldq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gtjhklrlag.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtlnpjlsvu.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmeieloh.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gtpwhrgmyu.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtnvlwvwii.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gtehlsqcxc.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtisecsgxo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtlghraxor.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtzeaduiey.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gtktilgwis.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtglminfuc.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gtqbmloyyn.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gtpkfhhwnq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gtkbhclcpq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtuwscwyrx.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtnekmxlrl.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtgbubkpel.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dashuyun.cn/Article/details/gtnahxtdqv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtepdmxtqj.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtcixjsc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtacgjtsqz.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gtgyxkakfz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gtgsatyeow.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gtliugzslu.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtmsmlqcip.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgjpcdst.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfxgvetu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtjglobhco.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gtyvrcnhcf.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gtamzschwo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxtovledk.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gthyhsrpat.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzrohnvsc.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtkysnmczx.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gtywrxaywa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gtscgxacmy.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtxcuoqfwi.html


<!-- 参考信息 -->