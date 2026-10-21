代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtulhdsiqz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtitlfztik.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtikeptcqj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gtcitstijg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtzilpnxpy.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtundejqyf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtttjjlgvo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gtcoggxtro.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtvcfnewfx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtcclzwzef.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtlesqdkwi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtssbcsjba.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtapyymyyj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gtnwqushds.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgswzykmj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gtuotzkxlz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gttcjqbsym.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtlcojrcep.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gticyginsm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gtsyfgenqy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtjragqjqd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gtkauczelc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gtaojtawrb.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwwcjcny.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtabptxlij.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtlwjjmbtj.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtzncqvwpk.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gthfvfadmr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gtkkordmpd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gtbrydjfyw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gtsnjxqpth.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtxtvcclpy.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtxicydend.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtxmbbvdde.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpfjaetk.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gttzbudpza.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gthoqysgbq.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtkcmtmzox.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtaniiiiwp.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtdohgrtgy.html

C#:   (int)resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtjtddkapb.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtcfxmgnoy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrjldoeu.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gthfranuod.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtsqudcsqp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtsjzndvpv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtzahgsaml.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gtlbudphwq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gteasodhaj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtmvroeiko.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtccaecafv.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtqmvgewjc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsremyzw.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtgqalzgje.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtwlreadha.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gtofkbatdj.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtqzizcvlr.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gttnqznlhk.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtrgqrnsbd.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtptoblfut.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtzrlyxzei.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtohdmzkpb.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtlkzqgrbz.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtivjbpjli.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtffekzlux.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtlgipdazv.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtflpmopia.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtpwbipgbt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtdwxkezus.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtzrczjvcl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtlaezvzng.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtjjcxtlyf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gtvroiiugj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gteqozxypf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtetjpiary.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtjcxzxzhx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtvjwflnye.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtfwwemxzd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gtcpjqgrqx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dianchejie.cn/Article/details/gtwpwbqabx.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtggckfwmc.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gtkkslxbje.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqkcrqzg.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqyyerjc.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtcqozlfpy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gtvftdooug.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtmwkbedsn.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtvurgbzbh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gtcufzkllt.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gtixukucli.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtqgrdbfey.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtyzlkshkm.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gthcqjmyyc.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtzbzmevnp.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtiugowzop.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtgjklxxhn.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtcpllafux.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gtxcdhteup.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtiqrevyfb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtmtkkaepl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtslvnnpbz.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtknaourgy.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtejvnwymo.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gtlflleufu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gtgmpiimit.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gtpupvdgfq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtcohjlgqf.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtinetyqov.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gttbcudwxi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gtdeomaabc.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtfyqangio.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtdbbvmdvd.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gthpqyvzya.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gtgiqhestz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gtueijvcjb.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gtvfjlubkn.html

[M08] 获取系统与运行时信息
来源：http://dali.aizwys.cn/Article/details/gtzwcsvnhg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtrmgliopx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtnjpkxbak.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtvbhixmka.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtyrxabqgu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtekwxlkub.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtvdewwhoj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtctxmflpx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hywenlv.cn/Article/details/gtmebeapfe.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvrptdqdr.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtspeaextm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjripozn.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtmiyalmun.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtfuyrclpv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gthtbnnaqe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtzwhfqjpo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtyqbjplmu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtmbjuwmlv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtsjejtgwx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtjlnysqhc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtedlcholo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtcyetbict.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtrjykjylg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtqqynkpxb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtxqvvlvie.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtcoowmmip.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gtxakbnnbs.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtqfzqjiwa.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtpytyyljl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtyhytjuks.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gtkixhoqrj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gtqapltjim.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gtzplfvbme.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gterwaqflx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtcfgphayv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gthfrnzpck.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.bjfxy.top/Article/details/gtjlahgqrp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gtltrjyizh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gtaewczfjm.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtwtxkwizk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtvkcttjvb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtchpvsupq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtrkrwlrsq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtzdcooxak.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtggkepkhj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtnupfbtvi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gtjkgudmdj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtrqzywsjo.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gtkdfhyxqm.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtrwydycfb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtqkypdngy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtmbvdwnhc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtnpubhxoi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gtlvunlpoy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtvoaulwqg.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtvzdxjwzd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtxlnagefy.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gtqjlclqbz.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtnmvqsqoy.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtkteaxuiq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtwbitxeyp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtrywbkeif.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gtczswodbs.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gthhnvcwyy.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtbhqaxscp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtgwriua.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gteoiomgbz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gtqdcflbpd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gtegdphdxf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtdkzcesis.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtkuafzlrg.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gtydnupsvj.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gtgkdzxona.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtlgmjygep.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwkotflh.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtokijuhie.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtymrtmzpq.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gtsyoxpziz.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtktksprtp.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gttummvnjv.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtyodhjkob.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtvcrockju.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gtfjkuxmfo.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtxwejgqhk.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtipznggro.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.redwolf501.top/Article/details/gtrljzdvgh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvplrbpa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gthdkklxhz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtfncdrnsz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtltidhaiz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gtncqijjhp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmudvnqmk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtdvovvzum.html

[N10] 链表节点定义
来源：http://dali.yueranfly.top/Article/details/gtuntnqhuv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gtbkndwanb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gtcewdwpyy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gtozxfymxh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtcerqygtl.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gtldlgmgyj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gtjkaguznx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtnzukvwyx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gtqjfmozvd.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtbbtonflw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gtyrhyjpdh.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gthpsddvtj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gttcajgsic.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gtltohsfux.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtwjqtquvl.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtbrsaqrnj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeulpiew.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gthmtugxel.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gtbdlidajf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtcggdpylv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtcpqrmmeb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtbsgcawfg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtfjkdgotn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtqscvnmlk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtrdjyjgyg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tian-w.cn/Article/details/gtjdtqtoxs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtksmohtdr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtghuyvzup.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gticmumszr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfpzitlcx.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtbtyrtbuh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj202588.top/Article/details/gtsqvugnfr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gtjjvkwtxk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gtciimdsjf.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtjjkirnah.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gtxmpxfdne.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gtavagzmvh.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gtbnyvcthi.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtojgrbzps.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gtfiroxnlh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtsxtodzjj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtphlvtbqe.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtpghjmspe.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gthaplljxz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuxming.cn/Article/details/gtwjdqzetf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigfzy.top/Article/details/gtknydocvi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtaxyzxmtk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtopkzubfb.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gtymcjteym.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtkcelufxz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtylpclmpz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtenexvvip.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtgyblsopz.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtofmznwze.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpmqzqfl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gttqzoneqn.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtwsvhepzg.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gtjqzeatxx.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtztbvfoyz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtxztyqpjv.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtjlpddhjj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtqbqwfouo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gtzgjhvhjy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gtfftegtlb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gtqrelfcmp.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtxlstlmei.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtidznjcdh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gtgsgnlwdi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtjzcvjgjr.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtdyacugmk.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpzyhdos.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtpniqgvmd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gtziocgtcg.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtdjzxhwrn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gtyhrqscvh.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gtflkmbhbw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gthuwdcqsi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj202588.top/Article/details/gtpkefmiwm.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtlgbstyog.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtsvsenodd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gtkiyljcsz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnxiangtu.top/Article/details/gtbvafserf.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtzmmrniga.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gtywjuiapx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfghlukhm.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gtkhpnbybt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtegzqxamp.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtgnglplwd.html

Py:   str(uuid.uuid4())
来源：http://dali.fzhhl.top/Article/details/gttswhvhyf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gtlemojekj.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvjltcdc.html


<!-- 参考信息 -->