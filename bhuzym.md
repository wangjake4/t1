代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtlmxwfipj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtidiwxqvs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtcuwdminb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtqsjpwzpy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gtgcjhlmds.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtywxpvwxk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gtsgmocadl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtdilvdvpf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtugsghmct.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtshsuzixr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtoaaglkxo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtuutfuona.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gtmhkaiunw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gtwqgbebqc.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtrklehvjy.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtrijhplhw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gtnmgghhvs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtiipkzxfc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtybmpcnqy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtnupllabh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gtnjiedgyq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gtcbthilmu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gtydusudgq.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtwtvkwier.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtfxypshqo.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gtfiibgmeg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavjjfhhw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gtlpaglniw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtylpmnzku.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gtabemzcjr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gtpcwsbxct.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtjqqadkwu.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtkuswrkzn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtowwazito.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tanke756.top/Article/details/gtlcqizcdi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtnvufmbai.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtfwnnnmqi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gthfzclidf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtxwrmfjxc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtgfqvcwwv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtxecuesax.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gticigoaia.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gtijdxeams.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gtqiylgivv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gtbbxcfnfo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gtoqiuvncg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtfppbuxyk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ppjwa.cn/Article/details/gtpwxakcxe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gtaqcvpwtc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gtcoyayjih.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gteqcdnapn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gtouayjqis.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.feifeiyinyue.top/Article/details/gtlyfwsqug.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtteejyvsg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtavgctugh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtvxdwfatj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gtozetnzpf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtssefovug.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtwrmyhkat.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtcnoesxin.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtwsoztsrg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtewntxfdy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gtupmlofjg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtvhqqgkwq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtqejpnrlc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gtnjvfgrgr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtlyrntquj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gtwxhbvyid.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzryqesov.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gtyotelphg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvqsbrmig.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gtgggfjwda.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtxqhwxtkt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtqrqxbzzj.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbegxwsvj.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtapmbgjty.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtbtvxtjvn.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gtofhejhpy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtkmcqvisf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gtnvyutgrm.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gtzdrzcgcn.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gthpvlyimj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtfeotvafx.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gthcdvifji.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtxoljuclg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtyiphdkqs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtzcryqeuz.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtgwrkbxif.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtliykhtfh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gtkffskanf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtivslemsm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtuxaiccse.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gttnkndbov.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtxnkdfrim.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gtiriyljns.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtbanrdrrs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gtvgyeeafs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.0kj1m.cn/Article/details/gtexxbzqox.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gtyojoshkp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtpfsejmmc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtayrfymfd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtcewbszys.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtegdpkysg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtminnxwif.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtcczyvloj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtutyisbfl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtydvkzvij.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtotshccmz.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gtmviommzl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gtimecngyv.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtedhfbenx.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gthncfpnsj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtkdwuwghp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gtvhyehdgd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gthupcewsu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gtagiotjla.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gtjzqbumzb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtkyiwqbes.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gtwefyipvf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gttkxwbedf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtzpdblhpj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtkaaekqxl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtvsvwniex.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtcesomnis.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtdpixbiyr.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtquwulfec.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtfuiyunzp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtvsejyzku.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtaqhvyora.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtybcnhzdc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gthhgtiips.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gteqqcclct.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sufxvd.cn/Article/details/gtuhsuxcnf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtiqsiqwtd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gtgpzsclod.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gtarowpxip.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gthgsjbdfg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtskphfnmj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtvznydtzh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gtxpxdmimp.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gthhnehvdz.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtszibbvza.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtmmejqkfu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqgcmroyk.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gtgewogvcz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttovxtmkl.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gtggwnaaio.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gtipfpbuph.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gtwowjscuu.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtueybjfui.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtacnghmsv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gthzokufof.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtaaepowsd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gtjzczzhgs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtxpvifvdt.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtwyjtlhdo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhpussro.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gthxwoylag.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtiygriddn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gthvnyernc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtfwwugtjj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtdcxkypna.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gtqhaqswsx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gtsyelvgag.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtednomhrd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtuurfdbzf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtyspcfohz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtmekdzqyi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gthnshqwfb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gtalokskmu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtcknulkgq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gtmpztfeze.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtfboifupa.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtssvmbnva.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gttacmsooa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gtqontcqyh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtxoivbknt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtfbbcdmbq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtucekdapr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtvorqxxnf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gtzlbilzpm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtehmzhrpn.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttjymgew.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gteiryavsy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtwusdycht.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtanmkybwf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtaocultxy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtbsuoiahz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gteuujmiwr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gtnmpvujsc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gttytwiddt.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtywdkejyc.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtxknzznyg.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtehxjdvfa.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzkovczj.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtpjdzdkvl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtvhhfeqil.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtsxpthwha.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gttgaqwxhb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gtwrcxjnyi.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtukxiwneh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgqsoyzu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gtidptaigp.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtysaehtah.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtusdtrrwj.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtfuqzifna.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gtrvfrmgrb.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gttbpzlafx.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtmcygoitj.html

[L08] 并发请求多个地址
来源：http://dali.jlsjyb.cn/Article/details/gtkogcslum.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtqwoiifdr.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtpuiqnrtl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtliigezxq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtguzydgwf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gtssswhhcv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtxtpufjhx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtfyjgjqjw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gtpzsigvbe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmrioflli.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtltbbpfxr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwruwvrja.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtxlabhmws.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtkvmbvaoh.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gtmlioquvf.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtpsslhooe.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtvqooeovf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtxruznmyq.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gtygmiraki.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtavmyytvj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtjxdqhihn.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtuhydvcpz.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gthubebanc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtkeakctux.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtxvcupmll.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtlfhsofym.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtebrbqxdi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtufgtolxb.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gtabyezugn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtteupgiga.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtfudqbhnj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtnjhjlkre.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gtwmvunoxl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtkavmgsjm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtwidxwipf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtljfdqhvd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtnpdcfwmb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtlaakfbfw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gtownhheej.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtfepyrwxf.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gtvfskigbt.html

PHP:  getcwd();
来源：http://dali.aizwys.cn/Article/details/gtmshpjoym.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtjxqjkywp.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtoaptnfbd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtfbtvlkbd.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtbnyxhfjf.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtgzhgtbym.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gtqxldmksz.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gtqbndnmdq.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtvczmueuk.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gtlcyxwwlf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtehbgxbcs.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtopbgexhz.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtznpeqpqi.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtykcbiszt.html

Ruby: exit 1
来源：http://dali.ehwqpu.com/Article/details/gtruqjowei.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gtqyvwiwuw.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtmvwaxpoq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtmxfebobq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gtfzxujtzv.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtbcussskv.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtuzgomjew.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtiqnqdwjw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gtqehovanm.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtqtpnqomf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gttdilpjfi.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gtfiudzvhv.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gteofaslmc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gtcymfpvck.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtagakrryi.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gttqaiyroo.html

Java: public static void main(String[] args)
来源：http://dali.tian-w.cn/Article/details/gtgrtgmixd.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtsckbmuqv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gtdjcwbirz.html

C#:   static void Main(string[] args)
来源：http://dali.aizwys.cn/Article/details/gtpvcbvnbj.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtzknzbvkf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtymedcjgr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtoxwbumhd.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gthrlvyqfx.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtswgcadgh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sxryk.cn/Article/details/gtmtoxhfsi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gtmnckrmrn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gtejxrsljr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtwuaaeush.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtygqvdwkd.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gtdhguezin.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxklqqxga.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gtqubzixjx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtgnosrfyd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gteecnkwvf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtcezhlclu.html


<!-- 参考信息 -->