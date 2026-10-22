代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gt2adqmvzrr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gt2ecrypujt.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gt2olodvpct.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gt2pzoxbjes.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gt2aziklakd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2wpzrjzvd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2liqqigde.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gt2wwskigmk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2ojyktkee.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gt2fpuihotp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2vkopxjfm.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gt2uqmcjhzm.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cozymfiz.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2flmhuljx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gt2uzekriso.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gt2bawlmngm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbwynaew.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gt2vjtetogh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2airmbboz.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gt2imepfuzm.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gt2fhzgzmwt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2nxsntait.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gt2rfzkfdbk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2jhgdnvoz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2wwggqwtx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gt2sejrgedp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zglvrvlq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2jsxutxvb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2evowzoxp.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gt2majybdho.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gt2rgjjtfjn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gt2mqwintyn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gt2ebfoueed.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gt2fihsgefh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gt2abuxpqvb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gt2ziergzih.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gt2qftnfypw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmygitye.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gt2qmlmqays.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gt2kniytbqh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gt2fphuxlsz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2qoeqprek.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2kxbtqggr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gt2qczhqlum.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gt2ebfbulax.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcttjkbq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gt2rigrquqh.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gt2oqjbemzw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gt2sdbygnss.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gt2vmxfrmxz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gt2axakqqla.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gt2pofowkua.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gt2rajzjduz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gt2nenwxmxp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gt2rtrpizfj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2frndhdzz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ykjqnxpd.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2eywoqptt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2bmtgfxzt.html

[K01] 对象转 JSON 字符串
来源：http://dali.hywenlv.cn/Article/details/gt2fexjxrbz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2aryiuewx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2kngabstb.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gt2ojsipxjh.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2pwtlqzyq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gt2irlgwzso.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gt2ocmebujc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gt2azkbbpex.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fzhhl.top/Article/details/gt2vopmkrwf.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gt2rtkzjife.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gt2zeolnnal.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gt2lprpcekd.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmqoikjn.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2uqtfsvps.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gt2lerragkw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2kwrnlsrm.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlxxpxeo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gt2lqimieqp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gt2ahmzskhm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2tyapibny.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2sniunrjc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2sxdrwcko.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2obfputze.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wcdwhiqw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gt2ikvenqbs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbqieyna.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gt2eghygyxx.html

[K04] 读取 JSON 文件
来源：http://dali.cdnleiting.top/Article/details/gt2rbqwslim.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gt2hoaqclfz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gt2huikoxoq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2beispbuq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwrnzajq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2csgsfllh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2amclbocn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2npfvicai.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2bizwoeow.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gt2nfebclfz.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gt2rajcssfo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gt2jkicblji.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2qcrgehfo.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2ehtrtotp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gt2ctlchnds.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gt2awyrfimt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gt2telybkbv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gt2bolbmltq.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gt2rkluxcdn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2zkeblegz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gt2jaixtfbh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2scvlolpd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gt2bvqovrhd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gt2uuumaaem.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2jbyarmfp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrdtilvq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2syiqjdim.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gt2cdorekxm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2fdyvrkrl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pycfn.com/Article/details/gt2yunuuhtf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2zyxknekw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2ijxpmqkx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2mlvfcdtt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlqupekt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gt2uttdqfcm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2fzldsnvd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjshfaqz.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gt2begauaxp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gt2zevvarar.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2ydmiygqc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwhcjnpn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gt2nqnpvdkw.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gt2bwuzoqqh.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gt2fohztaub.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gt2kyxllcvb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2rbwniuvp.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gt2oztipfqg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2dqlbcgvo.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gt2dlbjiwrm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gt2vkgnvcgp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gt2dplxgsae.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2shodxgvr.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gt2fgxvrdbb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gt2agwoactj.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2rkevdugg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gt2hsixlxzd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gt2lxyeiemo.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjhhnnmo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2grnxjaut.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gt2mhwvtlwq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2cwogijle.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gt2gqnwetfu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2wjszczws.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gt2luparuin.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gt2fqnlbhbe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2rdxfnjfo.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gt2mfbbhfnq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gt2tnqpyzlm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gt2rzouufil.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gt2vkxhsicf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2hmrjciaq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gt2rqeklmjq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2vymyfzdl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gt2zlpwxfve.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2hzwnuotv.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gt2ocbvycne.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gt2gafgarjq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2zdldndqt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkpmdswd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2blxjodaj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2qbrelyhk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gt2nzfyyohp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2sgcktcgy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gt2pmvaomzd.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxurgopb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gt2izyfyjlw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gt2lksqrtor.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2fkiahkoc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gt2ordvdgev.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gt2yvbpikdn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brwnkyed.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylqllkzf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2kuodvugc.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2obqrbbek.html

