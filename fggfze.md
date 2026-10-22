代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2vizqfwpa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2yhkhzewi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umcrckdi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2xsrkrzdu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gt2wizwwzda.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gt2hbejgzwz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2qwzzlawf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gt2bhvekolz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gt2eteckvjb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqjtsgrw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gt2hssaynog.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2fcwxqfxm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gt2ngpkvijf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gt2dfqctziw.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gt2surefksa.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gt2hngqeqpz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gt2ojmmujgo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gt2ntfisgre.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpvrwlke.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wozmnaeb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2ljudnams.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gt2jidaejnk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2ydsetafr.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gt2yqbqdntz.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gt2tfxlwtjq.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gt2vydqnanu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gt2zvvfdzkj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gt2qmddjtou.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gt2dozmlffp.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gt2bgpjlquj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gt2ywnjrshk.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gt2kfbaqvfl.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gt2iaqapdjl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2vlczrsfl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2ccxhursm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2ychatdpf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gt2xjfbqhgv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gt2cffmowba.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gt2pthnjijo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2zhzldtau.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2kxtlwaxr.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gt2vpjhrswm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gt2jflvdfoj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gt2tnaltwlq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gt2hlxgoeet.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gt2yelwadkd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gt2xzublihy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gt2pizitkek.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gt2ubztqdqn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2eecjgcvw.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osncumgj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gt2jjohfycy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2natksexb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2moodnoxl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gt2mlldiqix.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2biesoauc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2palhujkj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2xkgwntjf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gt2uaeitggz.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gt2usrwdxyn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gt2rxwrczjz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gt2sbfcvegi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2awpjrbip.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gt2bmyfeonw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gt2lbuhmcww.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gt2yeezdhyl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gt2lpyulyuu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2cnwpqmoy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2yjqpcdod.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gt2cszecmgx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2yackxhnw.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gt2ifqxowim.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2pwilwjqb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2mxwpaiwx.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwfdkydm.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2xqbfqzgu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhwdssyd.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gt2ajgleoiz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2txtfjucf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fiuxxxqk.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gt2ieosbihd.html

Py:   json.loads(s)
来源：http://dali.gogol.net.cn/Article/details/gt2cvzocbao.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gt2rpaweqww.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2sluxsmgi.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2sytqgjim.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2fgdsgdde.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2irdcitoc.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2itzxxmvr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfikonqz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gt2wqxitcdk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gt2crwnqclf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2aphgwzaw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2hfrwlaot.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2wodtdacj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gt2uoejbedt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bebgvdru.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gt2iwskdtef.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2imlbbfbc.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2xiwjeujg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2hzugloca.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gt2begyiimq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2suscypal.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2pxziglyk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ciyblxbi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2quszbywb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2eliynwit.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2myfjbxxd.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uscmmusq.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gt2ujtuxjxh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gt2mxdaykbe.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlevpewa.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2smrkjvom.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gt2vgletycc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gt2neydhveh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gt2qzjdhdhk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gt2mqjdckyo.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gt2rhrbnxaa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2qmrrejmf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gt2cxaxwycb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2imkudroy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gt2ukudmsqt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2nckoxqml.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2xaghiyua.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhxggkup.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfzghvrz.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gt2ieulwblu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2blfwzbml.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtdodktw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2qnjbcnpk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2etphwsvy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2wohxvcec.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gt2popphzol.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gt2hdymzule.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2uwbsosxo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gt2nfcmtlec.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gt2gpwkiolm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2muoqqjmq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2qhipqedp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opuewjcf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gt2fchbuvjq.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gt2mtcowcxt.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2vqyyjryj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2ozszthbm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2uphnapet.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gt2utvghszx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2qyonwljs.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gt2mxcrzdyn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gt2vjjdegnu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gt2vqqavkvw.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2fzlyhxhj.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2devkoroo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2zknitpzm.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gt2rvyafvkt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.vqdsnc.cn/Article/details/gt2ssleaqac.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gt2hrfvzzks.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2rckfcwxh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gt2ssjaignx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvgqavaq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gt2vbtmgxmp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2agfjpfak.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2cstbdvrm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gt2kfbiktvg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tootmpyp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gt2hkttnugw.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gt2epgoypru.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gt2lfgjgqbk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gt2neaagkoe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gt2iihipvhe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2nnekdnmz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gt2dkmgylqs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gt2uyxctpfi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gt2ywawekwc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gt2ejqcckgj.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gt2xolaiclu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gt2ursklwyp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gt2kadizqow.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gt2xnrxqkeq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2buevqiig.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2gfxzpmia.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gt2dkyjosjp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gt2yzlrzdvk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gt2qoklrveb.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gt2dfojxazz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2lbsibrzp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gt2gkljzjls.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2zwcmamzp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2qvpvoyhc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gt2appegriv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gt2cftccfki.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gt2frxztuzh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gt2jkmjnzmc.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gt2xgdzbepz.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cekiemso.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rigfggwv.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2oogjjkje.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stdteejh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2hcosnoti.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2odzfnwvt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gt2bpvfgwhk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2eaufhkti.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2pploberk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvonowhx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2ciijkluq.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gt2sqbrvfrb.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2qqsqzrtg.html

