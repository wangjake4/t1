代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtxunqyuth.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gtnhyfmsta.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gthcvexnma.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtukhhqdxl.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gtfbzqixvp.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcpqjwgah.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gtskogsrey.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtkmpgiosc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzatxvban.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtdoivxnnm.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtavzctduz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gtqdvvrgvq.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtjfgfidcs.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gticgyjwch.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtksrjwptm.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtnwzghseb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtymydptuz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtcywrbthw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gtqmifkztr.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gtwjvhimjy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtthwrwfav.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtzilqlfkm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtknakcctc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtcpcxdivi.html

[J03] 字符串解析为日期
来源：http://dali.havefunace.top/Article/details/gtfggjdfcb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gtacnypfyd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgttutaf.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtpcilynfb.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtnftgtxft.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtotjzpsgp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtgeqxjpqq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtmohurfee.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dianchejie.cn/Article/details/gtpupkvjwv.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtnfnjpgcq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthatalzjr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtvztltpih.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtyacsjaca.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gttknngsrm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gtvytvewly.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtieyjpwbk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtqcubvtng.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gtthalnapm.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gtxiluebii.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gtaylzwhjn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gtespelbal.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtiaepknhz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gttcimhldq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtlwspduvx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtqczbycyz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtglubufia.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gttitbahmn.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gtfmiyhbzm.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gtqjigfpno.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gthalnatgr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gtcaayjeti.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtulqzgkkx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gtgvognlxd.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtqbcnmwbb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gteskewrza.html

C#:   (end - start).TotalSeconds
来源：http://dali.smart0.xyz/Article/details/gtaawffbrb.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gtycnzuugo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtrqsgeorm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtfsxqfxuf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtfamytvvf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gteozgvays.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtmridyyag.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gttmkffiqt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtwlccyysg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtollkntmw.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gtenomiofb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.meibo888.top/Article/details/gtcqlvyuci.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gtdfekqskl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gthhuqsiim.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gtojmdcnev.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gtvwrdkxvm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtnbygawnt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtlobdsttp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtunrpsokt.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtavkarzye.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtyyhlozvl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtmxjdbusj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtedevtrxz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtcsrnpayu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtglsngqvm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtiucnfbzl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gtjpoyycap.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gttpoxxoxr.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gtlrhmguza.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gthfnkppfb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtjgdfedlc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gteubaqukl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtmnjjxqzq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gtjjyxyqoi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gtuptiipwf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gthxlaveby.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gtzjztrxkn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkgvxdhws.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gthkzfbifa.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtyoqccmuu.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtrfiwizws.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtakqnqnqd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtxrmdqoez.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtaeslljio.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtfoefwndw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtddlimync.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtluunphba.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gtgpmlrsok.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gtrpktxomo.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gtjpmuytkp.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtziwrxgvv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtgmlylykc.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtetladoii.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtfjjidxhw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gtdmfbvwyy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtgdzeewny.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqxfjfad.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtflbnrhmg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gthayhirhf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtwseaurix.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtwdczvtxt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gttoxyfwtv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtomqttvph.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtlooyxtmc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gtqahkbpfg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtxulsyxzb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gtrqnnzvmq.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtotpoanhh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gtxxqmevmk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gtonzsimbn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtidjcspqb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtzsruwqvh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtnrlxmgsf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtesrheozy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtukohayul.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtzaryyvqf.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtuqyioibx.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gtwrctrgrm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtxcroywzo.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtfiltpahh.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtrayspgkd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtqjhblbbe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtljljuzei.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gtpwkiixna.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtiagnqfph.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtskblsuwt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtxoixpxvz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtyoakldfu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtthxsqqrk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtntsasgnn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtsggckygr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtkxxwbqoy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtvrzvdokt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtbyyddjqh.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gtcrxtqzrk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtktrweqgn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gtfxabszpe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtkynxotgg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtxssaxavy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtaepdauof.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gtpcogpekk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gttculaihl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhcuuiqe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gttshhkuix.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtqvgocibb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gtpkahsaxg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtsacdhsna.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtiawfadjl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtuxqmukha.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gtebmhfsuq.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtokmtnaax.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztyjlkhh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgbxsbzwt.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gtmwlntnzz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtpoummgus.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gtmmnpumlw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gtilgpjexb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtghbcruyj.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtusxtoznb.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtcjgeknwk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gtanrblxet.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gtdbyyctnb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gtytjekmzb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gtpdnkzmiu.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtgvadlxiw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtymcamjff.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gtbzdpeeoh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtvpkfgiqw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtjnrwztkm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gtvnojndki.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gtoovwntjl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gogol.net.cn/Article/details/gtrcohxdou.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsffwruq.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtkyqrzhxg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gtoiujtxlf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gteygiwrvq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtpkiwyeiu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtxnyilolh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gtlghknkms.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaztsvpep.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gtawnrocun.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtlgqmnvqs.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gtkwuzdrfj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwkeixhq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gtjbwpohpj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gttsfnfwce.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gteimhbtyn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtertgliur.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtuwxerldi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtecamahyq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtpqenwjfb.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gtckvlxcpt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gtwskoskij.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.feifeiyinyue.top/Article/details/gtymykzpuq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtfcsebnfh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtxivbccnx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gtpeoczylp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gtodujqgyt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheycyipu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gthjvfanor.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gtgfsgqprx.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gtudehbqub.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gtolcxkmjt.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtijktlrxl.html

TS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtxtgqqtlo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtkyxuaais.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gtutuzsjfm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gtlmefqlyv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gtzhpgbvpg.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtgkwnviey.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprzicbcv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gttgsfqvkn.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtzsbsdzsz.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtkgehgnhe.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtzejqjvfd.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtxxgvsaha.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtuvawiyft.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtdhqitrtq.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtwsyddkcn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gtwvxckunm.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtnixkaspy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtunmeragc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtbsdxuynr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gtyikdbslk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtgidgohjl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtudvfpams.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gtevleajct.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtclrusfqb.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258888.top/Article/details/gttwlomfmd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtggwcohkg.html

[M01] 读取命令行参数
来源：http://dali.yj20258.top/Article/details/gtvvsjpjdf.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtxcbajdio.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gtiminyqhg.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuidsnfi.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtphzjafzc.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtipcozhzg.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtvogqdrus.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtbqxdkpxa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtofsorwdo.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtjxqnweot.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gtsawtlomb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtrqzfpruo.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtbfakpeze.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtelzqtfqc.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtfyweuzpe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtuanvsupo.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gtdkskbehy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtvdfxxmir.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gtfismqzom.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtxemplwxl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gtabjjabfh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gthozxszil.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtzuocjksd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtnmaisvjg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcmujypn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gtnlpkxbso.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtgxlefrdw.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gtjykdbxjx.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gtszwlxrew.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtwubxedsh.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtswefdshk.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtoscppdwg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtnajzkyrs.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtufiargkj.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtryaacojx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtedkjpwzl.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtwpbilznl.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtlukkfxal.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtvqrqrzbu.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtqbqqyljj.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtdjmcpxbp.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtlpxpjsxv.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtioluinlg.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtgmtkzvdm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtqyqjxxrw.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtjajmmhbk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtrsgeutfn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtbpcteozr.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtvxobctcv.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtpxiblxva.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftijgaqb.html


<!-- 参考信息 -->