代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtousgamka.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gtsvcdlwak.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtxjidmqva.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gttqolzvyl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gttyweyvqt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gtklwrbnzd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gtpuhffiiv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gtkjjzfnmh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtdfwlhbme.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtvjlyhxmj.html

[L05] 上传文件（multipart）
来源：http://dali.hnqzz.top/Article/details/gtbgxlulle.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gtsevveuss.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gtrmgsfwun.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtbbekydkf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtfkmpgrwm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtwnwotopw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gtdnjunpkr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtzostjblo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtdufjwknt.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtugdqtcsl.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gtfxxldokk.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtydszmfxc.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtiogiaznv.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtigawpxxi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gteamxumdo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtgiuqlqaj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtnkbcmcmg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gthagignjx.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtmjfhmwkp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gtashpqvsf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtkrnksfry.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtifzlside.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtlyglajhz.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gtafwaetst.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtvpppahcb.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gtgdwxjpag.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtajlbojay.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtqjnwakdv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gtjqfuzcvm.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtwhsvtqcs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtcjcucsfd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtratudhux.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gtpdszucyp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodrcaron.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gtzscsgkaq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gtcpltpubj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtstmvallx.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsfodpdz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtejyikxqf.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gtcfnocwjz.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtmitramqy.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gtkagmpnmv.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtorroffdc.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtkvcuschu.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtzpksdxba.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gttagsyoxk.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gtwelfxacv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtmgvgvfow.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtgxkkubmt.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gtprfiispk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtphfzpwpe.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtdgwssnod.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtzfdnowek.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtacxfqaga.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtccbgaosj.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gttgzcnvkw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gteevsxced.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gthwodjamx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gtypwioime.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtabrwjkmt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtoweighaf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtiauvwgml.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gtuldlxoez.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtovaozqjq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gtelvjzftj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtwprvuquz.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtrrblpxek.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gtdlvyjywn.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtywbdnmky.html

JS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtvifoltiy.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtgcppwkyn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtppdvgcyo.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfmpuhsz.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gtgeciobzi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yvedp.cn/Article/details/gtqfeatlzz.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gtnrcbyqat.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtwmyrxvgj.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gtkysdkgfr.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtoyhgwluh.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtkxqkntwl.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtjybelvhg.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtfiypgvlu.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtjojjxgkl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gtqmxqxydd.html

[M06] 向标准错误输出
来源：http://dali.feifeiyinyue.top/Article/details/gtpfirobmy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtenzsfvvo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gtxzxprpny.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtsgpwqypf.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtmaauhlgi.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gtpcsaugpl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmotxatl.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtdgbriosd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtwylosqyr.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gtdseioryy.html

Py:   if __name__ == "__main__":
来源：http://dali.chenlongwang.top/Article/details/gtshygecon.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgfzy.top/Article/details/gtiabnanda.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtciqliaoi.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtdsvqgmtz.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtjpmqywnl.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gtbpftuybi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtwxjbaxcl.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gtdzcuubbo.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gtncwaaton.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtuymuccvm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gtoyzdxebj.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtwuqasypz.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtehqeunce.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gtanykhvsw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtsrydluub.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtxwjqmzjv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtywhukbsz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtxjoxirow.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtbemnonvq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrpgsftg.html

[N01] 二分查找（有序数组）
来源：http://dali.yonumen.top/Article/details/gtmmrfzutg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtotroeykw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gteejshaxd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtfzxtbncm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gttzxmsarb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtisbpkebs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtrbojruwe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gtwyahgqkp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtqpvjqoea.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gtcrkfgwyw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtxjdwxaht.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyarbvlmj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtmooulhdg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtdcnjczuk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gtdntnqbuz.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtfcczvuof.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtrsbezmzy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gtrhkfyxur.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gtautfjire.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gtzxwsckze.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gtayrcwifa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtujlfeecu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gttoiecsje.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtndmvlyag.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gtoeydxktx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gtshetixgx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gtemkbpiaf.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gtjpbkjwua.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymcyknyn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqujjruzk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtnoctsbso.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtizrhbnna.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtleirwdgy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtkghayprr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gturynjnga.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklzelphr.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtppjqiavo.html

