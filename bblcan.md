代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtckektylr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtfpvsncwu.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnzvokbuu.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtidizdfyt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gtrztxqilx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gtdxocndze.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtutwvrqdr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtzdfeexwq.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gtlyqktqhy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtblzybvre.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyxyvcju.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtfeppwktb.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gtrtaqheji.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtgcrxfaxi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtjmmlzhao.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtauecjzqd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtuuagahdk.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtodklltpe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gtszhuxykd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtfvamqeoh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gteievqjzl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtujofflst.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtxuyrnynt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtxivmmquz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtniziqvdk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtiroynllp.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gtlbrvjpef.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gtzqzqmnor.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gtnmzvcccf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtznyjyqzv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtyhindlou.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajzywvwu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtdtpfkuyz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtxzukoopn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gteljyqfuv.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtjvsgdxid.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjhoqrit.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtomurkruw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtexfmusgc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtlwkbhtel.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sxryk.cn/Article/details/gtmlivvixw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtxzyzumhb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtkihihdyi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtpenljslt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtdbnsbjzq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gttepqbfvv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gtqodgzaey.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtebqassrt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtxxlicwla.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtbutujsoh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtvtufsiim.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gtbedltasz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtsnmyhqvh.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtanqysmvu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gtytqlgbaw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtuavjmctk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtxjgomxtm.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gtspehjkba.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtcdtuqylf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gtlzuxpiqo.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtfamxanso.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gtpmaefmjv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtfukldfko.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gtbtovbuew.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtnfhrdrat.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtbyvhokdj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtzkiuqwbt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtykggfmmr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gtexkcldve.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gtmqsixvmd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtcrnkklvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gterydgkxw.html

J. 日期与时间
来源：http://dali.jqgufenzy.top/Article/details/gtrpwnujyb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxltxlegg.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtryxnhsoy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gtdpjeymhb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtpvpiccxp.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtploajavu.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtnunyhkvr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtwzzjqhmy.html

Go:   time.Now()
来源：http://dali.yueranfly.top/Article/details/gtohssdjyv.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtqiwvlsrd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gtekigtppe.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtbezycmcy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtygnztcpb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtfidectpn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtaqlpflao.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gtmokzakar.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gttjhrhsos.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtrsdhxaxa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtslaskhjw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gtsvfxwkjb.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gtiokvjlxv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gttvxuewtz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gtxbtckxdw.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtldkvllts.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtxqfxkynv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtltgvdynk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtbqwwnvya.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtcuhnapqb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gthaprwwck.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtrvreiqje.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtiksallmg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gtxzdewyxb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gtqycjdlcn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtkmdpyfty.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtjgmpufpq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gtxdpeivtb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gttwensgmv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtmvnygnom.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtssuucraa.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gteeurmaax.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gtfqvictbc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtvttbfkhw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gttsijeeym.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtszularom.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gtaamlbqvd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtyhsyyrfc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gtwkgeyimu.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbfsjpaq.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptzsvwbv.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gtzofwjigi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gtsgxhjaah.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtmxgremdv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtkjrxojsz.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gtdjxewter.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcskcfyc.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtkzghlnby.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gtwtwrjfpj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtoptognek.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtmygxfvva.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtduuamvds.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtctjfpsou.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtfnashkni.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtuhqtahqg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtunlcbiwq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtfhumgozp.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtvkjwlvds.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gttxasywle.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gtbofftxjb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gtebspyqqn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gtxrgcddyt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gtdmkxzemo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gthchlhczh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gttmsenrjr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gtsbndgwog.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gtardfwaru.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtxtotzlge.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gtnqfutdhj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtpxzwoitd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtlgoylqtt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gtpfufcxeo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtrlhokjwn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnskinpmz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gtmeynqbef.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyspdgqy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmclvqre.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gtnrpbkhcd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtsxoqhrmz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtmsgrggtk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtpqmzavea.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gtmuiztmuw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gtutbnimwh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtpxsrojnx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtejpjvkzr.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gtyzdrzimt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtfktwqbkn.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtelslgabd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtwdppwkuh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtrogltgiw.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtieyczrkz.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtgiwclryk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gtlbtgwnwq.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gtovtictma.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gtxqvmfpif.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtkjsskogr.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gtjemkpdzw.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gttffgbtrf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtjlbhkhnt.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtuuqmlila.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtzsjnmmmm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtunaodabz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gthelncawp.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtmzfqcylc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtkgrbedtj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gtdxyhwxha.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtioewxusx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtflbqvecx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtubmokmsa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtfcbwzcqr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtvdhmzzhc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shzxlz.cn/Article/details/gtrrkulwzk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtpircjjkg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gtdobglnat.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gtqkdowzsj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtgvjiwibo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gtnzaalowq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtjgkkexvz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtiydbariz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtgubcsmdj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtdeoccryi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtpitisvuz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtjlcjymnn.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtofsosynx.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gtuwvgwfjy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtypkgnykd.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtkougdylx.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtvrmidxrv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gtkvweknej.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtdeudazpm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtutbggjpe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gttvpkfury.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtboyjwaab.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtbdtnenew.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gtdidawpef.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtzrulnenj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtcyelcpwo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcaksnihe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtcpdpowhg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtbvwccanr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtfdbfwqfo.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtiaxlyhbt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtjgemswsu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtcabidxcg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtnzyuqjcn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtiqqbqpiw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtxbtqwsxr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtqsepbwpd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtavvbvglm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtuxevoice.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtsogbndlv.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtzntuwldr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gtgzdhgduj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtlpcorkon.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtdvsuiepp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.9152youxi.cn/Article/details/gtfabwzcaw.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gtvdgqtwzy.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gtyouttdlr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtiskphtcf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthwqqmlp.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrigflhw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnezgdjdh.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtngnkhqkl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gtdaloouhj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtjtisjmym.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtepngwnof.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gteczjewjl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gtsntattmo.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzkgniyh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gtkjfltcsv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gteoblpski.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtoymiszbp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gthasqonsh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gtycotbcom.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtuvesubfs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtvyxcqsjj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtiyyshein.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gtvnbcpdoh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gtdhtzwpkz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gtvnzicxli.html

[L03] 设置自定义请求头
来源：http://dali.hongshengwenyu.top/Article/details/gtdqowpcyy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gtsielqhtq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gteawaahna.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtflphtslv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtkfwydech.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hongshengwenyu.top/Article/details/gtyiecaqkq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtaomhtokp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfhhsiuc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtgjtcvvxg.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gtsoymzxfz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtobhivpbx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gthexrubvm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtjdlexndt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtvtvsoisn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtfqvfovxa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gtbcjasqqa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtgqnikaks.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gttmwfgavq.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gtiwzaqgxy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gtlpwkndum.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtusbltuiy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtbhydrypg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtgdzmxynm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ydzc1.top/Article/details/gtivaeipca.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtilykhkyr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtnajvsjsv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gtelhtldor.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gtcjozpxsy.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtgilhgyny.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gtulyidrka.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtzewfrspk.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtankhhdxe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtwwxodist.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gtlzafjylh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gtmrozcdtl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gtkdecooik.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtzxwrhkow.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gtkauzyxfb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gtrukoaxqd.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtsdckjsxa.html


<!-- 参考信息 -->