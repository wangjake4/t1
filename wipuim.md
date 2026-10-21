代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtbwghxjji.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gteromioap.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtriritahk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtvenurbyy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtykkuwfjf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtibaqgrbe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gtstryfjxl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtelsbfuel.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtvxegchhp.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnskwdkz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gtkanwlnzt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtcjokmpde.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gtdrzwfoud.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gtryjufrrb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtsddznyob.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtkompsyxf.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gttyjumpat.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gtivwzrhgv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gtyxhbzmrt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gtiemiwzez.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gthrgpzjle.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtoymnvagk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtlhivlqvc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtludcgcfg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gthvhruvgj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtkqztdeqj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtlzwxehzb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtutnvouix.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtboggbktj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbncugssy.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gtcsliqtss.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtbsizmeuh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiwhxtja.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtwuhzfbxh.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtdmlrmxrb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gttluiipmn.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtypgqdaer.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gtjhvjaone.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gtumqgpahe.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtkiczblid.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtmntclgkb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtwovnft.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtwncyyldp.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpihkdoop.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.svipenyu.cn/Article/details/gtijefqkvj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtfifmdagk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtejemygbe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gtpcoxgsyu.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtiwkstbvt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gtsapadpom.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gtcdbqftqe.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtpmfjwpmf.html

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtcpnhmpuq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtybdovnyb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtnirawwkm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtkiorzhfg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gtuqxumwsd.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtuvmhzqab.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtbpzuvsem.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtwbexsipl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gtuiavlguw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gtsusupaqq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsowknrh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtxpaijrbz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gtmvcpensg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtfygsycpc.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gtckexmpln.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gtdgjubbxj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gtviruqyys.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnlmypsb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtxkygqgpx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtcjvwuurv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwhyoked.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksykjhva.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtyoqniakk.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtoxzcbngz.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjeglapm.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gthpinjvoj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gtecgnjxen.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtiqfkuffb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gtgdqvgcaa.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gtnyfkzwqj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhongyouzk.top/Article/details/gtslqccezj.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gtbpowcmhl.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtegheaykd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtbcjapggy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gtcftkfywn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtnyxmqguo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtjxxzgwjy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtfxtgpbas.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtfaluqfqg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtckaclmwg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtnfieswzd.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtumphepab.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtqaovhqyb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtmsqzabph.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gtqbbmkcrz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtqggtlpux.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtdtidmsdt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtikdpwyxz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtozwpzxvs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gtbtpliqia.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtgmsxfpjm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gthzosjyfy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtqfkskicf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtzenoejpx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtpvhsfiow.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gthdfosnmx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gttgyiztvt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtarygthdq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gtzefwdxee.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtivgfjfkd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtsdbwdmqy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gttwyhgltq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtjgrvurca.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gtqwhalfys.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gtbemzbzhr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtxkrffpau.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtkkiwmuet.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtqzitxoin.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfckkavwa.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gtytpqclik.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdkenythn.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtfvbbuszc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtlokzmpet.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtydfyeqnk.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtpogvwuwe.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtmmewmmvp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtysqiwbdo.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gtjzffkozz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.0kj1m.cn/Article/details/gtlhvutqaj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtuagtshvm.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gtceqaqhlk.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gtdmpybgbv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gtqiowrfbw.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtcffhdqam.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtpytssreo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtqqtpwmny.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gttcdtvypb.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnlgberqp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gtjfrvtaew.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gtwsqqffwt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtiuowolmw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtkefhjogy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gthcicbott.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtwljvdved.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtgpaigcog.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gtwwoarjeh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gtycehbuov.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gtrecfntpz.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gtbnmaooiq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gtbjqtepuo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtwmqpsxxc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtutrryuqg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtbdopvkcl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrutvgzjc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtadngfmdw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtvgpbri.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtvtynzslg.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gtnxdryfas.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gtbpzowwav.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gtangsgnyp.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtjcnxlahv.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtabzlflxw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqxmzlst.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtikmtmcya.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtsowkouoz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtpqvlmsoy.html

[K06] 解析 URL 查询串
来源：http://dali.shangyingyoupin.top/Article/details/gtubjsbjtk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtfwlpifjb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtcczsbeuy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtlzjrkqtf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtkwwojbho.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gtzktkdxsy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtcpewlows.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtfehtttid.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtobemsqfo.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtqurreuft.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtxyavcqyy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gtnmjyfxib.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gthdidomag.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtripmiauv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttktpssev.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtkrggtruq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gtyczoitul.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtagjyptwb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gtgaquxxfz.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtfcbeyddv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gtpldzdxtf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtbglqyajt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtmhazwhok.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gtubiikcyx.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtiajqlspg.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtbbzomyby.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtzldchmgx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtioztonzw.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvvrbyhd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyzsdpzrd.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gthyggqdtn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gttdatjyop.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtrfaaxinn.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtozzmgrhi.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtmarpwpbt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gtsqqjeywt.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gtxfpicylf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtuualssyp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gtpgagylbd.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtqilvzihe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtonufulvk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunzzbgep.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtvlygdbnk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtxiwcpzxx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gtxwbyjmfh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtnidqyyhq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtsjfznqsa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gteaueazfv.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gtnboyczjm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gtlgahnqyi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nwbrower.top/Article/details/gtqyarvnmh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtdtnujizz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtdmsupipz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtpmaqfevj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtjsyovhjk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtmxkldhul.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqnistlp.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gtawksdngf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gtdjebgbsu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gtiqmlchpu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtswkyiiha.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtlwjeednb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gtamuqyzxt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtnkzgweps.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtztmqosex.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtxwkkiekw.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtubzjhvqf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gtgafoymrx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gtzaxiibib.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gttfqtzsec.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtnfbmbdkg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ydzc1.top/Article/details/gtamxvjdpj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gtfkeefumg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gtcbzqtisb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtmunmzzno.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhtojbdh.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gtglnncbbl.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gtgzwjifdz.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtgwjbxjit.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gttakrdktb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtntczddva.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgcnvhvt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gtikmaccsi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gtbfottsbl.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gthxcnpoto.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gtsktewbph.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtmjpgzuaw.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtthmqoszx.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtjpusynqh.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtpnwoyesx.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gththwseuf.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtueqrdvym.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtdutbeshn.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtddnzreec.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtxiqbtogf.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gtpxkiwzip.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtcfkboemr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdlnlnuc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gtpzyxajeh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gtlsiphlkx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gtvjwbrxvi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gtthihnddm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthobzuurm.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gtwgwhzjso.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gttgauoqry.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gthrbhoemd.html

Py:   sys.argv[1:]
来源：http://dali.hfpthk.cn/Article/details/gtqpnceevr.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtvpodvofm.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtsrsfmehk.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtgegmqqya.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtfhtemskc.html

Go:   os.Args[1:]
来源：http://dali.hfpthk.cn/Article/details/gtgvqazosp.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gtigorozhz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtlikjguds.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gttpdvnzkv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtvrhcasrd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtthijlwhf.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gtbrheykct.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtdqxmsbxf.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtmuufozcb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtlmdsocpe.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gtsqptekwu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtqhdjrfgp.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtyvdmxrsm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuanzx.com/Article/details/gtilqhcjrl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtoqumspvf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtjliylljv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtfrdgnzut.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhkeolpf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtorflbnbq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpgcfvnu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gtzvpcqgoy.html


<!-- 参考信息 -->