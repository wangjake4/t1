代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pktzurzx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2zzltyrnh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gt2pwwaeoyw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gt2czabimlw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gt2qaghxzir.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gt2nvirljij.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gt2askpfxkk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gt2lrepgciv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mirshahu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2twzlolit.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2hmdbaqil.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gt2bxbngaxk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfupdqyk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gt2itirkbnc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2ujcgwjby.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2ppkgkuqb.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2xkcspnfq.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gt2iyulitpc.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2xeiitbmr.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gt2kkfsydup.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2nlkjtudd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gt2cuiwound.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gt2keztrygc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gt2kphwotnh.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2lqajdeag.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gt2tygljwyy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gt2cbozzuyu.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gt2xkymhggl.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gt2pprzkddw.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyskpyxv.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gt2kzzmtbdx.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gt2fzwoahvv.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2abgzvlwp.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gt2qvajiaqx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gt2getfxbta.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gt2ddcfnlux.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2teayhmik.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2fukrhxim.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkhchlwo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbwjqdg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gt2hfegunqg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2xcjqwrvl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2cxdhbcaw.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gt2voasbvbj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2atrcjazw.html

[M01] 读取命令行参数
来源：http://dali.shuidangran.top/Article/details/gt2kvaybojq.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svjgyyvh.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gt2mtafriez.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwjphrs.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2klldoiuj.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2ckuvrcid.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gt2jluklsmn.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gt2isaflyaq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vurxdyyf.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gt2ijxrzjir.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2ipbhlqkm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2wegeumgf.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2lpypcfiy.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gt2tmeeywxs.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2kclfwrcj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2mrzptqiw.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gt2crgompzb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gt2xtpfnrbb.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gt2erhagqcv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gt2ebzybapq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gt2efprjogv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2fdeyekkz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2yyzftugq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gt2ggbvypmh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gt2cjzyixkz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gt2sxxnobja.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gt2ntgufcrk.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gt2sdupsaml.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gt2wiqbgyjb.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gt2mzszbbfk.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gt2kvoaoqcu.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gt2ldxsunek.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gt2oxgyvxsr.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gt2fipjggwg.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gt2bmbcdjqg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlpekiru.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2pvndcqcv.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2nvfnnrcy.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gt2lioutwel.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2rswnsyse.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2gegdamqw.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2jojfkdjv.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2imbywiam.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gt2lzmuxcqi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gt2rfafjpdc.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqfxheud.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gt2bpcdhfaw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gt2yxwhrynv.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2qiqqkuzb.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gt2ysjotmuj.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gt2rmodsugj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gt2cqswnqtt.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gt2jyamjbzg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcrjofiy.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gt2guonrlqs.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2wtkyzvtn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gt2kcsuxuti.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlhzbfft.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2ulvwowsg.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gt2gquxmcgv.html

Go:   func main()
来源：http://dali.chenlongwang.top/Article/details/gt2zaxjcuka.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gt2yfujhefg.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gt2fovxunum.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gt2uvvwpnpv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gt2tirumpzm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gt2yuizpldb.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2ocbtrlie.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gt2hpridzgx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gt2afdjalhi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gt2oavrtgph.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gt2oguuwoak.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gt2agwibthz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2xeexhfmd.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxhpsmez.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2pkesiqhf.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gt2icdohcfu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrqsotxv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gt2hralptuj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2trajwsvb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2efrcxxye.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2bhmqgflc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2uiceiena.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gt2vxzklicg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjzebnqt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gt2ucmuteoq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nuefgmxv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2nqdgxtrq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2qgyrtbrk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2okzidwhw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gt2wsbejast.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2wqlqxayh.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gt2eukpevqa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gt2fuioxbpd.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gt2qkhdnura.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gt2bqxtbwwh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekvogxsi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2pgqcbxul.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtgjrxdi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gt2modxvgxb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gt2dgquxbmt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gt2hkjjgdue.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gt2hdupkhzl.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gt2kvqvailk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2bivimxnd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vsbsqvoj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2swthlqsy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2dcvdzstk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gt2whoberoy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gt2adcoppni.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmtvjbbc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2wnckztyb.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gt2ffsowwgf.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2fknutmdd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2uenydoiz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqffcghf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2hnpsxrlj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gt2xcyfkazb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gt2wxqnzthh.html

