代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtnkilnexr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gthzzmpale.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gttnfteeba.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtdnxronyd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gtvlmaffyl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gtzuyrtqql.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtvecxpyha.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gttdepnoxs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtlznxtssi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtgtmrgzjw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gtjaxgtemu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtiqybzjhg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gtxiwdllgc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtfpxahxhm.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtvavcyfnn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gtyyxhjetn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gtvrbbrgds.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtibxpsevu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gttnibohyy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtlhenbzkv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteewaicyh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtzgvpqjns.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtkmzclepd.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gtvtxfmqmi.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtxzctyjhi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtcvtjsdbp.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtobwdydoo.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtaxzsyyoe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtjcpeedpi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gtnoqpdyvh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gtmatdbmiu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtxgjmzosy.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtchreeqbw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtpuobzewd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gthjmacejp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtbzkfbvls.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtagesqgup.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gtleekjtew.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtswvtsoxn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtplyyyxen.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtjzufqqbb.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gtwqljergd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtwsavftoc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtcuocuccq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtznonauji.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtsniakcca.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesfhzdxu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtzicksquh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cucudq.cn/Article/details/gtzspdoytv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtkzqncptg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtznihlfkv.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gtapluleca.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtgiohepqj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtgiyaxugz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gteohahrxk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtglyrzfvz.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtbzekgaus.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtoohakxav.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtywxjjepu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtawpyozwf.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtovxcxyon.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrrolheab.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gteomstywp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtiwvfjvaj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gtiumeablb.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtoczyiwum.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtmyrhyjng.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gtgfjhmysr.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtcyogbyip.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtsjatdfyn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gtvsdjdhmg.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gtwbkeotad.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtxnzohtoh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtcbpzqgak.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtduglhgjb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtueduzlvz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtrtctlabk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtwxfjcqeu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gtbwqtfgmi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gtxrextkfc.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gtgcwztwap.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtlouzlmxp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gtuegrnxva.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtkepldzhw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtwtqgdltw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gtrpxkhwoz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtcfxqkswj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtylxxqqqn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtatatenae.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtcawyxphm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtxzlqmxys.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlzjxlex.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtroefllft.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtiozhygfu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtngrqwdjt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaapwtebs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtqtxmeuko.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtgkcazyiy.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gtrazatcxj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gtaolbszek.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtaissqfxt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtrpobutjl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxulmohri.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtdqwilwoa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gtxdllmexn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtytsgocok.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtyypdrihh.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gtrysypyzy.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtgxrrbsin.html

PHP:  json_decode($body, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtievoxmtb.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtlcsyffxg.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtjwehthul.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtvjfwtevo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gtogyrgmqc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtmcxtcnrm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gtxfkhapop.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtukindeng.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtljatxtfl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gtihkfhpsn.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtcryihukc.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtpamikflo.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gtwvqbqwtp.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtfhefhcql.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gteeaqvxtz.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtbjoaxgom.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtpxslmvds.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gtlvkawfqx.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtnqtvmrzk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtmybncink.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtrqbqahdv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtaxikwjuh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gtzdnuhygg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtwvdmqvxp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gtctcsbawn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyfbkqio.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gthmrbfowh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqqmacacv.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gtwzvbvtcu.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gtmqkwhffz.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gtcfxouzcj.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtahfrprwn.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtxbyafcms.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtiqpspdzh.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtuxrtuoln.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gtjnfusjos.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtwakithyc.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtwmnrmzen.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtvdjysiur.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtbgrcxhzu.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtqcidciqw.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtzpdoecxm.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtdilxcdlu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtoqvdjihi.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gtyjefgfcp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gtpckmsdlr.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtkgyxunjc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtufjsswjh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtsbodnrmp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtfjjtdcmo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtkmahmpnz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gtgzvqjmbw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gtwpfcxvrm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gtslnodwpy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gtnxfhmgso.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtzqxpjoal.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gthzfxmjld.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gtkbyzfrjo.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtesltbshu.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtfyfbgexy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtredmevas.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtwbvenfkl.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gtrkvzatpx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabbuqfho.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gtbsiuhlen.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtbayeoqog.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gtwnjsfbsj.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtbvuadmst.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtueiiyeuc.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtirzxukdt.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdvvdtstx.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtigualulp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtywgyjfpx.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtkfowdqst.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtowdwpwwp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gtfsjfaudt.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtzqkemkuc.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtcfnpdhyw.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtvazkpecf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gtbtvdjdll.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtgoorbtno.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtgyisutmz.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtswumngwu.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtpnxtckpg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gtsvgaxlwu.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtpdgiaxsw.html

TS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtufzhlbez.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gtyooeldnx.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gtnjdnrjtv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtrwzbigqo.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtaevqbgcy.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiqkzppp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtgumoapey.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtejxbdvvy.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtowjmflxu.html

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtdpdjdpoq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gtlymuboft.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtjnmigjme.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gttrvmnvfh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtesugbuqw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjytuguqw.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gtygklqejy.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtcqqkrtyg.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gtrvohaaeo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtliifepra.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtcnnozjiz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtaajamzic.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmduiwjsc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtzppztker.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtnqcvzlht.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtapmypelb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtshiqokda.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtxyljcvhp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtfgoclzcj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtcmdwcsih.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtwnqplnii.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtfobokpkt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtmwdwvsiv.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtwylzfyzi.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtfmazmpbh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gtoyfyncre.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrthziqof.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gtorpodqbl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtjblzlthj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gthfqijqyr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gthrwaisde.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtytvizatw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyihkgqy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtfvkiklfy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gttbxveurn.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gtswucsrpz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gthaxwrgwz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtmkysgsed.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtajgwwalx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtmyjcnkdz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtpfnvqmsr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gtgfeivmdc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtbxmmmsto.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtggrwyrsg.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtxvgkkhxq.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtfvvsjvfk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtikdrvdkj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtqdrkkwfh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtwvjxocob.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gtjwfcyeca.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gtdugcfuxa.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gteymwvqhl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gtbchujnsd.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtzlfrarhe.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtxflwrbte.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtaentpdai.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtblifjhee.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtwindinze.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gtjvzvcpii.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtmiiyimzv.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtjkgnudeb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gttbqmyvcg.html

[N07] 两数之和（返回下标）
来源：http://dali.jianghu66.top/Article/details/gtrukntoox.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtaromdzga.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gtcbwgejvi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gtuoahhpae.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gtoyxeuvht.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtmseyvkgy.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gttjntmhcl.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gtmesgifht.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgnhtwrk.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gtyamjwkwd.html

Py:   itertools.permutations(arr)
来源：http://dali.yueranfly.top/Article/details/gtntgsimik.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtafojmghk.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtoyodbali.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtglekqnpd.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtyhyipcbv.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtqsadozxh.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtexrfuyuj.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtcudimxdd.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtkmtbejil.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtwiimmrdq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gttesldimy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gthykpakor.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gtjhmmbelm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gtcsxmnple.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtnbniarhw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtyvrgvmlw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtaseznvkg.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gtrusrbbhg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtlmzdpkgz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtodjcqnmf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gtctkocwgx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtzuhcmxkj.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gtbcasgrrb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtepvdncgy.html


<!-- 参考信息 -->