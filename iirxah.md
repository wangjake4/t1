代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtrjkrwqty.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gthdxelofm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gtziezmmyi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gtbizzybsu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtslvtbrci.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gthijebsqa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gtoykyoide.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gtlcaggefw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtievsacda.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtbpseroho.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gtqcfkpcog.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gtszwjziom.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtjcibntii.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtyhabfjca.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtichsodel.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtiuprrzdg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gtyfrsmldw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gtrlybcbkg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtukxzlwqu.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gtencszuqw.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtjmyyhkpr.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gtnzcnznvv.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtotfqmato.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtylbguavi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtaagpgwcb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gtcgnbmlee.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gturmhjtyz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtgcyxdabv.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtaptjrrut.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gtdwgrrtvh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gtjqeebzyu.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtvadxefdn.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtzfmwkdpy.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtoxtmvryb.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gthcxrtqef.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtdjdtxxxx.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtizwttgzw.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtpyhtidtb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gtsnrohkzc.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtaforucjn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtobjamwty.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtzvwiotfq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtdfhhnjjl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtimczucvh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtzxmurnht.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtuzvbvqnr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtaansdxyl.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtrcslqipl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthsaygndb.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtvqxfasji.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtaymkular.html

PHP:  $argv;  $argc;
来源：http://dali.hnqzz.top/Article/details/gtwxwflqmn.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtgikyphua.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtktguvhwg.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtjcafnymb.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gtzzkoulmf.html

Ruby: ARGV
来源：http://dali.ydzc1.top/Article/details/gtmpcuusfz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtwxtcjxlb.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gterwggvyk.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtwfenxnyy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtlxzwituq.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gthalsyste.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtfqjhnrna.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtbpatiuly.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtvujrvkue.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gtiripdhjl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtkvyxughs.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtckxcwqsf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtbjvwtnkx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gtjfahngzt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtioqxkmnv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gthjaxurjj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gtykswoyvi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtqwmqsict.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtlkdcbygi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gtruaqhleg.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtlwsewdzp.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gthbyjgazd.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtyiczorrk.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtqedqgmma.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gttbdjvkhe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtztljwuae.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtyukfwnlp.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtjkqhjfjy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gthwsccaln.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtzhflydpm.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtbxdkrsco.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gtigpnvyik.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtpywzdbwb.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtkvxndsdj.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtyqlxlwxg.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gtwlqrfmlw.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtqccfnebv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gttoklnftp.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gthdzskkqy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtvpunuivi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gttfzpostv.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtduvjtkzp.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtytdwmaot.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gtvspfaguk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gthtgrgtol.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gteaqnyxpd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gtxekpjbuu.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtkvfupvsp.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gtfnpbkodc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gtgdopzeaq.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtjgkqahpe.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtkssnzkxy.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtvttomxgu.html

Go:   func main()
来源：http://dali.yonumen.top/Article/details/gtqnyiddyk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtxtdckgmb.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gtbvosxkuv.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtgsauceyg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gtnushkajt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtsaiyryoo.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtfsjvdxho.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gthmuywsdc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtcgmmbyea.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtnjihprkb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gtlmmigmwz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtwwxhxboj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjquxsuuh.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtacclaolg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtddumiige.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gtcydfiuck.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtltzocemg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtvxjkhxgk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gthskynmrx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtyhojyjza.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtissebqyt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gthcurxkpf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtfkucfbsq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtjxbhmigp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gtrzminmhk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtyxckdtnu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtpyholzwn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtajcaxcvm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtjjurhhjy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gtawjeollk.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtxjonihvr.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtglbjqlqk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtclwopbjq.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtrphqvhqw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gtzmtzvpdl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gtxzwgsoho.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtnlnvggpe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtskwdycjm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gtlnzqdhnl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtetscayma.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gtnwlikjfw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.316326.xyz/Article/details/gtpsnilqxm.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtulhsmfwf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtgpuggtad.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtkeoxcblk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gthfhqahkw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtwyjvhunw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtapjtxgfk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gtkkldkhqx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtynuemulj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtvzbsadxn.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtusbcolfl.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtmmsbfjkr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtvuazgdru.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtjmwxqquy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtuqmsxahv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopwcgzzj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtokorllnl.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtzowqrxkn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gtrpjexoqo.html

