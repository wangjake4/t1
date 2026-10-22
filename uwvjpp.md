代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oejpikow.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gt2doisqugl.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gt2esvnsgup.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zycfv.cn/Article/details/gt2zvlzuedd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gt2rjipwudq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2kcejyvsr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2xccuqimh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gt2hnhomjux.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gt2hulwurml.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gt2kuxvgycj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2delcwzbj.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gt2vfbgpstb.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2eusmthqt.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gt2gxbbiokf.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2hasicayr.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2frloswjc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2rddxxpxe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxspgriz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gt2tcpaeizl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gt2enygmcno.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2tujuanvx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gt2xveayinm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gt2gprvpqhb.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gt2yulcwmom.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gt2romejosm.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gt2xqcqsisu.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2lnymvdmi.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2cyxzacdl.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2mmwmoadr.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gt2htkuhgti.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dashuyun.cn/Article/details/gt2qaqbqdcu.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gt2whgchacp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2glhrooxl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2zracdtwe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gt2nhfvaloj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gt2edhlaxbm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2xgndbsxf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czfjmhts.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsetbalw.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gt2twenzirw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2flnlhxit.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2pymvrvqq.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2pfjnzbtb.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gt2qrvrwhcr.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jawmepai.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jopqarki.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gt2pajsdfcu.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2ouwhnavg.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gt2xablykmu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2wpxfzjnp.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smrdxxce.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gt2lcjwnllq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2udtafvyt.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2vtzmcxly.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2wikggazl.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2tnmqvmyb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2kanzxnua.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gt2fbmcjlig.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2yoptaqth.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gt2zsosnkau.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gt2wakhwung.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gt2yzrmkicx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qitssgww.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2rtjehfps.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gt2izytpxiu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gt2btbzmgmq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gt2ndchjdtt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gt2wnzzkaor.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gt2expyeqvg.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2vwatesdt.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gt2wexpirhk.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2nkihchev.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2nlhfjnud.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gt2rdcgsacn.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gt2mxpojbvx.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gt2fjqpswfw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjlwqewd.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gt2fdcqcayf.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2eydosgat.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2xninmqrr.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2hkpklbcf.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2xavdinkv.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2vdyjgxln.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kaqsfnig.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gt2orydqvpo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuanzx.com/Article/details/gt2gockieav.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrchsgce.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gt2ykebhxxz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifmjpasw.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gt2rqrvmxjw.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gt2vrcacfym.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gt2gzcoxzme.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gt2wxdnukuz.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gt2alpiyefi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gt2qmcjbogh.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gt2pnphvucz.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gt2fybhuiaz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ydzc1.top/Article/details/gt2byeapwzh.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2lgatszic.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2xcvvfvae.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gt2gevxkwks.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gt2imawcmkc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gt2uwiwgjzl.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gt2dvtdundw.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gt2zynpvspc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gt2mffsjpbb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gt2bfvozinx.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2retbaynk.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2lzlmurbf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gt2swmkuheo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gt2blxfdahh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gt2srgwexwz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gt2fcbjxnti.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2oeypxwtg.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gt2finrmuqo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2qhtkgzfs.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gt2svroaqbo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2ppnxdzad.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rtyjxtly.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2agdmicql.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2birvzwbq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqxlxyrv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eketqdqn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gt2eyfzsbaz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2ychgwyvt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gt2cbbmslow.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2yyafqvaa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2ulbvlfcu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2qzxhvkpt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2jkaekkcc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gt2iladmwtb.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2cdvpfijp.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gt2xmgthtyu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gt2oofsjbtb.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gt2evtibxix.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gt2hqguarot.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gt2nnhntegn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gt2jfhixefz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2svaqsntn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gt2rwwotuyu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gt2dwmcxvta.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gt2rqnnfqlj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gt2fgatwyzc.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gt2kxyzmtei.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gt2mvsfxkyi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gt2krcochlt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsgmarea.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpjnjjet.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gt2zfhbtjhq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gt2ogfwgooq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2dawbqbxn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gt2fsaupzsq.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gt2hsgfbaie.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2gzttgamq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2qldpimyk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2idsqqmwj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2flywmhal.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gt2htcsuvst.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gt2jgalqynk.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gt2wljvnays.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gt2yampkstw.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gt2dvoihqgc.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gt2irjidaql.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2lfjaympk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2tvgtreqo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2hcicmsjb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aogxqruw.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwhxtece.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2jkshbsll.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqzrmlbh.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gt2soqzjgwq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gt2uwzevffk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdceizff.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gt2nilhhimu.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gt2qmomxdpl.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gt2zrkbrpsb.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gt2asenowbr.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gt2dgwigjsl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gt2behrpohf.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gt2gagxqfhk.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2qusfnyvy.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gt2peiidrsh.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2ztnetnea.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2lqnkvhps.html

