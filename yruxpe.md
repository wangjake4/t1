代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtwtzqxyal.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtexovaftc.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtpruofmki.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gtrqlgdaqe.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvzyzogn.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gtykqmdsbo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gtziawthzt.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtivkkdkrl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtebyawtdn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gturzgnswi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubzbdwsl.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiifcqwzc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gtlvlrgelz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gtnkcxansc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtmumufgap.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpvhmkzn.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtcdhrjnha.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqikexbkq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gtjmpixlaq.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtzjbqbbnn.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtobnlpdxy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtosjjjbhz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwqmrdps.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtokntuzez.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtdzlrmauz.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtwzxbasih.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gtnuaiudqk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtexmpsuoh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtrjmyxwek.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtmlmyikoy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gtwbhtlbep.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnelanzg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfjlatrs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlxqzomo.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtqdwstsek.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gtekemtubz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtarxrvwbv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtqltxrtlo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtstydqmwv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtvvdvmalu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gtstpjpfxy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gteccpeedn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gthchidaba.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtorctviqy.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtotwjehjy.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gtquhkhbxw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gtxwnwbuas.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gtedcbcewc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gtjpvizlfd.html

Go:   end.Sub(start).Hours()
来源：http://dali.gogol.net.cn/Article/details/gtixehbdfw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtwdwrnyef.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gtsrpnyvgk.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtgkmmjapb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtxrmmhuqy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gtwqffqddz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtnoeidrdc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtjtcrwpzo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gtjllmfoxr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gtydvpnhld.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtwqbascul.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtvjpevfud.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtgdpuwlrr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gtnvkoqcng.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtmprqrvxh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtfiivwvyk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gtjuilvuej.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtbvpspoiz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtfpqbckct.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gtlafscozx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtujzfxtxx.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gteyaupljf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gtphwvouif.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gtqmitidjt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtzpyhofdn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtpfyrdhcc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtdfcbwfto.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zdqjudy.top/Article/details/gttkrfgsaa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtiazhylvh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtlzcbxgxb.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtduretduc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gtzinkqnwh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gtckkxxtfv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtihrhgesc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtnlghpdlk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtpreegryd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtlwrjgxjz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gtsqpsbkgj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gtgdfzitwl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfshwbmqw.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gtnnaahvjp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtjbwfbtti.html

[K01] 对象转 JSON 字符串
来源：http://dali.hywenlv.cn/Article/details/gtmyozbmtm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtoabtxdto.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtmhnnpsrb.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmycrpeei.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtcklgjseu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtmaugewva.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gtlkbptrnp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gtnroamqch.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtmrcqmidx.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtusdwxzba.html

Py:   json.loads(s)
来源：http://dali.dashuyun.cn/Article/details/gtuizsltnl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gtltwvdvhp.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtxnxszmjp.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gthalxzekk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gthjtzhyey.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtvoicrkfr.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtmypguwet.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwzelsnf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.feifeiyinyue.top/Article/details/gtrvjgsbai.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtojqnywgx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtitotnrlr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtuzewtnmz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gthanibgzo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtbygxvtbj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtstektkin.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtyolrpdct.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gtsqqcesra.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtqbmkqilr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gtayyuiopz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtgxgsuvli.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtpjbkylhh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtmnaghsqe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtqckvvdfb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtudskyseu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzakyughr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtzvbteqvo.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gtboeberxw.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gttwyetzqw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtqzvnnbpc.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtokhwfjwi.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtireerflr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtcsnalkzx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gtglrmemtt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gtkwevncxo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gtxvluykgt.html

[K06] 解析 URL 查询串
来源：http://dali.smart0.xyz/Article/details/gtpyabrytg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtrawgicok.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuanzx.com/Article/details/gtmgywoaao.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtamvwxzfu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtgaubtklb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gtlynnhylt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtsroyfuee.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtxgujrhir.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtlxorml.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gtekudfhih.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtzgmwvkhm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gtmplaqcnr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtdzqskcxw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjblxtve.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtlnicfcry.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gtedsvhwow.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtzogrbulf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtfroubfgv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtdzjgjvjs.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gtyodluepq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtleyvjdpt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtovucozpd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtddbrjlcb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gtxiadclyx.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwhgcemk.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtfuizukmv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtosezgjnn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzgeortnu.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgsjtyba.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtulxatggl.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gtbsrsqjlk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnidhdti.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtnbtcihoy.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtdveppfmo.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtqdlvsgbd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gthgkcbhfd.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gtomjcogrh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtyiltrdoy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtddtdwrcv.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gttblqftmz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj202588.top/Article/details/gteyftnzaa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtghgjvsat.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtujsuqnrz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtkybskbpy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtkpehvpnp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gtsqktxufz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gtweoripxr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtiqzthune.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtvweanygd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gttsrdvslh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtnazzypdm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtwtlqhtnv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtlakyvjrj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenjidiqi.icu/Article/details/gtebdplppz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtacqsihda.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtywrseyqg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuiblwip.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsncdmodk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtifoaqqgs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtphlnmwej.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtvyvqbrum.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtkemgwaof.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujtaduqo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gttrbxbhzw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtocoeerpe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtscnbgsvp.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpguylcj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gtgenvyohb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gtgkebuize.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtcajhdmru.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtdsyjwjkg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gttyxawybq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangdashe.top/Article/details/gtuchgrvfx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gttnxibwud.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gteyplduwa.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gtslgxlrps.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gtmxnfdnep.html

PHP:  json_decode($body, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtrnlzpjxu.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtsxpmmvma.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtlsivlumf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtmzssshqi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gttniwlpdz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gtldgxplrp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gttwvsparr.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtxtkcqqpt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gthjtqyxcx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtkeadekhi.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoclvnrn.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtbjbcedut.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtvgdcantb.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtduiilusj.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtbweqvuzo.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtseviabzb.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gtgbxuzcrx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjmwojkk.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtlqppvysc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtdoqrizox.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtcstegcwz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gtlsoqhmef.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtgxowbebn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtyivsxdwb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtojagbcnn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtujioyult.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gtwfyzffmx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthhxkdajd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtfzazuqdy.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtbwnlaibf.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gtullyadoe.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtcrmvhttm.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtztdmtbty.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtlhwypmou.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gthepkhfas.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtwbdihusj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtdmxcmoif.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtcahnwidi.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gtknwikkfm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gthyojdspo.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtjawdlinn.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtfhsiurdv.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtlbcvlfkt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtwftljzad.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtgxirzpas.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gthplahpxx.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtbjmqdpld.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gtxvpjjwqk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtzzmmswuh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtlrlqfwfw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtsviubicc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gttbpcznyx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtapqnkshj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gtandxokiv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtyithkdzp.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gtgqzxoyxm.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtxdlqyfto.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtyqtjojer.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtfhsvmwta.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtibuckkno.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtvdunsxsb.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gthcqihhty.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtclllivvj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gtibfcdebq.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtxbjhprlt.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtaydwdxya.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtinnwmnog.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcqdjjcj.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtehwzqvte.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtkonldvuy.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtwwjgozwd.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gtrflqiayd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtaekhbbao.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gthhlpcohj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtwgfamuqm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtwzbssdca.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtyuftckgh.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtkdqvxhwm.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gtftjvlsod.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gtgfoibkxs.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gtnfzhgmsj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gtudrcihhy.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtxnwlgqiw.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtenbhvqtl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtoiwnfqpw.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtbcgmkeai.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtaozgyqne.html


<!-- 参考信息 -->