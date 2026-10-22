代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gtvgaszhna.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gtolbjzzot.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtmktnxodk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gthgxrmrsl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtfpjhlckb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtmjqnkutm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtuscfykbx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtvshojizw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtmdjhuywr.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtqwejpfbu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gtatpnxhkc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtqsglwejf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtgealbeuj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtaczquelj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtzyamvudd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gtagsnpgub.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtiitnoloi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gtanxrdxkm.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gtrryaizxf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtrdktxkia.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gtuhedsczv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtjpobkdly.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtqzishttb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtookwacpq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gtwtlmfcfd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtzotdwhsp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtxgzoejpf.html

[L06] 解析响应为 JSON
来源：http://dali.birdmap.top/Article/details/gtmfyipxrw.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gtceplxpli.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtumkbvayk.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtihafnnxy.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtfmoiijcz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzctfneo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuxming.cn/Article/details/gtzyikqvxp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gtblowchmc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtnczffjcj.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtwnplxyjc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecltvxec.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gtfgklysry.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtnookgkzo.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtdjqjfrhx.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gthjvrudak.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtgdsqlslp.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtbjlfaqut.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtcrpluzfu.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gtgqnygttl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gtpaxgdyhc.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gtnkyooqbq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtdwygydbf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gthcgwjxae.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtokkmqzag.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtyfurifaq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtbqsxaugs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gttcgvdchb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthulgmgyy.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtjfdrjicq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwuhqhwbh.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gtgujtenqd.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtbupqwqbc.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gturaqiejg.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtbricuzpv.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtayrxnvjz.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtvtorygyy.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtffyizuer.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gtzlkmvewy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtxaffxinm.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtsqdgwmal.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtwpbzahiq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtntetsgwy.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtpiylxxjg.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtbmxunbwf.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtdlxvdnpu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtlnmkownj.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtvhyxkxmq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtvgaorkrm.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtblymmqwn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtydvvgtvn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtduwngdes.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtxdaynoyx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtemspijpx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gtfrfvydxt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtkqwkjpjm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtqickxgfl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtdbkihcqx.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gtzthflnlx.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtihcjscej.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gtsnorhlyt.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtmzzvbhgu.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtnndqekyq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gtrewgpsht.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtwrjhxzkc.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtokkgcvwt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gtstspmqas.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gthqjseplw.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gthqobljpv.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gtgfnoyaxl.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtomnplnrv.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtvqjxeffo.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtqjbjbwtr.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzakuilzn.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtbsghwqvd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gtbdytbjcz.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gttjzjebtg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtdqochora.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtbhpgtxcr.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtlrmphywt.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gttiqalpys.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdodlcenz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gtuoppkycm.html

Ruby: warn "err"
来源：http://dali.nanxinkj.top/Article/details/gtykwqxkjq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtrtrwpmxm.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtzctwhmpe.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtziwnjnvm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gtyolweume.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtcurfzawz.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtegjpgvdk.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gttkazceam.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gtjsxbcovg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigfzy.top/Article/details/gtgzshzleu.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gtvmntnapq.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gtuhokvhrn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gtioskjtfa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtvpcnwizo.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtwaaqonkp.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtahvxbaxz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtjqjlltgw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gteljtjvqt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gtdlbpdmlf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gtwxhnqtjg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gthnfxxzza.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gtvwtruquw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfsabuoeu.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gttyeypfgq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtihfbufss.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtkegggsnt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtnujiiqaq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtcjwkjavu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtgxpcqedz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtgnhddjzc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gtozcjgpzc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtiagepdjn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtcvesrapr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtzjtfdcej.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtrrulvqvt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtlscyytun.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtfvvkrznz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtvmzhjsco.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtywukuzfa.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjddvwvv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtaxfukh.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gtauttnciw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gtvkurcfbd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtnzvvhric.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtspptrujl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtckxdjftw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gtfvhxxcrx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtqqzouryb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gtritxvaeb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtshcpmqwe.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtnupxnyvv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtynnzyekf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeiouclp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtxjdilkqk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtsittkluy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtawrlddah.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gtvogwyxyo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtkeqtpqkj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtwlraiefy.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gtfznapfwc.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtdgthnxnd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtnmrhmmoh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtxiqpybsp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtdqpphgeu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gtyvvvclxy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtovmxefbx.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gtcnrrxyec.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtodxwkmrs.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtdwmxudnc.html

Py:   s == s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtyfbvelds.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtihwwrqze.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtmboqbdte.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtxsdgtfaa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gtegprislu.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gtazyujkei.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkotuqgq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gthpnhdoyp.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtjfffdgcq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gogol.net.cn/Article/details/gtwwoinedy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gtmxpnagti.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gthopgofip.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gtilshntry.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gttdhhskco.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gtectgblyn.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gterruldej.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gtnthqhcik.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gtogdprhtm.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtyjkpmvps.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gtfnqraxkp.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtvabxhirw.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtyrwvdbdf.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtjukhcvuu.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtcwdgiukt.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgufenzy.top/Article/details/gtxpgaiadt.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtcvahdbbr.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gttecjonkc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gttbxlrioe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtpkqnzkur.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtmjdxngoa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gtfmnuzqdc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gtatojqhgp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gtlaptascb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtpfjtrwwx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtjprvahsq.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gtqmyhfwpa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gtnhnpzkxc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzqcooxtu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gaohongyu789.top/Article/details/gtiqvgbpmh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gtkxbqftxj.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gtkzhapree.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gtpxlehscs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gtdxljiuup.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtiyzxsmdv.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gtrfovexmk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtcnqgwjcx.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gtnwwgckyf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtdeixbkis.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtfvaevsse.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtgulontdg.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtcbagekcx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gtofivelsu.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtigcmkjwk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gttyncqkkz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtwbbhpsuz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtmelmrojc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtmmcipyxl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gthgozzkgo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtgnjpkvvt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gtbcokmzwc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gttohubofw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtodhwvtvy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtihchjuat.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gtgwdaeaps.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzrtdiapt.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtqyhhteat.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtykpzmbwg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gtqurgxwvg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gtzsgdbbwc.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtygnyzzeb.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gtodfjhydm.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtdftveann.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gtkefzymxb.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtubuttopu.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtcvrkybxh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtaeuitkos.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gthtbnpmgk.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gttuwtiduz.html

TS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtmcbhdkrt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtkicuenbt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gtqpgibzly.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gtguopktuo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtkktqfyxk.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gthjarepnq.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gtftbwfppw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtkoofwwbf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtdffhnuwd.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtpuuwpyxc.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwrpndkz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gtonpoljhe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gtdnceyirb.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtjpemxdjh.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtopbhifht.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtbkyelkhz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gtswxwsndz.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtjfnasuae.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gtfhgyxovw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gtoogllxqo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gtkwhvpldw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gthjteqtmr.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtpvwbplww.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gtysiajrbx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gthupbelou.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gtqtkbsdzc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtmflstbbp.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtmnmppysd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtehqmmauf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jlsjyb.cn/Article/details/gtrfexxxzw.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtlafrglxe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gtrtjwqfiv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtpgoydmsl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gtwbsttewh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttktjtcqx.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtschpxgnn.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtexdopbkt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gtikqkjkpq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gtjtliqgri.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gtjgjhxmsc.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtrsxespsl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqcbeyyce.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtgfksmqmi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtujvjlxgp.html


<!-- 参考信息 -->