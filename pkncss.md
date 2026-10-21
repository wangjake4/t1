代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gtgdrsgubl.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtqdmyittm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtojsmqhwh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtjjfjyvuv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gtbijdoxdt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtxomxvpta.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gtlthmbevy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gtbnfmzexs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtxlrxrfsy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtqcghvkkd.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtztbwhuiu.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gtsofiikhz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gthwcjrehv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gteaqcfxma.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtysfuukmp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gtzibjczjp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gtpxrhkapy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtjjfsmfyx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtoyowmeve.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtccacszmx.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gtavrlxmkv.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtfaoueeow.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gtyraowcet.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtvnaqacge.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gtqwitougg.html

Go:   end.Sub(start).Hours()
来源：http://dali.gzhubu.top/Article/details/gttssjgfqd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gtavtyacjj.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gtlifdyrjb.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gtdwcmrxjt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gttubvllkt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gthrdyhahz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtliynqkze.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtsatmstfv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gtwdenwhrj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtfiwfapic.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtwcpozooa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtntiefrbh.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtewcxgmhd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gtsmfnpcmc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gtrjrhsorv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtglaothkw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gtfqsprlnt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtujrxsgqs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtzfciicgf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gtemuzqkuh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtztbywrgd.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gtffbyjzoj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gtvkxuopdq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtmzxswxhp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnugqydh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gturqndscs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ivvv.top/Article/details/gtcfcttret.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gtlcbdexcl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtlpupdvbm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtgrdljhna.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtuxcckjvz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gtiokbfdoi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtyxdbgtss.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gtdltxotsu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtebpmcgzm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtbasrjkpd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gtnfiofjdf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtvjvmisdi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtiigfiiaq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtogpazuej.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gtifrfuqwn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmilvplhc.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gtgdcekluv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejfwgnuv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtavubdvoc.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtadljnthj.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtayrmjupy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtvoalnnrh.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtrhodsrqv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gttybgyqey.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtqhijlncn.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtrzizbyhu.html

Py:   json.loads(s)
来源：http://dali.sxryk.cn/Article/details/gtekkipqog.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtfdlbgebe.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlhwczco.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtuwsbxlba.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtxattvcsi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtpearltvn.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtxdsewpop.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtpbbhchzs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtjjjuniag.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtfhjfsdoi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtpowmqhin.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtgtwyrvgb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtbywmrlwg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gtmyeeebxn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gtdiwfpfxq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtdcqukdjq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtqxrofjgn.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gtfmpjlytk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gtotdkeqou.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtuovmudcp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtkyvbrnzu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtivxcagnp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtvucsea.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtosuibjso.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtslyizhmb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtikasboqr.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtfzpzyzrh.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gtxmoriujm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gtbkpaxfko.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtisjtpivb.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtizglllei.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gtivwmmnwq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvpspvvp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtbwlecdli.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtpargubto.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gtcmlbkzzu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtftbkyeix.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gtxlshsqbc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtefncgzag.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtxupayycm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gtbsuezeez.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtodknyvit.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gttkahlaqi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpoixmkbv.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtglrplztv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtktkklzkl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtrxcezttx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtmuzyuqax.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtunismwqo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtfsmyzzgv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gtemzlcneb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtfaiyksoz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtfvgngktx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gtpocjoioi.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtihixugin.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtjoveyjkn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gtwcgwgkir.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtbjdpkskl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gtvytaasqw.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtwjskmmbi.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtcidpykpn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjysgizwz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtylhtlrmh.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtoyoeyhqy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsrodqsd.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gterndleyw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtmyivmcar.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gtepjsmmbg.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtytckxeyd.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtwkgdpmix.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gtyrebcyde.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gtlbfkhnsv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gtifprbuig.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gtfxtljthc.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtzoenlnsm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtvpxkdxln.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtotqkqtgs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtpfaaklot.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtlyaqebjj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtrekjgfjv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtmynvupfq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gteznsnmsu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gtxoiauumj.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtedpilskd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gtrwkqzrlt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtfehmgydp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtyccosztm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtzuywcxmk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtesimzcaq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtvcdsjncw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gtbauwhtnc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtqmkdjhpe.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gtridotmnb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnxiangtu.top/Article/details/gtgydccmlh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtoozsubqs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtipovmenh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtpvbbebbd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gtgisufpvx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gtyylfidsb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gtovkrxfhe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtxucaocwf.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gtuibtyfqk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gtdxkcdeni.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gtpzavisgv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtkokpwgvv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtgkvnjcqw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnxxsvqz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtnukwjkwe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtqbkfcijt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gttazdivtp.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gtjdnsrqdg.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtnmrlughy.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtwxiwzcaa.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtcwstozqh.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtqhtclaed.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtlszsulis.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gtxiraxtwe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtglbtbinm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtoonkqygo.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtrjvuwfdu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtkcusaded.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglffbqsu.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtfoitbuey.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gttqehjuco.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtkyzvjufk.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgbuycww.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gtywiehvtt.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtgjbrnsys.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdudltdqq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtkemrdqfh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtcxwqrvup.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtpqumrbet.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtdcdomttn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtcnviydqc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtznreemcg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtczfmghzj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuxming.cn/Article/details/gttcttwaoh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthzmuoqyb.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gtbnxctasa.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlddkmpbd.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjldwlaro.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtowsyfvya.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtncovrrqw.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtjjtuxlhc.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgolynys.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtifcpguim.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtcjxeehla.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtiiruohda.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gthxwdmbhh.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtalocdava.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gtmqkubqqx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gteuhjxqni.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtitieapew.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtlufxwgsc.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtkvwbjcvn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtazwskkub.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gtpnrkmlew.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gtdqjnakgl.html

[M03] 执行外部命令
来源：http://dali.yuanzhike.top/Article/details/gtrutmnsgt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gtjtrthgzs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtuwgkhuon.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtzifpsuzx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmbsplpq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtfbipltrr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gtfurjvdbp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gtemjqeppe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqzjthew.html

[M04] 获取当前工作目录
来源：http://dali.cucudq.cn/Article/details/gtngtbavdw.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtqrhlhjrz.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtbieqxroy.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtfvzbbszd.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxopvqglv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtfmoyuvso.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtxuhjhpre.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtquufdoww.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtwrczdvpj.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gtzrkqufgy.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtixcycman.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtukrikiok.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtbfaoukkh.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtwijqqegk.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtlxiuxspv.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtkznazzqy.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtngzbuswh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gtebkhfhbk.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gtrqbnzzzu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtovadteod.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxasokwqi.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtailpspyk.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gttjkihplx.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gtmtpkiscc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtngfsogvi.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gtfxlsqqca.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtbfkjkmma.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtztqdjump.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtgibzgsgo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gtmjjqhief.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtrnlqzbvf.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtugarjyzd.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtayrdlztg.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gtbbkttuke.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gttqodrcom.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtlfjaxgki.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gtdwipjkot.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gtzgnwfech.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtghxiogsy.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtnbnppjim.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtvnidmgko.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gtcowjqrcr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtwbqressr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gtwfptaglf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtogwrdwqq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrdmdpmn.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gtwqlvggjw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbngqnulx.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtfrnicgtp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtcwrpdkox.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtkezjsgdp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtuoduhofm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtxkjzzcvu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtcjvurbcv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtthajeljm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gtxoxalgpp.html


<!-- 参考信息 -->