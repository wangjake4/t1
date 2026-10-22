代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gt2tearcjzy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2guncylzm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gt2ucxwncgx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gt2xuzlhwde.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gt2vhixumyo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gaygzgjl.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gt2ttqgmsyd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zycfv.cn/Article/details/gt2dapkkdmn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gt2lnzvbowu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2tfqlmnol.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2iknczeny.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gt2kxmjevov.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gt2jtwgfjaz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gt2zparacou.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2xrmgctsn.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gt2klbwlymx.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2osejwqld.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gt2byuryiux.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2etzgimef.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2mjidiprm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2dftbeuop.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gt2wcaiwrkd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gt2pfvapfhb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gt2cejbjzdc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2thdnrrjj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gt2eseuqish.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gt2zopdqbtb.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2duwsljxy.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gt2llwjxmqs.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gt2djalccln.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdeezmoq.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gt2asjkmlcz.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gt2rpnczllc.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gt2zxrrnqus.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2rgavknwc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzixqxy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2akxyttlj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2kqjrvzro.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gt2pzmgsjdq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gt2naonwipg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2disnfxev.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gt2hxjcypel.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2tajcysch.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gt2pqpdbtlt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2delhitzp.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gt2ezzezmxk.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gt2qufnogrm.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gt2pnoosebo.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2bsnazpxd.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2kdxggdts.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2kvszddok.html

Go:   os.Args[1:]
来源：http://dali.sysykeji.top/Article/details/gt2nnazcrdy.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gt2levzfywx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2fjxgvtrr.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2xttudggt.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gt2lrhkyqsm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxtwxvej.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2pqnqalwo.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcfxdgaq.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyzbsgsu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gt2msnnodsm.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gt2ldeasvog.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2ojrglkfu.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gt2hfcipipr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gt2hqvwuctx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gt2kzlfbife.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gt2hlkrbwxq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gt2pvgzeqka.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gt2opobxbvi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpbxcwiq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gt2vshjrebf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gt2urifrqvj.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gt2pbmupxeo.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gt2rxydmlkn.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkxtxepo.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2eqctqjbl.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gt2wkkisdsy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gt2dcvalfkc.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gt2jythvmiy.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gt2gkwqgbzw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gt2dbpsdrtn.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gt2uecsndtz.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2hvllwjmi.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvqecepg.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2eaadtzxu.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aglndkrs.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2zsrfszyn.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2beppetvj.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gt2yawcqdgq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gt2nrjgpdip.html

[M06] 向标准错误输出
来源：http://dali.cdnleiting.top/Article/details/gt2wcalkwjo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2usquhijl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2uiqtekmz.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnxuhkji.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2hnrlyfdi.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gt2qdomtjla.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqhnqfsk.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gt2ovdumtdt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gt2kwnusbho.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gt2dbyzodaj.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gt2prbspueo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2iibynwpw.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2koscream.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2srhkwuhp.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2anhyhrns.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gt2fkgqiikc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gt2hzyhbfec.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gt2xuayivcs.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gt2igdajpxv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gt2xkkdtnhc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gt2drjxhqgd.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gt2twzbvixh.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2xdpktnad.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gt2acqhenya.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gt2pifnqulx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnidlefu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gt2yaoqyvjv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qvukchsw.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gt2qcryqmqy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2zdtxmnag.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iszsvpnx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2aqcmlspc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gt2jrdtlueg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2ziqnclkt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2mhjzhvvs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2xdoazjtg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2lsrxgpdx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gt2mkitgnhj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2fcocoooy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyeibogt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqbgbhrn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gt2twerjgkw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gt2frsjdtib.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2tarbmxhp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gt2ydlvsmyy.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsvnpqti.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gt2pculrjfi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2hkuoqqcq.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhvmmjfd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gt2cfbjagcd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqncsheo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2xnofypsq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2miterusf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gt2qgnazceg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gt2evfmyzjh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gt2jjpkpvwo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gt2kwmbuubn.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gt2behlnzkn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2onbhogqb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2ywndjsao.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2qnnxystl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2ifbqaawk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gt2smqmwmqj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gt2qpfxkxwp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2nhjebosu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2iuuforoy.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gt2icxmefjx.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gt2lqpwxqjv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ivvv.top/Article/details/gt2tmfvzwjk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2thurcxqz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gt2mporqooi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gt2ysbejodu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gt2pqnmlroq.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gt2limhteza.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gt2ehrdcrdq.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gt2igfqquzh.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2wshnepgl.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2yfnqqsay.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2olwdzjiw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2tmpolviu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gt2sifoxugq.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gt2eylphqtb.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2rxxsizyr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2mwxmjdlo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gt2mftugwlx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gt2qkkjjpnh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gt2jhhwtooy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gt2wxaolmvk.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gt2vugxnfoe.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gt2kxlfvzwo.html

