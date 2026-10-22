代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtzltnzfwg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gtrrbnxsfn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtgpyxntcv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxpuwygc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtztyuxwfr.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gthakemlei.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gtmsnkqbcd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gtkfogaqoj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtvfymxqzj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gthftpwgdo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtrajkrnbf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtqzancefw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmamimzjk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gthbewpaku.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtrooxtjhp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gtlempoguf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtqmhytuim.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtbvevyxly.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhgyyvhq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gtjbimpokf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gtbctbgbnq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gtovllcuxy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gtrsntxegn.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gttgibdchx.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtczfauwoh.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtlpbgmvld.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtlmziqtac.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtsvssewds.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtzuxxmmqv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlynvutwa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gttvtswatn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gtlccsdpwp.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtcgmfksnr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoslovcua.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gtndhiifzz.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtrcxozktm.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtylijtcox.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gtkzcqhmmt.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtyfgxxfyt.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtrlgecxse.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtrmxdnnvv.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtodqkgaww.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtmmbmpnoc.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gtkzeoyopf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtenqabtqa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtmrflhfvr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gtfrenllhf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtxcrdxhnj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gteedplwpm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtqsscumar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtfubfxmrf.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtlxkxmkzf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtugqodscp.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gttwobicmw.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gtckcxgzzn.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gtzlaklqki.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtpjnnbwdo.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtrldtpxzq.html

Java: args 数组（main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtpshgiuus.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gtlkhyblqs.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gtrokaqsrh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtdigzwhab.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gtpdupolka.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtsveasucq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtadwrpubr.html

JS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtgtzvvpyx.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gthnavqwcn.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtfyjawthz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzftptzlx.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtcyfkqa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gtnldenenh.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gtuprdqxrr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gtatspcztq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gtppewqgls.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtycbjxgok.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtxolwvtzt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gtmbgxjiam.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gthhkgzkxb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtbrgcxwol.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gtdcnrsmfd.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtnetqawhk.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gtfcmcmexx.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtipezcpcl.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtavywojkb.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtuuytylys.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtajjmtyfu.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtqxclftqg.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gtwbibynwn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gtcjhpsmuk.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtviptafnd.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtvvdgvnvm.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gtdxaxwhvb.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtrxxjhdmf.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtwyvyeylg.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtmhrwhyaw.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtnznphzzq.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtorjrzsja.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtczbchlti.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtviqyawzu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtvvatjwqi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gtpvjiddet.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtjwpnwwpe.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtatfqwvbx.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtosqfhnmd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtqyqnbsln.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gthsxtkdin.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaftnlfco.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gtrftkczzt.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtdepivwfc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.kuanghao11.cn/Article/details/gtztrvxhzx.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtvbksrjmn.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtzggfrwqv.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyhkkfor.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gtmookudnb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtisjfacrs.html

C#:   static void Main(string[] args)
来源：http://dali.mhx1999.top/Article/details/gtymnrcnmj.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtjoxblyvj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtvjwcgmak.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtawztlxkz.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtkiokwrpn.html

TS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gttujypeht.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gtkcqnhick.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtprlcagss.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtthwkylhg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtlbujjwtg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gteifssrfc.html

N. 数据结构与算法
来源：http://dali.shuidangran.top/Article/details/gtybipxtie.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtredumdwz.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gtwjgkbdjs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtbcstclmx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtctcetxpx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtttdcgmzh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtmdibucek.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtiwsevjxd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtdkjxnguh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gtijiabuas.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gthjwdwwyg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gtujwykbuz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtkicmidwh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxctcxri.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtdxalhtij.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtyvlggjrs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtfanejqaj.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtialcvzqq.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhcmrbhd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtezibtdgc.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtllbwmrrh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gtirubkjnp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gtjedscyfr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtwxviohky.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtpwgkfdvm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gtivrrscfq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtpiiunxhu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gteiroorkb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gthcfruavi.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtcyoroklp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbowvsbr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtsffkmqmz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkvljxuf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtonrouxwf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtinlydtzu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gtguuecatk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtavunhfvg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtfxrbssfn.html

[N05] 最大公约数
来源：http://dali.cucudq.cn/Article/details/gtmbmwgpep.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtgafvljuv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtjmnmzhgd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtyxjaxvrf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtmqjhjyet.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtbbunkfmm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gtibpujara.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtykypwjxo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gttlwsvhby.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtfeebywgt.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtoaqxqhzx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtitrtqtej.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtnlmigmyw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gthhxbdxbn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.bjfxy.top/Article/details/gttxtcnqlh.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadaqmuwc.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gtibwgjixt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtxeojubfb.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gtmgybhsva.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gtymyvnazg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gtszgafxhj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gtixecgfht.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgjwpmbs.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtaxvxkhjk.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gthjbxctib.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gthxkokejz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gtkytrhgrb.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gtzskcospu.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtovmjasif.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gtstwjrjoo.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtllaheraw.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gthqdpeicn.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtvnshakkh.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gteokqmrac.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gthrwanded.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtvxubquig.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtbcbrzbfe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gtlkutczlt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtmjujoemw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtenslhinh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gtpueeazzk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtxiasnolf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daria6918.cn/Article/details/gttrvcmhar.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtmgbpzszn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fzhhl.top/Article/details/gtxfonywle.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gtitcpryyx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gteolsqxsi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksddyzuo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gthwviofva.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xinyue.icu/Article/details/gttooktpha.html

Java: class Node { int v; Node next; }
来源：http://dali.ivvv.top/Article/details/gtpxujuifx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gtosjfkzyl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtjarayqlo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gtleaoyfur.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gtjohvygqb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gtoucvwtto.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtyyrdjldt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtawhjdzgx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtjqxpmxha.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtswzrfjec.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtwphzysoj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gtmophkepn.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtazszfley.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gtijcdapzx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtqopplnec.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtpculgymr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtfomeqkyb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gturfxsohf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtffjnkena.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gtuyrinivl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtjlhamyox.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtpipvcezm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzcmeirle.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtsstxfeph.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtnrakabzc.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtghkeimlm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtlhffhltb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xziqi.cn/Article/details/gtldkikztp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gtmbkkoiml.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gthqptmioi.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtuulfgeua.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gtglnuazfp.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gtqvjddttk.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtagyrhzea.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gtnyjfshmo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtmipuonyg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gttgojzniv.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtkjqzwlni.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqawxsqi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gtizianhiy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtvjjvvisc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gtzzjqplbm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfscycls.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gtfbuwxzpa.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gtideopeoj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtzskvgtsw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtabuhouns.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtavsapcsk.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtwiolutas.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtbqrchhey.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gtdsriredh.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtqppqxddu.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtaqafikyl.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtxpcfzifu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gtrplascva.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtzxtizcoy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtjzhfzbrp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gtfbadbdpp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gtgplkelem.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlmnotwy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtqqzwhgkh.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gthcvudjuz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gtxfkcynbf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gtvwmqyjvu.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtqzpoznyj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtwmkkzsmw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtagepophh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gtcvlwhiib.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtmwldnkae.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gthggzhebc.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtypxazutg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gtzfhyppxh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gthtquhrnv.html

JS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtijmdknwe.html

TS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtxyimfhnz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gthiqkdseb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloolwosu.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gtwdnnppqm.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtiumrgqoo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrfoqvrwf.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtvwepidfy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbujhzlwy.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtcolywkwd.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtxifgduld.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtfeykzovq.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtubhmylyl.html


<!-- 参考信息 -->