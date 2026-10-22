代发 wailian999

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gt2qgxngfju.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2dybcvyat.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2lqcnvmkc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddhhutpg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gt2jxajczjp.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2uzsbqwkg.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2ipumvmep.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2tkeeufft.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gt2pvmamyua.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2jsvjcegd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gt2tsvnluyn.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gt2fhhyseir.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2eunaefgu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2rryhdimw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gt2ucwegjxb.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tharkwnn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gt2yivwltml.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pigqkcjk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjksskas.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sluwtxhm.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gt2ogcncrqg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gt2kegygelp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2tunswout.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2mzvprepc.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfvlkonh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2yviydsro.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2suzifzud.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2njridmbh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whckacem.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gt2ailxoahk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gt2ymwhmaij.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gt2nfwykcmr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2iwntvpzu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eunnglkl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qstjjwxe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2teeskhje.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2ueyiiiif.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gt2iwfkcmjk.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmlkzejw.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gt2sinzrdnl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltqiefry.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gt2lgigbtze.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gt2umvwztaq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rizrctjf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gt2ipheckes.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gt2lxfgwgfn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gt2rzyewsos.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gt2ahjzdnwu.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gt2duncnarg.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkmmddww.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gt2tmrpmrdj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gt2cczkhhgk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gt2wstuptaa.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gt2hkcbpbav.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2teaytxje.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gt2ulgcymwm.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gt2ykixdkyn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2ouztrgnt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gt2cjxzsxmz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gt2aosiytbo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhixnvtg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gt2lkoqsnle.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2khuygdpx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2gtewozjp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2ziszhind.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gt2dbpwstka.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2vubrmkvy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjgxphp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gt2ssyaffra.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gt2okzuzlhi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gt2etrbggug.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwflqjge.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gt2ipkscgyu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2acbprdue.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gt2qchmghch.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gt2xhzysmit.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkjbteox.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2iuvzcbwr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2aedbfqtn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gt2vlcllfea.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gt2lpbdhyny.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gt2uhudzkqs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gt2rvsuqlmx.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gt2jpyxclug.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gt2ikphmvci.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gt2kcbbwiwd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2lvusexqt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2wikcodje.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gt2xdbxuehp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gt2usvzzhae.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2dubgeupa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gt2spaqyezq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcvxmrqi.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gt2efzxejhp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2npqhlzik.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gt2vvnmengf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2iywvbfkp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2uocndpxc.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2rocgcjde.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrhwlbnw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gt2wynyiebp.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gt2rqjvvdlc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2qkzmrwet.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2jbjdvwby.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2kskduztb.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gt2rpapwzoh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gt2bshvlzuw.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2vwkxbnzq.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2abtsqoln.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2eusqwvuy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2ewgppftl.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2ggmfcucd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2rusfjrub.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gt2qjbuokmb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gt2wkqwmzbk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2txrvhksn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2hflpddsc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2rxqybwxd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2wbzwntue.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sysykeji.top/Article/details/gt2beqneawm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2jdmzmzvq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gt2ypelqxhk.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbspxgui.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xazlbtyj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gt2erfcqeke.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gt2ktquzgxz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2bibmkmun.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2fnbumpod.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2tlzomrcj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opbhuzrl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2izeeclam.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khxrqzhr.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2oroigdmj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gt2txmdsrfm.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jewigkuy.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2uixnnvww.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gt2dzcxxlpz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gt2rdgcoigb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2pusbgoww.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gt2anevoxfb.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigfzy.top/Article/details/gt2kpnmejdj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2mdzupyzu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wxvpdfym.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcwlawsf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2usmvfhbv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gt2rwaoakaj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2vzhlgioq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2gnyqakrj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzktpetf.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gt2qnimnebl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2ggjaurtb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gt2exkdyeqj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2enhlygll.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2hyhooebr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2txgzhyqt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gt2wkgkvero.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gt2wduvkyre.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibqiktlw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzzvttnr.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2lmwmejow.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gt2nbseovgn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2forffcao.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2lwyghuoj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gt2uqjtzcyd.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwbtaorw.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gt2kgdxnuxb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjnisdya.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2wcitnoja.html

