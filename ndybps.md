代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gtrsysymbi.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gtmheyncqf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtaaswvxdu.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtinykayuk.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtwuwdxtig.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtunfufxne.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtjmdrherq.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtpiqmsaaj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswtkaqbb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtqtujnmiu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtwtavmsmb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gteufzuggy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtktenzlng.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtdkomfxcn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtcamgqofd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtaogntylt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gtwjvcfoot.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gttuhikqnu.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gtoeosiymq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gtpoqsoebp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtoknhmncx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtsipsfcwl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gttrurojmx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtnmsgsspo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwprshtwr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusbwmbei.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnoravil.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtbhluuofr.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtvdsxxcti.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtnnceabum.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtigkwexmd.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtpuiehobl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gtnhzkqgae.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtfmklzmeo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gtxqpoersu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gtryndrzhd.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gtdxmoiwai.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtbugtxvwx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtkwhunehl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtjaqekrgb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtmhedkavh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gtcsarggcn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtqpickmxh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtmkabffqv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtwhwcgvow.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtiwvwethk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtljllviek.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gtwwefldds.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtofucdwdr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtflwpccpx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtecjgttwf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtwkluavzt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gtwfteeyck.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtujfvbkcv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gtnlcyxqyu.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzszpilgw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtqimrouav.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtlbckoefv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtpexlyvvx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtiffyusqh.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gtglaaktfz.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gtwbjqotet.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtvdupsvkc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrbbmlmdd.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtngkjyfyr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsqqjavbq.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gtaeizolwe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtjyarpzph.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gtodrryuqx.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtfjshxjyn.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtcaibhfah.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gtvfwmafng.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gtdgzdukds.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gtechhmyyw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gtodcaxxeb.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtfwonyxvc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtcgvjacjt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gtdfvzbuoc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtzdzhiowm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtjxpdxvmo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtnriomcle.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gtadlhdbaw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtsyifcvxq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gthdwonccz.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtabystgan.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gtiztkfpdn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangdashe.top/Article/details/gtqeybncsz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtiqinyavj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtndpzotko.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gtqixwqgxi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtmnkovgew.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gtpdfkxbfi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtswonyaaj.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gtcssawvrl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gtuolgqleb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmleiypa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtnqhmgqsx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtokxtcmuj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gtygjalkbf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtiqcsdcen.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtxbpvdvyu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gtjknzabls.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gtlojsxcwn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gtwgmnynbx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtmvdplidw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtibjorhlu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtupzqzfnl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtaoqubgqc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gtocdvpdtk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gtnqlwoqri.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtfmqlfipi.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gtscpkwcwi.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gteynlmwiw.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gtpklonlvg.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtuzrrqsll.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtrkuwcekg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtbxshydyt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtyaknsnfc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gtguapaiqn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzagkuwx.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtccjncafv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gtjbnwqqhk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gtbytvkwya.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtasbyxrqz.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtuugtubfj.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gtqhdtwnyc.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtbczxrxkm.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtakjmagfd.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtzcrpeblk.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtsvpbbjtp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtvgrtmmsj.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gtwqaipcti.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtbmcdtuzm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtzmxupxgd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtwdecdxqr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtwvipghmi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtwpyglext.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtlgcroxuc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthgswoqop.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gtpsbwjwoy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrbbhgjrl.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtrorzvzjs.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtedmmdzlo.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gtoikqotjb.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtmyhhkqde.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtcujzjrhy.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtlobpcwvd.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gtzfrdhoyx.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gtxwkerqrp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtmuhgjgbl.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtncjnypja.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtliqnmbfd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrudxrdag.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtidljwfkq.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwwkddai.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtaxquowwz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtkgeyywoa.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtnzxzhwdm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gttuelelbb.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlznkwfid.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtvewvztmq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gttogzfgbb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtixuerqbl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtkyzvvdon.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gtajkracsi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtvkjpigmy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gtmhndxeob.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gtlguygeia.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtkucjxjge.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtrfybwdmh.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtdbvllumc.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtycsvlysk.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtoghgrdun.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigfzy.top/Article/details/gtgbvkrnsg.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtzadzhtwa.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gtjoespqew.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtujhcmias.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gtjukdsxwu.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gthfrxcvkb.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gtcqgeaupe.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtloqnkjeo.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtycnvcxpf.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtedzmevtd.html

Go:   os.Exit(1)
来源：http://dali.andypj.xyz/Article/details/gtsgnomesl.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtvufjowxj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gtwcwomboq.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gtmopmovjn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtpnchbxuy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtxzmujmqi.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtvlrytyin.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtwzxunevm.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gtgabecguv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtcbqugqws.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtipkrwpdz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtbcjvzben.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gtkbcisymf.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtyvdbzmdh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtvbjznmtp.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtkjvkbzxq.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtczkhabrq.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtkfcxziaj.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gtckibevct.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtramiotgk.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtubieawgb.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtpggbwrlh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gtyiksuqcy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtfzszhhvj.html

JS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtdvfrdztd.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtyyediqev.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gtizqmhxfu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtadjwhrfg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gtftrgcwco.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gtzkkurhlb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gteourgtqm.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtamevthpt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtollhrzit.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtajjfzboe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtxxfjfawx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtjqgznuyg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtzvvueyfv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtsxvipxfz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtenlhjnqp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtvlbadugc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gtziridety.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtccbeprou.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gtoytrsppv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtwgwhsjhk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gtjajawfjo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtkcjgjhst.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gttzwkhjrd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gtsjtakrzx.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtngudtbaa.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtnccazlbd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnqzz.top/Article/details/gtvceppkdx.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gtfuetotoz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gtsycwzzhr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gtlxaofzlb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtosicqmld.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtynwjpyip.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtzgkfzbfg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gtwjbeqeuh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gtrhcukelz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubsllpxf.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtlptinofp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtrarbeenf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtqluapsyi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtoaeaicir.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtgcdmmvcn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtwgvqfuwd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gtxqmatwtt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtogwedrfc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtcrsrqjox.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqdordbv.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtpgtpikir.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtbcrflpno.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtjijwdoef.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtizveokfz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gtpialggyb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtzubfwfzq.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gtyigfettz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtolubeyfw.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtmxdfenjh.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtpkrfsptq.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtqjvofqeu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtyuvcredm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtcqdltlam.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gtfbrjcqga.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gtjcfdpaug.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtrulysaak.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtaafnzfbn.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtdpgpuqtq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gtxlmmfbox.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gtensserxq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtebozzoln.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gtvlybsrrd.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtpmthgbfm.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gtifgwjtev.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gtbqdmaqtj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtkjdstfif.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gtefllwxmx.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gtgzxkgakn.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtissdqnaa.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtjtzwsbou.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtcegexmze.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtsyqodlak.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtvkmgdeyq.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gtvxjcvifs.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtwingnnua.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthznvfab.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtkrqopesu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtnhotmadk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtxuyrsbxz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gttlbuevgh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gtchaetgce.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gtiaebbqts.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtxqtngfgd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gtbqelmxks.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gtuekqvuux.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtiejaxgix.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtfzsyhplo.html


<!-- 参考信息 -->