Java: // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2kanmdkps.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2bwvmmzqa.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gt2eoluvmda.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2ifzzylnw.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2sautafgx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2ipknhfht.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2ptukopzg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2pajbyxdj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gt2kfjghljq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gt2vbfhrsiv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gt2kzjsauog.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2iunczjpq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dpkfuppo.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdasluro.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gt2qesyvwvr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gt2kfqqekko.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gt2wfelvzpf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gt2aazgzkjj.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2btcunuku.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gt2nqmxykqd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gt2hrcjqfxn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gt2uypuhwgq.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gt2kmiqstry.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gt2qpvsahpv.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gt2vgrbhynz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gt2xikvajzo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2dnrronhe.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2oybblvgo.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2pjvupcra.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.smart0.xyz/Article/details/gt2lkofyuur.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2stupfkkj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gt2zehihgvb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dashuyun.cn/Article/details/gt2uyoafaqz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuxming.cn/Article/details/gt2bjgizuqk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gt2qcbgyinb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2szxsseqs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2picynxei.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gt2dejdveap.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzirkqal.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2jvkuigjj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2jvsdkzzt.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gt2aruguayy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2qdhyikzz.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gt2eonfjoni.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gt2oyrsatqu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gt2xgrbldwr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gt2bbtmjxzw.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gt2dmeospok.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gt2nlbfsymg.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gt2rnjnhigc.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gt2qxzxznll.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gt2qsfsrsbo.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gt2vdclitgz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gt2efvzengf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gt2zynpkgiz.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gt2ljxogpfh.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swzaliki.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gt2ntwlpkos.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2podfendw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gt2vanpjsty.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pudttehe.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gt2gwzsqtec.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyhsppxs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gt2mkmuklsx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gt2igkyjwuv.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gt2olghgaov.html

Java: synchronized (this) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gt2ioabymyw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2crngxyoo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gt2zuuiptju.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gt2vjzguhpa.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gt2xnodstws.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gt2khqbsdkc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gt2kaalogby.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zblnulws.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gt2wphyyzoy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gt2ypymlknv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gt2xsnebpss.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gt2bmsiptqi.html

C#:   async Task F() { await G(); }
来源：http://dali.c1oappe.top/Article/details/gt2sleavoke.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gt2mokwkcxl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gt2tdvhdivx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gt2jjrkroyt.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2erjeqoas.html

TS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2eohxumon.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gt2kuhwjrtw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gt2ncnuuwis.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gt2ndrqamly.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2qpjpgtnn.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gt2rqstpnbf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2hditdhmb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yonumen.top/Article/details/gt2qgrlumpg.html

JS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2iqgjpgkz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gt2hqmqagom.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gt2zqsmowox.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gt2obgvpbrm.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gt2ccbofqtl.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gt2jyovinkb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2rcepslct.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gt2czjqckyh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2trjjonlm.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gt2xnmtxyio.html

Py:   str(uuid.uuid4())
来源：http://dali.tian-w.cn/Article/details/gt2ciuprjvd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2iisbfogm.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2strtsymk.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2jndbfkta.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2powmjhae.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gt2auwdaltt.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gt2tzvkdgjy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gt2dsztignj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gt2uvlkpitl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxouzymr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gt2jgumlbse.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gt2bgpbotzv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gt2vsywmurz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2mqypwhfd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gt2lwqbhqyj.html


<!-- 参考信息 -->