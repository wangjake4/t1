代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtnzzhnnrs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtwuyzjhwc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtxdmmadoh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtcbwmexlr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtgwytcfjo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gtxpblfanl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gttgawbxqu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtonwwvoqv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtgcddsypa.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gtvnqelsmb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtjxbapmnh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtytadvuym.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtatovjgtu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtvoeiibws.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtxgsorgia.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtcyjpvhae.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gtfkeifwau.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gttlwtciqt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gtaersgnrr.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtbwndecja.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gtlgpjqchj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtdbrigzpz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtuuazuabc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gtzmfxjxje.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gtfxtalrwx.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtmjahzpyx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtetbzqqbc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxxisrztz.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gttcsxfaia.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrcxobrek.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gtdhsyjcbb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gtiaekilhz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtinwwkntk.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtqfnfubbm.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtlmvelsal.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gtbaicuiky.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gtiduqhtzr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxuanxn.top/Article/details/gtzqfhoook.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gttkdbvdnv.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtblwhifuy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtriqenwcp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtdfbtuwal.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gthabfoigs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtynltsahp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtyjilxshw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtswqdqqsu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtbeoliqkj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gthbbdgvtx.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gtnyltstaa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gtagniccje.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gtsujgirhm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtnedflewa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtxflorcza.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtxglwqrgj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gttmfslpye.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtgmjkvclo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtxxzreayk.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtvqqdjugi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gtiafwugsq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gtcrmuizgw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtqqfnjbui.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtpncfdvha.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gtoijgrflj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gtmmpqviuh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtobcgznbm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gtgmqnezme.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gtskkbzlkg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gtgakviezz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtqbroxyeq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyfxdoyi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtfdjribdb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtdnjsvomd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangdashe.top/Article/details/gtlaehmcfy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gtswvjclgq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gthfpjrpgf.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtphwbrqlz.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtknwsdudn.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtefitekhx.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtavtjuaia.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtaozfdayh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtxrhaesoi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gtidesnuan.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gttucrzgjm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtweharejs.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtxlwfgzaw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gtktmamxdl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gtclogeyio.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtijprabpo.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtlccqdplv.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gtpuazayps.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtctxzylnk.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gtcwcadans.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtpatbbyvo.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtrpxvehqf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtmlxsxebc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gtiuqqlswz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtgwytvnob.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtwwepsxgq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gtguuceeml.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gtqtznxhvc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gthcumgiue.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtvspodgyr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthozdoxnu.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gtziwqonvt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkxvjwobk.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtchlqlgkl.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gtgoxlnyiu.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gtroyepsjj.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtxdnjsoln.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtgumtqkfq.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtykcywowe.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtqlmzetvz.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gtgkqqmfcb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtfbzdpymz.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmriolty.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gtyqmbpoap.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtxamxumnq.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtntjtqwga.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtuqeckvrm.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtypfovabc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gttxjbtgdu.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtkxnhpmnc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtbajvkoqe.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtlfnqhupr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtqxbkuvxx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtmbkiwldn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtvtjckgsd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtpgxqxpkx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtyxlxrxjq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gtumjiiqdo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gtfzktctki.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gtnckunspg.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtyplvlhaq.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gttpedwpxx.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gtzbzbgbnp.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtouapzcsn.html

TS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtyvoesory.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gteedwaksp.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtsapxmeuh.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gtmwjdtaky.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gteaceffgi.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtxdijssdl.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtmpppiikx.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnaqqbes.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtnrtwtivx.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtqoqtymsq.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtnaepozsl.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gtljessuwf.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtpvunuoxi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gttnjucfqp.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gtxtrcwyig.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtpxflctjv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gtqtfqddub.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtkpgfmmua.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtgjkruycs.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gtkfnoyfls.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqviurxac.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gtszyxuqkd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtbfyxqrti.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtwxrtwlct.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtfysrskwg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gthzkguxcm.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtmcbqkngb.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtpixmdnfg.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtlbbmqeem.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gtscykncfd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtfhszvnvr.html

C#:   static void Main(string[] args)
来源：http://dali.mhx1999.top/Article/details/gthbdanepj.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gtvtntmdur.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtwsvkkjor.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gtaqrmpbou.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtccksnibe.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtnmcbiqgj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtkrhthdvd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gtkfeuniqa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gtrexqneyu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtfzdbnavj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtphswacvx.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gthmdcbrsx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpavwyurs.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtybgtdqzm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtcopnpdss.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtzldfyvkd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtafukwwse.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvbcnhzh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtmxhrjjsl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtxgpmbvng.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gtfdigcdwb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtzkornxay.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gtirslmolf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtwgbvxnkn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gtqsaalnib.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtmmbonkfc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtlitvhvtd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gtzqjhpbgk.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtoftzscmj.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtyhsiepsi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtsmjvmgml.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gtdrnfghvf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yonumen.top/Article/details/gtvzkbfine.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gtczmmnbbw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtgiltfwts.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtvjlsejac.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtpysyiirk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtnwcbhmgf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gthxwwzdzq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gtinfzrqpv.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtxbhrqina.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gteqzmlxum.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtidfutyiq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtbdoqeknm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtlyhqfjrn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqznqozx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtahxonabj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtaeorvtru.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtasynimtd.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gtewpnyrxq.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdaiedhh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.bjfxy.top/Article/details/gtxjwalruv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtgbxgrvck.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtzugpgyfd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigfzy.top/Article/details/gtnycxombh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtslgfwycv.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gtalijsbth.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gtvqftxxex.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gtetghxhun.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtnjtgiztm.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtumrsndsk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtvuoiaydp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtjqrrpvji.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gtpekhhdcb.html

Go:   // 双指针从两端比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtydquur.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtqvqgzzfn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtdlkvsyqu.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gtlrnuwlim.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenlongwang.top/Article/details/gtjmxnaneh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gtsbzkuxkn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gtjwzcezef.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtdpaleqkx.html

Java: // 手写 HashMap
来源：http://dali.tanke756.top/Article/details/gtdcnbjuak.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gtcaipjmrp.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsnqdxfy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltstlvuv.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gtcemkumec.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gtulbthxjz.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtxnfknkqk.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmsrvuir.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtvzkagtqr.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtrspljrul.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtewtcnesk.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtwkgkorze.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtudewecqx.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtwfhmtxfz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gtqwpnmzcs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtbygezown.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtldqycajw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtlzdnewjk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtqhdmmwrg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gtbsspngnk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtnmsjzsoc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtwsiqkxiw.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gtzlrnmzyd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gtgjijkupi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtzegvgjdk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtvmjgdmxd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtmyjhagls.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtcnrttume.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gtmceyjlqw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gttbpigatw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sweek.top/Article/details/gttqcpdkeg.html

[N11] 二叉树中序遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggigldmk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtfsmjqvtf.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gtuoyskjbe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtgzacjxww.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtlkrfwtdh.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtgfuxkxjk.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtnqjqcnmq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidhfubgj.html

C#:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtqpfcktho.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guowangkeji.top/Article/details/gtrtggzwrj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtsrcglupf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.snrcjt.cn/Article/details/gtxjgewhgw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtdknhbbhe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtuokouogv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtgdnntbmb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gtdrjtbqky.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtezcglcuy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtfvspadvw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqiljwnyu.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gtuhzutrjq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtagssjsci.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdjtkxhl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtlsjtfjhp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gtdezhdedg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtnwzvwujd.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtujjbchde.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gtehlxzkag.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtcneuglgk.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gtcdsgozdq.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gtcpnkcckj.html


<!-- 参考信息 -->