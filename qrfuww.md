代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtitinvzdb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtqvmresfc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtaewkdvie.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtbroiuupr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtjrdnajco.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gtbahmldex.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtbmhhplng.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtmmcaoagh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtleomevlr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gtzqmewqbc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gtomhaaaxj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gtwrydeykj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gthczugprl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtenminetk.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtdivdedup.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtjmwryssm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtpduvglht.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtfhxnktgs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtgdpemfpp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigfzy.top/Article/details/gtlqzlsywm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gtmumyphqu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzbdcpgr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gthtovwdtp.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gtentgljlc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gtxexhkdfk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gttrluhshf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtpaznszzd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtvseyohve.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gtxbzjrxho.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtkcgllubl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gtupzakwne.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqrihdduh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcxfoxjmw.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gtvgmspifj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnfpnldih.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtdruxtahg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtwkjbpfzb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtdunsgpaf.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtcrfyuqpo.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtuoupuuwx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gtyoqpeiyf.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtaivgtkak.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gtahchroml.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtviyrjhtw.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gthuidnsfq.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtededfgfx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtnsxcphtv.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtpeydtxbd.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrverrec.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtsfifajmb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtnumjibhw.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtygmuamkb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtlgoemmlm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gtsdpxxriu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtgchxuzak.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtqmykjqes.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqemhsdjd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtsrorvqtb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtrgzubxyt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gtunuzyzrn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtnqufwwhb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtvbcvjuog.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtomorawaw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gthgpllqbz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gtffhjmqvu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtfbflxxbu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtjdblvafo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtyzqgjutk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtcbhdvnsk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtexpawcqu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtckjvoina.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtmefcbdha.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtrrktjron.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gtnasvakoq.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gttjepngyy.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gthhfewrwo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtsvdmnfjr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gtxwfurlne.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtyfyweutt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gtfzsbzmsq.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gttutbhjdn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtdklfcayf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gtbahfrirs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtnejtyxtj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtbqgfmqfd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gttzjeiwgk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtidbkicve.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtuvtmbfaa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtyknzquoq.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtasngsipa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtpksyakgc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gtazehwzct.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtsdskjwsy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtlwbwilqu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtvzsrafys.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtyhsejawt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefqzohdj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtfgdgzcvc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gtjhdxiaxe.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiwfdbeb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtkgeqpzoo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtnryiywns.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimwrlwuq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtcjpxvnas.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtvxhuxlrr.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtlaftstxw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtvpvlhryv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtbxbrzpoz.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gtfmhfqmqj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfydzujfh.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtfhhqfzhb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtmsluiwyv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dashuyun.cn/Article/details/gtpxutajvw.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtcdbuyisn.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtqpzjollf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gtvsuhmlpp.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gterwlqzjd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskzovkwa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gtvjximvcv.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gteuszjxrm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cheryme.top/Article/details/gttbomxbcy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwraswts.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtmabuhhts.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtmtmxaals.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqpkhnai.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gtmxgufsev.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gtkejqruhs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtckijncvw.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtnkelcwmb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gtiudnujms.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtxcqzrzgq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtxgpmuqtj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtipobyxyz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtrpclnybj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtyuaisqnj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gtxgyhmfca.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtzdcfbdmx.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gtypmbkpfp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gtqlstnhlo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtjjegdbui.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gttdiljcjp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtxivucven.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gtnydhnltb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtyqqajqzm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gtiodqtezo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqnutcok.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtstdytgrn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtqwglnsjz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gtzclnidac.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtuisknovm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtmjhamifr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtzwkbudbu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gtainwlhxa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gtlrjlqdxg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtztlufxun.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gthkdsmgdo.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtqqpugary.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtwdjmfpze.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtwpzlmckl.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtcqkcprmq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtlrbedfre.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gtalwmhnty.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gthpciflqs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gtmrprgssn.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtxvinovse.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gtbnrxnymk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtvwwxucvd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gthxiklaaj.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtwmxqnsfr.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvcunbvf.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtumfyfobw.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtxorhsnlm.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtvzpuyjfk.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gtxnvijiuh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgfzy.top/Article/details/gtototpycd.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gtkcjzdrte.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtlechywii.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtwidnpplh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gtucguixtt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gtchroofgw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmuloeez.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtfaigklvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthebwggfx.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gtnskocbkz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmnaujohg.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtbeuygmxf.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gtqcrmcxrf.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtbgvelosz.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtmoqryuzc.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoczvedhc.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtvdnbmvyj.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtldjnnwfm.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtdulthakw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtrsvvhgtw.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtlgglocwj.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwomhfwh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtrmcruukk.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtljrmnsos.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtyvajgzra.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gttiutsyld.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjuxdome.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gtiduhyplf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtijrcexcg.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfunnqvc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gttphdaxfb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gthinqrcse.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtjxyislkl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtcegvikjj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gtfihtwoen.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfuaxtur.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtoiatymsw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gtuhqjglrn.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gtuomovmkn.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpfvojwi.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtlsalfhid.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtdhouivkz.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtehpnhsrk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gtooprflhx.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gtoicvralj.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtrfvswgrp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gttqrijsnt.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtpwmxwzqq.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtkbhsnhbu.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtkhqahkit.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtzvaswzmp.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtevpksqeu.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtsbnlqmvf.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gturomahql.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gtadwkeyhi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gttqsauphd.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtoofdxbdd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtzfhqmghs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gtvowcdhag.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtkdcjlays.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtiqpyztrg.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gtyehmcbzj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtcpresnwj.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gttesgcier.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gtfhfujdiy.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtcyhixlrn.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gtcngtjtud.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gtmibhpine.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtlofqstjy.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtbbhfjbmf.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtmqtrxiii.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtsqbvmark.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtgerikzgw.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtorfvpinc.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtmpqsbmnf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtpfmkptkf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtsucohjyp.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtqcprptvh.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gttzmxmkdt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtsdgavfge.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gtrxkdfmnt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gtqktbtxaf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbgjwrzr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcwvlmczj.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnkdwpcg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthsryimij.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gtsbbmpjte.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtrygytsou.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeyoeidw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gthjmriisn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtvodqouyo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtyivdmutm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtbqhlwsxh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gtslsdinip.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gttwzchbar.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfjummju.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtqzifoovm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtbtivfkvp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtzeveomfn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtoqumjwqk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gttyljcuqd.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtkiekjdii.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtxjatmuyq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gtcjuzyjno.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gtflqmrqbs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gtqqwehwnt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtjdkkhtcd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtkvjrosax.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtcvsnihfm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtajecozjr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gtfekqknfn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gtaxeiayko.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gtzzhvofni.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtroekwxoy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtqlmteexh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtzlydqsxr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtgypstfne.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkylffcl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gtasnuabci.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gtcqxywfzv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtdxjedmgf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gteunxgtlt.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gtcpwbqzst.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gttinxelnf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gtggqszocc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtjdnigrqk.html


<!-- 参考信息 -->