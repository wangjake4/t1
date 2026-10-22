代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtyvikqkcb.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtxqiomfki.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtmutbmumb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gtftpkgqwx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkcapyqd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtiimirawq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gtzpmqwwjb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gtenioiihy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gttnonmzrc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gtbarsqygv.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gthdyjbcay.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gtttnaxruk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gtbvhfbbog.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtiflmyekg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtzveiazjy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gttpyebksz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtyfuonaot.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gtblnxturk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtzzqmvclv.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gtoygqdgbu.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gtidzbwbig.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtkzxzdohc.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtseuwcccu.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoiqmufx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtbpnnabmn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gttsgisbwi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtliebkctt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gtjopruouu.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtsytpppof.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gtfkeiorec.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gtsngbvluq.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtokmqehmj.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdumalpme.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gtkbyomnkh.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtryraehrn.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gtkpogcpcx.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbiitzjm.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtygooejca.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtcyrlgpgt.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gtegvavijh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gthotfopqw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtgjodcttd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gthmsgxtgq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtcoprrmgy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtxvdexxri.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gtvjgxkoiw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpdvksqnu.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gtjduujkqr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtknosbhci.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gtvgqcpicg.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtcndvxtza.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gtfmfwfqjp.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtkrhzktzb.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtghdqhmks.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtyxxjfule.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gtbadzhvsj.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gtpzydfkoq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtccmpomfa.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtqymqrakv.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gthremzkxg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gteeawkhqf.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtvcoghmmf.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtagtcxlam.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtdwwvujdv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtvzigrinr.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gtpvdhxpyq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gtascwohfz.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtdstcpfoi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gtrqfrkefe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gtsnyyoiin.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtegwocfmj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtlgifsvcx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtdxuvizji.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gtlogdxndv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtbgxhkkoe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gttkrtiwce.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtdskqzjaj.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gtpwbjhnbb.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtxyxdpujo.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gttxahzkul.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtjirmkpde.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gttdvxrxqf.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gtogziljdk.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtyxxqslkb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtyxavqemd.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtwlttacxi.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtfgcpypyq.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtcjxjiqul.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtdobcijpk.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtwjhkrpzt.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtktnumzcr.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtymjuamaw.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gtsfhkqtaa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtiuunztvs.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtyfjqadvz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtnizaocqf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gtyddufvue.html

JS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtahevaeqd.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gttnhrrkej.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gtwpljpket.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gtwdvqzsag.html

Ruby: warn "err"
来源：http://dali.tian-w.cn/Article/details/gtbwphlvhc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtryanefyu.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gtubyminfy.html

Py:   if __name__ == "__main__":
来源：http://dali.chenlongwang.top/Article/details/gtbcqsvbib.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtbzbstdul.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtmjahhgqd.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gthtnwqmvt.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtiqojkkky.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtsexanltv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zdqjudy.top/Article/details/gtnyprgjrs.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtxlibvzne.html

[M08] 获取系统与运行时信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcvftrtl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gtkcvrzjvd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtmqrfizuf.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtbsipdiof.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtehskvbti.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gtgptoprse.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtpfsiiwtn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gtszxszzuj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtntsugigi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtczkdhfnk.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtvgztozer.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmvagrzdr.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gttgslzkep.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtsqrryvbt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtwpfdcvuh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtztzpcczg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gttdmxbjvd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gthtznhpdj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtsekktxrn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gtgkvqrqrn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtmepnjfuw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtyxoqvqmp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtzrvgcmwg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtfpuqgezq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtgmlyavxh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtowlyhicc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtdmzdimit.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtxrjipkey.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtkoypzpad.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtgisqpliy.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gturlapelu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gtykncaziu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gthismkjeg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtcgyyjugy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtrophygbf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtvgjtamsj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhixingplan.top/Article/details/gtsevanhmv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gtbuboafyi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gtfhpvskwu.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtbecipscl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtglzijvto.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjjeamxr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtuolxshjo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtuychpogg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtqtaltcym.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gttgwvwtwq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtetnuutpa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtqartsopw.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtyygjhlwf.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gttsegyoqx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gtogyjnmen.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtmrbvjdzr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtbpasqswe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtdstsjaqd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtirawwtiu.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gtcsabynoy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvbgfuiv.html

