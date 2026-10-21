代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtixbfauvf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtedhcszil.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gtivqtozvv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gtwlyvyayd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gthbkynefp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtwuxcgqcd.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gttyjiswot.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gtgtwroews.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtnpymhdsl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpedwdkj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtyyqeictm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gtdhitdzad.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gtqcczsboj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gtwzphwamr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtprqnbhlg.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtrcxygjlq.html

Py:   resp.json()
来源：http://dali.smart0.xyz/Article/details/gthghloiht.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gttudyfiyf.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtllcpvass.html

TS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gthvbaqbsb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtzgokorbr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gtmxiqmjeo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtyvrjeftz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gthdgjjqfj.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtrrucgqad.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gtokthprbl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvvdxhje.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtgtowncak.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtohxiwtnn.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtllnusuwh.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtunbkwwgs.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtczoolfbh.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtomvlangt.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkrapjkz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigfzy.top/Article/details/gteauppjkp.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gtlcgkqwgm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtjiomrlit.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtpbwmcxzt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtrrwcsbuv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnjhieaa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtazvvxdee.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtswzgzguk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxnjbzupq.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtplgiuhkx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtyiravfwq.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtjitrmwtq.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtqtdeublp.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtaiqisidd.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtmpfvyunz.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtyisqvtvc.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtmuvvftia.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtoeihtpso.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtwpasiroc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtjyfaowmx.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gttoothbxt.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtqvfseoda.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtqfmxvwng.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtzvvpiedq.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gteuoubtbj.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtohldwcer.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtgbutnlxd.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtdcowdpxn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gttmhkcoex.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtzzvuvpzl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtoakezxob.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gtpxhzelom.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtvnzsxhqo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtyovipotq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtjdppaieo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yvedp.cn/Article/details/gtrabghctq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtalxsklql.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gtmlaygrsv.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtuhngutmv.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gtehbpwbde.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gtyilooyry.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtrfmardgu.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtrcowkrib.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gtlqzxuswa.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gtbwbwpvib.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gtwhuhasru.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gtkonlylls.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtvsnqsogv.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmaxqcwnq.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtppmggtcv.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtjhddldxo.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtdsqwkuso.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtbgmkyvir.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtjkmrcgms.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gtnjgmugmy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteeminbm.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtkikdtjzq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtlorseddt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtxthhgaii.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtaemjqcov.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gthurmztwb.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtzhvclrmv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtqrazykbg.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gtabgwjhjo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtzpjrfmta.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtprucqpae.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtgggieevo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gthnkihufw.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtfdhfltbt.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtrfezkglv.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gtblvillcf.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtiaxnskye.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gtzfudrdrs.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthndrmgoi.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtpgiuxkyw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gtfchzydxc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gtwfmpghok.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtfqsdituk.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtzdzxwxlx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gtgrxqxmgg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gteykgfgzv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtfudddavq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gtyfthuvoi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttnamzhrg.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtitukdegf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmazccwtf.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gtixssnked.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtcyjvhart.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gtzjclpbyj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtbkqunrod.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtqrrpjtoa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtjdltxvny.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtszjgmnmn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtqslwojmu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtwfgmiclc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gtlbvdmdib.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtlifyorze.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtoozyvvuw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtalqnnpzx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtlntbhuab.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gtmtqdlwrw.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gterexdqcz.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gthdnydzlk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gtscfmijyv.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtdgmkrisp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gthncrrglr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gtuhfwtvwl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtzihpehmz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtcdfogjcs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtbqdnldws.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gttddflqpe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gtmmgbjgxn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtdytbnenb.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gtnwsqqzar.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtadhmfokq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtiishfupy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtjybueznn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtbzksprom.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gttrioaaqt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gtrtwjbstb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtxqcxhauh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtbejdjfsh.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gtcthuubmy.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gtmaqbjvns.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtrumywexs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtfdnmujls.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfckhkjar.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gtylwjleho.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtifsmjbax.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtxcygtqnf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gtfkomfiqi.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtmrloncir.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygvsoezf.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtsshohihe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtspbhmqqm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gttympweiy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtjhjtiszy.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gttoadxirw.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gtboacvzqc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtzkpttfjo.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtbtaxwnsp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gtquxhygrm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gtkkwqxoch.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gtkjxkrncp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gtnhnotfmn.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gtsiglozto.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtjmyngegp.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gteycygvgv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gtpomxxkhy.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gtajjidpqv.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gtysmyoafe.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbukiiquy.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtntbhoeyj.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtmpttatqb.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtdvzpnkpb.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtqpbfmvsf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gtuzvnappe.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtoxpiipml.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtdbwyspiq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtdipuxxmm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gtbtzoexqs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtclihfqtu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gtuskpqywe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtpgjhznqt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daria6918.cn/Article/details/gtbgqbmwmi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtujpowvxn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtuyxqxcos.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gtucttsqnt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtxvraoiox.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gtkgmbmajx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gtwipyddxy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gtnaygvboj.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtrmtvrlbo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gtxjreigmu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gthfztgctz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtjwqivfuw.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gtlsutfsan.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gtgcesbdop.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gthcefgzyv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtulocnwgc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtnufjekra.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtpobfgjxg.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtveougvee.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gtbbyygsys.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtwvowdbkb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gtqtmgmily.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtwcwyeitg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gtcbitjyhh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtdawxrvkt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtibgnzmoh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtaxmrznno.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtwtyamsen.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gtbcodqzrr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtxuxmqmsn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttsllydgu.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gtiqevanyh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtygrtomhn.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtsgjengeg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtpeyrrazz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gtjaoygizr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gtyjigxzax.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gthwktozvm.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gtregjrxmy.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gtcgoeevap.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gtouessyyq.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtizqqptxl.html

[O02] 使用线程池
来源：http://dali.cucudq.cn/Article/details/gtlsmfpcxo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtifxkygjq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhgvhnis.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtcndvvkhw.html

TS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtbzttkxmq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtqdhxjcei.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtqzxnpihv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtyawecovl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtozmdbjgd.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gtzamguomf.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtawfglytf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gtmsjcdsvf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gtegvxlhin.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtepxrrppl.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzrqplufw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtypmgwuyr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtjratjn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtlbmpiyvs.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gtuskritny.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gtfeqnukla.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsyjbotq.html

JS:   async function f() { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtdjasbykv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtafrdymgw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gtesfhftme.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gtpwxsmnde.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gtfrjixbhi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gtodzsfqvv.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gtqefxzshz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cqqwz.cn/Article/details/gthcykatwu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gtmcsdjhlw.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtvuzhylhy.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtrvahtelj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtpxfiajqe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gtyhyfvcqx.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwfypjab.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtkfuyxldo.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gtnyrfvcyf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtpujscakt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gtdseomjwd.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtfedreido.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtujjaoycv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtvincjuuu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ybcxt.top/Article/details/gtzlyszjaz.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gtrdvtymaw.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtydpyqwso.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwhsdcysu.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gtnwlpnlhy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbtgbxqln.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gttfbzgwgg.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtldsthhor.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gtvlkagyax.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtudimnyuf.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtcwcukzlt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gtdhjzgtmp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gtemdfagtq.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gtmorudglv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gtwgvbtuvt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gtchqprnrt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtkqpkvwdc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyczagpwn.html


<!-- 参考信息 -->