代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtqgkymfok.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gthxuzudbn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtpgeakcuc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtsepyqjdc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtzfjfwrfr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gthxpagkfc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtjbszqzah.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gtytnssoch.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gtrbncfaag.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtimagmddz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteubqsdqk.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtbdmikkjw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtbjxtqqso.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtvypnabsm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtujemfsop.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gtbfvqjotp.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gtaaulqjyu.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtffsajmqp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtocteoybu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttmaqirpm.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtftrvkyhm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcimqzviz.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gtidtkqjck.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtqtygjwpv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtscwipniy.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtlhzigzhf.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gteqojxjqf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gtgmyqklqh.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtqytryhtj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtikhomkme.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gthwqbwezy.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtsnrkcakl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtssaoyfft.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtqriaogrd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtlhphbdoc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtjwcftshc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gtvjurahjn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gtxeaqkxry.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtiovkvjes.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tianlin.xyz/Article/details/gtmdaocndp.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gtockcjkwp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtzxsjhkvi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gtuvghlied.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtbtsfykgf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtpuhauihm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtultqyvvb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtlhnzsmoz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.birdmap.top/Article/details/gtrwyiooqd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtgfgiyxgp.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtmsqhybcq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtcidvchuc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtztoualwc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtslfxxoxo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtubztcmau.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gtcnmquiur.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gtgghryjbq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtjuixjuwe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gttvievdlt.html

[L05] 上传文件（multipart）
来源：http://dali.hnqzz.top/Article/details/gtdgmohopb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gtaqokbefv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gtsuhhywhc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtghedrrla.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtirrrlylw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtaqgbygyw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gtpcrmshxm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gtcngrbxrn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtafkiffsb.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtqdxaahiu.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtwpwvfygq.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtokdgxkro.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtqimpaswg.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtmguvoqvu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxbtwmci.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gtrujsheit.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtbttdbzhs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtquivhyyf.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtonbbfzew.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gtxgjivktc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gtxbdrfrak.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtlpokchrc.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtlmltmtla.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gteqeumsth.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtdokxehvy.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gtjfqwpzjh.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtyofibvga.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gtfjlhahyk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gtsoinsjhp.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gtwuazathg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gttfgtcyuz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gttfqqrvjd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gtrevgxtub.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gtzydetfyy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gtdckojogu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gtbzcwemsa.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtndzswqdu.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtqyznsgmy.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtecpjcfdd.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gteeyfqclj.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkhhpuxq.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtcmgxqwie.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gttorslyrn.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtluzzobqt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtfalgrqrm.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gtvlcluvzi.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gtffmgzuai.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtwuzdxlsq.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gtzbczjvpd.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtdkthnlix.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtbnxxorzi.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtzedofsmz.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtltvnqnpy.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtjfkzxyug.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtlbdlbhzf.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gtewflfrij.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygtrepqn.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtysskwoqb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gtuefyhzzi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtfcbrurlg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtojufmkjz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtzsgriykh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gtdqfuzdjj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtbnagwghm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtfypvdsjh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtxpcqytxu.html

[M04] 获取当前工作目录
来源：http://dali.zdqjudy.top/Article/details/gtbvcnqnpv.html

Py:   os.getcwd()
来源：http://dali.zhixingplan.top/Article/details/gttwprfcqs.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gtgerkwzuf.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtaqfzebjn.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtwhuhlhpq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gtjbsuwsjl.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvueaqlyz.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gtuldnhaqh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gtjmdglaez.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gtqkxteapd.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxmtnzbhs.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtzkqlfvxw.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtewdekedj.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtgvfebjzq.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtrhqqkhfz.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtklelkivh.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtjyiwmwae.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gtsbnxndno.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gttgrpvaak.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtxshdxhei.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtjburspks.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjjvgywa.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtevvvbsby.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gtrveoumax.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtqbwgnjuj.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gtgbxjhgkh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gttuhufgat.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gtagoafhix.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtvbfdcqrv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfkhutou.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtisiqmryf.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtzlfwffhq.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzzeestp.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtgoiigqey.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gthomvjflz.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnwxvboz.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtyypskltd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtpyflgxdp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtyfhgmzrk.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtrscaphgm.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtfzdniinh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gtrmejibht.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gtlgaxcdms.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gtfracscej.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtqqnstyhw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfylzghiz.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gtoznhcejc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtsudjhnlf.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtboxjyqie.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtzxhdsemm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gtsehegzsd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtnrpqjotl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtrdnyvmev.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtfwwddtrl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtpannotzs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gtsxfkrzcv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtutbcllyp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gtcpgzvopu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtumhlqgst.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtuayumwmg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtdqmokhtl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtojzlkqxp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaatcjquh.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtlwlemfwz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtiwflgwhd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gtsvsvuoea.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvcovfml.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gtossyzgjh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gtnumeebbu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtffkcuuii.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtjugmlygs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shuidangran.top/Article/details/gteryrrjrr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtspakureg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gtfyuyorby.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gtvhhtecke.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gtvoqicpwl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzfcucgy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtaoyebigx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtzboinfup.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtzwwueqrk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtczkddrfn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gtzquroqhq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtluutggym.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtdznuvqud.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gtiuyycyxg.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gtdmlbdgsr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gtwremqyiu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtecdwntfz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlapukzjr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtxaqkuqde.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gtjbdgqjil.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gtdrtvatkx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gteywrimhs.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gtnmtxxtye.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtwqamapxq.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtokcudlkq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtvklmfoxr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtmnapicxu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gtpkutsoxl.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gtgtrtpcuk.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gtxmzpejya.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtnqgbmpau.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtakynorzp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtuwzezdrr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gtupcaldzt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gtcntrzytt.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gtrtnicqec.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gtbhavmkgz.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gtddtjhioh.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtvedxccsq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtbkttyqmf.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gtuetzqqhq.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtytnieikw.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtridmozoj.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtmfrvkynj.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtjvafzhub.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtvuqabmtn.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtmtkhvacf.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtjpwtjebo.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtysesbasi.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtabfnkqgu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gtldvudrpn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtaekfgena.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtyhbliozx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtmqauaprs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtnbhkdags.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gtrxlsgzdl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtirtdtotn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gtovjpoxdy.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gteirsxwvn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gtzxpxdmer.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtnezcbdpf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gtoewdbhxp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gtanachrka.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gtignswcyw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtbixwdzrq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinghuilouyu.cn/Article/details/gtimxvqhcq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtsvidgscp.html

[N11] 二叉树中序遍历
来源：http://dali.jqgfzy.top/Article/details/gtxlrjiltc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtitrivdgt.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gtvsdrtcbw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtabjcyixu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gtaztovlhk.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtctsdkhjf.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtriiulnzt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtrdjenifz.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzydjiklv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gtcutaehme.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtqwdbjtbr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gtidzdywjl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtaextuvad.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtphlmdpsd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtxbkeyiob.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gtwsyzkizh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gtxonjwzdj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtenczrnvl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtiwpmnuui.html

O. 并发与异步
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszrpniid.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpjzpucto.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gtvpeilhrq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtclrpphsc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gthtoymfss.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gtjyozwgav.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtlgilieyq.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtzdzhhvia.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gthbbepqxa.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtnosyjhox.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gtjizzrsuk.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtrvztrzzu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtnvyknnkq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gtlghwmzzf.html

JS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gttnuwflpa.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtyggfddtr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gtrcnrczia.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtedoisapy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shangyingyoupin.top/Article/details/gtjvcvoywc.html


<!-- 参考信息 -->