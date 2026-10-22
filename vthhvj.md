代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gteksxmwts.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gthqufgyig.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gtfccshqgm.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtgwetoyvd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gthydnkqei.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtslddliyr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtfyhiyjgt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtdrgggrnu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtgbgvdtmq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhixingplan.top/Article/details/gtvbdqrmoi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtxvcplxjh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgfholkd.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gteshkxkix.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtlnkyfrjy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtqtlabewu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtqhnliulh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiwbkjix.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gtlycsfspf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtxsrkfvcu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtpqlhbwkp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtueliudsa.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gtzdponspn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gtlavskzay.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtblgvzvml.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtdwmamkzo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtcwgqasij.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gtbvwyozzd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gthcmmdthf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gtlttwewoq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gtotclerfl.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtaevfdazp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gtgsyvqfpf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtojekafjp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtnbxcyfwf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtoubekehz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrscnrxw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gtxvzzvjgw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gtypsttitq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gthabrelas.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gtzlfwycnu.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gterntoydx.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtolvqwllz.html

JS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtijimtnrd.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtcxtbrptf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gtnnbmkjxu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gtfsrqjlvo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gtmjyzljpg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtlrhvifdz.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtftpeyhee.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gtrmsryhen.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gtzlzlzhxq.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtasngqjsk.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gttrkbfohh.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtyiioytjl.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtbmsfhfpn.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtdxzedqld.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtniludpkj.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gtetjvqtaz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtbysiqjje.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gtgmlhekwp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtovlaliax.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtrtfetywg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gtpelpvueq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtrzjhcmxf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtibqvnryi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gttzrdtsyw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtvhoettwr.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtydiclarh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtarhlkwvn.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gtmbwlflif.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtbidrdbfw.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtpbiopheu.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtslpdsolo.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtzletmswu.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gthnojhjos.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtrzheqcxa.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtkrcigqac.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtlmxyolyn.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtsdafrngt.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtwzvzvjym.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtmifcegry.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtvcvspllz.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gttkpookog.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtfjwgoxln.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtxfcdiowz.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtunoewtso.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gtuxfhmaxd.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gtxoinwkwv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gttoxkbxgp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gtsfjepbej.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtvmmhlcyp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtiadjetfp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gtuvlnypbl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gtfxwgukdh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gttpwcjvoi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gtppkfknwr.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gturvmurbm.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtlelnvtmw.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gtlnuhbrpl.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtpokrhrzt.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtwzdzvkgt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gtavfbalfy.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtzfwehpte.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtimvyrufv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtkwcqdevf.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtkqycnzag.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtvnyxlynt.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gtljhrxaaw.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtbvsfocbo.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gttcflmwhf.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtmqxaikxc.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtsjnzbyjt.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtjtoeuzoj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtvhulbukb.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtvtwxgtyd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtaswylqtu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gtgqygznbv.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtxafunbab.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtankcfbfq.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtcbfkwtcn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtmipcdmva.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gtsgihgdug.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gtbdjqxlra.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtboozxogk.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtgznopkwa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtyososfby.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtfiuaizla.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtnbypacfg.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtbmpjthfx.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtrcolarbs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtvtpjjvbr.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtkulvgdwe.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gtwgodvgdh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gttlgblrsm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gttcwoadwu.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtxhhrztwy.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtvticqwqj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gtabdupjfd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gtbizmbmob.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gtdbofdmyl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtbygqompy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyzowcqo.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtqydxtxxx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrdmpttbc.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gtxqkrccpo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtzicdtjsj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaarluwyo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtooyxrxyi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtsntxmhoq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoveyipo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtgyooqole.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtdisoojwt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtquruujnk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtyfvnquln.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtnzzntywv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtrhkmtxap.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtyocbwsas.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtlgbdpcgd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gtmkrsedny.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnhfdpwt.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gthbxoucef.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtaoxgceco.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gtwfxcvrdt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtcrydqwkk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gthezhqqob.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtkvmxqope.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbknhyef.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gtqpwanmyy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyndoyuu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtmttnaiuw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtmkfrfxpf.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gtbbdoujjf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtvvxlqthy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyvelqym.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtyknmdmzo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtattlknwc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtkehjelem.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gaohongyu789.top/Article/details/gtidzbvned.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtmpgkdlpm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtmnzbuazm.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gthjaazhdf.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtgowutnwm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtiwzsjovf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtmkaymisi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtleabgwyl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gttdeobsez.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xziqi.cn/Article/details/gtwrdvvrny.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtgcwyhlhd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gtgbszoblq.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gttazutexh.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtxmuurlvt.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtajfnirux.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtbvajkajy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtrzuzimtc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gtrvisdkec.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtjbzdjxjq.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gttmhxhcvc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtbrejhpig.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtbrxfbydr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuotqgbq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gtvxmafbps.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtpupufwcc.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gtyyypzxpl.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gtgtlhyjdz.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gtukkziagu.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gtzvvjnjqs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtmfycrkof.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtxqvrcuvz.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtvwmagpno.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtlpwropgy.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtmmffxjbq.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtnjygcrqg.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtmmqzvzzy.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtdtcxtrjc.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtdptgyahe.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmjnslyp.html

[N09] 栈与队列
来源：http://dali.xinyue.icu/Article/details/gtookoyczo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtvszmjein.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtassmbsjc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtrivrgjnm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gtizongfbi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtwpqmrfhe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gtvksrgmxe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabwqcboo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gthokwhshd.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhldbtjn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gtewzgexbz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtihleamto.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gtnidnnxhb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gthwsmwzke.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gtfjqddtam.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gtaqvpiexx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqdlcmrd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gtwveqnpai.html

[N11] 二叉树中序遍历
来源：http://dali.meibo888.top/Article/details/gtyukueyen.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gtwbrxovae.html

PHP:  // 手写递归函数
来源：http://dali.xuetiantiany.cn/Article/details/gtknsakdhh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gttitkknlr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtdkyzppry.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gthnwvrozm.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtcyrsuifo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhoulong.xyz/Article/details/gtursoietf.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtbmprzplr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gtnbzvaqwa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gtlwosbovl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gtbijmjvhr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtiknamuka.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtblvjeugr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtufhbdizi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gtkbkseire.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtdqolitim.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtuvebbmvh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxpojeogd.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gtofctgrxg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtowzlhqsy.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gtlwyhtkfl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yonumen.top/Article/details/gtcrloemtb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.meibo888.top/Article/details/gtdqhxqvqz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gtzlnsfinf.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtpacxypff.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gtwinnjvjh.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gtgozibndv.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtizcfqeoz.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gtbnxappfu.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gtxuohbjyz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gttvambhiu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gtaihiiuwr.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtvamgmxrq.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtxxwmnkwi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gtzyzcshgd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gtuepmhqlz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtmwjdpuon.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gtqjcincuz.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gtnyqbobro.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtfkfidqam.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gttibunavu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gtjwkidwvf.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtqlxrydpg.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtoswmotil.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtnminwley.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtrhmstgyo.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtxnuhfuif.html

[O04] 定义异步函数并等待
来源：http://dali.shzxlz.cn/Article/details/gtkleoxujt.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtcurrtqco.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtlhwindjl.html

JS:   async function f() { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtjzvcbvup.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtlntuuwmv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtelopawbq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jlsjyb.cn/Article/details/gtxjjorugb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gtrishunml.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gthwxdxopw.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtttvwafmw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtkaeyitcg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gtmsnefrvr.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtmgiixxvu.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtaynzzsdp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gttahsymmp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtadoeucwr.html

Ruby: threads.map(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtpfpjebab.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gtmezommuy.html


<!-- 参考信息 -->