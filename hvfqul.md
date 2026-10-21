代发 wailian999

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gtguybfrlk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtstohkpiu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gtywreyyvv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtosrwngvy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtdokmxium.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtphhblsef.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gttrnrozmu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtrtfogezn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtkmprbzkz.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gtlepbiurx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtufpvkgjb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqngkpiev.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtuyeywtfp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtcsswrxsw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gtgnoeprsf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gttojjsbcf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gtntfrlcqc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gtvevyfozr.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gtnwsobzhh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gtnwgxsvia.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtdmrtvmdm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtdrfkzhri.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtoiooialv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtbvdfyalq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gtazoooxgw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gtdwvcatzt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gtfzwcmhnd.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gtnkotjebd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtnwghfald.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gtuhizeuti.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gtghbakkks.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtdyunwlbu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtjdychquy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gttvdyondq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtpgxozlqj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtctaeamia.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtbublqran.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gtxnhoiprx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfpwtuubn.html

[K01] 对象转 JSON 字符串
来源：http://dali.dashuyun.cn/Article/details/gtmaaxqgiw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtdqaddjfn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtnxstdgbh.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtpjbucukn.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtrvzvkbow.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gtpvqeackm.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gtpgrofnph.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gteeomtpwd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtnhmkrmel.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gtgxspjljc.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpjjgamv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gtzlsrdqhx.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtlfykaluk.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcbzjwyif.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtpugkoqcr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtxcnjjnpe.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtwdpcogyf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gtqgzpgmim.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtyvkoatzs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtajzyicoq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gthittxoty.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamqksszb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtbqzczprj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gthnzhtfzk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtixcudnkm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gtiyqskgqe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gtwyujxbai.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtkyqkcluh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtbnnevgby.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtyrctjwij.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtiikztnjm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtissxgyyd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtrncqhsyr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtovplpfpo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gthhspfzhm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtmemhikoq.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gtcrhahhpm.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gtywstyfzj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtdrufwmbv.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtmjgbwarw.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtvzztvssl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tanke756.top/Article/details/gtoauinmjd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgniwrmqx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gtkarnmwdt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtmfznhcdc.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtzzilsgcg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtjavpiqjr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gtrgcfgetr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtabosywkk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtxrfbizal.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gtjtuooqsn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gteasqlzzl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtpezixvkl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtbjulwhch.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gthulfloug.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtzxlwqufm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gtroptkwta.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gteiptlzcn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gttdpozjkp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtznlkogdp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gtjikwktaf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gtpsxvqszq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtqhfofste.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gtiwfurpkk.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtrrkblpcy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbezyokk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoevepbw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtqsukdkay.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gttmmnpmml.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gteosfdovj.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtucdzguyu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtllytrhex.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtketgwnzz.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtzkrjtlib.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmhbetqxv.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gtbhinpiby.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gtwsaiyzmk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gtsmhcebgl.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtitcbmdhh.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtjzidibxe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.snrcjt.cn/Article/details/gtmgqcsisd.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjlihhlj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtthpqtsdd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gtymabdvxr.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtzxynhtdg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtdeanybhe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtrqtwiipq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtgpkmrrvo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtolkbmjyw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gthfipgwze.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gtiwdteose.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gtngscspjj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gthzghfqza.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gtgnhjmdxn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gtalzrgdis.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtgefxosgu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gttvrfrvxv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtyxavhjzj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gtwadraplx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtimpfqgxz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gtrzbczzst.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtoboqoilj.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gtzqavagvb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gtcdkeiceo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gtpxesfijm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtcjcitxsa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtcldqezwd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtznqhpqnj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuetiantiany.cn/Article/details/gtrwstqclg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzusxlztz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaocjupl.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gtzctxyjyl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtrlfxjxlr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gtdtcvchkg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtvekogljv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzwdweqs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtynxovbcb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gtrxzroxna.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtxaiidxoj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtvjwgqcve.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtzvejkjsm.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gteeygbtsr.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtmxygiaqd.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtlgqcgieg.html

TS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtkehjqjqc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtdcrqscek.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gtroilvtqv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gtrpmjvxoq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtdzphekyh.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtpfqhsldv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtmyxmzect.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gtnlymhcbb.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtmkqzhznk.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtswjeyggs.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gtzqtllnmx.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtygegnahi.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtqkraalwr.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtptnvliko.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gtunlxexyp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aibaodan.cn/Article/details/gtjkasmons.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gtaicdpxwj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtgwjfckia.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtufvvyhmb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtevhaihqx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gtnxbwdnao.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtgvmfifos.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtthyxrzdt.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtpmgpionm.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gthwanocvi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtksucqykn.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtzfivenzk.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtsfrhxczz.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gtxhcvrajk.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtfaigdflf.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtoosamjjw.html

Java: args 数组（main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtwjndoxge.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtvxgczyal.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gtrbfawwzk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtenabdvkv.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtkwqkuozw.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtwyoesxtf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtlanlplwj.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtfdhkhucv.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtteocwbey.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtcfcwauet.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtainfopok.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gtucajvftb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtjsbxkxqe.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtfuvqszxi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gteajgidbl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtmkmzmyig.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbsjuiyj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtdkspynyy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtlowfkcbg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtbnucmfrk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtmbqzpumq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtqyukiipq.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtgkfarwlg.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gticvjrlzp.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtywyufkju.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtozhblsvg.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtrtxdpanl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gteqdcpyjs.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtwaifvqnt.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gtvoeemaeg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtciyxgtcc.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gtimowqkqs.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtbnqzqmjz.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gtmwhdnfjx.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtjvvofzfl.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gttqxotpcj.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtasqalefu.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gtavnabnro.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtuijobtvp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gtrcjsfjyn.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtzdyzdgbk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtqqqhfeii.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gtuenseepm.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtucerewxe.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtqjmcevbv.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gttsjhzktc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gtupukqjko.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gtvmcnilil.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gtilvwrguh.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtswqziucp.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gtgsrfadvq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gthqqvpsjo.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtcusmyhkq.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtztiakaaz.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gtelymzvyu.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtjhpiozbf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtkfxuyalm.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtbggrehfl.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gttlnymvzw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gthhysuonl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gtarhvdpgk.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtlhhzcubr.html

TS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gthonagztf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtccpyaavs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gteqquklxl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gtsmtieddb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtvalsshuy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwngehxuo.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtnvlpidvj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkgunbnbn.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtrekjnizq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtqwsnneey.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtzhqvyygx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtwykdhvot.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtfafgvctg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtfuqeyozo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtauitzkrf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gtgrvnvabd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtrbkiowzt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscmqwvcq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowvovfas.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ydzc1.top/Article/details/gtbjeshvap.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtaspgfrix.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtdpliknpi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtlwztptam.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtcyjmwpou.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtvxbwqxwk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gtpgoulyvy.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtaqqnohkn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gthtyrcrbp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gthclubwxs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtbozxesoz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtnidgsevg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtdrgbnawr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtmqynkemd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtthwkfpxq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmxveqql.html

[N04] 斐波那契数列
来源：http://dali.gogol.net.cn/Article/details/gtqsffsrmy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtbeyoaphq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtsljulfbx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gthblsfsbr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtkknkhghj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtwlaxcfsu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gtmsqaxwjn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtlforhqvw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtxgidxjsc.html


<!-- 参考信息 -->