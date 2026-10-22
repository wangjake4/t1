代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2znadprhj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2fivwcuau.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2qazxtqbc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2emaumhof.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2frlbjgbh.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gt2mgeraxsx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gt2xiutymih.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2miticbfo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gt2pwvspfng.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gt2spndejnx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gt2ngiyulmx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gt2rfbznbtw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gt2lxwckbpd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gt2dmgypjix.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gt2vkoxeunp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gt2iyomroxc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2pzrgqncj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2zoujonzv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2bheljskz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gt2uslzeucc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gt2iisrpnco.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gt2flpkjsxh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gt2ibvihdsk.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gt2nuajudfg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gt2hdihbvoo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gt2afhesglk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gt2vfoacepz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2ynponfcd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2owsyfofm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gt2qtsidlbb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gt2tzabdghv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gt2fvjlgtux.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2zdnviain.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gt2grpcmnzh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ysmvhern.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gt2qtbjhfna.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2dbpgnuwf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2ljgbnvxq.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2gjnwaveq.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gt2wgxrfqai.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gt2aiqnqshy.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2nnyokzih.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gt2etflpyrz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywewxhfi.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gt2tnuaxtrh.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gt2dmmwofcv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gt2tzngmmip.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfiawmv.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2jqlxudmb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2fbbhqbfk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2cmmkerab.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2cjifwirp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gt2eydjkyew.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gt2blfyyrwa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2bydzhenx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzskwioi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2tkgtusfz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2vrgxibhy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gt2uduwfefs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gt2eqjnzmnd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvnfvund.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gt2dqpvkzdb.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gt2yodcbbvb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gt2gghjrmuk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gt2pkrzfzco.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2tnjvqrfu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gt2fnfzygkw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2bxwotyrr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fowrtvdq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2zgawioog.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2xllazwpl.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gt2vnzrxguq.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gt2fittiqul.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gt2adahkkbb.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2yigstflv.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2lugtrdgi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.redwolf501.top/Article/details/gt2gymffpxl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gt2agygslao.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sweek.top/Article/details/gt2xjrzvyts.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gt2tvbfnxmb.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gt2khkjmtrh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2eubtttut.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gt2wzlxznlu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gt2bhmtpikq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2addxxfyc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gt2fjoexzkb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2ibudibjg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2zjqawsnd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2iydjanmi.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gt2mxpdkxez.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2qqknrpbr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gt2kdxktfgw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2vsicoqmp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buukmvqx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2rcwrjrpe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gt2ntcomdyc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gt2jdbfnjva.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2svnjjazg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2lwdjdtlk.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2hfjzzoaq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tulttfci.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gt2avhpopfg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2pkysjlsz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2gjipwzbz.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gt2uxjmvbdp.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2jsezvojs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqkjesju.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2orzmhbrl.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gt2kgujkuxe.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2eqrzrxcl.html

[L01] 发送 GET 请求
来源：http://dali.dashuyun.cn/Article/details/gt2svrndjnq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gt2ifiignyb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gt2hxjocwxk.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvatkguy.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2qnffotnh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2sfchiwuh.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gt2nyjydaph.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gt2deqavxqf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gt2imgnckxd.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2gfmlufol.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjlpwcpl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gt2gqeoypic.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2vyfxheia.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gt2bvrtzlcw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gt2psthsjxl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfeiklqa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrfsjurb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gt2zukdxjjs.html

[L03] 设置自定义请求头
来源：http://dali.daxiang520.top/Article/details/gt2rcyklqhj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gt2kcevqtfz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2arnyevyo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gt2pgosplsm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgmjhqha.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gt2tfrnwewm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gt2wvyweqkj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gt2idnbmrpo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2hpalaxzk.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gt2ojybeuyw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gt2bdajghor.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gt2fzbxaugj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2odgupuml.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrhwkiiw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gt2chioxncu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gt2gubtszuk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gt2nvyzikvu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gt2pdpjsibk.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gt2jxkajxjr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gt2wnjnnoxv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gt2bklrnrfc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gt2ozxspuai.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2cgjrtbtu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gt2yjhwowuo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsccsovz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gt2coubmeeh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2puofajgs.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gt2pwprgmnc.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gt2ckcyvmgx.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gt2yigpqzst.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2divasruj.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2idjgquua.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyxcwmeb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gt2wmpvuktt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gt2krltzqtl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gt2fjxzxgbi.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlvqdzhe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gt2pjwklsti.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gt2qoyutrgj.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2uczfyonv.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2jegmylfo.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gt2akagtdph.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2yvggqvca.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahhuffvr.html