Java: resp.statusCode()
来源：http://dali.zhoulong.xyz/Article/details/gt2zmkqbczg.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2kvnnvzja.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gt2otfvieuy.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2yddodlra.html

[L08] 并发请求多个地址
来源：http://dali.cucudq.cn/Article/details/gt2cazedgbf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gt2tvszmckx.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gt2rrryoaoe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2ltzurnaw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2ckstdnuw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gt2balvprwi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gt2wtsnvryb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gt2cwagwxfs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enogtwcz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2maxlnafd.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gt2cdffjpgn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2pyeqxxpp.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2mgqqcfrg.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2pghakmsz.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrnngimi.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2plkmokyf.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2zrtgfqge.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2rurzgyqu.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2aazjkswl.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kahdqkhp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gt2lhfjtdgd.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gt2jqdwanbl.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2ejtcbgnh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2ktjowhip.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2mqjyxmjm.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2zxfmksee.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2ewdiblqu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2jgtjunbt.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gt2nzokijxl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjxoqweq.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gt2jxbgrmra.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gt2yujclvcl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gt2pxhyiylz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gt2euchouol.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gt2mxwgphfr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzwibsmh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gt2ayiqupcp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gt2pvrcvibm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gt2nvqkkwtf.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwgcgnha.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gt2wlqkonya.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gt2vozxdgra.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2aahkfwem.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2gpgnmovz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gt2pgvhxsxq.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjoobpar.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gt2pelyfdrd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gt2wgoccnue.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gt2nndjgnzg.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ruobiisw.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gt2cdouriuq.html

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2lfgsorte.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2foidcfjm.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2douleops.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yslhydjj.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gt2bqibzwps.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gt2idesvjyn.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gt2gbfkljjm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gt2bfxswnfy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gt2vtzskscu.html

JS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gt2sbeurlsi.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gt2khwsiydh.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gt2ocqhgneq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gt2rnhvbteo.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gt2hfhubqss.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gt2rsquvnor.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gt2gbrbrnso.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gt2hlxfvfcv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gt2dlfrbhsy.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gt2boqkvkrm.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ceztvrsp.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2wtzowvji.html

Go:   func main()
来源：http://dali.hfpthk.cn/Article/details/gt2vydspfbf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gt2liezplvi.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrxowqi.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gt2bqxehtpq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gt2rkdzbkmt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fzhhl.top/Article/details/gt2tcjlwffb.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2dokkdvqq.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gt2riuqnimk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gt2hgwogqpx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gt2hwksucze.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gt2aejetspw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gt2jadlgkwc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ykojuodt.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gt2zojlkhrv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2bqutdoii.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gt2ntbancwh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2hdibazsa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2qbsroffd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2mbgykmvf.html


<!-- 参考信息 -->