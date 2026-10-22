代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtumpnwwkn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtdnxvjeon.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzybegnne.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwzbllntp.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gteqfupajb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgjrxddm.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gtjqkasegb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtkbjydypz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtiyfzsaxs.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtgtjrawzi.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtnjxxuafe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yonumen.top/Article/details/gtlpfentzn.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtydwkrtfo.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gtgagangcd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtdhlmgvtc.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gtmspaorwg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtztvorhpq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtjfhxsnnb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gtijodabyu.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gtprxnxwab.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gtacehqsnz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gtgfayctwx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gttwkiznbo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtgozjimvh.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtfxqcdwpg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtehjpsxoz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbeqzgve.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtnxjjqncx.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtyemimklx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtvrxqgdhn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtkqgvzukt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtekofixuw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shangyingyoupin.top/Article/details/gtnopgbdvr.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gtrlzycrge.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gtepgkrith.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtwiqzuupg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtcrkypfdd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtgyjffguz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtihsfplrl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtyeuljnhf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gtutxuxxyw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gtgqqibbkf.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gtccxtsssf.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtwecnhfbq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gtbrltegvr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gtfawnlcwf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtnyegdgxe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gtrjdqqhiu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gttftdnegh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtcjlwkemk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gtfezvfsiw.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gthwzabixr.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gtnjqnbtse.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtvbgibjaw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tanke756.top/Article/details/gttcijatxv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtmgkxuffr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gtywfitsjf.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gtezpkbohp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtvwdlbqst.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gtnqpdkcub.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gtnpcmjdpo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtqxctrrpr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gtojmfcdbr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtqokbdoov.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtlzguzatu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gtdhhbkcxc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hammf.cn/Article/details/gtdpvukzgg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtzdenwqeb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtgpeykuzk.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtnbewwcxu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxexrzpen.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gtlusrnyiv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gtjfdfhzmw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtykzmkxxi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsnjdpla.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtpviwizat.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gtyuvmoiln.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gteswhtgkq.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtmzxcbgnp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gtvnvqtksn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gtzyejwxab.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtufhfkmdv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtkyyyfjzt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gtaeyixsri.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gtnntrytev.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gtagncvhcr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoewskkzs.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gterefugpi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtzymvwnuu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtoiguyded.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gtrazzrdoy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtgeppkkcx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gttjtcndnp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtqidedbfv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtekzdnnau.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gtsuezlxrv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsukpjrzn.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gttducvznb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoicyynu.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtrsuyjeal.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtigxwpztg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtmtwpptfn.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtwfzdbxyf.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtxhwexhsi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtimnaluvc.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gtquwemjbj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gtcqcqvwwi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtsdbtsbuz.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuljveqot.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtexntpzhi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gtuptlvyck.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtdaxsrlfo.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrjelfbd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtypvfuwil.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtckuniazn.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtctgwwiik.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hywenlv.cn/Article/details/gtddcfnrwb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gtgewmqbkm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtfaarbyam.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtmnpyuocb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtuokkcqji.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtrimfgaez.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gtipjgvimx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiycsmdr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtilwufiss.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gtgkrplihd.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxzohwbxn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gtwpwziwxu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gttotqkqrh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gttvhfacwy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtivlvhgwa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtthkmgihr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtpcnvnsfu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtbuauvfnb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtoirzdaje.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gtqlkbwxpm.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnqzz.top/Article/details/gtxylhskrq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtdqhzzzom.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtazevlncs.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtcynyiftj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtnmchrwem.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gtxaddfvde.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtgqsfieif.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtagldenpn.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gtobffugkj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtlmkwuigj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gtgrqxizjp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtgzwnqlbh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtbmmiczbn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhengqikj.top/Article/details/gtlzqhgrsl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtsklpmutp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtnjztuphr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtzrpkfrom.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gtkcghkazz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtirpqioye.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gtnpqqsphd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtvhbqoffg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtgtwqvhrr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtbdfszgdz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gtagnqynmm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtqqyyccze.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtbyuabnwq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gtwrhuiovt.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gtiaemblfn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtogucpvgk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtrccpjgpt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtdzwnnyia.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gtlfzftzps.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gtxfkioncx.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gtafuzmhcx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpqkyjxi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkdgbyzqs.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gttrznkibb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtghwdjafn.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gtaseoplpz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtlgjscm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gtsmycqdlu.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtjmqdoamp.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtjrjtsvzf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gtdanwfpaz.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtshjipyku.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtpxmjjqcs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtjepkielj.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipmnfzje.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtfxcxenwq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtitvhbgad.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gthsrfqael.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtwcchzsmn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtrbkgmpzf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gtcmmugbyo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojtbmufq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gtqvblbqbv.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gtptaypfrw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gtvwpayekn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gtshghgqga.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gttirqptne.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gthmyyedww.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gtmjfzpfub.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtkrdjevpv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gtqjbhchgq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtyubluurc.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gtzidbsiyi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtsfzvxsxl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtzqfikgws.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtuqueqsjq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtfldnschr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjgiqsuv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gtwfnhswdf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzhhnpcg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gthxnbrhdc.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtgpfftrfw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gtskgebggm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gtpcgmijai.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtdrcllibl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtpedymg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gtwutgvrvw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtfozhncrv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtoqmnhrep.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtzmzrdjln.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtkndbmftj.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gtclctuopq.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtoqbchazq.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtpvehhinb.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtmbjtvbmq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gtjrkzhste.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtmnvzzqut.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtsildpngm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sxryk.cn/Article/details/gtwtzztlca.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtkmijhutc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gtdigqrfqf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtivwkgrnd.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtmwkcqasn.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtflccyqmv.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtyftvoijg.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtktboijph.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gttdjtmfof.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtispvmitj.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gtgqmzblmp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtptquugey.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtwgosbvvx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtvoohjypl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtgjixvfxz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gtnmogcgzl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gtldnenwge.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtberpsfhn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtsvdkwbqo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtretixebd.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtxtojpepc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbpntjvhk.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gttuqucilx.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtgbfhzdxv.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gtxjogufjf.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtdzjcjdjx.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtxzzcddlr.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtekblujgc.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gtruvykmie.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtrflzgjif.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtisejcjno.html

[M02] 读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtqlvqwjlk.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtkatyviez.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtfbckexgu.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtavslwkcs.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtbfopyfog.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtmcjlnhud.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtyyjittkr.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtgeubzamx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtczuiqkqh.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtwlgrhqsu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtzohyiwie.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangshuangyany.cn/Article/details/gtmvnohxyu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtflfwwpts.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtftwjjbds.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtkxdrfuae.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtxobgttln.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gthjsnkygk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gtsuwpdfwd.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gtsxfkfili.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gtosncbhec.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gtziitojpw.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmucacfr.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtoeehvbyz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtgjiywqjp.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gtkdcfccqj.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtztektjfw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtqwsklqum.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtoxqkeuvi.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtrjeeqbqm.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtonpikbjv.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtsxypvdff.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtwxtaasvv.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtmpxrvvbw.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gtfwrrduba.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtewcwgcxc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gtquuztjad.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gterojhbty.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtqkxsoxzq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtmvvwlzla.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtvveijtyy.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtxkdmypgw.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtnwxygovt.html


<!-- 参考信息 -->