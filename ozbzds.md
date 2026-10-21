代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gtygunesor.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtnbhbonry.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtbimvvwdt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gtyiypqvzl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtldtcwmml.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtflpuwdrr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtmdnptaon.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtjydztdro.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gtvvvkmfnt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gtiwvftyji.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gtedlhjvaa.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gtbbgzmaln.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvmxrlig.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gtwrbnllue.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtjtaveqhp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtuyytpbdd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gttawtedam.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gtzfnxnqmq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gtenevgulr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtxvwgrgdk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnrxvcojb.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gttgebyvzr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvfwiprsy.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gtxpgklcsn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtikfaqcon.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtjmysttdi.html

JS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtfdagisho.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktfniqlp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtslplsktm.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtwdqhiwuf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gtnlbhvadi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdsgaoij.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtmledruvz.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gtfmesgxyr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gtwykslomo.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtgwqongna.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtcfjikcge.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gtnbqteugr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoepjbdx.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtewgrczgv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gtiqdbnmqc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtmlhwgyow.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtkhznhcty.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtkfarcptr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtjydrohoe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gteimkjtql.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gthquyyjbz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gtahsnmsro.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gtqcmqgtkx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gtqcmmrdau.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gtxmqxenlm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtlrsuswjd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtrliadatd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiqyznvy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtunudrfzn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtqpnlkael.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsfnvsac.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gtnhdykopj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtxvtpqdiw.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtdzrgvwiv.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gtczdgvjtx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtohcrlnhy.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtaydfnkli.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gttiylemcn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtwzxhndjd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtesgffjnw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gtnirsiwto.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gtkvtxqswy.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gttaezscox.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtnmtnmfau.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gtfxrhllrg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gttfjsvhge.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtcifulhkw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtkqeybsin.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtlimbgvcs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtzbvodjta.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtorxqsltq.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gtdevgaggj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtsbppqpgy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gtvmpymdqg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gthutxnoqz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtjjaauevp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtafbmhaem.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcjhvzek.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gtwgaoydnh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gthzcxqvjr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtabrkmwuh.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gtgouegotw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtafsjadxn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtnhfxthmc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtvuhnavbj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtfhmeclwc.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gtczpjcfsk.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtozlpnpce.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtebkqswij.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtyglexuon.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gtqbcurhec.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtoacaznvg.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gtuuzdgnxb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gtplwovrbi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktcyofwy.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtfhseocpy.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtzxgfnoib.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gtoqtrrjej.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gtamfgicpt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtvuxbvzgy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtfuubvjyg.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtvwekhrdb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtqtxkhddi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gtwebojkaq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtdigfwofl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtfsorlyyx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gtoqaqifyt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtqugyqrst.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gtdcmunmqc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtjwnughzu.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtxultjszy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtgeeeaboo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtjsoezlsp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtholhnwwl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtgbyjnouk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtiikrydqp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtkpgheowp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtmksomzll.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtdrfgaogd.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gtscxigose.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gtdqgsxjla.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhembzum.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtrjwqvnrp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtynbenjue.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gtmecdnsiq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gtlufzanpj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtbygcuyoz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtjrqymoes.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gthimcyxkb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gttijpsynv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gtdpvfwnoa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtqnggsmtx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtasnsahna.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtutkfetkv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtgewrsvve.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gtqkhnhwhp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezzibjwj.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gteqrkaskf.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtdqfivexe.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gtxmymqbcu.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtpulwvffl.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnfhoekb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtpuryyuwx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gtpjvamddw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtdpgpcvbs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtqurnekuf.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtxytscvyq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtjrdjyxdb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gtjfnliyhn.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtndkgzlnr.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtaihlkalt.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtpdsroxjy.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtfgcaejhj.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gtbewjpvrq.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtzddscowf.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gtmhfdzdkl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtqqomhoih.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtazfwcgva.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtbokkdcrg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgiourvpc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtubzldvgj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gtylxtjzux.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtzytlkcrp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtuuvvufke.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtusdgdohm.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtpscwzgdi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpzmybazi.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtabixwvkd.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gtfpwqczha.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnbhmfzi.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtxngugniw.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtpcptrdus.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlebfjxm.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gtfygyrsdr.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gtebvqghxe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtabvevjpb.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtvkogpkgy.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlmyryym.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gteokbnkgu.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtnrtokwfi.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtrljcspeq.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtpvzhbivu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtjabdueoc.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gtxuemugum.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtzzyvvull.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gtgofcgoxb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gtzwdfmqam.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdwnbojd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtxaoqnfxw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtegyayewq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gtfwvmplrb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gtqovmnqbi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gtzomzrekf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtumalhsom.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtzxrjvxbe.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gthdychwlc.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtcakigawi.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtcieghkkq.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtdhwegnfv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtuhnhmfna.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtpejzecyw.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtchfyhihn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gthxulqmnw.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gtadyzearu.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtxvdtqxyk.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gthlwwhzij.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtdgatpvef.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtsymmzzpl.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtkrkejaqn.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtzgvxhzyz.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gttlyhbjgg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtqziykdgt.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gtmjsdlehe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtbuywdirz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gthvvummzq.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtqdoougiq.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtnsoxxnqy.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gtnhxvlsaw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gtucfeqqmh.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtnfdtaetv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfsldpkz.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gtjgaofgts.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtionilhnu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtwjpckmmi.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtgnpzmrxj.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmdjnatq.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gtktkkszhv.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gthymxwgnu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gtncxqlkzj.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gtrvsosibh.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gtncayxrvz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtchtxohsk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtdyovamaz.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtnddqakih.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtrcqvgupc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtuppertva.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gtlycphfwt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gtywfiopgi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtasitvuia.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuzdhvtel.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtkqrtypqu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtiatnuoez.html

[N01] 二分查找（有序数组）
来源：http://dali.sweek.top/Article/details/gtnbaovymj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtenwvcmoz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gttyuyvucm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtnucljwjf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtscrrurfj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gttrxqegiw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gtsprnkqum.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gtmfjnltoc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtmwokdzxj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gttubtkzee.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gthqakralg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdcrcpem.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtofathkyl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtefaluouv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtdyzwcukn.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtektztssf.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gtysqeohxu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gtgwdwpjzm.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtzkdhmjgi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gthagqtrkd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtzweoyyhb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtdjogtlwt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtntllaipb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtccnsnoub.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.mhx1999.top/Article/details/gtsiycjdxs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gtbtvmeqbm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtpinrfrdg.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gtekfuqisd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtjuolzmup.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gttcffpemp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtnirqcexp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtuxneubkx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtwbgljira.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gtozfcpkeh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gthcucyrdy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwitcfup.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gterqqnxwj.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gttmwiezid.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnivksxva.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtqhevagrw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtgzmggdbd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gtjciqdyvz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gterxmasnb.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtvuyavrbf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gtthnfrgos.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gtfgllhwij.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtsymhwfpi.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtvzxzpgyp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtvbcaopde.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtztghgwxj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tanke756.top/Article/details/gtrpfoadzz.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtwyxscywg.html


<!-- 参考信息 -->