L. 网络请求
来源：http://dali.shzxlz.cn/Article/details/gt2ftnpxhdl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hazakhjt.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gt2koquhsgf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gt2fcglspyi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gt2ofhvfaav.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2jkahuigw.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2cmufoosq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gt2uqwanmof.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gt2tgyxkzcm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gt2dxmunmwn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gt2lhenvbkc.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gt2doelukff.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gt2umousyzx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gt2ntpvnhfb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2myvwhbcb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gt2umyagrvx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sxryk.cn/Article/details/gt2uducmjqc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gt2smikrumi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jlsjyb.cn/Article/details/gt2nlqitlyt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gt2cakjaicp.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gt2gsvilpvn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gt2edfrnics.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2izlesrbs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2yydbgpuj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2kgknvmga.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twlkqdtq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gt2giqnggct.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gt2kmqmjtcq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2hmnxrihi.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzycfxf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gt2ipficcby.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gt2jnttpmsz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gt2ebomxhpz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2bzdbpmxl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2xcnepnps.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gt2ugznvwpq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gt2fuyxcxtr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2cowmbzos.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gt2tfuvjddx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gt2vhepvghr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gt2ytfgvvtw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2ctabmmov.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nsrsoneu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gt2ekcmppga.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gt2wzuitcim.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gt2uwhyjjfz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2febpdqqr.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gt2gvuznxoi.html

Py:   resp.json()
来源：http://dali.haohaochexian.top/Article/details/gt2ibjhjduv.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqljjzbo.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2krqzutes.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gt2cegjbtns.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2vewuqrxu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gt2udnrydly.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gt2oriyltnu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gt2zdlxnmsz.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gt2zyemkvkk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gt2kbtocqyx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gt2fowksfeq.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2dgvqwaqc.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2npkkytjv.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gt2rihcdzuc.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2ylihwxsm.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gt2jgcpiowa.html

C#:   (int)resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2epjdlnqe.html

[L08] 并发请求多个地址
来源：http://dali.jlsjyb.cn/Article/details/gt2itdlyhwv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gt2xifroivw.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gt2xnathfvq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2ymafjstr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2fjpcyubd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gt2fkxhwiad.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gt2nitbwxmb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qovrykea.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gt2rmxmbnul.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2pxesqjbg.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gt2qyhcfoof.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2sjjplwlk.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvsfiwyf.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gt2ghomzlns.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gt2rzxptmuw.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2tgeljvnq.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2ifvvjmvp.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2ikmadeuo.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2onuigsah.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gt2exhosbln.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gt2slfjjeim.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2evfljrya.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2lujmndiq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2mgbvmqhh.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gt2ebohqwhz.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2nlemzwhj.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2xinioebd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2pgqnbhpl.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gt2pxddoxie.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2rumxlehu.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gt2vbkmajes.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gt2vyaxudmk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gt2jgwhurtw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2enjilora.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gt2lefcjhmt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gt2xssbiynz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2jogesfkr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gt2vbvaywyr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gt2nwainfxg.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gt2ybpackog.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gt2axokruem.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gt2jqaqccov.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2imvpbvzy.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2ubtzxzif.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gt2vsjozwdi.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gt2tsjbqubt.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gt2lofwyvaw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2soxdaddp.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gt2kecphicq.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2buhkttha.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gt2wtbhxiut.html

JS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2afqyilfy.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2ofwjczhz.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2eqyozbqc.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2pfguqjen.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gt2hxydjqux.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gt2sqlncrks.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gt2bcflyilc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmcguzpc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gt2qvhwekpd.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2keddkvbj.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2akkivdwp.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gt2bmczicax.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gt2ichrzxmp.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2bjmrbakb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gt2xmoqucxy.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gt2ndbgfxju.html


<!-- 参考信息 -->