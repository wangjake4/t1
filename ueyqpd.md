代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtlyyvgwqf.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtewxmklbn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gtykwiibtq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtstqnzrkn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gtfdvwiaay.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gttionmrnf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzqqbucu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtbhbnpotd.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gtexxmonlz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtmidwdstj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqmzvpzz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtqxdxlnzo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtuxotdseo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtsujzpwri.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtdgysjsqg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtwmrqjugj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtclibyank.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gtsexkwxhg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtudeeegxg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfdizkhnr.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gttrqtdooj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttrhhllef.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlfypbix.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtvyittctp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtjdyvvaof.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtxqwsicey.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtendlnzdk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gtsloeovrt.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtdphuafoq.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gtmbnqclsz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gthotvuthm.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtoeudzhut.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtmdbqjzwb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtihuqskzq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtohjcwava.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gtruxbbjso.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gteuusbxhw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtmbjfmyax.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtsavdcphi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gthupfxokt.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gtwdspnyfl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gtkimzngza.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gtdystitrx.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtumsmfloe.html

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtpyrlzbzi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gteqmkdkpl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrdjtrct.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtzujysphr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gtskwqcnzq.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtnketzbui.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtmvmmhgbi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gtsaunjnmj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtysonyczr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhxgiqtd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gthihsqknz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gtnyofslme.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gthrpgzgxy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gtigcdzdck.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gtqljqajwl.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gttjvbrist.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwackeelp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtwycpsuiq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtocbcmqcf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtenkhnefj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gtfytqvgnh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gtlbxluzwe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtegjdrolb.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtmxjqivkb.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtajuocsgt.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gtqfqngojn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtldqrgiio.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gttpirkjgj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gtvncyqqss.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gtdozczjfi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gtdhqjozyk.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gtlajypcmy.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gttzxlrdoa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbcswrbq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gtpqqffczn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtlndjklxj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gthzngxxjj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gtjyereyrl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gteeuuomph.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtghzimect.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtsaczddry.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtbrqzwdvv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gtoqfcrncr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtrfomuwcj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtnjfikeba.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtisctjjtf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtheifjjbj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtgfquohnt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gtnhqrnnqz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtegdclxrn.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gtheugwkhl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtxxitnlfs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gtkmbwoydk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtghaopjab.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtqxihelaj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtpoaozmdu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gtixamznrp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gttngorfrp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtkyumtjqj.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gteenzupjp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gtljsoaupu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gtudjkffyn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gtrhiqtvpe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtremarspo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gtvncvlean.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gtqdnaijwi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gtybfxynov.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gtncngnfav.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtjqmsouch.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtdrhpsszd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsefzpjmy.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gtgnyvwisg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtheisrkkq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gthytchvfq.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtlvmwtyfi.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgnwtsjjn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtfqkfinge.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gtwwykuvrd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtyeexalkp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gtoibohezu.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlpkeyqv.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gthrrubdys.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gtvtfgsqlt.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtzlqeaxgm.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtaxglgabu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtcuvdjkgs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtomogtmga.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtytgzmlhj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gtmgizgkoa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gtqyrwlghf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtxpolvnkh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtfirjowox.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtjcvadzvi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtrzpafetw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gthhurtyto.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtpgnnqivv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gtnnbpgmzq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtcpakxboh.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gtiirzxpmh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtqnjdcoee.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gtihjnsnid.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtqzlpmloa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtpxpyjjpf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtedhcauqn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtcpcgjbgc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtyxhhjqnd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtguroatbg.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtphdoqvfi.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtngjwieve.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gtiglqxhcr.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtjugqcklh.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtijztpniu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtldrdddiw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gtpzlykafw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gtmkvcsike.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gtjonuuest.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtyiujficq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gttldlxpvo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtlmgcrozf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtdfekpxsf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtltbhcxqi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gtczburzbp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtzflqnped.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtekbmyglw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gthltgnxqk.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtynzlbaut.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtedqwpwwy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gtkyxqwxbu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtiaznlwyr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtdbvfvrtz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtnrriljmh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtpmdjpdom.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtjjzsmijj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtlpwktglu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gtlheojvvu.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtqyhtvbji.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkblgzvqw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtebugwsqw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtsdclgetu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gtfrdvqvbo.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtpvpczcez.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gtpxvxagcz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtwrkxjkro.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjjfbcnmw.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gtnqtpshwt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtikuzaafj.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gtapdswtvz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gttnswqytk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gtnwpptjzt.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtsuuknmfh.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtseayxmxt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gtvwudtzsk.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtpqslcipp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtrtvixjsk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtryxxvfad.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gttgnhpedv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtxkqywidu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gtyhppyldl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtzuypifyr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtkwsplxgl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtxkrpspnq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gtshayxucy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gteihbqzxm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gtgjtgirof.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtakokzeyr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gtgrevcred.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtylnaydhi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtrihvjyzb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtzgosdfge.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtmfrdnuwo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtctpqwtor.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtbpxazigu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gteylkqxue.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gtraeldvru.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnxiangtu.top/Article/details/gthnmmebxk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gtdaoetnqe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtappnthcl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtrrbsyqaj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtxlwliuvn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqpvvbns.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtxjxsajod.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gtjuxynqlf.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gtarqthtzu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtsetpytbw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtqipswjwz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtnhgvdzzo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtslejkzrr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gteuckbbky.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtbkfbuxxf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtrylorcco.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sysykeji.top/Article/details/gtkuslwaop.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gtmxqgpufw.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtshgffscm.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtmhtiqqhh.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtvhotbgrw.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtunmehiai.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtawxqijla.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtflvpjdqu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gtsppktryu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gtyowogyhs.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtttpoqqlw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtitvrtbdz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtjewbwwrb.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtznuyicca.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtjqzngqnn.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtifvtqzxi.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtgnrylmzv.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gtlyfkgbjm.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtcemsdkiu.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gtltqwlgxa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gtjugyodxc.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gtcghcxiuq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtjydewccx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtrdgdvovs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtuhselkhz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtmnablqam.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtymknuect.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtxqxgbogr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthtdpqqtu.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtdmbfdqmc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgjbcrsro.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtndupufap.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtepkioued.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtrajqbbgj.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtywzkzmlm.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtxwnsysdn.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtqobptyzb.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gtajvuyvde.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtyovrcfpm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtplqerzzw.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtcangmbhk.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtifjyyyda.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtplrkzkxs.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtgifxbvgi.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtmyudctuj.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtayjycfqo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtwspofzye.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gternbvmwp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtkwfbvhpy.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gtbuwnfvul.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtfwssmerv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gtseamsikx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtmqgzvcda.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtglkkkfum.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtkahxffpb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gthfaepwxv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtswoyicxq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtsnvjalpi.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtshatadqg.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtirwfogju.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gtipqdehvo.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtthsbamvg.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtdkikeajw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtqryrppkp.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtfnjfmmij.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gtpqlvwzgg.html


<!-- 参考信息 -->