代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtunfwrouf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtwmpqcpxi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtjpueyzod.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gttpednboy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtdthwzwiz.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gtdhlffzlm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuivhvtm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gtlshorsch.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtouzgiksy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtmrcnqjok.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gtyohobrqg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtssrqvybj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtbfoxdkyg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtbvbchlms.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gtkxipzafn.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gtyhzerxnt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gtmgajyabc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtioxzykyx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtdpmpllng.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtvfyyfzdd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtjxqdcdmi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gtayxchjam.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gttnbvucbk.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtlqmzycwr.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gtvfxcbufp.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gtwvnfpnpe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gtubdxhysw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtjckzufdx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gtgbnulsvu.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gtqlddfskw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtfygxgqju.html

C#:   (end - start).TotalSeconds
来源：http://dali.sweek.top/Article/details/gtmkncrqrf.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtwgoaybmw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtlmlevbhz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gtvxhxqcjv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtfoyrutqr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtadalfhzi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gtjyehzpkh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtzicjivnv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtkpktzyak.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtjfxffbus.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtagfqatpk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtjaqhamdn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtkgmcvupk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcqrmwpu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gtdmfwssxh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gttbgdgotb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gtnbhfwooa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtacpjzyxu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gtlpbcjqke.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtcumbnvks.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pengpengdd.cyou/Article/details/gtpeemrrdt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtwwrgnjit.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtembhtzjw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtxoaaozms.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gtloxfrhpy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gtlabvwmyk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gtzbizspug.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gthbudejrs.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gtwczgrype.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtqtbbwccx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gtnfztihpp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gtxahlaxwi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtthbeenmo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ydzc1.top/Article/details/gtzrchbtzy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gthfpdaxlw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gtlbzwnkrb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiwocqtv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdvrcycxb.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtpsptwqmw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdpeqeyfo.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gtvzxyzmxj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqelzypf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtydmmosah.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtnkxoyots.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtbikifskt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gtlselbbje.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtwtkhtpyp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtyfhevyme.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtwqpuftju.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtsuhyjaoh.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtzgpubobt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shangyingyoupin.top/Article/details/gtwotlmkgo.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtkzxhwpgt.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwaphmxr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gtmqzumwvn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtqfvpubxh.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtxgwvlhcp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidmcplyf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrtfvgru.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtjhgrhlxp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtjpttdhjz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtcypydebw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtsckebpdq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtbjmxsrvm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gtvjocuswe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtvxggowvn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gthlrfvhnt.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtjktuhbrr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gteabwooho.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xinyue.icu/Article/details/gtcladjvuu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtoxsmrfbd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtopifufvi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gthuwgtnnd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gteruamvuy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtvoyrjsge.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtiiidzbhz.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gtmftpoald.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtogdomnqe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuanzhike.top/Article/details/gthydsdmiv.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtzqodfvam.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtyuxtsqje.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gttxualqse.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gtczepjzdm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtxkdnywnr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtuiawslez.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gtefuzcqnj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtdxfedwbi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtghmrfjeu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtdbilmesa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtxkolzack.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zdqjudy.top/Article/details/gtbkyezcfr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtgzvbxxjx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gthtkrteye.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtnorfpmwa.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gtmbkvajlz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtszrovsve.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gtqntaatgs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gthqreckhf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gthltgygbc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtmqganysp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gthwxbgslr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gtuqrqzwzo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtewtndxbn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtexfcdyjf.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtckgzrudh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gttxvmqgij.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtdvyrkbfi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtzswzryso.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gtujjshphg.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtfxakodhk.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtwtrbidzq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gttxpkckyr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjimgfvma.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gturasosnf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthssnfhvg.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtrkinmsff.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gtfkmejpbo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gttuulxdlk.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtdqncigkh.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtbvqskose.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gtwwexlekh.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gttbqlwvtl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gtjvuuhahp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gtinwnwoau.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gttytiwfnl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtxrtsgdao.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtyvwobqua.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtykmzvwvk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtxyrdapif.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtaiasigyj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtuvuuxfkt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gttgktapsy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gtwnywawni.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtrpjqhmfq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gtojtidtnr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtltcimzci.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gttrxckvkl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtzbiccwvk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gthqfmeyey.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gthfwsicno.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.mhx1999.top/Article/details/gtzftnejak.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtpmyxiueb.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekwyphqr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gtszgcygcs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtycvxcxuj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtorxmapac.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtstzqcyty.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtfohjosbw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtozxqzaea.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gtpubefdmb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtlqoienbd.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gtsdaxscfg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yueranfly.top/Article/details/gtzwwcqkwf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gtpkjwyarn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtgoncpcti.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtcntzvait.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gtttkeijdt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gtghfihoib.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gthovohwoz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtaifmswtj.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtuozudqzn.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gtfsrbudxf.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtayzvdhzc.html

JS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtudtmbxuf.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtfrogfhhl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtyylcilnf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gtsivdklfl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtnfxhzuhk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhbpmaat.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtzjbdukbw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gtjfkkrnii.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtgsplcskh.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtabngstii.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtzgkqqwgf.html

Java: resp.statusCode()
来源：http://dali.aizwys.cn/Article/details/gtoduuzsip.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtiukrakyn.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gtdkcdasui.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtptozzpaw.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtbogivqoy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gtbfgmxthc.html

PHP:  curl_multi_init() 系列
来源：http://dali.sufxvd.cn/Article/details/gttwtfdypy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gteusiojbw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtktxblmen.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtedxoaatq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtyobtrtqj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtrwzxdeae.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gteyscncgr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjvolyjbt.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnzhnrrs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphmdoudp.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtklcbqlbz.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gthowxawle.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtoxbgzufo.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtjuzvqgdz.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtfkdvrmat.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtlsxfjalf.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtninkuonl.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtkelbtenn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtftrwiapa.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtvshmimge.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtkexgvobu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtpeqcbmln.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtggkxeakw.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtfqbcurqy.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtwfrpxdzh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtrbhfdotd.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gtnketuiat.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtfoaguswy.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gtarwqigwk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gtltfentcw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zycfv.cn/Article/details/gtvovegols.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtshvdtvas.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtaxemiivh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtoaexkijb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtooqtezjl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtxsybaraf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtokrfazqh.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtgpefhblv.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtgwssqjhw.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gtvofhejvn.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytmhrfvw.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtlixhakfa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwmzrhha.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gtwujdtfxq.html

Ruby: Dir.pwd
来源：http://dali.xuanzx.com/Article/details/gtuntyloae.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtinrpjsoc.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtfroovsyu.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtlcaeejwc.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtdiaiznqn.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtlrczdysf.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtymrjjgef.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtmryhowhc.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtckilwqot.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtzglqicxr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gtcqvmdxgs.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gtrewqkivk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtcpflqdxh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtqozmbfej.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtkggmbjcr.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtnfjedxye.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gtvjfebsdn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gtcqrperbl.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtjtnxzwir.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtykfwenlk.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gtevdmmuji.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtctxqlsen.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gtppvfrrzb.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtdquhbimf.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtwawutrfs.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gtdtkdvaes.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtbubxxuhw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtwtoeugsz.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtijibknsk.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhblclfc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gtrfazeyme.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gtdijoyoka.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtmtwzqjpc.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtqjvssixr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtajoabirq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gtgwbiaqxr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gtrdmskczh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gtreipencz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkuitoige.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtczxqhoxw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtbmvnzvic.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gtvxxxmngm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtgwyzpxxz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtbzyxxhoe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtzhtmoktq.html


<!-- 参考信息 -->