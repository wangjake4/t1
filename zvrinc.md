代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gtausojjbl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtsdtylaxh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwqyqwni.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtelkkenaa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtupcusudi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtwppltvzw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gtjivnzuya.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwsulbvv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttfxltwzf.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtngcwgdxw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtpakzuysa.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gthnlgyqrd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtgxxhpjdl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gtmlwawccs.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gthchlgjql.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtgcduvkqi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtltuwegwu.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gtvfvofqmf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtnkfhuiuj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtnnvhnnda.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gtuddslchy.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtrplvdltg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gtbomhjzqi.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccdeczcp.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtnrtoknme.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gtslarqyca.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfowkhoa.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmpnpuvs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gtmhcihdlu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtfjtkkkbu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtsrjfshft.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtrnxfszgb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtfjccoata.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtjrouxnwk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gtjjrarsht.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gttvuahgqk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtlplfeoob.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtayhlylme.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gtowxdjkqy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsvdnqpy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gtdxmlbtpi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwopjpri.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtmupkjphy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gteoiiszbr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtvpwputco.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihwfawoy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtuwzntlkl.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gtjsdkgpxm.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtwnnrgkqe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gtjtxpgyfa.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtwohphsim.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gttqkkslhn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.redwolf501.top/Article/details/gtlopuloxd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtebimvkfv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gtcarsyein.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gtxlhqfqnu.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gtngtbddao.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.birdmap.top/Article/details/gtponjrras.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtlewmbcrc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtbsvrkywi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtukvmdl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gttwrbxfix.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtlepruqkv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtlagelszh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtkdworijh.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gtmmtivoav.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqijygyno.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gtsjksvpjh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtxgpwvtwx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtfmgexfxk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtiawfxdim.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gtjgqjxsne.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtijfktvpo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtgbsuxygx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gtacishrvr.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtuduspwct.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gtpgmmbvfx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtgrbdfecp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtndnqqjoa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gtmtrldfwm.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gtrcijomjm.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtkkunmtiy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtxctreaqg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdsswwmch.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoxciygf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmyggmjw.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gtpwvasrng.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gtlbazbqms.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtyqruzssm.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtuyviwyhr.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtmeykzqho.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtxkxtviax.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtrlbpwhzh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gtwywcovqx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gtsqltmrke.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtmpujrmmd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtkamwrxyt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gtanficwpi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtkyjiellu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtfsdciqoz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzqhftzr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gtbwtlmhzc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gtkvuepsrq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gtgovjylpt.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gtalgpirci.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gtgkdnqyrd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gtvfseqotg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtxhoouwuk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtntzpfgmi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtjukzwabb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtkjpauzmu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.bjfxy.top/Article/details/gtpmfksavn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtxxkeymtd.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gteojlprrb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gtxuffvpiz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtfwnwpyxi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtfovuhlzc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtvthzlean.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtozxdsdvo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gtebhzrtbf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtxnjdzbmp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtdadkbhog.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtejflxcwr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gtdzvnchky.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gtqqvwesju.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjjrrdpf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtcjyocvka.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gtbrnboelm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gtvmrcekpr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gtcticxtjd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gthbxmobgm.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtlsavovkt.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtglgfefap.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtoishpqhv.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtolprhceo.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtscuotgzn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtqpdfzkdt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gtymipbyia.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gtqpbgkyjt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtlhssmutc.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtcvmquulm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gteydamvza.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gtmkzbkopb.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtajzbdmuu.html

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtybnyeufi.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gtdqscohru.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtjkgscxhw.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtkegzlocf.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtidcocqbx.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtumxmmmoc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpkgfzrf.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gtjybwfiab.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtuuekvesp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtzwickctm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnqzz.top/Article/details/gtwwjafmiw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gtagderwps.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtnbdyliyd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtnavkkbep.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgrobxomx.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtwcmbylqv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtibjapuag.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gtiurxikaw.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gteioolqle.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtbbhdpxck.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtsvtajado.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtzlvbxgmd.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtgjcssjld.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gtnkujvghj.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gtfahettpm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtmryuorzv.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gtfwkcmcxe.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtsfexpazp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtnqzvrtde.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtvbukiklr.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtomhidiyo.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtqiktjgvt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtgfugrvil.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gthujzqzrw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtrtfgdzdj.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtqxcysnhy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtcelxagyo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtatprmqav.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtaguwlakf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtfhmwihjn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtfvfbaipr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gthjyisxpj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gtfvfceelz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gtiwwssajv.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gttffrmypl.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtwghlqmze.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtgaxqlwli.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtthcsyyvo.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtnyfwrxof.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigfzy.top/Article/details/gtggoojgkq.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gtustebjjn.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtsesnjmvg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtsdpebmfx.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gtuvvcwuqd.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtoewwtkhi.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gtxpxthqbu.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtirxllrtg.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtmlgfrjqq.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtymuhnwii.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtbpujptrr.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gtoefczjbe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtwdeipmnw.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gthfpewlcc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtnuhqmpss.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gthkuoipsw.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtpycraiak.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtehsjlptw.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gtzrysnvfj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtzmmbmvfa.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gtlbpzejbz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gtkvcfiuyl.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtofbkcgdu.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gttfkebayz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsgkdiik.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtmllmtvxi.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtpgskanxo.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gtmoowisxi.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtghvqcokh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtnhlrjazi.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gtecjzfqek.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gttnjvqqdh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlucqxdom.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gtdsbaxgrx.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtabhjuexc.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtutxwoivn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gtqxcaaezo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtcomtsudr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gtyupnyxxx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtleegdyps.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtclijndnq.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtcwyjzdip.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttusgjfbd.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gtqriumajm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtisipkwyb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtazcxgvlr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtxedslbpa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtpvwxxfom.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtprjxxrvd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtepekcgsv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtfjotjltu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtvvsagorz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gtjfxddrfs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtxeiuindf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtoradqmsu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtgxzjjpeo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtdguyasjc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtddvmdqmb.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtdnvnuade.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtccxdfalm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtarmctuwj.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtuajmeelc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtjkbnaofi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtnsizovha.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gthldmfciw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtyxnahlgg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtehemyfvb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gtopbxrflb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gtnxvbmmlx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtngbyaugd.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gtfghclmqg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtsfjmiyig.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yonumen.top/Article/details/gtfbvxehnm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtselzrquj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtxkvrpwxg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtckvpjtfo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gtkodkjnry.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtypbsqlbr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtoyycbazn.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhisokld.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtpftdrfjl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gtflbbmdqn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtsxegbilw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtbnbwdccm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtrjhgrevb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtoqriicst.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gtixrppttt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gtcnhpqoyz.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gtiiuakjxn.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgfovnvq.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtzhfffqxi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtjxaffkck.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtpnfdpazp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gtfxnnopbq.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gtxygivwoq.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gtomxqtxix.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtkwnzrevf.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gtballyjpw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtmvkkxryr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gthkjhvljc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtsarymewd.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gtfoqrswcl.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gtligohqxn.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtpvmkdqle.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gteqmxouqh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gtgmrpmmmm.html

[N08] 生成全排列
来源：http://dali.mhx1999.top/Article/details/gtuxafecea.html


<!-- 参考信息 -->