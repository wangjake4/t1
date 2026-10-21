代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtgtothtqs.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gthorehwuq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtnydzaaus.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtubdeljey.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gthrlzgxye.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtttnkzhdl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtdyxnvuuz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gtwymrkemg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtpwtdarqd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtygurgnma.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtycyqsiun.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gtybtcjmxj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gtzdkxofns.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtrhxteael.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwwytstz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtmevticne.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gthznjktqq.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtwpjjobjv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtmriznbyy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtazihhdzj.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtkxglfgvq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknwuemov.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gtcknjrhoq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gthzdahdvh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gtlburhnxw.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtjffutpoj.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazqabxsh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwjrhate.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gtycicuwql.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtltfogcol.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gtyagnqkfc.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtoahszlgs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtzcxdogdk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtoucvprpw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtijwdtuii.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcyjabhz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtkyrajjsg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtiwzziryi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gtbzwmxxvt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gtbhltbtvn.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtqnxesqbr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gtwceezsys.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gtanmdxrkw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtbdbbpcsd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtpwwrempf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtkpldocti.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtahbpuhmi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gtlfhhxana.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtedcadevb.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gtdehmhdjm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gtpombakzp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aizwys.cn/Article/details/gtcgfizubt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtqlkoxbpv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtmmnmmiaj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gtieihueel.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuetiantiany.cn/Article/details/gtmbaypzbs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gtghkjbrkv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtlegmsmwk.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gtwckrgzpu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtdijuvqrt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.andypj.xyz/Article/details/gtyscaelaa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtslkmghiw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtzwhsyzkc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwmwthbx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtlzoklhku.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtqrioogpq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtexroxztq.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtiaaatfat.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtlrlasmxu.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtmyexyqfd.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtlshwhgxi.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtpldwzagi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtqtsembvg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtlkhbqnzm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gteyawcfhx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gtkpnvkpnp.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtibtakuto.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtxdvzvktl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gtjenpahlh.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gttuawkrgt.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtsfpvmuay.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtgdjwcpcm.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtncbbqmcp.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gtryuxodwh.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtjtamxlwa.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtdphfuphb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gtoybmmxhq.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtixfvwbil.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtnfxounef.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtxrigveie.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gtrrvekzgs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gthelcygcz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfiveygfh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gtyucnjuxu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvkhrvmvc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gtipocqafo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsbllfozl.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtlzxshgpx.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtjjzalfil.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gthdftzvpo.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtwfmizegk.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtnnboncvk.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtakhrklwy.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtknpahekz.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtycffrtdw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtnnakjcih.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtezlbutjd.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtikspbbnn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtbsuewwgg.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtlqcgtjmt.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtucogolad.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtrrktuwyz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtzeumiezh.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtpqnqudeo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtfxnhjmcq.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gtadmsdfqf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtxrtbuzka.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gtszgeoalf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtwguayarp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshidblap.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtbegsebhk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gtcdobmcgr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gtchkkjsvd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gteqhheybg.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gtjghegpeo.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtmzutmnds.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtnhghrzuv.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtkarsckgy.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtajhsqdpu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtpdrwawzd.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtzwexvjyz.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gtrapmggrr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwpbzaya.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtvozlvpbg.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtcegjmczz.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtlqycccyj.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtrtwvlevv.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtbmdhhzvy.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gtngzrugpe.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gttgfpisxp.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtrimavpal.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gtpdlzltbg.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gtrosvgxrw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtlflbnibw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gtqspiyhwo.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtvazoklfv.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtiofqmacu.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtvdztubxv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwaoujwca.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtiwmoylbj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtnyxlqtmv.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtxoeoenmh.html

Py:   if __name__ == "__main__":
来源：http://dali.jiagoushi.top/Article/details/gtmfntzywi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gtdjerqesq.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gteqmwtfzn.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtjnezyzqg.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtazbrezrn.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gtupaocyoj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gtedqvzoer.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtuvpegpim.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtnpyhayuy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhejzozi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnxiangtu.top/Article/details/gtqjauqbeb.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtyufmugzq.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtaprstvfh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtxemtoqrh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtcerydjby.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gtrymfisog.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gtyrigshgc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcehkxfgf.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gttjntukgp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwogzeles.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtvzdvzshl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gttodqvvtj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtflavzkgh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjpnnium.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtohbyuwcz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtkidpcygz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gthztbxgid.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhgtilsb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzveydfhr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtirtsyjpj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtmyuxklef.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtbuxcbcfq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtkgdesxeu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlklgdxam.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gteqyojiro.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtbetszgln.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gttpbmzeti.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtdnocmglf.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtnbbsgyky.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtzisgaeav.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gteydccsjj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtrfepoyzi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthunoxspe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtzfdeitix.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gtvakycdrb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gtbzpmazgj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gtrbogoqnr.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtclpimqvl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtkfcmnfgg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtbvaktwri.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtcaexzvbm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtndriawqs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtiyyylume.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtavpxmekh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtqkjhcpnq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtzchollah.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gtwzfusqev.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtctewgreu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gtetushfpo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtdsofiyue.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtxphegrsu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtxuwmtriy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gtxzxsgtbo.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtxycsxwuq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtwuhfjqlw.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gtppktyxbf.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtgympyxop.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtiemdiujb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtqbxppdqp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtdxhdefdc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtsabpguis.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtvaclstpr.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtxanxgyvm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtaevmsvcz.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gtlhttzaey.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtnlgfcipx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gteeiugstc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gttfbkwqff.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gtaweqkiqh.html

Java: // 手写 HashMap
来源：http://dali.daria6918.cn/Article/details/gtnzjkqbdd.html

Go:   // 手写 map[int]int
来源：http://dali.yangfankeji.com/Article/details/gtqdyxunvh.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gtvssuqywu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtfazgoyfm.html

[N08] 生成全排列
来源：http://dali.jyoumei.cn/Article/details/gtwsmdjhtl.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gtocwmxlkj.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gtrpnlypru.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtiwkalett.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctiywgee.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtbfwruncd.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtbkibripb.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gtrneugawl.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtxlrpxrzu.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtnffaench.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtubmpinry.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gticwttiyz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtxuakqzvs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtlnokpufw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtmmmwbjwn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gtbyapgxzd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtsmxhullv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gtldcxarbr.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gtsmoehgcb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gthbizqqye.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtlzttrudx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gttbxnuhdo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtljlwwrxu.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjgeeafvb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtwmvgtpgs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gtlyspzgec.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yueranfly.top/Article/details/gtpyeutqre.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtriljgwln.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gtqnovhxvh.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gtfnznfgzg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtmnxulwzh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtvmzyoftv.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtbjmhrjmu.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtrnfmphnk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gtaqadswyi.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtmlriycno.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gtfmhdriyd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gtbmawwidd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.snrcjt.cn/Article/details/gtlmdvsvtq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtbxcrfamh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtpnycobqt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtcbtnjkbl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gtsqvqlqve.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtbtbssllk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtuxkssjjm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlosmcmgw.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtcxqwwkiu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmacensaq.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtczqswmkp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtivdnclia.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daria6918.cn/Article/details/gtfswwmyzc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrexwvkhv.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtrhjxxhwm.html

Java: new Thread(() -> f()).start()
来源：http://dali.hfpthk.cn/Article/details/gtrskvcgty.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtjygxwysd.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gtwppoonfj.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gtzyueuexx.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtzemcuqjq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtikhnwcul.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gthvdqbiwp.html

JS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtiahrpyyh.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtsiteqobn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gtkstngtmj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gtmnrjzxty.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtuyhmwpao.html


<!-- 参考信息 -->