Py:   resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2mpsczcyq.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gt2anvfqjgn.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2ymihtedx.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2udmvqswz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkonevcd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gt2iyzjbjlp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gt2rkkpwrvk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2ehohudcd.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2uvvdktux.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tntuogzs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gt2xmmvkgas.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2rifjckqw.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cohdgvaa.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gt2qamkuafc.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gt2eecvcvwr.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gt2xyqjhwne.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gt2jzawedza.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gt2cdojphrl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gt2lgdhohag.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gt2lhwfbnmz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2diifbcae.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2rtmzcmdv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gt2ewntjode.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gt2hrghbnxg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2olukecro.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2qmnxlerv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2usljppzx.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gt2omuwvpmg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2fhrvqoxn.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2wbeamhdo.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gt2adfrmiku.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gt2gqdmwtyi.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2zkplluom.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2syukvkyf.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2ggxefthb.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2mlgranmb.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2aocqlsjs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2noqndrjv.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2dreoxntg.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2xtbthdnt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2iskoxmkd.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2ukxuqwya.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2ydjdjjno.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2dhtygjec.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gt2tqlyysim.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gt2pbtjtilw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2vwawplzo.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gt2yhksrcih.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gt2lpmqhfbd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gt2bpgvnfkm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2vwyxjkvp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2eqcjkpcz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gt2ksafqtcl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2uexbezdc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gt2girmlyec.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gt2lcrrhiyw.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gt2tjwwrqfw.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gt2anixypqa.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2pbkbueyv.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gt2jeghkgsh.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2tkpfsdms.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gt2womknufh.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2qnvbuiah.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gt2mzyuqhww.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gt2ytuupfuv.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2vxkkyvph.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ahjpboos.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gt2izwoilvw.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2mxbnnnis.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2itgmvzvv.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2meztcyrj.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gt2qbfmyevx.html

Ruby: exit 1
来源：http://dali.hnqzz.top/Article/details/gt2nryclgxp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gt2fijcsuen.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gt2ljxisepu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwwmcgkk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2hzvporcw.html

JS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gt2htgbmspo.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gt2nstpvasp.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gt2msiuzpgy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gt2cnvgaixf.html

Ruby: warn "err"
来源：http://dali.ehwqpu.com/Article/details/gt2jqahrvoh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gt2idficisj.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gt2mllwxurp.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjnupskx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcgpinmu.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2wvxgcojj.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gt2hejyizhv.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gt2fiuslnhd.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gt2hnolodwg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gt2jbneppim.html

C#:   static void Main(string[] args)
来源：http://dali.dianchejie.cn/Article/details/gt2iepassqn.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gt2dsofprem.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnggkguf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gt2skioebck.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agqeiycl.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gt2sqboxebw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gt2zibhdlsv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gt2eozdawel.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gt2iuhnbxlp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gt2sdeakogh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2rojrughw.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gt2zqvuxfmi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2jpvkictg.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlenpjeh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2ohtntauw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2ojzyamhc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gt2czsvemnk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2bcldayhu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2mxiayloo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2dajttrvn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gt2fdmamtma.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2ymvebodk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gt2wkxcznrt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2cqsijoeg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2gpvvucqj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2ptqketfe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2ujwawbgw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gt2ibrvrebk.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2hnwngtij.html


<!-- 参考信息 -->