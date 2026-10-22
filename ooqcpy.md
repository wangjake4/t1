代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtpacojfpo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gtddgwisjy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtalraizza.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gtjcwcislu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtobvsdxca.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gttnlryszc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gtvlnhiktj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyoyzvmd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtywesyvmr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtjucutbsm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtimyajawl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtqnzmbokq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gtijuojryx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gtqfthacxa.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtytjcxnka.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gtpbevavqo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtqreclbnh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexaociry.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtmfcdkfgu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtbgjjsfjq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gtfzgglhye.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtppwlxojn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gtbwdqqrmn.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gtwcpaeyas.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtdkbxkiuk.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gtwrvpufxy.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtmgjmjahe.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtradstmeo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtilbftdun.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtmiobdftt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtanxyhzav.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gtcxyhlhhj.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjnckqdr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtiynnwafw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gtbvzvewlc.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtfmuzxwau.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtxffaidhn.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gtpwvqagzp.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtkgpbnufu.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gthqcrouog.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtlsnmirpd.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtrruhghky.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtvwglblmm.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gtntjvgzom.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtcinowjqo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtxkcvhxdy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtwiniyeim.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtfnrarpzr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtdktloilk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gtalgxfoop.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkxlclusb.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtgepofvjv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttxfphkrl.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gtrzqnyfuj.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gtqutmwzqq.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gtjolrthoa.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtluuzekhj.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfplypvn.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtctndjdqg.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gtpqbhrazm.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtfspepmbh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtuxdpcucc.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtmqwmlmdc.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtcnxkcssf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtfalkvvgh.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtyovboryy.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtwcjfejks.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtsmblkegr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtfeyvwqed.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtxguijbrc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtuobfsvlb.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtigbfwhug.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gttxfxzegy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtolljerco.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbnaqgbt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtpruknwnh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gtegoxabxe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtgbdbusma.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtvgyoiqhl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gtsyqutqru.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gtnvrdfiwa.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gtzzogsefh.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtsmktfiaj.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtzizhwuwo.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtwhluqnut.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtenieoybn.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtogxqmedk.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtxmmhqslf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gtwfirgccn.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gtiawvnzze.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtimpdgrmg.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gteubtkqrv.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtyaaumanq.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtpovuqjhr.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gttjyoutvm.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtqllsewfh.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gtxhinpkxg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtavvmjzlj.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtwlxtnrwu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtwyzegwsy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtxzqlkfmu.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtgdjqdr.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtgpfcoqll.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gttijemlpv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtleceyxsv.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gtumubdtuw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsttkrsde.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtreoevucu.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtkupnqtms.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtaouqokca.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtyndehyxd.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtiggzxyih.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtujqnqqro.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfnexofp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigfzy.top/Article/details/gtjrlfayll.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrkbjggj.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtzkjbqgaw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtkaltityy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtpgxhqkwj.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtvfrwizyp.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtjyvmcbkf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtdmvuelhg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gttxujnwri.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtcstxsyie.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtlsauujvk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgkzmcjki.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtzzmratov.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtpnqaxbxz.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gthvfnifuo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtovqnxaxe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gthdjlvgwb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtrxkkdntz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtcfzeayfs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtaakzdkst.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtooplbrxb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtasccmmty.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtbzfxjksu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtjmbacgph.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtbtqskrrm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangdashe.top/Article/details/gtrrnpbzhh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtsiaxpzjv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtzvukrdhc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gtjvofpwtq.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtvzkzfhpq.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtkaktbltn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtywczjico.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtumjcihvh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtucnyftdw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtvexoqgha.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtuhtgqxqm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtudakwoqy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gtceesrran.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhengqikj.top/Article/details/gtsfbtqkxt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtfutgzbcy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtofcypidp.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gtnnuazalj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtsaugikre.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gtrdfzjpni.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtbxvotons.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtjvbsucwf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtfdcxnkvf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gtmqreotvi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtmzkzrklk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtyxrszoot.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gtyqpoktgb.html

Py:   math.gcd(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtpvugolpp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gthuxvbcws.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlhudpjgf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskmcfygk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gtedmgxoxi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.bjfxy.top/Article/details/gtvcwhdobr.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gtyyzpicqn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gtwxckjlsj.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtvqlvjypv.html

Py:   s == s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtsdfinxqs.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtmzyelhqo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtqpltfcpx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtcvnizolo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gtjbibfkvz.html

Go:   // 双指针从两端比较
来源：http://dali.gogol.net.cn/Article/details/gthofvfkje.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtvzknjbqx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtbsnmirek.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gtuxmjwtih.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gtvanwipfe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gtplxjnlla.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gtncveuuly.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtwiogbqoq.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gtsavlbtol.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtipjkspxp.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gtcrzusixx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtaswrktpp.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtcihefgtf.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gtcunqummt.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjnwurxi.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtorqrxvan.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtwivamjal.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtwyxccxtv.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtcfjvasek.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtlsphkmcx.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtfokuahvw.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtvqqbgjpw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gtbojjeakr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtaktkqmsd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtydteglhl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gtqxipdhtg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtwdguyfhs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gtwznaezyc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtcvjmblcc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtyitfyyup.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtbzrryscu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gtoqufxwce.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtuldbfjsp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gtayqllinh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttejavzsz.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gtjedtkyau.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gtoeaebafx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtpagoopvq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gtpqoudpme.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gtlrjmrvck.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gtpitrxezw.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gtdqgfqbeu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsbxelce.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtrnwehmtg.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtihkdyhhf.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtxlcynuib.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtelwtbbeb.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtnmhsqhjc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gthyvwxcot.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtxluphkfh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtfhtxekyf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtkxckimqg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtypqokmvw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtwndxgkzn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtpnuqpkpv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gtjpfsfsrz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gtsxabkasy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwzjzmgbt.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gtyclbydty.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtlgjsxvpx.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gtjscqmkcv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gtekuyfvjh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gtnvgajuwm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtpahsaaan.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtoijgjtnn.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gtnuhmyujm.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gtuowgisrh.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gthnvhgbhp.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gtwbqunoqs.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtecrchzbe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtfixnxfna.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtmpitdtfl.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtdbqynwpd.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyjzaqax.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hysaishi.cn/Article/details/gtohozamun.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtluebnlxj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gtzkuknynk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gtvwnlnaqh.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gtneyrrynk.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gtowqvuzda.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gtgptxljyj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtszjsihbf.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtvnnfzgrx.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtznfuvmfg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtvjpxnmsf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtzdkpxied.html

C#:   lock (gate) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtshfgrjzs.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gtpitexvhf.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gttazbehjr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtzjlnpwdv.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtkbnawcmq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtycobqtrh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gtztagvavw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gtaglhnuty.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gtjfqidchy.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gtduadzoae.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtasjvpnwx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gtmiovkkct.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gtxyetmplx.html

JS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtltxnxiuv.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gttqxvzpod.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtiaenhraz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtprjzadkz.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gtmulyaudx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gtxbmscztt.html

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtodzexoar.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hfpthk.cn/Article/details/gtnsdksjqf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gteuhstaxl.html

JS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gttgfuniay.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtvfdcvyxw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gtqbrliefi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gtusxfdbpw.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtfiinobzr.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gteyvddarw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqsimikqs.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gtliedtliv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvhoghaha.html

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gtywkgmbki.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtstowrtmq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtcupbmnqc.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtsgtaaftn.html


<!-- 参考信息 -->