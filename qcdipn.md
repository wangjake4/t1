代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtapkcpczm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtxzugstgt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gtaanferne.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gtznedgmmk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtgwplhlsp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gtkkwvnnls.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtashtaqnp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtlkvxxqai.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebfzcpvu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gtlvndokyf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gtxtyplgwe.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gthmeraury.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtoxgmharb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtzifjlpte.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gthrfmatej.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gttikwrxva.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gttxbrkkdd.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gttrxyychc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvuxjixa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xinyue.icu/Article/details/gtmhqfgfbu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gtrdzpbtio.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtxjminszu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gtpmxrvhya.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gtiexbrxqt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gtnebtvftx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gtzawhzfpm.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtbcihbklo.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gtypmxxijq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gthymxtwdf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtaetdnued.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtjrphtzot.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtciipnkwo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtpbzbebbt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtojqiryqx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtzoxdqmsf.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtsbtklood.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gttgynfmse.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gtjjjeormx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gtyxwixqud.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtgmlsbunm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtgjbvawyn.html

Go:   end.Sub(start).Hours()
来源：http://dali.pycfn.com/Article/details/gtqpgizncr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdczpyapv.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtltawcngi.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gthnzjqphd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtgzwmevqc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gtcycxnnwu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtxdnzjdlc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtbfvtpuuq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtlgtctgir.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmirwqce.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtcvusqvtf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtnshkfdci.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtjuxxeceh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtpqfizlqy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdobhbqnk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtzbxsbawg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gtxleotctf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtiedtcjtf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gtcnuuoluv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtftfpgjgy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gtwjnuaqrj.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gticuvzihv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gteveedaqw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtvzqxmvam.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gthklukvkb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtibvnzdxm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gtgvwkyjth.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtzusqtpzr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtcodqdmdw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtttyeamgl.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gttrmekgro.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtumnojsac.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gtuogbdphn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtgbeubgrs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtuunxzeus.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtxdcyglxg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gttnlipvuu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gtwahpxjtc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gtcbhsswxs.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtikppwzsw.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtwulcswbg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfjpucaqg.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gtszwslbby.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtfqecufjd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtxshstklj.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtvzwsmqln.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtcipeqbni.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gtmtflsznn.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtovkxxbbq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtuunxzfcx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtmxjfguiu.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gtwoefmksg.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtaittlnec.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gtbekmqpuo.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtbjsjzwsr.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtzqfxuqfe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtznumgrwv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gthcguprjb.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtjgkyiplq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gtxskfjolw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gtqrwcchfd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtrlvuayjo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtkdvvjyyp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtfsmepkmn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtrkafvntw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtfehqdbay.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gtupelvbwe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtcmmvvahr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtumawxdod.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gtlfyvbdas.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtqrbouczb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtwjbubcjg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqxkfetp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtaudyawom.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gthmqdlneu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtmrpdzxgo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtexxqtzse.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtkqeocrfa.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gtafyaivrh.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtxganotup.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gtlpxipxzl.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzcmuilt.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gthmuygpjd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gtchzueeun.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pengpengdd.cyou/Article/details/gtuwkvvszs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yvedp.cn/Article/details/gtvaknywrq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtoznoahzb.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtjmsseqzy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtqrwmuouw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gtglklqslu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtvbarvxuj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtsbwnrehx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gthrxjvque.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtvzfhrxae.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtliyoylji.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtpwcaagrx.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gtnxccokwe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtqhnlzoih.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtmunfpwak.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtzibdwest.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtqvgmggps.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtiguhvisx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gtsgamfcxb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gtimoekfhf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqrkpexg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtiufaxhuj.html

Py:   pickle.dumps(obj)
来源：http://dali.haohaochexian.top/Article/details/gtbilymzxm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtdhdlckmc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtaoayzcxz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtinumxsdf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtzsylelbh.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gthlwyhgmi.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gtlrucuyfh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtozhqymbw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtouuqhdzk.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtkjbrarvh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtquwcdgda.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gtofstmxhw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtjngvdcup.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhoulong.xyz/Article/details/gtuohkfcih.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtdtobzvvc.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtgsequazp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gtbsnwxtby.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gtalklawwj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmfbmfmb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gtcgbuqvzz.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtmalqqyib.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiivlmqbz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gtwzkvunjt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtqbvzdnfg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtheemioyb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gtftuxykbq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtmtzybcte.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrjiydvu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gtvvyxsdok.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gtommjvjnw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gtwltfcovp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcynujyi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtlnuygxrx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtxxkqdvuf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsrhuuhc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gttwpjkdnz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtjzloqrfx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gteiuotkrq.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtpppmcwga.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gthetnillz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gtblatzmty.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtdghczrkx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtbybljywz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gtzufkywft.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gtgprzpcpg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gthjrbvcnn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gthlfwrmzb.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gtrppkhxpc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gtlgvdgyzv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gtmazukboq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtnlbkkoti.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtbsiccikz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gtqpajxjoy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtrltjsmkz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtyntjldku.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtfhhevwso.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtxqlarrqp.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gtzyarbpji.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gtoyfwhhik.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtbpuyalvf.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtmcqunyfq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtuxkuelfz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gtuxrldckg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtzvwnkhbd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gthkhtulyp.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtzhzulfhq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gtxnxjaand.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtnqgrnpue.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtzgsmctsl.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtxntarmbt.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtpsyjrifx.html

Go:   resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtrzsplpuz.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gtnsiogdaq.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtpbtkluzb.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gtfcjthpap.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtywmjqwjy.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtnchglzor.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtcqnojfyx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtgvtnnudg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gtgoejzuxv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtheqdmaro.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtvwkosise.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gtypapuvso.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtcqpjtnzt.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtfvtejdwa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gteoklhwmz.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gtlxrabqib.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtngszyjzd.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gtkmszpqdj.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gttgfgmjik.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtndijbjqf.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdfkupka.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtitszwrnl.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gtwhzzwwgd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtbmfmgeob.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtbntnbqyw.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtjlgyosem.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtdgvvjsgn.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtshtdahmn.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtqawkrycc.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtfotgmjqb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gthvrjlnwa.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtjljpucrr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtpbazrujn.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtybrigqgc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtpsteaqrh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gtaroavlcd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtcruutvem.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtnddctkoi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gtibknmuzr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtvzyaxgtw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtqvgjhorz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gtorrxrxps.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gtyxyxikhz.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gtmuxaedau.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gtnyzjdrea.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtzlsjvlua.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtnowkxead.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gttsvnaqoc.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gtuydipoik.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gtiyvncnah.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtbdxrqhxk.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtxzcfgyrz.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtbsvssyax.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtqihphkec.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnluvthke.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtuyrorxwa.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtldwcljsp.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjthqkmc.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gtsgfslpnl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtegtlfklx.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnilhrpbj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtenjnjvkw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtlgjukvkh.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtlkehnudy.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtfedrpmlx.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gttegwmwjt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtsnyedshn.html

Ruby: warn "err"
来源：http://dali.cucudq.cn/Article/details/gtdmrhkryr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yvedp.cn/Article/details/gteyehbmmd.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtqoguhieq.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtiwzbtbtc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gtlookemef.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtmewpwqui.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtczarzrna.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtxgncwcsi.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gtbbjufhtq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gtkyrhvjau.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gttvkution.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtvnmireoh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtrfpnfgmi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gtnkdgjauv.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtrlclxktv.html


<!-- 参考信息 -->