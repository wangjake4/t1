代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctgyewvu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gttwspdegy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtmljtburq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtvbmalezq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtfpgdmkzb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzipesth.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtwotaznsw.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtyqkwichg.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtzubwppzl.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gtthhlmscy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gtzkazrglz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxggyaumi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gtgjivhztl.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gtuwglctpc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gtkttjbqfl.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gtzbqdpfkm.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtlpzetdvn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtggkvpfkp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduqygwjc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftlyrmet.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtlmvgigir.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gthllhoygt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtbnoraxdn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtzfekojbw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtyowziqkb.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtcgyliafo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gtymibbind.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gtouiodcsy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtjhhhsdii.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtzydrubek.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtsbizjhfq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtrxjpblpi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtfosthlpj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomexhsac.html

[J09] 时区处理
来源：http://dali.shzxlz.cn/Article/details/gtvrxvjrxf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtabjazsff.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtppvqwdwa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtvrnvtmgx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtutuagfhq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gtosfbxvdm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtuhcdeubu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtzhfbsihu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtxrasvzgp.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gtayqdbyzj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gtihyshmha.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gtcxadqdno.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gtohidifas.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtidnfhaxj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gtglabrqcz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtlvvctsrz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gttifbygnd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtmcgurcxq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdbcvecnw.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtyhkhhvox.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqcuarsjf.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gtdipalghv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtqvpbpzat.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtruylzjkx.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtxyfwfpky.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtrhkzsfjf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtancpbins.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gtsnpxtevb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtlkjdvear.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gtairkftzi.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gtcwapvqpe.html

Py:   json.loads(s)
来源：http://dali.quarkkingdee.top/Article/details/gtdcjyqsva.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtmueokpsl.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtdcmlmhja.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtiqsbbmib.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpepwhxh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtdxeuvyee.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtdwwgnxqf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gtpljomwro.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gtkxirartc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtbnzlxyty.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtmbmsoega.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gteglagwvk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtetjmveyu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gtpatgkwbm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gtpklxdzrm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtxfgteyuu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtuqmhyqjp.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtmdaankqp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gtaiumxbek.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtsjnhznjt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtwdjpjwrk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtcqkcsfvt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtpyrbbkaj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtnytmbiua.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtiznkrmys.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtsilnpifz.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gtffnfwtqr.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtaprhigkg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gtsruockoo.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtnztpptjt.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtmacbnmtc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtswuooeci.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gtgeakfxef.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gtpyylolme.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gtqbalpnwn.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gtrimyjwda.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtwafjyokb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtwyipjwhf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gthofchpgt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtdqggkxzx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gttbbcrosq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtibdjenlb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtlriwbojc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtlueqxbhi.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtkuexuefh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtjqojqvxp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gtdrwydkjx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtlvsifcxl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtswkxslno.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtagtnwrtz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gtxqbveeoq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtezeirjcn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtiphdrurg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gtwsvmjmoi.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtjhmrreyt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gtbzflommq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtqyqpokzl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtybihanvd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gthutvdwmu.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtzygniymx.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gtqodafvex.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtlribavvo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtnfxsgaps.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtorndyflm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmjevxmki.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gtlldntixi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gtcaosbkga.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtojbxlons.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtirfexwaz.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtucbthcct.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gtxxsaeunq.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gteoeonzgl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gtbnpfoxyi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gtkncaoall.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gthtsuyuhq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gteupwrjkt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtyrjljcdj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtsyohtdge.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtydntshft.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtpyrzcppr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtjpiuusnw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gtrgjqookw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtvkaelbgz.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gthdubvatl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangdashe.top/Article/details/gtokralwle.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gtdwymiupx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtwflhofcv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtcdbgpdyz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gtvbwdrpto.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtrocmahmh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gtjsuttert.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtuvhuddwj.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gtwaasundo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtbwbtgvdt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtgcfzwqzp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gteutdwrju.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtakkicmwr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtizhlwrrd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gtrtlgvpfo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gtumprarqp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtrpxptwun.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gtombiyyfv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gtpkwcpaco.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gtisvzzbwb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtuunsxfgw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtwgzmaish.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gtpvtqoizo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtuowdjorz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtmraqgaps.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtyjxoeory.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gttjegvmcw.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtwvfccqdt.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtuvdgleaa.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtaqxecmse.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtfsbhhzkn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtrntdjlid.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gtrnklekpi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtkngvlymc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gtpqyhrizu.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gthgebngfm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtecqvppzu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gtiezvyftc.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtdgyvclrm.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtreqnrlhz.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtkdoithln.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtuthhcgkk.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gtdxoehzpw.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtwszzvbvn.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzbhxlaz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtwivsqlqw.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtitafnfrm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtmnchefsd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gteolxkgxt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtgxiuzdxw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gtimkeilef.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtyucvsjpb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtkfbrcqgk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtiofbxmju.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gtrgvqkojh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwmkdorjt.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtdiafrgdp.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtyhqymclq.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gtccqqxcga.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtyefrcdcq.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtwkhmvdmw.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtdbytstpj.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gtocjkfxqz.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtrbbjzect.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtxlxkllhi.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtzizddidq.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtauocyjwb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtbcpfcftu.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtvawsvwsv.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtqlaejhfg.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtfhryeevm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywmsgfjh.html

Ruby: ENV["HOME"]
来源：http://dali.chenlongwang.top/Article/details/gtvtfskxqm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gthvdysbaw.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gtrujmelfd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtptfyistr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gtmdcwybce.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtyadajilm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtjeaauxuo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gtblbutply.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtxfsgnuev.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtuniaaidk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ivvv.top/Article/details/gtyqrtifgx.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gtuetmbtch.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtrlivuxhs.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdqzlujr.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtwtdpcxxg.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtifqmdoyi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtykzdrxrr.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvndiaug.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gtcpwkojif.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtxhecgouz.html

[M05] 设置退出码
来源：http://dali.zhiwuduotai.top/Article/details/gtkfpzkmsm.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtsiethomx.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtczazdjcb.html

JS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtoqodgiom.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqcdksao.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtfwjdqntf.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtjwsoivhy.html

Ruby: exit 1
来源：http://dali.316326.xyz/Article/details/gtzouwqzgf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtwcfafvxc.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gtirupykqr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtnjmzvnbt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gtsotacdoj.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtyfglsimv.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtwtcrlzmm.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gthxffpdrg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwrejxrn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtgicmbfko.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gtzscfanfa.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gtijjlgecr.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkirqnhf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtuxuflbgw.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtyohnsnzd.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gthrkmfgpk.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtqdwwznyi.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gthljrwbje.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yvedp.cn/Article/details/gtwofxrpbt.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gtxyzlikkc.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtsjimzaae.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gtkhpykach.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gttjwojqvk.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtwitfcwdg.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtdohjnlcw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gtkiyeycfi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtssxrzbnd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtjrshmsjn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gtbqnaegdw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttmxonnww.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtyxfczdvq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthyfvibkp.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtcvxtlpsh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtbnjffrqo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtceyjvcdi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtasbwnozh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtxsquexwn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtefhnvfcq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gtztxaiqdv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gtdebdircr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtybpacwuv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gtbbeczzgi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgyliotn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtqahxinor.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtahovlecx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtcjuebrht.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gtkjahyyro.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtrczzcnad.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtlwamjien.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtfgxajkep.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gtdogrcxcj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gtljjodabp.html


<!-- 参考信息 -->