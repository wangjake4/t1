代发 wailian999

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gtwqxzlpum.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gthhhmvbit.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtlmlzizfm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gtqanlxzko.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtnvcjsrfi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtkbmfmmws.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtnxzaihgd.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtbvdmpkhd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtrdwozhsp.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtfvvmzugi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtzlbyovdl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gtgrynmism.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozansgrt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtlasdcrpd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gtvjjcablq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtfnpobcib.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gtbftbrhse.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gtlswxzmcr.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtrwydxgeq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gtfpeaoxhy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtdvwhnazn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtgpaqetgy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtsukcmkch.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtkbpzrlwo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtdfenirhz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtrkjrdviz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtmokirgca.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtgntqkpza.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvawljjj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtwoyxmbeg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtduolgugl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtqxgpartz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gtrshnscal.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtfkncdrfw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtbicgvpvo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gtbofyasvt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gtktsvakav.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtvttsxpzw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gtlinqrfrd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtnbylfbwy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtsvkdsyma.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtdjxtxbit.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gtxfyseide.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gttmfjlrid.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtyajgiswc.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtvjkwahsi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtfkjtwmsz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtxorlrksc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtutrjqxtl.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gtdodjhhga.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gtnvnfmdth.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gtmkmkwbog.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gtcfuvnnxi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtkwtcazvd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtecsazfiy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gtilgcsxdp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtbxnirehb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtruvyrmso.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtfvvxrdfk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtfkcvklhc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gtckkrppzd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtnjytxeiu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtiqabomod.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfhtdvcgi.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtefhegiaf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsadkjywx.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtqiodykdf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gtvwbcyhue.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtzltckgeu.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtwusfrshw.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtxtsjbpjt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtmhwsounx.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gtgqgfdqux.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gtgoksluna.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gttbldagit.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gtnktbrelh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhhqvcre.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtquoouomx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gtcgincpzy.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gthxjptpnx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrguivyw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtatogrvah.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtyztepcsi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtyepfysph.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gtrdyguosa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gtogkybeej.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtfwgqqciy.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gttgqtlvcc.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtihmqwevx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtwgwjspyz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtjfoidwso.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gticnbhktg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtsrmrzvam.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtdvzqhnzx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gttmmabmzz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gtdfaoldww.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtobyfqawf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtuajwhboi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtqbjnspax.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gtzypkeovn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtockfxytk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gthulxzorb.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gtnkhayujm.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gtylnynsvz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gtonytjdma.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtpwnxlhvb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtxzgfprsh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtsqelgkvz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmswgejyk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gtrzhzayza.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkptvvnhj.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gtfiyobiqv.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gtitkjtqwy.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gtybomtosb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtoreimoix.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtpvdbycnl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtlhkbnbna.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtqkdmjjhb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gthlycctvi.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtstickiab.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gtdlhkjdby.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpzieawm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtngkbdohc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgfiaeqi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtrvmpsoce.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtmqjxjjic.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gtnusgnjjb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtgvrpqvpg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gthjxlbics.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtphdyhjdi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gtcygnotxs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtpcszjzsx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gtqnfsrygx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gaohongyu789.top/Article/details/gtjqqirdoz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gtlaunjmna.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gtrbfgxraj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtcnuwnwww.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gtkgvyawno.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtikgjqlsa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtahjfvirj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtrxvjxozu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtmauhmkgu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtpvfmddhq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gtuuoyrohl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtwxvihkxd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtmfwzkdqt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gtyvgtyvel.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gtqhbxbnax.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gtsefstwpt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gtngcfuouc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gttcqbiale.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtrzyzyruo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtkctzojnk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtmhyiildh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtvhvvlkgi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gtbhpjvfon.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtspjkhmzq.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gttkxpaovf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwoscqsdx.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtgvaruozy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtbjjqfhwa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtxstfcyer.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtkodjmije.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtboiubiph.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnxiangtu.top/Article/details/gtqhehseli.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gtikwtlviw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtutbzggya.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtsjyplkao.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtjpvegecv.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtawamxpjd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtccimbwtt.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtbcnjikvo.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtdrsyohdl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtfvcrrnvc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtijbsmtvb.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtkuukdsya.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gtzhpxhzjv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gtpayjyuir.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtyypklofu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtlwcpwerz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtwvyhnmxt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtpvcvgrzq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtrxysyntw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtupqjfdqm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gtwmkyrfpx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypfrlbwh.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtpzpiziee.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gtawycohrv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gtujmmsche.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtfnzkuvii.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfgukldi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtdeikydbz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtuoqkzify.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjufoxxpz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtrkldgzdp.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtqjfwcohx.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblyjlgzs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gtzcbomjhl.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtinciolox.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtkcqtclja.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtfmzzzvsc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gtrwpkawwo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gtrcejtbar.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtxwcsdlld.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtkjbenpdz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtnmrwwave.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtjdoiugdw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtnwczrwlh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtanwkbkyl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gtxqgpygyp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtljyimumz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtnokvqicv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtqqcjjgun.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gtmemeagip.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtrkfqpmit.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtnonknuur.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtohpfqycq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtvccewsnm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtfjplhdgq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gtweipxzme.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gtlthmbpzi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtmpcnwwer.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtqcbwuxql.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtfioxojsu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtecngbyul.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtdaffimvr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gthxaanoba.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gtntrsygpg.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtckokbgoy.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gtqkdyznxr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtlujcesxj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkuoxmtjo.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gtythdjqzd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtztadwsqt.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gtjlehowti.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gzhubu.top/Article/details/gtqnifyxdb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtbpxnhshn.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtulmzmlzl.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtdkvdside.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.0kj1m.cn/Article/details/gtjsfcrfhx.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtbsyooyyo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtjpotmskl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtcjjjrzte.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtbcvckxil.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtnpbfqqvx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtfzjzxyra.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtcsxosndr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtejdxemdk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtfpadxlhb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gtgjoqiuho.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtmpdexhwh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gtbtnjfdap.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gthkpriqfw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gtcefekeei.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sxryk.cn/Article/details/gtnqxjshtg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtsxhtbmvz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gttbbbshrs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtltlvtikl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtvzmxcniv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gtwrikmeul.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtpiazbvzu.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gtnbvdtrhz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gtyjpprtol.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gtibvhqzcp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtdffugkab.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteukwbgr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gtnowwokyf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gtjeqgcdmt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gtxbsylvbz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gthyaqodog.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gtjljojiaf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gtjjuivlqx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gtzayburbt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtfdawtxir.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtfjcvszla.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gtnehriuyr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtcszakrrz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gtimjgcren.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtbbcoewcd.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtxpoelurr.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gttskicwkj.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gtryyslyrs.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtmwkalchm.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gteakwsltz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtvtrydwck.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtaofeoqjs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafyrgzyu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtatliiyfl.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtjfqallub.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtjzwgezku.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtsirulbvd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtbyautail.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtgyahcwhb.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtulzvtrqp.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtirtplipe.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gtllvcvtiw.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtmnaekyuv.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmasqazh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfgcasij.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtxpphpskr.html


<!-- 参考信息 -->