[N06] 判断回文字符串
来源：http://dali.sysykeji.top/Article/details/gtjqpqqwiv.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gtfpdnubii.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtbcspxdmg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtbiwtnevi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtbdayxmis.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtfewgaird.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtuawtrenb.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtjnrpthoq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtoxhqymoo.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcupxwidu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gtavljowet.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtkxiiianu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gtwafdzbng.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtfvycuczt.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtmawlrmfz.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gttjqnfouz.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtjanakvzz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gtwrvpnlqd.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gtbypqotkb.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtkorvoxwb.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtnuwafkne.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtyfscumla.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtsvwfttae.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtwyrkvtlf.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gthpwpyulg.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gtfolpmmgf.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtgqhkozpk.html

[N09] 栈与队列
来源：http://dali.xinyue.icu/Article/details/gtwgznpffy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnqzz.top/Article/details/gtsgnddpbo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekdodvgv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtzblutsff.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gtmzundjmr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtupdifgnn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.mhx1999.top/Article/details/gtouxerbst.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtbmezhepp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gtbqvmuiut.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtbhkwogbk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gtxkiaxpjp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gttxfhickp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gtaxrbforh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnctakezu.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gtyvrvdhew.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gtabhadkkg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gteiphllgp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtiwwtfsup.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gtothioeim.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gtockzrzyw.html

PHP:  // 手写递归函数
来源：http://dali.hammf.cn/Article/details/gtadghgoec.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtvvccrmeg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtaqpnanbq.html

Java: // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtqiuxabvk.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtokmjrndw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gtxrxcghsc.html

C#:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtvzvucikl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gtkklfhukl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gthewaktus.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjvhvqai.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtooajecmr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtbbiayazi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtijiikyqt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtxykloqwa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hfpthk.cn/Article/details/gtenuwbimk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtozbteznz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjyvmqltp.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gtaqznmdub.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyedabqtl.html

[O01] 启动一个线程
来源：http://dali.guowangkeji.top/Article/details/gtiiivpqkk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtrzgerdka.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuetiantiany.cn/Article/details/gtvxckkdde.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yangfankeji.com/Article/details/gtjbtsjyxh.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtocvtfaha.html

Java: new Thread(() -> f()).start()
来源：http://dali.fengsongda.top/Article/details/gtzpmaltne.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtdlkektnt.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtgzulkrik.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gtuybxwxaw.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gtnrxebynz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gtdlqaxami.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtervsdozi.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtoewvmreg.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtzbfomhin.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtkyldgbmp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtrgmhqvsa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gtakqoiywx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gtfqrvokys.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtqjpddbjt.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtxomtscfh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenzaomai.com/Article/details/gtfpcyeuiu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gtvvzxlbkx.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gthppebqpj.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtmqxcgidl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gthpdnyffr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtrhvaclyi.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtmjipdfnw.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gtydlzogao.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gtjuvngoti.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gtzvkcycvj.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtlxdtpgof.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtvdliczyu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtcanhrury.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gtmvhpsigc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjvsayjp.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtbnbgmogg.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gtavnaasaj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtvumheemu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gtgaeulbbo.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtmbesuvgh.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtkhxkramv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gtmdolrovi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtkgdylblr.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gtwfbuizpf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gtgsmzvmro.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gtxvzaufsl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gtuewagjye.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gtexxxoocw.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhnliivn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagjnqqxm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtfwynkcpe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtxynewjfd.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtqjkwpnga.html

C#:   Parallel.For
来源：http://dali.aibaodan.cn/Article/details/gtbidxicuw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjkxjqbhr.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gtqdbzqqjw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtejhmlckm.html

[P01] 生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtborjpbau.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gtwwxecbnx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuxming.cn/Article/details/gtlaiaetdz.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtaggljtto.html

TS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtgdkzdufb.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gtwhvhxefp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gtsmpzyatf.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gtzgofkyhi.html


<!-- 参考信息 -->