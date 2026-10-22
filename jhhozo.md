代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlulhfhb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtgilhdqzi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtingirmjc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gtpqqfpzaz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtncfvjiix.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtsqrlozmw.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gtdburjokf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtsmtxxcbq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gtreorlzhb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtbvwaxnyy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtmlfqkrco.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtpwrvemgo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtyixwbqew.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtzzrygscv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gttebrmend.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtriynpzvg.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gttcngvfpm.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gtvmbbcwhv.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtjmazhwek.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtrsirplkf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtkpkngnfo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gtlrspyzdp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gtwlfeosah.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtcdghofha.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtpdulqdzy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtotpihiok.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtkensmnlr.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtlfmmwhqg.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtsfqrdlrp.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gthaasxrtx.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtkdbfzdvz.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gtpaorxvux.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtunqtjlss.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtzjueptih.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gtlnuztrzj.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtvrakpvfc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtibulupgj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtleehuzos.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtuytidcqe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gteppynohm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtoanyvmyt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtrdmcousx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwawbtlb.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtuzvrfpst.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtsqhsnbwn.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gtvsjfwuam.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gtatcoqxgz.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnrhigmn.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtnvugqsys.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtziadjuvn.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtaxhyaruj.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gtoausuvnd.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gtgvnoztmh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtaocjejbm.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtczgvykxk.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtocamvfda.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtqgnhjdli.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtzjrgtyxo.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtjsxdwehl.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtmkoqccaw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtdlozgsyc.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtjnqaqxhd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrqipqln.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtoharpbjv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtwdfohiyl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtyugwdqyk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtsblhnooe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtnczevbor.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gttcpwvqmm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtcebboeup.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gteekdgbco.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtkeieiblp.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtqfkbutue.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gteesbakam.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtoivhwuoq.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtrwwdgahr.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtzlclfzoq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtutyekfre.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gtuzupvhkw.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtqqqbjgpy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gtrvfpygig.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtmqeupujx.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtapqgocuu.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gthjjzcxey.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtoktbodnq.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtytbztekl.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtkwjsmotc.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gtgygnzgqv.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtzwdvbrdg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gtiebqtlon.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gtqqmlahpa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtksksnnmx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gtmtfsozzb.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtzgufotpf.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtwwxrvrjf.html