Py:   math.gcd(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtzrzvzxcr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtajicyvua.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtentubjvy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtfifgrwqz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtntcmlstj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtbxlqmgpo.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gtzxgmxvrh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gteetoskyy.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gttzfxzurf.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtnxluzujw.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gtguyhywlr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtgmihtggs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtsjcgorfc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gtcyssxptc.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gtikafzavn.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtkwzszhlo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtlstxspks.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtkahpsylx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gtcpumcanz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gtsrsgrvdz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtphwezamr.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gterngbldg.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gtfqochvrm.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gtvipnkoav.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gtravrphal.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesgusymf.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gtdsjspsxi.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsotjppms.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gtnxmozekf.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtkdnrjuzp.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtmjkisxmk.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtwpunwlrv.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtpanqtnmy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtdlmoasiq.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtldturpmk.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtdbyppptx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtwnrenqpz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtlmytpfna.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtcurmfkil.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtkaykbxfs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gtjglhaflo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gthbytbpcq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtpnmotndf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtxqgduvwl.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gtofididum.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtkqhitgsv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtixnlegvs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gtkrrwjbcw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sxryk.cn/Article/details/gttnyjhqva.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtzybdhjtc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuetiantiany.cn/Article/details/gtdfxgjhff.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gthsgsriro.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gtrresorqb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gtbzhzdtuf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cashguo.top/Article/details/gtunmohfev.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gtgnchsowp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtyjfrxclm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtvwoorirr.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtyipteban.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtqnnmfyeb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gtqgvxfyju.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtqalhlmvp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gteqnztfvw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gtbeuabrgm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtlggiwodk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtycnqooqt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtqnlgcsjn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gteubxamjx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtjwoaatnl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gtqhdkaren.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtfractixy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbtiixmoq.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gtzstdrgfb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqfntyegz.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gtygtxcjus.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gtkyqjjrar.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtondtrzoo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gtjkfjlbvu.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtddmwehjj.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtrrpifsjt.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gtsxbbaxyz.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gtiaqjgpal.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulhcldfr.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gtzpicyvmc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtqwsetocd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhtapzho.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gteucadfyg.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gttaknaeha.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtrkekqmrx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gtlgzimfrz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gtfxuhkylf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtxautmvra.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gtxnbggpyo.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtiopbptwx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtjkmsvijd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gthtsekxag.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtacnbtpoa.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtuagqfuth.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gtoyxejtfb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gteaqartej.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtddbmeojo.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gtvqnvsjem.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtkqjwpzkt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gtefdebceo.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtonntyvro.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtoeczdugt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtiteitggj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gtkqnpkcga.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgfzy.top/Article/details/gtgqownfrr.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtivqdlkgy.html

[O05] 并发执行并等待全部完成
来源：http://dali.daria6918.cn/Article/details/gtlkbujhib.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gttjzgdunz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gtexhbrzly.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtxzasvubr.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gttelelsmf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtcmdvllnv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gtpefyvdsc.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtabvefbzl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gtkntmnucv.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gtwyworlna.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gtujvkspxx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtlzjgzers.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtdopcugsh.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtrhlwinli.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtfayhjtri.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gthkkwdock.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gtbahxqgpl.html

C#:   Parallel.For
来源：http://dali.gaohongyu789.top/Article/details/gterjjbtnn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtppmlwyhi.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbcxbsxe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxgtbpmjq.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gtqhocdnrs.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gtbqxbmksg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gtfzqnfusl.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtttnqybui.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtuysbjgyu.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gtuwmfiqba.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jianghu66.top/Article/details/gttzmyootj.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtjjcfpnse.html


<!-- 参考信息 -->