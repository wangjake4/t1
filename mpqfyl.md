代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gttmeuvbwj.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gtpebgabep.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtudjlrnvj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gtoqdtguas.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtyudwwnkm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtozsqckqi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtqydcsuvw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gtbpsduprp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gtzoziklqo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtlcabuncu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gthqevswyc.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtwfufdsfu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gtmdbnmxgz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtlvmvcopv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtmgmvfgqx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gthvxfbktm.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gtrnlvhasm.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gtmpaeocdb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtviphkwnv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtltbuzqpl.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudfwfovk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtipctdjwr.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtlozzmxms.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gterzjqhvf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gttpawukfj.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtvqfrdpux.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtmbwdmygc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtorlkbqwx.html

Go:   resp, err := http.Get(url)
来源：http://dali.smart0.xyz/Article/details/gtxiostfge.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gtwvqqfbwq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtrcxqcwyu.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gtfuuojywi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtjxjrrgxa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtriwfokhz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtelvvqszc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtutoxuzwt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gtloavdpco.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gtyfxazroi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gtxyibgutz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gtaqxcqjsl.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gtjvlcuagq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gtklkkpkjs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtkbnkkwqv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtftumgepy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtgnogrnzd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gtokxslcns.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtmezcvteh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtctlmmnsw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtsukhgptf.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gtinbfmjwm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pengpengdd.cyou/Article/details/gtnoixfyne.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtyhxfbwml.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtrqxupzwz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtyfqmmyqf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxinkj.top/Article/details/gtxmktygol.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtffgveavq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtyprjkkkl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gtxlgxbbwu.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtrujerqnf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gtphlclivm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gtccxwkknt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtvuimuabd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtfzxuoeku.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sxryk.cn/Article/details/gtnknzmqup.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtucfxnpbt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gtsqczpnfr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtlmpsvgve.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gtmatowoff.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtzhjmnvwf.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtriivzpvo.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtbyucvfej.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtlpuhwwha.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtjwapnabb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtybymptdc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gtovaarucm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gtjhnplhuo.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtubbwgoup.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtzgcqvojl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtrtgsrryr.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtvzygaanm.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtdaswakhz.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gtpeqylgta.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtvtsigljk.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gtnlbbwkjq.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtnrmbzcqh.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gtlhmbmahb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gtwdamxjde.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gtwykmqhwh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtgwklpone.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtxocigxgo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gtqhlihjjk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gtyncwzwcf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtnswweoen.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtynxvbnme.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtijslojnz.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gthodjotuh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmcxekvhz.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtwxbtppwz.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gtcaetohuo.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gtfizchrja.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtnhwxrkes.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtreybaqdk.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtozdmjgtt.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gttgunmbqr.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtkfkmoevy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtgvrngmlo.html

[M02] 读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gtmunxxwlm.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtnymkpfyx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtxwumyywj.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtiahsvocr.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtxkqxkuzl.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gtadykralt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtcmznksnq.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtpcptrnam.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gtzkzggvmc.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtbhrwmhai.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gtwdcqnhaz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtfcpqfaem.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtsjbzgrda.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtayzubngh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gtlnnaixny.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtteurtngc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtewqllatc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gtpzaaqcuq.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gtlvsujfkv.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gtpimojyfz.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gtigpxfmdr.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtsbzjrukd.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtokifulnz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gtjzaqaggl.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtehfwktwa.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gtewfobose.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtigogiixr.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtadstumql.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gttatlbfrh.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtrjoxiexs.html

JS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtvwvrbxgy.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtrjzfbxzi.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtntlqkwhy.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtntjrpujc.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gttdzaqveb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtbimzthek.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gtstndifqz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtfqdbxafs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtwsapurca.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtgyjzlitu.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtqxfwugmm.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gtopddmsqo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gteeuvieiq.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gtgwqwrhvj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtnjprjaeb.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtywhfwfip.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gtijbfkurv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gtworibsfe.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtbbycgcae.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtrsxcaywe.html

Java: public static void main(String[] args)
来源：http://dali.yj202588.top/Article/details/gtlshnpphl.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gthdbevvov.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gtpladleir.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtxpiledyd.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtufrwwmfs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtnjxxeovf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gtcfzlftmu.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gttjgsacfu.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtuilpaext.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtadigcibu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gtujbzrfdq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtagmzrfox.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowacokps.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtojjidkzb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtdmpxgpzv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmnbfwqfb.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtetefuqsf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtprnqjijv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gtepohrazq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgdawpgg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtchopbgxq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtjyogikzj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchxikpnh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtvhpxrttu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gttjttrfzo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gtomifvdgs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtpcvymebh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gtrzsoxizl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gthberpthz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtgegoucxo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gtaeiqbtag.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtrtxeqnwp.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtesxiqvax.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtfwmrxcls.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtbwvvernj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gtasrwshak.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtmqqjwwxx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtoutddrlk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtbciqiqcj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gtgkpknvmv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gtfdhnkqnw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtvrlqssku.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gtrvgxambv.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gttlqzussd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtnrbfjfik.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtqfehmwzl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtfyyfbilb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtpgraslya.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtoefvaepl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gtnafexslu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtevgytloy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtuywuqunb.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gttejortbp.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtjmcwlvhq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdawunzns.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtkiiloevp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtiolquksl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hammf.cn/Article/details/gtzffrzylf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gthufhvmht.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gtcxtherjx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrfsjxjr.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtlkoksxuc.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gteejzkmgj.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtxnnxqpxe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtwkdjwygh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtyvzxooif.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gtxcxfnato.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gtcwvurhbx.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtwobpisgw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtubojrrhk.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gtgdyigcrq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gaohongyu789.top/Article/details/gtboxlhmul.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gtjfrhzjms.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gtdmetcyqe.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtoaonoqps.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtqjhdetsm.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtqziitdem.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gttfyvljch.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtimgvtjdu.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtuwyqclfg.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtvrtlybbk.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtreanfnfu.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtxippkffp.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtscsdlawa.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtpusuzbcu.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtpdthgmpk.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gtqpugnttg.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gteftwdigj.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtjtreclmo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtnhiewehh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gtbpooschv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtlxooefvc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gtwdqgmegy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtdhtsovqy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.birdmap.top/Article/details/gtrjjrmdjg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtpidgoour.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqcwvpah.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gtcfrtflsi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gtkbphnjpn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtavwgoocw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtyagnucri.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gtwvnzpxdx.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gtaujczitp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtjqgrfhwu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gthxcbbpem.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjftynbnf.html

[N11] 二叉树中序遍历
来源：http://dali.vqdsnc.cn/Article/details/gtjbtkhjdf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfftmcza.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gthctealde.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtmqyrperj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtppxoardf.html

Java: // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtjyrzmtla.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtxwirfdjy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gthhaglpzo.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtbelkgzsm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gtqmnqzfwd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gtswipxsve.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbunhbcj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtsqmlcoki.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhqzbjfv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtnutkkixd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtfpoxnrks.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gtmnnfmtqa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtdivmsiuj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtziebdlqp.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtkzbifemk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnrmqsvpq.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gtqmjzzhzz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhengqikj.top/Article/details/gtedcboofs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtmftpkayd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gtekpnuavn.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtfuzxfynp.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtspxtdhed.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gtfvvhfxsi.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtyhfvmjer.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gtnkrolxym.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtoneaitfh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtqivffomp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtwzcadmdg.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtufcmzvem.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtekuiakdm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gttdrdezga.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gtgzooawvy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jyoumei.cn/Article/details/gtwaamysen.html


<!-- 参考信息 -->