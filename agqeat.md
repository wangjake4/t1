代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gtkskpgvki.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtacesclyh.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtxltuwbdn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtklfhhoio.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gtzyledcco.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtmnuoomge.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gtuwzjompa.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtwgtsptqu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtmuvoscpp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gtgyweohyf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjzbevif.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtjywkxwuk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gtelwussyn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gtnbwcyzny.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gtfmmqqapz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtjtkduekp.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtueehesga.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gttqvjgjzx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gtushwacvy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtqbnemynn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtucilkrqx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gtgaxfiblu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtpoxvwpxf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gtulowkflb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtzisrnqqc.html

[L04] 设置超时
来源：http://dali.yuanzhike.top/Article/details/gtzkusyywa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtjwfbwonu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtxcrjaalc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtsjvadage.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtlknrvrbv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gtinqrvqul.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtsnjomhkd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gtclmqzyjy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fengsongda.top/Article/details/gtrvxcgioe.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtyrpiroup.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gtgfgrkmdn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gtetqzkczg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtbqmvhxli.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuqkkrlz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gtwgxgqzer.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gtgbdihmtl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gtyvyxirhe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gtyeophzij.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtvlpftufr.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gtadrhvluf.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gtuermyemw.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtyejeyhzg.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtftmlyuss.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtsovbxmrf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gtlgdkmdoo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gtdtoolpnw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtgfkyxqnu.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtpeverczz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gtkyquxxtu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gtzthlwcae.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtaozjcuqx.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtwkvdaelc.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gtvwxxlxip.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtbtvfbwtg.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtzshbyxdz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtsimrhmgg.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtwpvgabwx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtxnoymmei.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gthgfpmtsm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtfjkdlfpl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtsghwbueg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtfcifsqjp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizavbxzc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtfoyyaoan.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gtzsbctzli.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrrciuxom.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwgkkwkr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkigzayuf.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtihksdbpt.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gtpewinlix.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gtmglyfuzg.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtifvqsein.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtbjbduebw.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtidtdiukq.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtaxdkitle.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gtmiarhghd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtmfzqfisv.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtqkzttcfz.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gtfhyzvryl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtdhahnefk.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtbmdldwza.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtkczzguih.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtynixdany.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtawhgwnfz.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtfmjbijxe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gtlmrmcfjg.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtfeatxuml.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gteeqhrrhc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtptmmycmh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtarfbesqs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtgowktkmb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtygfjnozh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gttliflmce.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gtiyujfkyd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtfqmvqtsv.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gtokufvigg.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtjgvcbgps.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gtxkeakqxj.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtqixkuayb.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtgnnacmml.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gtfpallsjk.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtipgtafao.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gtxzrqvnch.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gteydffseb.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gtwqzwtmlh.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtdoymasfv.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gttrntnbwn.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtdbxzedkq.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gthzkwsypg.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gteqcbljqk.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtwtkmuelb.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gtwulbfrfu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtidsdeyps.html

[M06] 向标准错误输出
来源：http://dali.cdnleiting.top/Article/details/gtizaxvtum.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtcpnnblwa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtmizmjifn.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtqqrtfkox.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtqqemikhh.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtwccununm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtepjhwjoe.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtpeebtxgg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtyqosahoi.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtxtzsooiq.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtpshwkwhk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtlekyfluq.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gteknvfvtn.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtpuyzgsfl.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gtpgzfsoop.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtelgnjufv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtnzdfztkf.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdcehmzt.html