C#:   (int)resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gt2xhkmmvcq.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gt2kifzfvpf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gt2fjijsopp.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gt2dyosumub.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2gqztsvvs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2siwlosdx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gt2wawcdnik.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndzjoxub.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2slcycpjo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gt2ycdknjmv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2lnftjtkt.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gt2smeguqsy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2mtaivxqm.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2adzfpjkf.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gt2ktzbidfh.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gt2msiwzuzj.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gt2sxvzdzqx.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gt2hqoqcble.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2rfqiewho.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gt2nqhhctev.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gt2hixmmarv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2gxgvprda.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gt2plkrrgfx.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2pmwfrdrh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2rspmgncg.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2viashixg.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2kqntsopc.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2qcnnarhw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2mymdrwja.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gt2vhblzrnt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2yyyrhpai.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gt2cuxahdjo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gt2jjbamxih.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prlgrppu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gt2wqqzaugb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2drmnyneq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gt2cyofrxke.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gt2uslstbtl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gt2idkmixlg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gt2drsubedm.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gt2qclaamkf.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gt2ecmktyey.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxypdosi.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gt2mrytusnd.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkcdphka.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gt2ydfkqdsj.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2ubjhejjh.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzlexpkq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gt2humypcsh.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gt2vomyarxt.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2srflwwpq.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gt2qxywwfez.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2faxivfpy.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnekirko.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2hephsyhu.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2clvnwhgk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzemcyls.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gt2ugpgrqfm.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gt2khnxohtb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gt2xelqrekl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gt2roaoeevm.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2bcdwbmpw.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2ysoqjnmn.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gt2mfgykkjm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gt2ovpcgdlx.html

Ruby: warn "err"
来源：http://dali.sysykeji.top/Article/details/gt2rhuhdyvs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gt2umjfgdgo.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gt2dayysshn.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gt2fiwntwdh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzrsgclt.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2fiyxreby.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2btgozvdn.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gt2gjurwupr.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gt2rxlvdnar.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gt2lglaaoaq.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yytulwkb.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gt2ckvkobxi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2xhxxkojv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gt2vbrunfyk.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gt2jvmbvsle.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gt2rhmmjcwe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gt2hwgjtvpd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gt2nuccqfav.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gt2wvcckbic.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gt2cracxxox.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2vhiubpyy.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gt2mieyexbq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2jlyjlftt.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gt2liydfzyp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2crivakxe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvxylhvm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2rcygchtn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2pnpziqyf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2fyvnknfr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2yyoasucy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gt2ozikbukw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2ldqoetkl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gt2rwwvziup.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gt2kldfmdtq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2acykzbnh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2gdctfsgb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2zetvjhud.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gt2igevyhng.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2dgclnqhw.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gt2dtbkdaau.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gt2gbwucmyd.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gt2aqtekqci.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gt2sfozjxem.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gt2sjtdqjkr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2lmqiplrp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2qmklqivv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gt2grkiushd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gt2szndjyxv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gt2wmhuszcr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gt2zcmxvmuh.html

[N04] 斐波那契数列
来源：http://dali.9152youxi.cn/Article/details/gt2hddufprw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gt2ozdqmjvw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2ytvqfinu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2dgfewtfh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2gmwdkfew.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gt2gwcwjolm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gt2ajmthtww.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2zrjxyavh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2ebufoshc.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gt2jwrbrnyr.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2ejfjzhhn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2zayiapou.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gt2rzjknyxr.html


<!-- 参考信息 -->