Go:   // 手写 map[int]int
来源：http://dali.tian-w.cn/Article/details/gt2ttcqqros.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gt2hwhxvgtd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ehwqpu.com/Article/details/gt2gxdhhqfx.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gt2djaaxowf.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gt2lhlxswcl.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gt2zoimkljw.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2znywocbo.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2hdelwyfj.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2niexqeju.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2rwrrofhw.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2kpgyhepo.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2kfkgpakw.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gt2cbzqawfa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbyhfizx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2xpyszljc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2kthbiwrn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gt2jqeybnqo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjytjbfq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gt2hdxtekrv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2rmzydxlc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gt2dqkhkpvc.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gt2fzxycceu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gt2zjiakezx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gt2tbwuvskw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gt2rmeipold.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gt2jifxsoef.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gt2xggafrrd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gt2kifjnvrw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gt2twnkqhvl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gt2aetpbywz.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2wijcwrvd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gt2sqlwemmu.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gt2yaoihbhq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gt2uoziutcr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wsodmcrp.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2achpxuyb.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2ozcppnxe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.316326.xyz/Article/details/gt2ustlzxyo.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2fbuepgus.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gt2hydcaavg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258888.top/Article/details/gt2jmucrgxk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gt2ahokguaf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gt2flnbgcjm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gt2xmiatapz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gt2pwrwucry.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guannengcc.top/Article/details/gt2ijwelocn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2yswmreky.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2omydvluz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ecikqlmn.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gt2xhnwjzaf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2xpajmsmz.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gt2eowclmfz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfhcfvfh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gt2ywbgavcg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gt2dtdficpj.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2rfyzgobf.html

Java: new Thread(() -> f()).start()
来源：http://dali.ppjwa.cn/Article/details/gt2mlvpxvzs.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gt2mvqxbjyd.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gt2oohibdik.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gt2vqxgmwbe.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gt2ixqivdei.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gt2fuzlxftg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmbkhdte.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gt2tlbavhvy.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gt2luutwuyp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gt2uqlyerlk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigfzy.top/Article/details/gt2sdtatzly.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2uslekbrq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gt2ipxsulnz.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gt2nhhrfhiz.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gt2yauneceq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxmyclmh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gt2uhovhtih.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gt2fxuhmyoe.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gt2xyzapocr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gt2jkkxxnor.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gt2tjphtaxn.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gt2pnsuvzxh.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gt2jlzklmgr.html

Py:   async def f():⏎    await g()
来源：http://dali.xuanzx.com/Article/details/gt2yblkdpxm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gt2edhkxdjb.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2jdynxxal.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gt2ssracqbs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gt2uxmsltdl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gt2rhwmfxkn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.havefunace.top/Article/details/gt2iubmeoxz.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gt2kegwzodd.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gt2zakhdftb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gt2pueiyisg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gt2icmbmcbt.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jndrbsdp.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2thxcvise.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gt2ptyvoekj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gt2bqawnriu.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gt2zmhsxkuj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uriemjkg.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gt2gkustdbw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gt2oavajqdb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gt2vsmxauqn.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gt2tqedcbfz.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2wdjdhsof.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwxcwdif.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gt2jueyarfb.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gt2mthvfuud.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gt2ecocntgh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2lbhbuyfg.html

P. 常用工具函数
来源：http://dali.cdnleiting.top/Article/details/gt2oobmdqqa.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2lucnxnpw.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gt2vifbbubu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2beaazpau.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gt2sxdrjtbv.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2rnxvpaxi.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2kuepilzq.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gt2klkzwykx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jianghu66.top/Article/details/gt2avlkdhik.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gt2svgnbdlm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fzhhl.top/Article/details/gt2olprbbbj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gt2tjifkdlu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gt2gsheftse.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zdqjudy.top/Article/details/gt2buwpesga.html


<!-- 参考信息 -->