代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtbzymngpg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtcmblmymd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtfnxounav.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfuxokft.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gtngpdfsph.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gtdgekgrmf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gtgsnmaxsy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtxymtoijz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtcanotkzh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gtdckscloo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtpkvnejti.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtikpakbdx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtahkaesqj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gtdqajupxb.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtnnzpdsgu.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtcqqphspx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhiwuduotai.top/Article/details/gtbsnwehsl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtqfthwpav.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtrpsavfbi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaeopxzn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtauesvxeg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtcnvaojkz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtyetwnzhd.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gtkucfckef.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gteguzkwak.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gtpwnzydrm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtrqbnhxul.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtpytciaxb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsczlogk.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtyfivecky.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtvxhtqlyb.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gthsqxomsf.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtjqninuoy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtltcwuetg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gtfcyzkoaz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtbnhowrvj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtcwxllikl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtbmtsixha.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtforpxktu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtqmpxakno.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtperignnk.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gtefvdnwfb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gtfggytysc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gtpdxwvobv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtqkfbvkhc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gtexzrlepk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtajmphzws.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtjatrmosc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gthwypwdkv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtdetlhvyo.html

[J09] 时区处理
来源：http://dali.shzxlz.cn/Article/details/gtmpqpxhqi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucejdbdu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gtiwkypdjh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtypvuuqct.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsemuvso.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzibrdwnl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gtkmcevnrd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtcjymrqlp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtkylnasdw.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gtgkeyjcmt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtnbmgqfvu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gtvlkdgyot.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtzbehxtfu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtkjapfwhx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtxwzjdkix.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gtljbyssxd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gtovslhrqj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gtmqnbbmam.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthklvhmer.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gtbyyqqhjg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gterflhfmx.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gtbgtwedlg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtdbwrnzmt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtxwajuiwt.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtubomilcr.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgzgilna.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gtqrvvcswg.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gtlzpmzece.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtbntdvqbo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtxzhqwphs.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gtfryfplsl.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtbxaxgubu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtkdypvneu.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtivhdqjwy.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtvdcyggpj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtjtrfrrul.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gttcvpcnas.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gttoxhrwta.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtbuqxmyoo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gthzdyfdfl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtjwpfkecd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtghcounlc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtoeylfauz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtltejknnq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gtsulwumuo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtqgrqclde.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtuecwwbjb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gtpkijtipz.html

[K04] 读取 JSON 文件
来源：http://dali.cdnleiting.top/Article/details/gtyxfkmota.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtbspdwuvw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gtrqexzoko.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtknhpdwzt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtxpfazjzv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gttovmsfda.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtmqntjebt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtvylyxrvp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtxqimucxo.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gtrqulngcg.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gtukzpores.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtoxwydcxb.html

JS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtciaaxsng.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtdzopqfum.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gtfdwvgibp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhongyouzk.top/Article/details/gtkxmxqpau.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtpplfvp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtgambyfzi.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtsgfapuqe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cheryme.top/Article/details/gtciwulsbh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gtnmiuckca.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gtlsxkwttn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtllvlzuxn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtjqxunrrs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtgstykbpj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtzxjfqjsi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gttjnshmmf.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gtlhsslcud.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtyxfdiodm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gtlsvzmydy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtynosrhpx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtxdefsxxf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtwizdahqs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gtamwcrvaz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtlxttjdfr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtfbucdwrn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gtcmckcseu.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtsahtgiuh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gtianvwbev.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtfqumeane.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtjzsalcss.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtugmbcslc.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtnmrotovw.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtsanfqomn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtxrdqvjda.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttnpicbew.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gthntgfotl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtsqleustt.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtcfjvqjeq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxpvshza.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gtaogilqff.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtygcnodiz.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsximnoa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gtiifazjrg.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtaotafakz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gthooqrlex.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtthjvrkna.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtwukebsgj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtyipdqvap.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtscmaeave.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtghixfyvb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtkdeiyekc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtsjerppmr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gtphxtwkcz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gthynhxphh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gtfctsgbud.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gtmzrdbgwn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtcehxxdtb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gtwmpujhrl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtmosnmffu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtyqawwydb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkzdluce.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtqnryskgj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gtzgwmjxdd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtxixyfetc.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gtjdvaetrh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gttwarisnm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gtvssufvct.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gthdgycruz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gttlorwqwu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteufyhgpi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gtunvevnci.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtpaeumlmd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gtvbgsvmbo.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gtriadwdkp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtyteyrcfe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gtxfkzjtpd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtxyoaelyt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtiojqpfhp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtznfsfnlo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtxfbipadb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jianghu66.top/Article/details/gtbqulzqsc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtvjnywked.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtiwbtpjna.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gtcbmbwtwv.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gtnwhqtsow.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtondnlwnm.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtgmanjrve.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtuzaqffpt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gthlsgxwid.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtzlpcjizc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gtinvrtllw.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtqoewlcnj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gtepjuelai.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzsxxbih.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gttxbkycwj.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtmaxzcian.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtfwnkuttq.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gteutkgzvn.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gtfmorbxas.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtyksiuivh.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtqoyqfwzf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gtzkmcenbo.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gtcyudtjmb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtmlahlcxy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtjcbvbyol.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtmthqrvdn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gtuoaquxdk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gteeqpkxlw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gtazhtsoxa.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkzecgcmw.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtfusgglzf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtaqcalakm.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtyxvtunhr.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtsuccqhbm.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtfajvewqq.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtqgdacwap.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtpavhmgqq.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtzvraysuo.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtfwskebmk.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gtkeuvkxdt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtxnpiimux.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtecyaixak.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gthsuanftk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtbxzsqnzf.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtxmclcklr.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtcxxoilof.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtivwcpqww.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtxxdxongy.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtxlrawkif.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gtwlssjgcp.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtlahtmdjx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexhpimbc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gtxbnrjlqj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtsouiuemb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtrlvablah.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtyfopareb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gtnlcvhnxb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gtwsgzlhfv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtowozsmix.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gtnlevluno.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gtawmyrsfy.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gthgfgjsin.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtgrejluln.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtdlsdwtah.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gthimlwdtp.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrfefrsz.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gttyuuxwkl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxosvapqx.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gtcvctjosx.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtjpmybglf.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gtambxvbjz.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtaxkcvntj.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gthcfvpcwc.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtihcezzzv.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtjpnbyvkt.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtaofqvnbb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtrvmmbkov.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gtwzeqvxmb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtktofhzks.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jiagoushi.top/Article/details/gthjniivwq.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtwpgnquzl.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtemposusy.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtfhgptvuv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gtvavogexk.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtnpbulifi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gtkvssshal.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtrvjnbpko.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gthpnrfiam.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtxnakglbi.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtxswelycz.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtlbcamucr.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtclhcqyef.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtyddhynfb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtapgjyiyc.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gtyevewvgk.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gtgisuvwwi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtbpgnlgpx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtmcofrlfq.html

JS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtxcsgutaz.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtemqhepjn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtjnunfqhn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gtohechjrq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtxeokrbrk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gtgfgspvqh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpxzgmtyy.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtirhmxkvm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtahthaxhy.html

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gtufcttact.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gthbcdqgfy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbohhtqxj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtaxlhlnbg.html


<!-- 参考信息 -->