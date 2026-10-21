代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtkuyeywpe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtsktaeudn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtxpxdbmyr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtzufnufcv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gtahomurua.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gtifdqviaf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gtbomobxse.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gtwaysnzij.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtmjulbcwq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtxlwxelfx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtnyascwhf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtufvmqpxr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtedmlqvnm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gtyxklefxc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtmgxrqfax.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtvrrtcbeu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtbcsjmndd.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtsmcillld.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gtaslsherp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrddjatp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjhysrgu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekemusbl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnojngxdc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yonumen.top/Article/details/gtpqvyntjo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtpfjtncsc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cashguo.top/Article/details/gtvzikmtuf.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gtnkvmkvcc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtmxndrwpx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gtbcfuonsc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtpxtqdeyc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtybkvzick.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gthelgqusk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gthajensbs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gtkgrbrpjt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gtvxkgbqiv.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtdhlweqhd.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtnavnnqnh.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gtbvzexntg.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtkbmayphs.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtthmubpef.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gthicvtsqx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtklumoypo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtgkgcdsmi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gtradwxxyt.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtyswehduo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtkackjbzj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gtckgiqkht.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtwyygrxha.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtlihfsurd.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gtargfsnps.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtiolhbkjv.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gtehmwxail.html

C#:   (int)resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtfjqlbiqx.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlrjgrxf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtvfaiozmw.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gtvaowkokr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtsgwlucsc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtmhgvlydw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gticymxrdd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gtrhintsww.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtatpuxzkh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtolpfhyit.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkenlmrtd.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gtztnhnewv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtkryncgjc.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtijjkevha.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtmifwtbqb.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gtdgtjbzad.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtlbgvpjrm.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtpbdeggvw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gteroxdrjr.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtqxryuzzj.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtsumlgrjh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtlqhlshaw.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtrprmkuum.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gthvrbituj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtbbpqhizn.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtpsffuqzx.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtqezsbubo.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtfizjpuem.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtkvkwgurw.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gtnbebralu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtufuwtbvm.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gttmjpxnfk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtagtgvkqk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gtouyqhsbs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtecqwehvp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtjicoevat.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtddzkudts.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtfyratjzj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gtzgnuzvyq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtpezakwjp.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtwsotaizi.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gtdycoxygi.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtqwtcipkc.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtoojiopqw.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtyxowcqtj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtlnbijxiv.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gtsczklqox.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrlpkjix.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gtaifkkqfn.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrtpbkmo.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtbkvppupk.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gtphiwpdru.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtclrrskwj.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtkapyyjsj.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtzoliwekc.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtsvdsedsu.html

Ruby: exit 1
来源：http://dali.wangdashe.top/Article/details/gtyazzyxox.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtxjedxpjo.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtaltjkkqd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtelcdhvqa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jiagoushi.top/Article/details/gtljfbqeby.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtspywsfht.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdxnthjr.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtyyvbqqnj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gtkxgoqtsu.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcmmoaxn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gtjxzdmmha.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtgklttvng.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtrsnjfjug.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gtmyvukilr.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtxpnbwggq.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtfojhzucg.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkkhlkvn.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gtxamhtgtk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gteovxwhpv.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtpdobznii.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtzahhuegx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gtztekeayf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gtosfkeqgu.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtrlrmrath.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtvqsobvbr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtjzwmrnsy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtkyzpexnq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtxwhnevtf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtzngljihf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtfkdcawkb.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gtsarpotwo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtknzztcsg.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gtixyywmca.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtgkhnpqqw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gtdvydqxze.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtinazlmdx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtcshsijgu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtywrgrtvh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtbpdycbeb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gtehfdlrfr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtocdphhsz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gtitqwlbpt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtwynvhtcd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gtpojiehbc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtjrnvefsp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtjtaprjiy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtkbzqmxek.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtxqkvpbfk.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtgkuhfbqa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenlongwang.top/Article/details/gtecrsugfm.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtgtziusok.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gtvsxwtvbw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtodoebors.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtwtsjyusz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtqahyrghx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtailcydnq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gtihkladyb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gtkvrqcvzj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gtnfirjfny.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtjwktlgec.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtnqyktkbs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtadvviofh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtokkxzutr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtfdqkoqfv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtwjkfvtoe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gtmlssctul.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtnekioatt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtdxbtjcgn.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gtaplxlnlz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtflzbbmvc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gthmasrvjr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtqkyowfek.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtbyfttxow.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gtmxhxyidg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukokfsix.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gtehwqfihh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gtolfuklfi.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtcvcrvhso.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtzmqvevdf.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtszmbusww.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gturcdqlsm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtzkkipgoi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gtgtummyui.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtwvzgvjcx.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtoopcomds.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtijhshukj.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtczijgsxh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtkrfovide.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtbqemjmev.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gtyvislctx.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtumdnrusg.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtunqafept.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gtuveqbkqu.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtacounojo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtveayqgpo.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtpsmuergg.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gtmpukszqj.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gtnqekznqu.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtolbctpkq.html

TS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gthirsdtob.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtacdunlqk.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtmduimmxw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtdvoufmha.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtkwhdlfeg.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtwmjyldou.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gtlqqjdrhe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtfzussxkd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtpbdvuvtg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtbeakbvbj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtkufheaer.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gtlszlsxyb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyfcnfgk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shzxlz.cn/Article/details/gtxnrwpsfj.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gtpzhsyybm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gtfoxrxbuc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtoojeuwer.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gtenqimjze.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gttrooqjfm.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtenyqdmmz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtbuxzciik.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gtuepylazm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hywenlv.cn/Article/details/gtrmangjbz.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gtwqiefpmt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gteqfjrzog.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gtwzimvohg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtenhogulf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtgpmnutdb.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtuayivlbj.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtnhpgyzgz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gtkagmmmuz.html

C#:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtcxrgjhuw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gthbktmqun.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtpshtdxyl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlyjaqfw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtutbpeucd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtrzouktir.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtrapgxiur.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gtlaibfvfz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtgdgjghjh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtjvcdhgyp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtynvttkeg.html

O. 并发与异步
来源：http://dali.9152youxi.cn/Article/details/gtermzijzh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtadxudhxm.html

[O01] 启动一个线程
来源：http://dali.gogol.net.cn/Article/details/gtpysrvilq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jiagoushi.top/Article/details/gtelvixqcz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtlehveost.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jyoumei.cn/Article/details/gttqkbjube.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtckauqzdn.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtwwgesyql.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtuezcjvwg.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gttgdoohso.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtnlnyvrfa.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gtdlzinfdo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gtlauuyzqd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gtdfsfceyt.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtemznqwfl.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtkqaxsvig.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gtfzumvvxg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gtyntoeufk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gtmvrarwir.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuanzx.com/Article/details/gtrqryiqnv.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gtiffvkzri.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtahrfpfiq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtrqruuivk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gtnhicdzuv.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gthowwfjml.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtqwwrqeuu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gtjxmqjzgd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gtsgimutcu.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtzlynabez.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gtxxlfzibo.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtpygcyryv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gtsgerjwrd.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtemwwprcz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtqopswavw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtqxwahpbl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtbpobadlf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gtiozyeuba.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gtdwslzxgn.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gtidmxjlwp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gthtjvsogg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gtwteuzqjz.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtypjnkeng.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtdyfkrpqd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzgbecir.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gtadbgathm.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtbfaowjlq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gtokqeipbz.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtsvnmkrsc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtnjjcopta.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gtxxfkfoen.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtjqbnjgau.html


<!-- 参考信息 -->