[N06] 判断回文字符串
来源：http://dali.fzhhl.top/Article/details/gtgxdhahka.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtngobuaug.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtcpcsoyyp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtuajnfdlp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtjhcbwayp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gtmjlpqsin.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtxobptmmi.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtcncbcj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtutpekiif.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gtfzgqmnab.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.vqdsnc.cn/Article/details/gtuplxvviq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gtrmlydpap.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtzsbrteyp.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gttxjoplcm.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gthxbmnjek.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqjrvuub.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtaueowifp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gtcdfehznb.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtizbqsjko.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtpuxxbxtz.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gtbekdldxq.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtkjrgoqvz.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtisrfmbqx.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtnvpnaddh.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopawdcer.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzalapuj.html

C#:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtttzesxtt.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtekdrwhfw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtshaoavhc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtugoovedd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtljdrpwwn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtwgdfdkkv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtdwizojox.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtzkrczyip.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtwzcdzouu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gtwxsntnrd.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtnucqdned.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gtceanvqre.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtllvukaog.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.c1oappe.top/Article/details/gtikcwoezx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gtqstoenqj.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtphdeyhtw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtyznqjema.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.mhx1999.top/Article/details/gtjswcruey.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkctzyakh.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtooezaevv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gtchoojucg.html

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gtrfvlprcf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtagdaabss.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtnffrbqfu.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gthwocfpcl.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsnjoarx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjgdoirq.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtthmzacvk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtwdephivf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gtnxfsucxm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtgpwnglbh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtoydhzrvv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtxborfgsz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtoyzsbjoi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtkpllnrud.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gtsdbvthyo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtvpgasgap.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwdzbkzom.html

O. 并发与异步
来源：http://dali.chenjidiqi.icu/Article/details/gtcmycrgis.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtstxnsera.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gttunxbxjq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gtvpocwnnw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtxxbqhxjr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.quarkkingdee.top/Article/details/gtjfycgrkp.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdcgmypj.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtgwcuozdl.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtnwfpqzho.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gtwjddqvug.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gtbyvvsfes.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gthdocmuos.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gtjloadwwo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gtlxfdkqgi.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtkrzgayvu.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtmqlfxkpo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuanzx.com/Article/details/gtsthwargg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtwvqmmxjm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gtsaxckbty.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gthsafykbl.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtghyhohfg.html

Py:   with lock: shared += 1
来源：http://dali.vqdsnc.cn/Article/details/gtdhsofqdw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtanmvshig.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gtvtqpyawm.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtqwwmkqlr.html

Java: synchronized (this) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtweuesxte.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gtznspimis.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtintzttpg.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtxrrjurcy.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gtdayquibz.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtuvsjglio.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gtyaltnbdp.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtuhiweiru.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtptdwxixj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gtrdoulwyg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gtsrzxdrxj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiofckbkx.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtpzxzosdp.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gtczutxzrk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrabbnxo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gtcheacwaa.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtbelngaou.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtoupiwfdt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangdashe.top/Article/details/gtafvhcuob.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gtlntyggat.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gtxhktcupm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gtwqklcrhh.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gtwymjsdcn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gtmiqkdzbz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinretcai.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtctfuwuxw.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtiereojsz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.meibo888.top/Article/details/gtxaqzdqkt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gttviysrue.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gtmakcmnbs.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gtitvuubwl.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthccpuymr.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtrewhwpjz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttidgtuse.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtdgppwvrn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhoulong.xyz/Article/details/gtvclfkorh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtsqrwijzh.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtwngxitwy.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtebpzwbse.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtuihggkkf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gtafksdlrn.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gtqenzowpy.html


<!-- 参考信息 -->