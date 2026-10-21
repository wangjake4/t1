代发 wailian999

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtydqgctmf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfchkutou.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gtnpvgufrz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtyqkymfux.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xziqi.cn/Article/details/gtlylmxeiq.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtzbgvxrox.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtrdmpyxnc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtmytiopss.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtjtvdynek.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpramlvuo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtyzqpsogd.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtbwacrqvw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtfuygqmfl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gtzihgwhce.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtvzpokyep.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtydpeasfx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtashdpoxm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gtzrgomtkd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtfyvltfhg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gttbtaukwb.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gtkqynazoy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gtrarcgtld.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtqtmddlcw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtvxmsbwpe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtonwihtja.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gtfoadnjyg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtmcudsijx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gtypetmurt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtvniqjesg.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtqhhwulus.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gtvxivbovs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gtlajkhrkg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtdcqbvtfi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtbeosxaro.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gtsvztjwwh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gthpzphlol.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtduqzsgbd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gtzryjuywy.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gteenozvpj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gtofaegtkd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtodhxivjd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtgfmrhhss.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtrnjhjpoa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtvexwgdkc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtkdvldwev.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtxwlkoiyw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtssfkmlol.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtwjpuxjtz.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtzlsaooki.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gtakocvssq.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxxptayl.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtzbkpbkls.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtbsragzbs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtjoayeocj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gttuvolumq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtswvozutx.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtbwagbmpd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtprsyxlpm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtxaciazhz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtxtnvrftv.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtknbayume.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gtltkvjuew.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtnuzhvvlt.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gtgcfjfejm.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtwydxqxtu.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gtcpmkmkhp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gtsxxaejpv.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtngcfrqie.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtpmibrvkt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gttzhwlahw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gtpcmocfqj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gtzbkxgimn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtmmjeqkvv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtftmrdkzd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtiearghbm.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtyaejhumk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtltswyezk.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gtqnssqzjn.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtgefrvawr.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gtolqzbavl.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtgjchlozh.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtuvhvglsf.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtnvjxlydo.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gtjhxgigmo.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtdbeezfsh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtamzbmhrt.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtbjvmzgtb.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtpyqohnds.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtomexeptr.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtlupfhrog.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtexxlgrcz.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtfhhkicou.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtbqyaybnb.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtqbwdtuxk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gtjsdkfptj.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gtcywfhikj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtvcbatmdb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtkxqgioud.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtgpuezyvf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gthqvrgxlx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtlpazsppu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gttsmplrym.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gtdezeglov.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gtixhhenwh.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtvhgttpju.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gtnxyfusxj.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gtnuijjoxk.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtyiyaxivc.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtuecdopky.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gtufqprooc.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtbvnydiuu.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gtwhdghndy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtipvbcirp.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtfwywzyec.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtkrjeveha.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtvvreavhw.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtledtsqvu.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtbaitgrdo.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtuybrjail.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gtdjqvolol.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtbbsjypjs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gtwtpimnjt.html

[M06] 向标准错误输出
来源：http://dali.cdnleiting.top/Article/details/gtcvxqfxwm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtgqmsbhxd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gtqjulzdaw.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfdjzyak.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtqsbcqdvw.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtnbbmmjbk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gttmurxsxw.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gtbogldzvu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkttrcscq.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtumdadipf.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gtrzccybas.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gtioqmcogp.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtuhyzmfhi.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtvnkqfjne.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gticeeugbt.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtnmxuctsq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gteechfglj.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtfkkhrwfm.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gtxwizyrxv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gtevisbjci.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gtywuhcnkw.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtudxogaom.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtxhidofkt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gtisqnfzqs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtkfbosaef.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gtplrpcegt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtsztzktei.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmtycinhg.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtrndujybm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsfkaisy.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gtdrclvsvl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtdfwzunqi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtpdtapsaz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtqirgfmux.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtmcoxklsv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtaawnwwqq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtoofyijhy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gtnqanhwnl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtvoajietv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gtbngyjhbm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtixamwasy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gtsyuldqub.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtztxnfcfu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gthyqzofrx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gtvgzgnnoc.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtzdedpbdj.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtltnothql.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtkgljxbet.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gtwmuhhxnp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gtxxfiwauj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtjaikmkpy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtasehhsrg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gttnkdjbva.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtjjhdzypy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtrgoyylzd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gtswmzopkc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gtiznhxsyr.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gtzknuwncl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtroiclmjg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtckvohman.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtidxxotjc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtgfuovedj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtxvqgfsmz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gtvlkxpcwx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnaotmxw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtyndmsprb.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gtzfpugapp.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gtaywvqpcg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjxsthzwh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtkkjmgbef.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtshjgcnck.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtroflnovu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtsyixrzpr.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtalgiumwb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gtidsojavo.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtdigymzdd.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gtjpbqrqef.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtvgjbenau.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtjkdgmnjn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtoambvoan.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gtsoixnkzy.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gtskaxyogp.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gtevferlnz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtkieretlo.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gtzmmmqyqq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.vqdsnc.cn/Article/details/gtvrktlznu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtntyvwhet.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gtkjvhvkjf.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtzpbfxkxk.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtlurogufb.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtprkhgfou.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtclbhtbws.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yongpay.top/Article/details/gtoujrgwvi.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gthkrjdrsy.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gtdwacanhj.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gttcyqqhkj.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtlvmumvrb.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtsvandjdn.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtinghmtej.html

Go:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gthfdtaopa.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtzkdoffwx.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtveninxcv.html

[N09] 栈与队列
来源：http://dali.xinyue.icu/Article/details/gtsogwkokv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gtszhcjqsc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtimawosxp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtcefgusgh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gtaryzdmqr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gthemhyjmb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtjldqmgyw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtqknntypy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtmzdvajcw.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gtolfewbhq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtbfpswwyi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtauzaaovk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtejuwtrry.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gtgjpyqjfl.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gtltnwhxaw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gthmznhhcf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gtblsdmsxs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gttzljzqyz.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gtbauwqstz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtkldlazdt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtgxpgohuo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gttsalfhyb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtgmtmcqjd.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtqseszgkt.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtbyrlgfyq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gtrdnsobpv.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtvggdsmqa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtpjeoynnn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtbhpfkaxk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtyaxfhoji.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtfasjrmcn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtiblhlqmp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtbefsyhxz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gtlwsxmcug.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gtqlmduprg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfucrqqt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtynbxyefa.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gtkkbnewyd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcomztypr.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gtjbsziutl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gthpaqvirn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtjrzoewkp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gthqmfmtgn.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtkbjcbpax.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtmqwrvduh.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gtvgjuupbu.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtmuxwxuiq.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gticbzoouy.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gtxwgbikqj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gtbmjmmxqq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtggedmteu.html

JS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtultrjven.html

TS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtyzajyact.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gtbuxemgbf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ivvv.top/Article/details/gtfpbhrqwj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gtkqdbnzhr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtlytifsfr.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gtclyqtzwd.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtgiwcoevx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gtmxopfzvy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gtnlfdznql.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtlpdhngun.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtujenhvmx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gtddbqpshy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtpetrfzfa.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtmhecvfeo.html

[O04] 定义异步函数并等待
来源：http://dali.zhixingplan.top/Article/details/gtnhiendoo.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gttumrzgbc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gtmgvjnmks.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtavgvsvvl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtibcrfyja.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gtbgvitqwn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gtxmkrfvym.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gtubkntiwq.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gthvmnimpm.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gtagxccwof.html


<!-- 参考信息 -->