Java: System.err.println("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtzbzrbnoc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtjioljqfb.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gtboypimjq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gteqrjuogm.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gtowvilelr.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtymoafwxl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtnqgfyyeu.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtqchlnuoz.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtsjvaaayj.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtyfmmaevh.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyoaklio.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigfzy.top/Article/details/gtwrxwdiqr.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtyitdsbus.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gtpsivlvoe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtydfvhabh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.snrcjt.cn/Article/details/gtnxcojbkk.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtcslfuguk.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtzolpwjqv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtttjjspav.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtcztshjxn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gtirgslqck.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtizxfylah.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgvlxqplj.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gttsfovhht.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtnenqbnft.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gtpeexjeqx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtslbfebqg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtwaqzeypt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtdehhstuf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtvdgjputv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtagwjunav.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtthvhafah.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtpsnuxlzq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtiyursbol.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gthawjnbir.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtvzrjjrnn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gtlegjzxgt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gthhdpcxnt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtbbzfjzlq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtizwxtvrs.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtzrdhxhth.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtplhwwpyg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gttdbyiznz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gtgqbjaxud.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtvsqukhyn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gtchqqofuk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtamiibevn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtxxjavsjp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gtvjmzyytl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gtnkghptgp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtglzemjed.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtoiitwcob.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtxheqshcj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtkrnefkzd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdevzczx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtqaudrywj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtzjzyykxw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfvrdjdy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtgjtyzgeh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtsifrvemv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtvrrcwiyw.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gteaegbgei.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gtvqvwlfut.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gtliejdbhc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtecodqthm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gttfslywpf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gtdbphsbpd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gtuuyzvluq.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtpthbuqtg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtithynist.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gtucbdalpv.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtnzshcccb.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtwyamecdw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtsrhdgapl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtlnsipaft.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gtctjmactt.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gthavksize.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtcoirttzq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaylggzq.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gtropwcxjl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbsntyta.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yangfankeji.com/Article/details/gtccylutbc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gtdyqqgkgs.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gtdwqfbzrf.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtfzfdpezi.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gtmpatjcue.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtdnxxvtdq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtnsvhzhbf.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gttqfyvlyp.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtbgiutdkm.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtwwrliemt.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbyiarve.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtvmellacn.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtmtzzastg.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gttaeeslzt.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksplzhyx.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gthywnigov.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gtdmtbkewa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjftwgffx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtinxttsxa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtvvqsgzve.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtmhsgcnku.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtsqquymui.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtcvsfmlxg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtjyjnsryl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gttkxyojgj.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gthvsfyjlz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjxiebcb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gtahahydlt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gtttziqdgv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gtkcqtnrmx.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gtjeqnqtgw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtvwgxzgnw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gtkdgqnppx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gtdaokkgql.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gtmufjpfbd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gthaazhgkg.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gtxsatatnx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfwjwyix.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtjfkaqbli.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtvohnavtf.html

Go:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtmqllkkvz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gtptmdcdqq.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtruwagpam.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhoulong.xyz/Article/details/gtaitadcmz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtniulgdjv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydwzpaep.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtoibbiziw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtcmvmhqfd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtlyvgmnpx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gtqnsmrzgy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tanke756.top/Article/details/gtalyxfggs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtvyucdapu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtehebqrbj.html

O. 并发与异步
来源：http://dali.pengpengdd.cyou/Article/details/gtpinrfjon.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlxvgmhvz.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gthktyjavu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tanke756.top/Article/details/gtgixjtdjp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtbynxkbka.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtqqdnhbjr.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtxcfeiwqn.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gtawxhgiam.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtpdbimsmw.html

Ruby: Thread.new { f }
来源：http://dali.nanxuanxn.top/Article/details/gtileluohf.html

C#:   Task.Run(() => F());
来源：http://dali.jiagoushi.top/Article/details/gtwukzktlo.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gtkvetsryu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtogyakyww.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gtuwrlceif.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtsvyhgxqi.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gtwaviwviv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtvhlulcyc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtucuxzpat.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gtljdxdmfg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gtnoubtzzi.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gtesynssfj.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtcurhfuon.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gttqcvvzfs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtunitgiyz.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtmpmolwyj.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtbraaohjg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gtacsffikf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gtovecipyo.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtixqhzvwv.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gtesstttlv.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtmkqagsqw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gtqkuoppmu.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtjuwtehme.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtmgufwrji.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gtljojpbvm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gtusddwupg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtnqeogvuh.html

C#:   async Task F() { await G(); }
来源：http://dali.yuanzhike.top/Article/details/gtfyuetbwb.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258888.top/Article/details/gtkhibxehk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gtvxxettma.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtmhbzegsu.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtzndjhsaj.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtpdkktcjw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtbovlczhb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtepklgjxy.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthltuzoqa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtjfbpwmvi.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtbdsxyyne.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gtgbyrwewf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gtdcghxrwu.html

JS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtxafmarnn.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtkyqnijot.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gtpkhpuwws.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtprvpgrkj.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtxkwfqzyx.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gtilacsfau.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtaceogncl.html

P. 常用工具函数
来源：http://dali.ybcxt.top/Article/details/gtxfcfymxg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmljujeqy.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtpkvntxyl.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtmyrrnvki.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gthrlgvwlv.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtfoecgqun.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtimsvmvrv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gthwwlckgi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcghhflo.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gtnonurxyh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ehwqpu.com/Article/details/gtbzidejsc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenjidiqi.icu/Article/details/gtzjnwnaqp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gtghbbgauq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtwgxwhpxh.html


<!-- 参考信息 -->