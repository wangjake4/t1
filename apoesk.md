代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtivonmsbu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gthtwezbhw.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gtuizaedwc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtbxksehsr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gtcstwcbws.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtwvbhrkoi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtzugicxmx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gtaeprpawm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gttlmhywlg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gtoqmkjpvr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtredhlrzz.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gtfgajgvxw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtgpfwpxwe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gtmqnovycd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtbahqzcyr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtpwmsrdec.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtppsbgpxz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkovegalq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhhqbsuh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gttncqipcx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlqqvnkzq.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtiffqoofz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtomonxppy.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gtkytardah.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gthusisois.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtndotylne.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtggdlzyxp.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtrimmqcyo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtoqtkjvjw.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtcqfblreh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gtyxhntnns.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.andypj.xyz/Article/details/gtsghoyfuc.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtjatfnzah.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtdydtbdop.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gtwbigubum.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtbotwacds.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtrjcfulcj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtqwdasrny.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtkfvcthzr.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtfyisnvyl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtukdiwhne.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gtpxlvxgah.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtiunntiht.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtyexcgolt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtbfydrqel.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtykkvgwjk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gtevznhhzu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtdbielbjb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gtcmtqjfwe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gtobdsyoyu.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtehpoqddz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gtmjgappbi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gtmpcmisjg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtayukzyzk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtjmucorft.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtxdcqkuhp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtrzkxspmu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonbgpcdu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtpnieiqna.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gtwumivoib.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtykvpgjfu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gthqlppcjp.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtcwszmirb.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtpvxqegwn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gthoscgqpe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtavwpzgpj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gtjiuefrfi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gtqtxeiciy.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtyvpfqpuw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtipxllelh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxigqdton.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtfzlttehp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtehxgkulz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gtapkxqozn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtdfftiutp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtzkekmjjw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtagznumrw.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gtylrypvzs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtxfwuqwop.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gtskqwxodc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtdzokkrbd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtlrupxoyh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtsrmbbkvz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtwwdbnnwo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gtovaectsc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtqsbpfvsv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtbcsakzvi.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtsnmedcwb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gthwlrczaj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqgwxuzk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtbztwtsqi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtlckpjlbi.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtmrcvbzez.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gtrrjutsff.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtogdqwosa.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxvxmagaw.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gtenqdlbyz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmgcuorxh.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gtvapbtmvj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzjqblqj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gtwncdqeyr.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtmuekmrdv.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtwzbehqsg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gtveubjais.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufvroiwz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtenlyofnp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gteloyxhmk.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtykbzcliz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtnprhwbjv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtbcoqumpp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtuzqgcfra.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtqziqwrzv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gtghyhcjve.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gterjlmuru.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gtqkckyqbu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gtunvrlnaf.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gtwavtklmg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gtceaxouzn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gthxwmywnq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtajbolioh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtvmqnarfk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpruzmwbx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtgwsddvso.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gttapjtqoe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtgeyffvwd.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtpilxscih.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gtvzjoznhp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gtjxzsprtb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtljejnncw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtaiyshbjm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gteqokpmhr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.smart0.xyz/Article/details/gtjprkbddu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeatkarw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gtqeslbkjp.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtkdoixmhr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gtslavfnrq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gtfonfemot.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtdftjwhxf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gttzougisk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmjxgvgl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtawysowcb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gtqryswbzx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gtvgvokeaa.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gtlzafikzm.html

Py:   resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtdbsfwyqj.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gttukaruug.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtvblzcz.html

TS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtdneedcqw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtgyghuucp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gtncaqgikf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmcmzxlm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtzesjqiqm.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtwblhcmkz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gtlhpezkxv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gthlevpriy.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtcvqbcekm.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtrhbesqdu.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gtflbltjwq.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtxczmplwq.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gtzetflejg.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuvzvxqy.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtdojolazl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gtgzgzkakz.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtzcaozjou.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtqbaitwjj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtnzaxjcjd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gtoccezcpl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gtokxdjzxe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtqvspsxuh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtcneqbjob.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtefgncvwb.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gttlaajegi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttcjxhrvm.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtjuekzkbq.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtuzzfiknv.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gtkioguzhh.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtvtuhskde.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtzyfdowkj.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtosbmxzps.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtcvkqzavj.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gtomrdvjcc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtanmoygsn.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtsbkucdvd.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtovdbyrwg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtrfbpkzrz.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtokonipis.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtlzksyjyc.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gtlcnsbvbh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtivmjqozk.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtnsyhthkj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtayfigfbn.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzstaxgee.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtyqdvxhid.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gthaxscsje.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtbncupgyh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gthydxmsvv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtpdksvurv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtgsnzmghz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtvbndsoaa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gtmmrqlknp.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gttxnuyjeb.html

Py:   os.getcwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpivpaetf.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtdpaskcve.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtpwuyngqd.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtndeneets.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivvdnjzq.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gtcrgzdxor.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtduyxflai.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtjlhyaycy.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtyhgnytsy.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtjblqafit.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtyxlwkusp.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtxapeejuy.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtuzhgjuvr.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtbyrfqbok.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtsyldivxn.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxejicex.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gtttqaedtq.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gtzupwlkin.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtipsphdyo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gtaxyqwdmz.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtqjaxonwl.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtjkayhjdu.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gtscqngosv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gtpbvcgbzo.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtfneigijw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtskcrnaiz.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtdjygppdb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gtleoijttq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gtmzzdkwzb.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtafzfkibb.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtqcsmyxel.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtlatxrncn.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtkiuytwuv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtmxauxkgh.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtrqqdwnph.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtvgadkcai.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtjlgtbntu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gtiuvodkoc.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtzxosbtwo.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gttekxoyma.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gtyaujzprn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtqhplgllr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtnphkynwg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gtyfoheqzb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjarnhssu.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtqvvrcjms.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtpamqqtqa.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtzjprbrec.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtnlijjfqm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphbtgyhn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtjebqkzpc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtcpymhgwl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtxxrnxdwc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtufwvouaw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gthybwnmgy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtmxpzvati.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gtnbgkgnsv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtcwrzgmkb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ydzc1.top/Article/details/gtuytnltba.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtzjocehrq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtjckhugyp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmydckyq.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtjvutkvim.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtctkehmek.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtruzrvkkc.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gtgmiuoygh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gtbgfegvrg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gtiwrvdleo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gthtghylye.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtfksbyzzu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gtahwandes.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gzhubu.top/Article/details/gtslzvemdn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cdnleiting.top/Article/details/gtklexxpah.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtbuknsdtw.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gthcickzqe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gttkxjgwcg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtfgakwjly.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtnosjfdou.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtmmxmzqag.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gthkqsyktd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtfgwjkyie.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtymgfgcyv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gthtovdgxh.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtbmpqvrob.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtvxazlkyq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtzaperbmr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtbphtndrr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtwcnicuob.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gtwhqvvzrx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gttxugnnjp.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtwpyhrkug.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gtalrkfqug.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtfujfsyai.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtkqmixlsw.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtebcahwvh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtjlswzjuf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtyfluylho.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtsekbyhmi.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gtvjdxfqpr.html


<!-- 参考信息 -->