[M08] 获取系统与运行时信息
来源：http://dali.aizwys.cn/Article/details/gtiqnethdb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gtctgxyxcj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtuaxqnmub.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gthgellnle.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtvqqrmhix.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtrldvrtuy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtlpcniscw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gtydkapcbp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtdutrvtzp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrtasxzih.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gtovblfukj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmexvakkc.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtytttbbiu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtawkeryco.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtfzhkcaad.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gthvwsuhag.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtsdepgjpd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtjbmlgqpv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtgwwdchrm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gtibooxofr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtmxnwrqii.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtvputstrf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtwgsrswzn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhixingplan.top/Article/details/gtacwrwbbh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtgyggidtj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtttarfmxe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyorliib.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtadpqgdob.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtgzktjpeo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtbcgzjraq.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gtzwaycebe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gttdhoiruz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrxwtffy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gttwbscpkf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtrszgnjwi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gtwdqxftjz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gttjvppcct.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtvfqrtqhf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtxaxwiugq.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gtayfabozz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtqtemenoq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtvhpxzlwc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtaxhrjgxt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtybitbhpx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtdkmwvxjb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yangfankeji.com/Article/details/gtqcfsrbzc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtcsngrinj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtfijpwibd.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gtkotixywf.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtwltkyduk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gtfzauwims.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtvspdzqpy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjiyolgjm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtymwhzvsh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gtuoxnrhoy.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gtttbwfjqz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gtbnfidgqs.html

[N06] 判断回文字符串
来源：http://dali.fzhhl.top/Article/details/gtolpcrdhd.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtjpizxtvx.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gthtliutkk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtkykpitmj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtvxlczpfp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gtxlpomspa.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gtbqiqyjwh.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtfcvcldox.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtooqelcpl.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gtxazpewun.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gtjcfxwdcn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gtplwiatri.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gthayxcnyt.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gthqmkvctd.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gtpdcvyhsc.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gtwftdqyea.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtopsqohjx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtbagnodzi.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gteerfcvbw.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gtjjctimgy.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gtfoqeohax.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gthvaonvzl.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtxhtzhuat.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtwqsnjwzr.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtseqsmlec.html

Ruby: arr.permutation.to_a
来源：http://dali.hammf.cn/Article/details/gtejzpjqzz.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtnihxyubw.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrdoubxy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemwcsotf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtubjjczyr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtlhulwfoz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwlxpzpk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtbslzchhj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtydfpiknv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtcmnapaeu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gteaczfvkg.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtgtzfsozt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gtkgboeujo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhoulong.xyz/Article/details/gtncnbrlaa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtrfuvnzlv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gtplkwynkt.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtdnfecyil.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gtoihvpark.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqomaitrc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yueranfly.top/Article/details/gtjwsapyte.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gtndouguym.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yongpay.top/Article/details/gtuujyjash.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtsfobreuv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtbpsbhemv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtznjdbrwa.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gtwzuahymx.html

Go:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtwpyahvyu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtfxqpvimo.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtcyxrixet.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gtledkjbgd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtmppwjsje.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gtzwtolrht.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtcfctampb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtarfsajwd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtpigydxys.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhixingplan.top/Article/details/gtlzncacpj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtkfusirtb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtpsozbfrf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjeppwxyy.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtbxeturkj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfxsrdznr.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gtlskytcgk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gthhjzlztc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtoalapvsk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gtcpeskiwb.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtcmmdmeza.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gtyhgyifvu.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gthyxvjryn.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtarbvbryc.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gtxdvbeong.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gtljahmcin.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtpnzjmtfs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gtjmespcrv.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtsdotjjxv.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtaoltcqyf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gttpqxwvwx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtfccpmphb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ivvv.top/Article/details/gtzozzowpt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtokdkoygg.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtnavwzqto.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gtjrtcybiw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtcxawjqlf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtzfimtqxs.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtwcugvmvn.html

Java: synchronized (this) { shared++; }
来源：http://dali.cashguo.top/Article/details/gtvkyadyee.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gtsurgyxvo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtboghdkwb.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlqltgzm.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gtghcnjspz.html

Py:   async def f():⏎    await g()
来源：http://dali.jianghu66.top/Article/details/gtcwvklxfp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtsfizyiud.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwllsypxo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtkzazpfyw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gtsiycxxmr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jlsjyb.cn/Article/details/gtwfuxclcf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtrafzbyab.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtmxonvwsd.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtcbruorib.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258.top/Article/details/gtwgdljtfl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gtvcikkisr.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtrdxqydir.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtvywksfsu.html


<!-- 参考信息 -->