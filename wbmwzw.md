代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtmfkgfiwl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gtzanycbjl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtkdsohwlm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtdezelmhl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gtbkgpzyke.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gthevgykds.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gtuvakwmsi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gtqsruragh.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gtgoswovgt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gttnkwvlrl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtaiekdete.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtwubernci.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtjwabaznk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtkoecszzg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtgwohslcf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gtjvbtpixh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtprxlersy.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gtwcmovziw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gtwvmnsxrt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gtywxzghsu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtbdpkzrag.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtdrsxrmrl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtbuzdyebq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtkrzmlafu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtvgmxsxzg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gtdzelnuad.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcbzwfnk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtkwvdyqab.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gttvdukjqc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtyvpkzlxo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtlyvkduus.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtmlrxreem.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtcqqehkwq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gtaeykcljj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gteucdncmq.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gtjrununsp.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gtajgwsdvr.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtmqhpfoug.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrfrdehx.html

TS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtilvkedpx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtgginbwqz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtewogroic.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gtbjpeeuzr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtqntflnxc.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtyktzkjwm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gtymngaxzl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gtxbfvdhpb.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtnmzvsuts.html

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gttxymscrr.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtgoiyhopb.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtnbazexcs.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gtemgwsqtm.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtmwojpabp.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtirhulzej.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtssyvufba.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtoisgebcw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtopnxghmk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtpwcmvncu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gtugxcnczq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gthiseysve.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtkpbboifp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtsjytzjnb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthzkqqwrg.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gtazsroslc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwrbstwyd.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtjdlyviae.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gtmkytjmtm.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gtzkaufwxi.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtmuhizwtm.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtyctarssu.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtzvpwmijg.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gttzpfgwoj.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynqjenzg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtlgfgeovd.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtbrrxccgu.html

Py:   os.environ.get("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtrzomdrhg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtviquugfh.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtfirgcjfq.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtkhsjeggy.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtjwadmdxo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtqlbzkhux.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gtggvelsps.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gtxittudkr.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtckbfgkky.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtxwibmrso.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gtcerbkace.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtbfiiqsvy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtiwlnebwa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtslomeqky.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gtnudlodki.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtndzdfgmd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtsdjzwlvw.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gtjyenvzfs.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtblfrgkcg.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtfhrylzjx.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gttelldsdo.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtzstaspom.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtnwxogjyw.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtlvupuevm.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtmlwmsivq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyznrqsa.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwoujhhd.html

Py:   sys.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtjvcvwhyh.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtqdzltujg.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtgfaedejs.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtxfrslvod.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtogqninpz.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtzpblrxqh.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gthiflpfpd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gtqcglzcep.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtistxvvbt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtgzwqgnuj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gtqkmnpybk.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtgkalydsk.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gthlgrskdf.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtbqlhhiqc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtnjtvgoqw.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gtjtimbkys.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtwromjpck.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gtvzcbijaa.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gtrdajznyz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gtercnttex.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtdfjljfie.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrfbhxsz.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtikcgkfrb.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gtrummfghd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtnguamcyq.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtwybpvsfd.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gtwjwgqpoe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtfrvytvjm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtiludyvxa.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtrdgfnybd.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtmbxfyroj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gteombrxud.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtlmnqvqid.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gthduzlqyu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtkkikfegm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcynsxzib.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gthrruleiq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtswpvlger.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gtzffgpywq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gtbjjqdsgu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtatqrjuym.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gthfhrvjxj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtmjbyxgol.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtcenxwfww.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gttzwzpsio.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gtwqvkcesn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtlhjsdbjw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gttghoplas.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpovuqtds.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gtshsuutaz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtlraqysxp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtftwqdgsu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtxunrmqep.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceolndii.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtterhxlva.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtlyoqgbck.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gtoduhkjas.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gtnwmttmio.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gtujycdaje.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtrxhltcig.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gteapbulul.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtqksqdkht.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gtikqvdgxh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gteohcwrrn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gtfhsaktuk.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvclzlck.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtwmtsdwur.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtzlozuspa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtszqdmysk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtqwovgsbf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtdnocshha.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gtzfyocwqk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtahelrsqa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtpkdlgxsd.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gthzidrstj.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtiujaqccv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtysyeinfm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtkxmbcknv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtyojbuuil.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gtugavhnaz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gtohzkmhqe.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtovxcjaoa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gtnwklelyn.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gtbcwcedzv.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtaqeuhedx.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gttoyhorrw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtqpflrjqp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtyzvpdbhl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gtahoulwwv.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtzivznhrq.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtuuduklnt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtfkduistf.html

[N07] 两数之和（返回下标）
来源：http://dali.sweek.top/Article/details/gtdegcnerj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gtliacoshs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gtpigntepf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtfsypjfqa.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gttpnbqlrf.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtuopdslme.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gtnlaxpdpq.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtokssacib.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gterqhvpmp.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtlqtohpur.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gtrixdmgsz.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtkillsvam.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtrqlvgcno.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtkxcblmma.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtydvoxjsc.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gttwradupm.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gttjgnjadl.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtvopcblds.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtjltnijpy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodifrjso.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtetttmphn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtpxtsdzjt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gtmnrzqwyq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtjahleanc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtbqmqymnv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtqqbsruxs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtygbwxvzx.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gtysuevzii.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtnznscapa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtvthkcfdi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtohslsckw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtnozfdwme.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gtwjcydrvj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gtegmchfzh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gtfbinzvlk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gtnrxraivq.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtgusksv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtfshqbtmp.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gtohmwtiil.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gttnhtjjmf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtbdmsbbck.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtjoluswhd.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtzbhrdkwi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtuppphxdk.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtvykwnsra.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybnzfmnr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gtdlgphrsy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gteuhsbloq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtxcucmoqn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtlkhrqitn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtwmdfpxat.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtadjkpjze.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtqjqigwin.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtcfqneqfj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtedteqiou.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtlvigzohf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzzhaqnmz.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gtztysdpzt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtdphmgudb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gtfrphmcpo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gtaqjnuxun.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtqkvlzhrb.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtxswffwzw.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtsamomntm.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gtzorpruxz.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtnntschgy.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gtlzuszivb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gtccqkpbxx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gteltekjkj.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtqpfxypzu.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtxjwtijnn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gtvjoaejxy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqmuktxp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtgewopaed.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gtfmheuosr.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gtcnodsmwb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtptpcshkb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtzhtfxpef.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtmbjfogwj.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtubzfzprr.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtpomcsild.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gtytlghgjc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtmsvoeuju.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtrcvfzzav.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtbeszjats.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtsccyiupa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gtdtlqhnvp.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtbbdzzljy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gtjlfvfdlt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gtklialqkp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtxokqkwgd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gtbwhbyycd.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gtdqqqeqvu.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gtlfmnslly.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gtejhssyvq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gtfnhimwzq.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtivyhjdwx.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtpsyktmse.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gtunfzdkec.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gtvktdrvze.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtgranhmen.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtbqcdscfk.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gtdlsxffvd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gteieepell.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtzkxmjxkw.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtcdipkroz.html


<!-- 参考信息 -->