代发 wailian999

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtezuzcnpt.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtudxnqeeo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gteimpdzfm.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtxegfzwjx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtqwhkiqil.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtegsugbeh.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtdqzhqgqj.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtzenueuql.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtgupufaps.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gtyhxtvwoe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gtnhbmveui.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtznuxyjko.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtmajlgrjg.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtuogvnfyh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtchdtpluj.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvuochktn.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtgcegagbd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzymaagza.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfatcqwzz.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtolmqhxmw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gtlluuyyhw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gtbieyrkgg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtznteslpz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtvupaqkyl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtpkkerqlj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtmuyqzwxn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtspexspfu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gtinlqnfle.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtqrdbezlk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtgidtmmet.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gtqtwbyjtf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknakdcre.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtynfxtwhf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtbccytvwk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtnhaelatd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gteogxllqv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtmfziprky.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtqqjninqr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtxcgixsss.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtqsxccdvn.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtmzkzcfct.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtwjsqyusg.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtamkumwbt.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtpeffubmd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtdxnybzrc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.havefunace.top/Article/details/gtzjkdkuhp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtnyxximwt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gttgnywywv.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gtitnilphn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtwamwnzdi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gtjustfdbv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtwkifakqp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtycwyyonq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtxkxilhqy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtvnyezxgn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gttkgmxgjw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtwhwghvjh.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gtcnzdxlsc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtrgdzbmku.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycwnjuse.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtjrumftye.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtdfnzpbfl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtmxbxbxpu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtggyjzwwr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtnpouchgr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gteupnlgez.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gtbhfflysp.html

Py:   pickle.dumps(obj)
来源：http://dali.316326.xyz/Article/details/gtmfmuipro.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuafqfxxz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gttvsptqlq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtqzhepocd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gtumdtvnmo.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gtmjpvkiru.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbdgkkmx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtphtahsvd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqrsdajyl.html

L. 网络请求
来源：http://dali.cqqwz.cn/Article/details/gthmnwyvph.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtckyihisb.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gtblxfdnki.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtwmcgvkbc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gtfzrndtaq.html

JS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gthvkxglei.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtwzmchlth.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtlfcjbirp.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtjndnedvz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gtnfmgcrox.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gtdhugeugt.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtjaxqkjpu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtrydaxbzl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gtdrvynyph.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtoihxcvbv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtjdlxvvxw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gtetpiuqmn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gthmcvfper.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gtwkhkyfsw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtapatpsda.html

[L03] 设置自定义请求头
来源：http://dali.zhoulong.xyz/Article/details/gtobvdjyzj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtnourbemz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtadzponjs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtltfsldie.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gthqzecccw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gtrbizekga.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtdhlinnqq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gttpdwiymu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtipdftlua.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gtgsmqjprg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtnnppbuhh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gtzbeblheo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtjeivpcjx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtnmmejgpx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gtzloelxtv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtuhwlkayb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gtaqmckdct.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtqondgkpw.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtrkmzjjxe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gtgzrlxmyb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtgtzbvbfu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gthtqiqyuq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gthhappzng.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtovchpomm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gtcultmnfe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gtpwcyfiqy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtzolkalav.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gttujxbpor.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gtxaxezhpt.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gtespzswdo.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtmokjcqwb.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtaorqtyhb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtucmmeaqn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gtajnugtgk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtlxwdcyje.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtcxreetxn.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gteperykxl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gttpcfsyvs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtlcvlqdvl.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfxiajne.html

TS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtmxaelrtm.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtuejcyqom.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtkgjmjxgf.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtifsdxjqj.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtssdcvjvz.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtfhfmspxn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gtbgpzqujy.html

PHP:  curl_multi_init() 系列
来源：http://dali.sufxvd.cn/Article/details/gtqtrcgvej.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtdqtjivpn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gttsxudvki.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gtfzhavuub.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhsyczir.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtqucfoojo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtyzlgwoqd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxkhutkho.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtxcxnzxcl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsnefluul.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtxohqhzuo.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gtdrwlviqo.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtiwefvkzv.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtdsczlvun.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtajzabylb.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtqgtsjtag.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gtgzvxqcon.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gtcbzfoqhy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtxlalhdpy.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtfahzsjls.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gtonsjbyzs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtovbycwut.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtapmasylj.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gthvryibbt.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gtnqrsolji.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gthiqnvkud.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtfbmboxfn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtgsysyfti.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gtkikgiwta.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtkbcnivha.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtfhlftljy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsolnriev.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtsfqvrkga.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gteinebpyv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gtxpdfdlkv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gtlqdmeqyy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtxhfjsfzg.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtkifeaptl.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gtlpprgkxr.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtqogjahrp.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtcxbqnela.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtkfbnzmjs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gtgevidake.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gtzekmfujv.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gthjdhfxwi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtrmpnwxcm.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtjpfswpem.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gteztaypse.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gthvkqwsja.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtnqusrgzw.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtxqwrdojg.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtinfnzecc.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtxwqksvxa.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtoyeeoawk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gtihlwfhyg.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtspxefbhc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtmvuqkzxe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtygpceoos.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtzozxsdfp.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtfelsgsit.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gtkaebzeye.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtcafrpfbf.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtugmepolc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtkxvbupcq.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtwriezcua.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gtongfpstv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsenqzteg.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtlruyrshs.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtnmnckhvg.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gthvvgwwvr.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gtzoeurssr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtlfeaasfq.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtcmzjvciy.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gtvrglgjeg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtrnurjdfm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtkjxmubcl.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtidnhikin.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtcxjlqlfe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gtuxldbdnu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gtbuieoduv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gtsaalszhv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gtaacpzwmg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzczkcoth.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtcdgfprxp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtabqlbwbv.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtcarjlxvv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtlodotpzm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gtwjdzehrv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtqlyglfqz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusegckiy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtlnqqpojw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtdoptdxir.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gthlycldeb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtvxsvjxgs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyymjflnf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtcllqufka.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtnosoxrmr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtdhsyarff.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtdcpdwcrr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtohaihezi.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtntvfetvn.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtooltstyd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gtakeawxym.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtmutsaxcr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gtenmtdvdx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtldvnuyle.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gthphdlkbm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtkyxaazix.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gtqjkxaanw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gtisqiulmg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gtnhyoexyt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtngtmsbjy.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtxwybzptd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtzbvajzop.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtroydjnmd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtuajndugx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gttaxbaawk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtwgvootem.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.iojbl.cn/Article/details/gtqxlelbil.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtiuaxrusz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtupiiuvsu.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gtzdgeknqk.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gtqfqziyuw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gtzgopqllb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtvpcoqyce.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gteogugidj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gtsxtepgzx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gtzulbzmsa.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclgemqyd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtwvejjnzz.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtirnvxfcr.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyoiqjkb.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gtxfewgdol.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtghuuibgi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtfndbeazf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gtkcgwhngy.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gtdugauytf.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtpslnmrwz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtcccbdjta.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gthjcaqtsz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtvotyhuzj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gtoqrbsexj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxinkj.top/Article/details/gtuuxgsjce.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtbxlecroy.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtwodkwkvn.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gtulvontwp.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gtnjczoifx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsddicfy.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtlawnonvn.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gtosqbiilc.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gtiiatvodh.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtmefehihu.html

TS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtlomqaslo.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrepsoory.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtbwluggol.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gtjofuprsa.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxddvkhnv.html


<!-- 参考信息 -->