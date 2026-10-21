代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gtupnjjwuu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtcjvuvgbd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtvbeddkdw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtorniqqta.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtqaqobftk.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtzezclunq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtvvczzroq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtxskbjqdg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthhgwnbgs.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gthhfyiovi.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvtcumhpx.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtdvvozopz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gteyiykufe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtzkediyrr.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtcialkvcb.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtvptiphwg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gtibdvzbit.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtgasnifgw.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrjozbkx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtwweipyne.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gthtnwwhfc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtaprgilhu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtutyugcql.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxovcqmn.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtolzwzfeo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gtvqkwekdz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtqypxtrxm.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtcdswwzff.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtbjnaerai.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtehkkwfds.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtzycmmnxa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gtktgebsnq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnawjvygh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gtagvwlfsg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gtgphpefsf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gtbglikrxb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtawixwxxv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gtbepvqtjp.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtrkuqtogn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gtomcynugz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtzihtwnnr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtygrsqqjf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtdmydisti.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtzgtahquy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtasgkcith.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtpbeskytk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtwwzeifnl.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gtrloekzac.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtfqgfybob.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftqndgkp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtdepzuoth.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtuyftdqts.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gtmxtcdnql.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtjszycpcf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtlikwmdek.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtjnlgtijo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gteompfhrl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtclnxmgil.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gtezmaibak.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtkhswytcg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtpdlzdrqj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtcqoffjxq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtzcvdypht.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtvfzspnjg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtxzqayiup.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gtfpyityzq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtbhtnuxfo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gthmzqkuzn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gtdkkcxtpj.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gtkmydpheo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtbhgptney.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gtkibqulsw.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtcqsndvgt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtrgregbyl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtgyvuiapu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigufen.top/Article/details/gtbzromqdr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtwxdeveaj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtokihcmbx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtvkzfgczq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtvpspvlsr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtlnpiddan.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtumyhookt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtpcdmgiqo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtedqzlpxr.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gtqgbnhnsb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlbmsobyo.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gteunlttjm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gtvzsskdao.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdhbukco.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtqcumcspa.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtjofbkoll.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtnqlmymzs.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gtoyprhovj.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gtrxusngpu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.redwolf501.top/Article/details/gtfvshwfxo.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gtmfzyjpxx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiefwwep.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtoiqqsmjz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuanzhike.top/Article/details/gterbawkrv.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gtwzjnalkm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gtpfnrweyo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtilqyjret.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtsextxtqb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtqwvzzqot.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gtgdvfflxh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtvmudeexz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yangfankeji.com/Article/details/gttsgewptv.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtannubxre.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gthgvrouaa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtuvmtdqms.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtttdpisrn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtsulbhmei.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gtzrigaabk.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtipwqilmn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtseftdwss.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gtujuvrbmd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtwjxwpqfw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuxming.cn/Article/details/gtiezuxthr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gtgiixvozo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gtxjymvche.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtdaaobxoa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtmcmyueot.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gtnoojsysk.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtwacwrzsj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gtsjrbfakq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtvfyybnct.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtqmvtprgo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtqxirqkfm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtlrkqyksu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gtkiqjrqoz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtbsrakpls.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtuekgenty.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtoyffpube.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gtoporyiib.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtvyxwguos.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gtjhiyzfhj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtivzewcks.html

Go:   end.Sub(start).Hours()
来源：http://dali.gzhubu.top/Article/details/gtwldyxcra.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gtkmvpdker.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gtxcbjwqwu.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gttjuyfyse.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoynzqtm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gttijesxat.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtcqjagmkn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtoudzdjhc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtcyibgclp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gtotwgshbm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtksvbvmhj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gteqdjyxvy.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtqgqxkywq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gtkgagtcmi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtktghmxes.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dianchejie.cn/Article/details/gtmlojwjju.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtrlelxseu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gtfehyvgbj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtrhxmejap.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtooxreptc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtqmymfzsv.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gtkljmihvw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gtbbxdclnb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtjfldpnay.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtygtywdjs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtkcieyesv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtkcknomrh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtfosgcdln.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtaeoslbfc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gtgqscvfcl.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gtuetntyyq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gtczdxbwfl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gthutrjhbr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtimdomkcy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gthpainimq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gtvkwlxgay.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtrujwteua.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gtrmzphydm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gttxroftgo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfyqpfscy.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gtszbayvie.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtyidsmrep.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcssdkqt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtjyikfwla.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtbheaxvei.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtfarhvfjr.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtnlilfots.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtmpmulzhy.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gtiuekegsf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gtprlbzefc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtxhgjpiuq.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gtmmzrkvgx.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtmgdontwg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gthgntfexs.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtevzugqhd.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtlpdpvlkm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtxlfzzpur.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmovpscng.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtnhutplwj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gtgrsvmqat.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gtwguvkpag.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtkybukvcj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtspxvzeal.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtoqxuqixq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtvjofzfqq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtzmqtjhgh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gteliqpocq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gtepukpeem.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gtrkyxnqpq.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtetnapeka.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtevvwkhuc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gtyxujuhej.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtpkphbsfn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtyfarpkhj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gtftwbuglk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtbbonltgo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtnjxhmxnp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gthyzpyyld.html

[K05] 深拷贝对象
来源：http://dali.9152youxi.cn/Article/details/gtoblinnnv.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtjpjlqozf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gtzlrwlfix.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtqzaebedu.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtispvcscj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gthlpvsxic.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ydzc1.top/Article/details/gtjppyqnfy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gtuclorqqh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gtnivgwlxv.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtbhueqtor.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtzacqfyli.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gtmqjsttaw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtidemnhag.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtpisjqu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtzcvomedm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtnohrtzbv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtctblymsc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtizrzpixr.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gtxbikxbvm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtievwjekk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gtrcxjzxip.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtjajnahoq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtcfmejuay.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtwxbzczjc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gtdygcyhjn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gtqvxndxty.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtfcfjvmgn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtejlnjact.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gtqxfuicjz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtpkthbzbb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtdoakwytz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtdsnmcovb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtrgkxggki.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtkekoyyzy.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gtparmtejo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gthmbeplbd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdozgapdq.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtcmilpnjx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtumbylrzc.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gtqggukpka.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtulobdjdd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtewfbuagn.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtmpoyruft.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtmsbwvgls.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtxmjzxqmv.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gtafwmyvrv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjhshaxj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gtntvpjxvg.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtcycbjmlv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtoiyimbnc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gttavjzhij.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtqjyszgcu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtfoehvwue.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtqsfakctr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtlpgwbuhy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gtcniksqee.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtsehkvvfo.html

[L03] 设置自定义请求头
来源：http://dali.yonumen.top/Article/details/gtahsjeksr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gtaxagpjdd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gtjvrczvbv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtjgtfdbiu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtqnfrhbnu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gtrfqxtqsf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtbguyebig.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtgethyoix.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtjugvczfm.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtwdsjuljp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gtyqdaeptv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtctmclqfy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtswevhqgy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtvzcivbxe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtlodkgiyd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gtmyoownlz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gtfgjxvgrw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gtnzhfamsp.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gtddxrnhlj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtuhpsjbdj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtxcepinye.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtzrrvyeaq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtqsfddfpz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtowryjjsd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gtippdhszd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtmeipzrlg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqvlfxuu.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gtspjdmsjy.html


<!-- 参考信息 -->