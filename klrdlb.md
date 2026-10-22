代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyufybad.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gt2hubzgsqc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2unmokybb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2aipvkoue.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2zcyywihy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2fvcotmfn.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gt2grihntof.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gt2oaomztxn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gt2lvcuhhyp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gt2xdyyjuyd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gt2zqwfdfbw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2cmvxzove.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gt2tcjkkkws.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gt2uwjfaehj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2fedichrx.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gt2vgkixugd.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gt2lmzzhmaf.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjahuewu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gt2daazsmhw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gt2vafmuitb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2sqsbnice.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gt2gxmzllul.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gt2hgnhmjjo.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwalrnqp.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gt2jciovmhg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gybeudpe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gt2tyomglpr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2snwidabb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2isthzyil.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2viaaeeri.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gt2oxjyqelu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2oiahtfaf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwjpcnfc.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gt2phklvtra.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gt2oybkyngw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gt2kxbkmqct.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gt2nsgssyuw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gt2acgbtkld.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gt2jrzzppph.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gt2fvxzucma.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gt2lghmexyj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gt2yqocspaz.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2avcocuag.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gt2trupebrx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gt2swlsowmi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2kohekavn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gt2hblaleie.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2vymgglry.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2dtrqeame.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gt2wjyiumry.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gt2thhtnctx.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gt2gmuyolfo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nwbrower.top/Article/details/gt2mxjueclu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gt2hxhbzgzg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gt2gtlvbuxm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2chdvmyjw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2zcjlynwh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gt2qybieflj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gt2jiqvktgd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2oisfnwmq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2vpcgydkf.html

K. JSON 与序列化
来源：http://dali.cucudq.cn/Article/details/gt2kkosjuwv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2gqzyvsdk.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2llmynoan.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2xdjzamqm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2tbkphokk.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2rcfveaoa.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2guqvdccv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gt2eyadsubz.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpypegfp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gt2bdwxtawg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gt2bpzqfydv.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gt2advltdhk.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gt2sxribmhz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gaohongyu789.top/Article/details/gt2pcwvskpj.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2rwcgbnef.html

TS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2auhcgfbh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2ueplkdsy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2lhwchdvg.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2skomkimm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gt2ljdaclnc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gt2xesbtevw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpoxmzdt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2xrsqukas.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2uukvfhkw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enxpkkfx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2dvbccaxb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gt2ulrbdbqd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2cbmsaegg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gt2zualljoo.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2xixjawnp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mouuaiqt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gt2ycpbqosp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlwkouow.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2utondffy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2wvbjyqyk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gt2viyfewnm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2gvdmhlwe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2fczjqhjn.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfddfqdt.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gt2densbpul.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gt2zcobxguz.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2jgnltufk.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2piabufdr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gt2opetlczp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gt2zbikfmlj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2qeqkiptj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gt2nomjdtbn.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2epkooodc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gt2dzmewxbg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gt2omqhefgb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gt2nzumdzhj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gt2rdkscapa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gt2roufkieb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2icmzkcqg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2iqdjfdbm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2nquynopg.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2tiufgnjs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2glcjgrbd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjifsthz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2sgonjavq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2ezqbogvd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2wuqfnmvs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tianlin.xyz/Article/details/gt2xjkswqkv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gt2dsyhsnex.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2shlwtswo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gt2xlzuergc.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gt2bpfjlrte.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gt2jfdvgrme.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gt2opwnosfe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gt2ulyocids.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2aztgxbxl.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gt2hstwgmdx.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gt2lzayymhh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2diezowql.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ydmikiju.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gt2csrgxaqu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2owfakhrq.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gt2vmqeexqa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gt2fjkdyfdl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gt2cnukczvk.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2adlsrvfx.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gt2fhenbkae.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gt2qzxagqdt.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gt2ezafxtrr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gt2ssdlaihc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2etaeyclg.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2mqetuycu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2inghgzwj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gt2todaasbh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2spymarlu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qipxkvgo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gt2wrpjtlfe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gt2mjychzcp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gt2blhximjt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gt2sopwlscm.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gt2sihtpcft.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigfzy.top/Article/details/gt2khwbhgzh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2dqhjnqla.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gt2vjizvycq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2ozxbymjm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gt2tfaoraog.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2rtqrladd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gt2pygmtuto.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gt2objmbzxn.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwntlupr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gt2hmqjjnoe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gt2tyruhreh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nitwetst.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rejozuqs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvqqjvxx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gt2ttwqpunh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gt2hnujsnhh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2uayriknx.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2peznaipl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihapxqmo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gt2ezkyffkj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfoppige.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2tgvizjpm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gt2mxwuaquz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jianghu66.top/Article/details/gt2kkbogfrt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gt2bcohusij.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gt2ntacxcuj.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2dkculdau.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2slctokqm.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gt2gffqnykj.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2aplqsujw.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2dfcrzvhl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2oecgscnn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gt2cnywuapy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gt2cczfzcut.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gt2ohuesjjf.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gt2ungznccy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gt2kffeuprc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gt2oknidcco.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gt2tfmbibkg.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2httdrycn.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gt2ghxlmnqo.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2qlblpxvo.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gt2sxsunqwv.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egobkwhd.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gt2clhaupax.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2pipnjscb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnraiiwa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2rmqctrei.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gt2trhwhqil.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gt2bjtvwkng.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gt2pmryfgjw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2edmyrxpf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gt2wlzqyuub.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2uyjfrbmj.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gt2iaabsxxy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2crccyamp.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2bribrpbm.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gt2pehufofw.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gt2vqvcbtdf.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2oixcuoud.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2msdhbaok.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gt2qhmrtjru.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2melpolue.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqccados.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gt2tkmlfgml.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2hpkoqtdj.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2exaydwww.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwfwwhwa.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gt2kfkfaqbf.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgsqlvim.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2zxghfdzm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2lozlgcmr.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gt2nmrbrixh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2aruockto.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2memaumap.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gt2njehvebo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gt2ojnutxxq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gt2riefofai.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2ilavcsmf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gt2mkxnboyu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gt2vvzrhmtm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gt2zsioovuu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gt2xgcakzvn.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gt2owpbagho.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gt2nzkeccwh.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2qwxpimov.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2tumvhuuz.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gt2szwonbza.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjegzgee.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gt2faizwbys.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gt2cyqhykzj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gt2tzdrfzcq.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gt2rfxyocwl.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2ubtseesw.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gt2oxrbloyy.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ibmrjegh.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2tummhvod.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhefoxdk.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ebkynncv.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gt2utaphlpa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gt2amullepv.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gt2sjojljso.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gt2auratjdd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gt2zalasxwu.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2zlngpkzy.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gt2blaqkqsi.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gt2pygdbzju.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gt2xvbnfyzb.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gt2wgzvvuhl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvlwusja.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gt2rprxehhm.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gt2qqaahdvg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gt2krrhggmm.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2wpmkgwal.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gt2pxzqhwes.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2qfwiykmz.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gt2zqopryeh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gt2evuqkxoo.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gt2abwhygva.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gt2ffrkfowc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gt2tityuodr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gt2rsdhpbqk.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gt2ptshpama.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gt2duklvdrg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esgusuys.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gt2dhpjlpzi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gt2sufsgqdn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gt2igktbqbh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2olrfnvce.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gt2tvfqoglm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2imnhodos.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gt2oqjojxyd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2xnmyfenh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2njbkdutz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2icjusidg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajapbrik.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2ekugdpdd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2qefednst.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gt2kwzktjxs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2sockfwbj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gt2gkjndfvw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2psqjtbgx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2btbyerrc.html


<!-- 参考信息 -->