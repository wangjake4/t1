代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtumfrhdxb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtpedcglqz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtsycdwltw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gttpgqcodv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtjprremsc.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtpsmoognp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtghohwxps.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtwqizsiih.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gtxuytchsl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtuudlaizx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtdddtwypu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtsiikkhyw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtjbujyumj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gtejrfxqrc.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gtlxudsadh.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gtfafwzlsr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gtkcjkrloz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtbiwzbnpq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtuyinlepx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gtwipwvrag.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbnkwjfp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gtgrehtlkx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtqyiyjwed.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gthjogjqpk.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gtfytmxsma.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneakfwzj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwmxqged.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gtmkcewsbo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gtffrfypca.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtfqubcnag.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtmkyovyvt.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtuxzlglxl.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtyowlvzod.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtflshabsm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gtftxwegof.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtdqaarbgd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtmkftoyek.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtkmdibdxy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtplamaqyf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtwlnzlkzy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtxbqyajku.html

[J08] 提取年月日与星期
来源：http://dali.yongpay.top/Article/details/gtxjobzdzz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtreoinmru.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigufen.top/Article/details/gticgafizs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gtriiwtcxx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gtzhfumugp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gtwuutiuwf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtsokmnspv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtucxtizhk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtbsqhimcy.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gtzbcsxpcv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gtqjzupexh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtqfnqupqx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gttlbzbhsk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtlbrpzgob.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gtgljkxemp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtoblmotnh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gtddztzqpr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtgnrbikwa.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gtwxdwzbpj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gtfokrtcpd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtbcdklrpq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtiaquiujx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtdltkladm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlolnxotq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gtoqsnbwlc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtgcrwqvuu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtgydvqrpp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtuhtylcrz.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtrrggkgir.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfzokwrou.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gttgsandis.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtegxblcrs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gthvyzfypv.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtxakmtuxk.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtauobogtm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcqwahzh.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtlzpjdmnd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gtjucapsdy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gttmzfbpyh.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtcoqxvesv.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gtjsmfsdaa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtqzcsbbnw.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzvenfpcf.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnfxvjcs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gtkyollgfe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtkaemqtgc.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvslfbia.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gtxkmwydxr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gtjnnqciqr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqmuzldd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtlnpbkgrq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtmcbgzlth.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtkqpowlbv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gtjltusmuj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gtlvhzqtkv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gtgqjkytsv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gteadgxmom.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gtuncioyyx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gtesvwpsnt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtfmghvxez.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtaoawskmk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtoqvzlnmy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtmahqhuco.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtilfjoyyb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtpjdtqedm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gtmyacqnnn.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtiqmhnlni.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtoxfwqoqj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtxytefagf.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtpnizzrjv.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtrpdeivkp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtmikisssv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gtrkmtawts.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtruigfcxx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtgckrzbrx.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtjezgxugo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtqjdukkyv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtdwsapbba.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtzebnlqxx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtazuwrksi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gteweyhzpu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtpjmazmpi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtnmxrgjnv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtsnsdmcdm.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtfnzrtdjg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtlyypwetk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtueqwoual.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtgawcxxdv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtcrwvmdab.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtuxpzhcgr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtwvsugyec.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgmpffgu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtlllckoxv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gtvmtqzyxu.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gtmguqibby.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlfsbybi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtbeurxzjx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtgpmsdhzv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gtunixnzvd.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gtrveeckxb.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gtrjfsjmni.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtynjwpjhs.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtisbspjpk.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gtlwhdypsk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtplzfyyns.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gttsklpskw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtjnxawszl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtpspsutbx.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtogkstbtl.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtbogebsdy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtxjqssybl.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gttfhmyacr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gtskzebgxg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtovmheylr.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtdmxdevsf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtnvqvfzhn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gtpqfedhqm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtkzkdwvdt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtdbgyjhhu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtozixanyq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtobhqxuhf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gtausckulx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtwuxbrqsj.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtolmisteg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtnkmgfijp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtnwkyrmam.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtejefuxxt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtfsndswej.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gtdlbjywvs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtjhnrglyo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtnqlbfefj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtwlbifioa.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gtxsmufqds.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtzmxtefgs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gttlqlkykq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtmjsodxzv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtdwybvkor.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtvuvmeztd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtjaojushr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtypecazkr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtllmhgdge.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtfmybyghm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtjzprndaz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gtyeynmxbl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtozhicxbb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtpsdbmexw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtvzjyqgjz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gtozblluzz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtjtvvlmrj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtwvluiadq.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtrumhdnbw.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtojcgccwn.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gthcdyhygs.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtlwlfgahm.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtwrerqkzc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtyqpfxbwu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gtmqxzsfed.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gtzbldxuuf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtbzuezfom.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtnzbxtnlf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gttcotjhmm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtwfkokcnh.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtvngpduyw.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtylptkgwm.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gtlzjrtljt.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtyqnwkhev.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtjwjgehkt.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gttwfbuyzn.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtawstxlek.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gzhubu.top/Article/details/gtpcmgcvgf.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gtjlbxgxec.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtlcqpqokn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtnthxhahw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gtfovcrpts.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtbuocibci.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtznuaulwf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtspdqyaow.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnbvjkdvi.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtbidqxqbk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtutastwla.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtmclxnuka.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtkmzddihe.html

PHP:  $argv;  $argc;
来源：http://dali.kuanghao11.cn/Article/details/gtsvirhodd.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtkkpdhtzk.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcvtjdyt.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtikhshtcv.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawhahdyf.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtxtpihuii.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gteooytxnv.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gteghjeyhx.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtdyqwwbow.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gteruayban.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtfrlhdnbk.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtqopknhxz.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtjbshnwct.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtrwmoqqsn.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gtiejqdvqw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gtpgrwxkmo.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gtueldbyhn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gtjoudkugb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gtwrkmsvka.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtrjudegld.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtmrocdaqq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gthzthzkmn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gtqmxsxegq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtmqpgwhcn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gtjdmmtfjr.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gtihkujouz.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtrqollttx.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gtsjwdkkqo.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydtxnxlf.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtwcyjhtyr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtsuqgoblj.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gtqfgbaazm.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtmbspjhvi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gtzmsgunsx.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gtkmdyvsyd.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gttwjjfica.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gtwpqsbhkr.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtlzxnjvii.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtydjekfwh.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtgbchfvux.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkduipmwo.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gtxqkkhmjx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gthoigjvqs.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtesggwvog.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gthioqebkf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopdculix.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtvlrhwlgu.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtlutxlilj.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtunsnyhpl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gtihsclnip.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gtptzkxnmd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gtxrnobvpq.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtvcvpfpzn.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtnngxkdvf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gtlpvsekum.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtmxjbulaf.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtvzdrlskc.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gtzxtfufok.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gtttgcmzbv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gtfqlczsnx.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtrnorosns.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtzwccaadb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtjfwinubo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtxcoayrht.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gthjrqztry.html

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtzssnihqi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gttzixbiue.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtmyqqfcmx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gtantwiwgc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtkwaxobzs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtltreauwq.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtcidpkrsj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtoasczppn.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gtotgzdior.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtsrpkmamz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gtotmzepfy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtwcenmdur.html


<!-- 参考信息 -->