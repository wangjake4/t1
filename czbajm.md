代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtyolimozh.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygrueftf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfgqdehc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gtzupqttki.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtiwljlgjt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtzvusgthd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gtzazckydj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgufenzy.top/Article/details/gtxyjwscgd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gtikzusizp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtmvfwhycc.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gtdjziexkw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtupkcvcrb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtjtrmguwx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtanngjihw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtjqjzsotw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gttgprtmrk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gtmimmxhsk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gtuuvfbvgo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtnkcpsvba.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gtsacrdeoy.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gtjcdlnabe.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gtujlsbrah.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtujggenyh.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtwgkjzzxp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwcrvshq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gtdrallsvd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gtcsmfiazg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gtykbtfsbu.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtmvrohrmu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtzvbjhslb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtfengwgdf.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtasxmgijp.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtiyyerwla.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gtskkytpnl.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtkiwxjfzr.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gtnthtloaw.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtpakcpulv.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gtprstkkef.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gtjxuizecd.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gtdtojdhvl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtrhzzqvqk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtxhwxrkug.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtdmiauwfi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtzczyqalj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gtjkykbemg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtmrlerwfp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrbprzimy.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gtygvhbhui.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmefxnbku.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtmpzjbceq.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtozfdcrot.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtovszomhu.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtbdozaheq.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxplxxhs.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtjqgmlslu.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtqukcsxkp.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyovxbgll.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtcrlapjnq.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtretodbxk.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gttjdroogn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtldlktdol.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtbzowvnjc.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtrzxqjfqp.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtstifkyps.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtyhesufsh.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtipktbtkr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gtcpgoosjo.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gtbgidqctv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjozxtbw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtjmexqcmk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtdlrvwdxd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtemjnbjcz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtcoktwmip.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdttbbjzh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gtydhcjbjt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtsvnmvdds.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtbhzrzwmn.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gtzajaosfv.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtvtszmdab.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhosgevg.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtmzafjbpc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtpveqktiz.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtjxceqchl.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtpqvhebnu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtfxngnofk.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmukrfqw.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtkroxoosu.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtdllklsby.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtygffjnpm.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtdjwxborb.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtuwktoxjo.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtetaosojs.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtdkvbfyla.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gtoxwfhzmy.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gthwbuottf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtpojrvdot.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gtcyqwmkdq.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtdywcbxpd.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtdebghhtk.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gtixihbxov.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gtclktekjw.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gteotvczya.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtvyhysaya.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gtrglrtnrd.html

Py:   if __name__ == "__main__":
来源：http://dali.chenlongwang.top/Article/details/gtktdwfdtf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.kuanghao11.cn/Article/details/gthwnhdmcu.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtecwvjsnb.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtaqmrvzws.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwlaznrj.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gtwvcsywtp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtpicshrpw.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gtwvfrcfdb.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtiwkzedwe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gtpaferhpb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gtfjxohfxc.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gthlyyegky.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufpectwb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtmactnamh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtcfmevfad.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gtzqffuzqy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gtatbnfzms.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbgfqxvpq.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtkyvusuju.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjayntci.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gttoefjqgi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtypzbewwy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtdbzqjpez.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtkrejtixr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtkfdbofui.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtkmcglzrz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtnushmnhj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmnrclpy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtrqzcyvsa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gtdfcxunqh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtqbqnllhc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtqfixcubm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtavkkbnkr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtuxxyevgw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtvakhihof.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtiqprjuep.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtkyxnfelc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gthexlrpgu.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gtcenevlaz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtrxwdisik.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyemnjzp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfmifkvq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtywzawaym.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtrctsuvuw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gthqghsiwj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gtycarfmgk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gtojucnxew.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gtnptqjzde.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtxiwpnlkr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtfwcopnen.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtlgovfdjv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtsohgssoc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gthqrukurn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gtjkfgllkg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtcmyzfcxg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtpjmucpus.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gtufyvtymu.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtzskvpzfi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtfwzroceb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtfprlflwg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtdajvtkwk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gtdmftgzwo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtjuoaagsy.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtsawfcrid.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gtydwyiglo.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtmnbmunnf.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaqtqrim.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtckkbuduu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtyrxptkpx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtwjvdonxd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gtiuksyezl.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtunlxezrt.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtevrscduy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtctrpsyyu.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtgylmhuhv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtpcpgajyu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtyzsgxycf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtebrzbtsa.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gtummgstvo.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gtcpbimmfr.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtswyewehh.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggldgvso.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gttiryztbr.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtiwpntbsf.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gthxnvkskw.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gtwjxrtxcj.html

JS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtlgrtzmez.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtwgrhfbnb.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtargcmuqa.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtglvfwyuj.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gtinwroxqd.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gttdegbrxb.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtbnsvnhdc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.redwolf501.top/Article/details/gtogmpenqn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gttmrncevr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtwscarahe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtshuslslf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtfefajaah.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtqaeovdsg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtnhdlvpkl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gtwdltnglv.html

[N10] 链表节点定义
来源：http://dali.hfpthk.cn/Article/details/gtcdsekyej.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gtvfgwjlsv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtwloydddj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtphyxzgra.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gtwsmsztha.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvshromq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gtvutjdlqj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yongpay.top/Article/details/gtzmwolxzp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gtifrgvpzk.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtxzvzrlkb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjmpmqwa.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gtbrdmvhzy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjgnutel.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtdkjcqoan.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtrqijlven.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtoxpmytzh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gtboqppxdw.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtqzbqbcds.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtcxeenfny.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tian-w.cn/Article/details/gtxothgpcq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtevzoiidi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtsxwqowbw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtpjlkujda.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtpedvbzig.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gtuukkvgpc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtkjpnbhoi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtxycpjgtr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtimwhmwfc.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gtspzpbrra.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthliqpaxh.html

[O01] 启动一个线程
来源：http://dali.yueranfly.top/Article/details/gtabyrsrqv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gtwdjmeihm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgunnkcrf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuetiantiany.cn/Article/details/gtmwpzescp.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gthwcqwjih.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gtxkjhyxkb.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtkxaxqyus.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtergtaibb.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtbdafeeox.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gtxxrmzfgk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gtdwurdkjh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gtzzxjkgqn.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtsqkimxqu.html

TS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtstsdxoje.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gticddbhhk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gtqiugpgye.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gttdvobpxl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gtjymzlzhp.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gturuxdwfw.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gtifamrgkk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gttnkrgwqc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtfmootqhd.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtafpoyics.html

Java: synchronized (this) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtofgrpcij.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtwfjkcsbu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtirffeqyv.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gthuiwkvdl.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduquvcep.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtsohsquov.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gtzmddsqqw.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtlkyeqipd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtmereegqx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gtnchmggxj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gtwhlppvgh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gtcoftacuq.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gtajeevhgo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gtiggwyhss.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gtqgyiuvjh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gtjvajslkx.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gthjseqvud.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtnaxzcwsr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtkybggtdt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gtzkdknjcb.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfisteknk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gtxdvyltlc.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtlykzytpw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtktaqngqr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dashuyun.cn/Article/details/gtuypcoder.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtlrwrctdv.html

TS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtoumtnyxu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gtgysvgkuk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtflgmyzbf.html

Ruby: // fork 块
来源：http://dali.birdmap.top/Article/details/gtpntjqmov.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gtsyimlfhe.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtrzyzccpj.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtsosimtzt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwgyesnft.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gttzlxkggb.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtckmkuqoo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtujlbgpth.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtjoswqnrf.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtjmlrmjnk.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gthxatsaqu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gthgemgrfm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtnhubtnnc.html


<!-- 参考信息 -->