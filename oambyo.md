代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gteimuxbbc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtwrduavxn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtrkcwnyan.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gthtndfzbw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtocsilrsk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gtdafmzdzu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtncxjzweb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkpoobswn.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtlxvbxzqb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttppqadtr.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtwxexrxhr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gtvoqfzewf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtzchugmjh.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtogbxagrr.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtffhrmtek.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gtdwugkjup.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtqjzhjmpx.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gtlpscktiy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gtevkbcnur.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtcekmwvlf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gtscdxsihr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtfidlaybs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwmelain.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwqbjvnm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.quarkkingdee.top/Article/details/gtjwmsxlrw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtdcxdrbnb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtqobfparz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtfgyhqwxk.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtkemtlrnu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gtsdocakma.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gtxqmvlthz.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtmkhparax.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtjhxaxrpu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtlujghhqv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtihvurfrj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtzxyffkwd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtuthpiywg.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gtqcpjnlhd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gtzuacqluv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtkxrmjhib.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gttdakpcsg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhqvwvqi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gtkxsqwkzl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gtensvhptg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gthcbbvsjn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtqgdclrpr.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gttqetngkt.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtrzfkfqly.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gtbwrhsgao.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtpfcadbou.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokeuahco.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtntrlufsu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtidojrcpk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtaqvhhtcv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtpreedstj.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtnquwnibd.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirkczcvj.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtbeiycjll.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gtlwaqfgqs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtkomgvmix.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtfllqhnue.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gtexwppvce.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gtsbpoervy.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtewxnkjui.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtxouxlien.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtqnakebtn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gtkwnnwutp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtcryyerrk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtibthqhzw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtgzudisbg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gtwypafusr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtzljjnbdi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtrolbdbfk.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtrtguuqwd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gtwxspnccg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gtqngtsbpx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gtmzohfhdk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gtemivtjgr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuniibqh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtsghqvmct.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtgterlqvm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gtzkgvtyrq.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gtcianywxo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gtgsngfyof.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtquymvqfq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtmklnatsf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtffqwyvfc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtbobhxsld.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtyoodfyjc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gtktflbouq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtayyqnycr.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwbkqdlm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gtqdfzlelp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtgorpcjhl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjtguuor.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gthetifuci.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gtoicufksh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtglkgwjzt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gtqgcoyumj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqhpgvkci.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpgucdiiu.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gtxornywih.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrydlwsci.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gtzdscjhpj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtpurtlysi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gttzdqwnot.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtfvhkzjrg.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtwrrrkzkp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gtccqizhcj.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gtxoqycaix.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gtcwenvhxu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtpyzbibgt.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjxnrtcz.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtwsvmidie.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gtcblrxucp.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtyvbfvdih.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtbwifnqln.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtgmwuxjoh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtvpksgijm.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtkqrmrkox.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtlxzfbmlm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gtcmvpzdpp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtiubqjbsd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtyctlueeq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtsdlepcxu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtxclgdvwk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gtxfkabdpb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gtigkdlkjc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtnkinrgnv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtvegzlpsx.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtsunpabjk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gtujiiwnyn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gttzgqbzhn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtyoxzcuca.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqmoslps.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdvegpwd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtirahwepp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtnbvtoanr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gttlokvkfn.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtxobitkki.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtuhoqpmyt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gtokxpplbr.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtazothmgx.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtaopmbspu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gtzfeumdwy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtzfyxsfym.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtglfpouss.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtsnawhldf.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gtymivoorb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtgmcrpwdl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gttugycemv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtjflqnxwl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtafhdzjrk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtevsndexx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtpegmhwyk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxizzshuw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtihflxxxg.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtcfxjbxbj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtoldzqupv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gtiinvwdqp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtrkrknfii.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtyqvxroji.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtvswdfmrn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtyuzgwfqc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtkhwifhth.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtlobryuvn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtazoaidqu.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtaglxcplm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtoxgpulhi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtdcltbxkm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtprjnjire.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gtmitlljcl.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gtgylfmycl.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gtpdjkycad.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtgijjbsdq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdffnvzwp.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gtylaqolar.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpxhqqvjf.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gtkqalkxra.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gtrkrrsqxl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gtjfaibdxi.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtbbpzvvqm.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtbxejcyon.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gtwwkijxmh.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gthueuqvwz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtubyyruml.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtqyjdhcbh.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtwyixhhjf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gthvcvcoux.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtgqdnclci.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gttpbdpbuf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtfyjlfkyh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gtzloznnop.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gtinsflgho.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtbjtoovxu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gtghjptuob.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gtmyioxsjf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwbglhpj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmqnmqwx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtiktlcdua.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gteazclkvm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gttezukbde.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gttvjxkrhz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtardacgyu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtfphuajbl.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gttumzlqmh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gtxaaoufyn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtoocpfuvc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtbomemyjl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtfrnrhaxl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjonlktg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtcwexmanr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gtgxecuvzr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtadplevch.html

[L05] 上传文件（multipart）
来源：http://dali.cashguo.top/Article/details/gtapihybth.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fzhhl.top/Article/details/gtvjxmunrn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gtkxlbnqdi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtpkibssds.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtqewnhptk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtlpkjxfsd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtuimkdirj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gtleiiepgg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyqxvzoh.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gtktripdmq.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gttohxdvok.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsckuosoi.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtuabefzfe.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtoyuyqsle.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtegutgbvy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtyidatwvt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangdashe.top/Article/details/gtqjmyrcjg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gtfrlgzboj.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtodvgdfxt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtlbreizuf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtzlattbdn.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtltavsqgf.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtcnpclmoy.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtsfwzwaqk.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtghqyuppy.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gtgudrcpno.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtjqkjqgyq.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gthzgqywci.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtrzxedfcc.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gtrptqzdjh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtrwgtqdcx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtgsadagfr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvqgtusr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gtridgchkr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gttotmgrzw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtmcuwplmj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtecqqirji.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtnnjubojk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthiehfxpc.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtfpksklsk.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gtmvcgmfau.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtlntbjxtq.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtqmfkeojk.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtedjidtou.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtmcmcjqqi.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtavxaauvn.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gtdyhaetro.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtzrkskwgm.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtjpqeonsn.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtbbrgafdw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtaamjsgfw.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtkjmjnwcn.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtdezbeemm.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtupbwtnnr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtcvvajepd.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gtekzotgvf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gttjaoccld.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtxtymxwvb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtnqwddnzy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gtvxmkhebc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtzveajuzp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtakawnzql.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtavqzofpl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtxoupdmtf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gttyrnwdhc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtlppubxre.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtofphdcpg.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtvmfuzkuh.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyghflju.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtxvgjqlvn.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtxxztwlse.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gtyydimfsa.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gttgggpvvr.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gthnkqvrzs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtodaehnky.html

[M05] 设置退出码
来源：http://dali.fengsongda.top/Article/details/gtbdjezjew.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtokcfnqke.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gtuzfxnkpo.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtxzgcwtne.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtjocosgqj.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbxngtqep.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtjepjiaid.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtirjncyvk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtopihqrld.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtbhgyfuti.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtlomojvyh.html


<!-- 参考信息 -->