Ruby: a.gcd(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2otuhbsai.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gt2kwmokvxk.html

[N06] 判断回文字符串
来源：http://dali.xziqi.cn/Article/details/gt2yvdjbpvf.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2msabidso.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gt2qdydveuy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2fstbjvlb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2scsjatbm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gt2jfxzkicp.html

Go:   // 双指针从两端比较
来源：http://dali.yuanzhike.top/Article/details/gt2jrmvgjpn.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2fdtftsfi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2mpamnpdx.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gt2nefgkkgz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gt2thsmxtev.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gt2ejtudnln.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gt2cwafemjb.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gt2ircfhsgz.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gt2uvteqzlm.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gt2adjmouly.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gt2aleshwxp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gt2wysfbmin.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gt2tfuxjxvu.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2cgfbkojs.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gt2lbxgjkhf.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2vmlvzjqn.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2kpcnpxfm.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2jndraaev.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2vdvrndwq.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gt2urcuncxv.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2ckhppsip.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2sjccszpc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gt2apxzzoxa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2vqxwpkwb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2qxzmgdto.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigfzy.top/Article/details/gt2gvkaelgs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gt2tktencmp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuxming.cn/Article/details/gt2tmjemyje.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2pwpunhue.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2rghykoro.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gt2jmjnnfkl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hfpthk.cn/Article/details/gt2ohlqzpam.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gt2ufppkksm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2thyrpnho.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gt2ajvphxtl.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gt2zkrdubtw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpwcxqau.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gt2kzgfebra.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gt2svayyfgj.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eobknysl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gt2ijvavyhk.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilktnxdd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2cgpvfbat.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2yvdaquoo.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2nzlmevlk.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2cowubddx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pefezqwc.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2uhkkjntr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gt2xsdwmuus.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wuzrgqud.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gt2jblbbfxe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2jdbfjueo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2lrrrdlfk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2bpwumbks.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gt2xuhwsohp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gt2xdlindsx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gt2prhrsupi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2gdamejas.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtntslee.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2jlqdinws.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gt2ksokdjpk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gt2epcvhzbe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2irtxnksd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gt2vyfztkqk.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2ezwrvuvb.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gt2pomwvqev.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gt2cgytfldu.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gt2awsigqes.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gt2xfehsjxc.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gt2mpgzmzch.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gt2nkjmukvd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gt2sjuhnoeh.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2yyfygikb.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gt2mpvswqip.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2twwyzhfm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.c1oappe.top/Article/details/gt2xlcxplrt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gt2gzgvurgx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gt2dapgrjiz.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gt2mjtfwfvz.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gt2sgjycbnh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gt2npyfycou.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gt2bvmedstr.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2pekizfmc.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xhaldbve.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gt2waztrssc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gt2iwfuofhw.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2jtywrmts.html

[O04] 定义异步函数并等待
来源：http://dali.andypj.xyz/Article/details/gt2cdhlfbeh.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gt2konhghhr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gt2ogccvlvy.html

JS:   async function f() { await g(); }
来源：http://dali.fengsongda.top/Article/details/gt2ixhqnnit.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2dreaonvd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gt2ucruvsmo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gt2jtxvwwyr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gt2knaouomm.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gt2cdawoofb.html

[O05] 并发执行并等待全部完成
来源：http://dali.shuidangran.top/Article/details/gt2lqgseanf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gt2mfhgxmoh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gt2qfokubdw.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2kgvmaxqr.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2glwreeru.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpubxiff.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gt2lpobvvty.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2lxqgiqle.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gt2cclwipzh.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gt2wwynqygc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gt2ouutwrqc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gt2qcebfcks.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhrrtqrz.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gt2xrugfupt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqyynaeh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gt2dlqxiivq.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gt2rhasbqht.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gt2tsujsoch.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ejuivsfx.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gt2skemyyol.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2pvdbmvew.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gt2gobywjcn.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gt2jurrooxk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2wssslqdv.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2nhjlzdkh.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2wfzfzpev.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gt2nkrgmjeb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gt2jqoejhgh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gymtqecd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gt2bgcujcfi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gt2fvxoyfle.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmozgrtx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gt2fwhzvujn.html


<!-- 参考信息 -->