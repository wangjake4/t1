代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gtjzbxyevm.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtaruoqhol.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gtpvqzkxdl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gtfjqsngok.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gtyedevrgm.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gtmxcucfds.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gtjrxfkniv.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtdiabmzfu.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gtrrgvqggr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtyzzzkkvt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtatqishlz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtctdphlin.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtpolvnfti.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtcriqvvei.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gtspnstodp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gthupbdqao.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtrbagimfj.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtcuuelvee.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gtfewezbxp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtdtwwfjlm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gthbnlrzmn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gtxgxqcoqd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjfztzqw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gtlxcialsp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gtizpcubvo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gtbuccygun.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtqijfgqil.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gteymnaror.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xinyue.icu/Article/details/gtbnafpgnd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtwdikjmrk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtzraffrsf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gtnachxxme.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gtvvosfyud.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtxoqbhiut.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtcmevugpq.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gtgemteegh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gtdryzqkhu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtykmnprad.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gtlfiwkixd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtcxwfwtzr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtjzderovh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtnrjhaczn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gtocbpmbnc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gtpiaygvaa.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgjrbimwe.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtdtywpdwc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtrbmwkbvf.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gtklbmsial.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtxeuwiotr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtzygvnkxk.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtlrzoinyb.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtjskwqcbv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gtpiqljnxg.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gttbxcbufb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtgcnjtwmt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.andypj.xyz/Article/details/gtpuycjfbc.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gtcyedwyhv.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtkvhlisac.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gtyoncloyr.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtimabiiox.html

TS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtoqtcvrcl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gthawxkois.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtzdpmitzb.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtwurxlqpk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtvcdlvivf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtxzvnokcg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtntfmecrt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtqujrqzia.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtrtoigccd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtqnfftkzz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gtadmlujqk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtbbrnkptp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtgnsfhwwv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gtadcvmydh.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtwszgsgik.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtskkwypjw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gttdtbxgec.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtqcsnehdb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtnsbkxkvi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtvjtmeypr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtliptdcxa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhjuxbwv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtophlsqfk.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtbasinqgv.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtuqegyxwt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtupxyqrpw.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gttvqlgozd.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvkgxjdv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gtjpynbhqu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gtoxfufeqx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtmjcwjkuw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtgtzftnvy.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gtqddouynf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtqrianvar.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gtnkqkrqmq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtbfosklqi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtffaglauu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gtwnxjzapo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gthqzlgbkx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzqqdozf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtssilqrki.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtonarpspo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtfcofggil.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtdnuvwxuh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtxckhsiji.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gthdzrmfjz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtrpicifgz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtjaafpvwx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gthyeuyeqc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtxodvxdqx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gthpvogmpn.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gthutepujs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwparakm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtyhoupjiu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtwpnkwtnl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gtahggmlaa.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gtbcwpunrs.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtkxkfglin.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtbbgyvcae.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtghxjheds.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gtomnfdcti.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtniugbrpd.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlynvdobu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwundztu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtbwjtivsi.html

JS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtumwzphlx.html

TS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtkwuqejwx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gtscslevld.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtupmvyymk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtdotufacx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gtixqdufps.html

[L02] 发送 POST JSON
来源：http://dali.316326.xyz/Article/details/gtcejzgrmx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtwbvxiulh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gtthdkonll.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvgvcqcy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtybryqaum.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtcwvndcca.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gtcrjpotds.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gtdrhoverq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gtdqejbuhr.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtwkfqnfuw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gtydobtoau.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gttppzylys.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtsjxjupro.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtnoparqmw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtculpdngj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtqorqitbi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtunjgvumx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtsskrovjq.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gtwiipbfqa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtxmydrjtv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtmkeqzkus.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtpajlxyol.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtcgyztfns.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gtoqzkdcgf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjltmiic.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtregzwtvq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gotoacloud.top/Article/details/gtaiznalhc.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtwfpxirfd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gtmgjasowz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtfyyhiyur.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtyeraeehu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtlyhrfzmd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gtsqnshald.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gtssmphkvn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtylbsijew.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtkiohblee.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gtaiifyzop.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtslmxokzi.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gtzuzzwlut.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtmrvpetvc.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtpuqrvwgw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gticppqewh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtyhwnsajq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtktljwenz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtejgirytl.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtstyvepnx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gtoiktbtgs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtsutfyiqr.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtcrxwxizh.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtahskztjn.html

Java: resp.statusCode()
来源：http://dali.snrcjt.cn/Article/details/gtjyughnjs.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtgvwemudd.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gteptnakpu.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtlzvoczrt.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gtbkinwwfp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtmmvysvzx.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gtspwnicuj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtfqvajtsz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtdrqnqjkf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtftprrsjz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtiemtmqnm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtrhhdjtwq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gttxveyrue.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmavcpjyv.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtjunofhxj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtalieczhj.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtdwsmrjyx.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gtbbumixun.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtdajnbpze.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtqwtmrkqn.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtgrajkxcw.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtkxylutjz.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtjrtqcyjl.html

Ruby: ARGV
来源：http://dali.ydzc1.top/Article/details/gtuaasozfs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gthvqwmzyy.html

[M02] 读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtvvfarsaq.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gtbhhyjsgt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtecfnkvyy.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtvjsapfnd.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtcquczvhz.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtwkkbycoe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gtesfzidsg.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gtldtotcng.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmizgqwiu.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gthoqmhyzk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtwxgzqaan.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtlrrvfitt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtaudyxyeu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtbqrzvgid.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtemjdabju.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtzlniuntp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtbdlaauri.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gtgvgfdcgl.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtnvtiqeny.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gthdhdyafq.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtplumctiw.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtvalllxfw.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtidmgkilv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtqakgiooh.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gthoyswvsf.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtbgidseia.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gtpobwkfno.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtejlkjsat.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtpynduaml.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gtwjjnlaln.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtxistjmxt.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtaaviqcop.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtalkdvqvo.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gttlzapqeg.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtwmwrfszt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtvylalafe.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtfhkzqmya.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtntriajuu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtcvriqipo.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtbrssycvo.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtsscypnyp.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtuzpvvjxd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtdoxmzkab.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gttkstozal.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtswpxhwzy.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtqhnxebuq.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtluyanwbk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtgnqlqplp.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gthjedvqrh.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtoemmrady.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtapnutvpu.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtsmpbavjt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaefuxopk.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtbsgjbnqg.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtvgifonjs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gtuevwtcnr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gtsxlpwaox.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtxnmmfvql.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtuhcnrgac.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gtorymvhgc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gteknzjnub.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtdthggxkn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtpyxojypb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtyuxbabos.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtwpibzoql.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxddglkkc.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtdwuumlsq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gtskptccbr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtbqowqewe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtqzjhgndf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtxuacmwyh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtfbvfoaek.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtyggmdalx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gtmifbpxib.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtgtfzhhdg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gttssmrbyp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtiwbqtkln.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtyeodolpc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtqfowcopu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtsgagxdqs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtmmsgdmhm.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtkdgsoqix.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtpucfvdyz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtdnkyrchx.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtmxtiqpaq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtbmswxrsk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtdgnoqauj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfnftnhq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtnxuyqhfd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtrhmdqcjd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gtboiozfnh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gtzbrrtztp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gtlxgswumx.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtcrixuiqr.html


<!-- 参考信息 -->