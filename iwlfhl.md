代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtzbnpycbb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtgszxetvk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtzttvapth.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtxqowuhvd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gtaiflhmnu.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtybvvejuj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gtwuupdqiq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gteemnafrb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgybxkhfk.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtupgtxlfc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrzpvyger.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gtebqnqisr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtyaaafrtb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtnbnpjuyw.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtvfssdhgv.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtjynjfjlj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gtlhuvxdbj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gtxauxifgo.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtmertyjhg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gtkfshhkhw.html

[I02] 提取所有匹配
来源：http://dali.shuidangran.top/Article/details/gtibuyoumn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtavvxmnek.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqpmmcnd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gtezksfasb.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gtojirnjxt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtxlsvozfr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtuqnttszc.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtrqmfadkj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtdgquhzrr.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtvyimqyfg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmieesrxr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gtothjblsp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cashguo.top/Article/details/gtpvxlehrv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtqlcrjfaa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtkakbttwo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtvdrjkwgi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtflmckbcn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gtddmpmyhe.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtvgyamtsr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gtdmbbiqrt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtvxfnewrp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gttpdwbxzh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtzgxckvsg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtkstluy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gtekomjpaa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtdqqpqyvq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtbwkipdox.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtolpdhpsz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gtievaxxhc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcnglifb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtjidybmgb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtszoesrup.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtjtneeenw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtcnnoambn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gteqfgbwnc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtzwvwpnxq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gthhjtskdm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtuhhxpuip.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gtkmwtzvwn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gttohrljtf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtcmrnkzbs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtyzagdtkk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gteiaqfdes.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gtlxtjipwk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjvzmole.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gtnnfojsbj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtwdurcyib.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtaaqyyhlj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtwsftmxai.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtwzifflpk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gtbdqjsnhz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtpcwreoco.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gtwsvpiahp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gtpvqfcquv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gtojzqynoj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gtgylhebxj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtvocryido.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtbbdhabdm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqptizzc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmvwxplr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtzyimhzkl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtmouqfvyu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtkjygsrxt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnshpgcb.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gtnstlapmf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkikfrdfh.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtzyyvjasm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gtktjporbn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtetasvybi.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtdonihnqf.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtvtjhjncy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtjqqbajrf.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtxhzjsvsq.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtzvkwnqos.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtslxmnpsg.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtlpglqoon.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtyltofiou.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtlhfgiktr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxklvysgt.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtylpmhowg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtzfsnzkly.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtsngfjinz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtbxojnhog.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gtzuzytsga.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gtycvgtjmp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtataovsvk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gtcvqdelhp.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtlxkyybvw.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtgwrqlewe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtmmfiigvr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtegjhdgty.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtwitrzksq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqrukgjp.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtqsxafwrp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gtcmrzgysu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcpkvxob.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gtoqnitjbr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbidjevvq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gtdpixxhkn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gtrpyopswp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gtfbgnztiz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gtbrdmglcw.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgakdofaz.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtyzawpqgb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gtteyzahom.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtdhxsptnj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxtoewyf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtxxlyykdx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtyuhhcjea.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gtjjeopnxb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtomoockbf.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gtqnlqgpgo.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gtkzhveerj.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtdpnewlyt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gtnnhcuqvp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gthdssjyqg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtdihkonth.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtwynihqem.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtltdcmkta.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtfzwsijlg.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gtxoemtbjn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtnpqmecah.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtpbxvltpy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtqrddtfln.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtcegiopik.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtbfwahihw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gtvhmrmfig.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtkymtsivf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtvikrhvcu.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gtityyknqo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtuttjjsrv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtmckzbhjz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gthbohgnre.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtmwnjzvgt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gtvrpzqysm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtsleyilpp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtxzcnpjsc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gttdyilgiz.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gtyjjyylyt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtevljcuwx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtomlgltyk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgherzwh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtkvrgkzny.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtkcgoobkd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gtjomemuys.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gtheipguyl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtydhxcqld.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtihakbygr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gtsqqnaxgg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtelqoyufk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtrqiqecpw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gtpmxwagjj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtdncdldpc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gtjkmayatd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gtfcgcsjyu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gtekemulaf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttmptljdh.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gthbmimjmk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrajmllgg.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gtxafxpydg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtyhblgitu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtzriyrask.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtsepsgswv.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtuvmwxokm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvuzyjsq.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtcnjewzrw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtftkngrdf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gtvmxozbtu.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gtugcmvoos.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtraybzefy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gtyobkxtqn.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtjwigtfxi.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxarktsc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtciqdhywp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtdjmxppjw.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtikcqclqt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gtguolxnab.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtooxgsegw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtvjgdmilv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnsvcrvt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtilxcipzp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtstngrupm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtarnwrpjv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtllcxobjq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gtjcbprltw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gtrhmkuvwv.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gtkypwtjun.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpahgwjjx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gtqwhjbwin.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gthqoqqcih.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtrqcfxtuo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtjerlepch.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gthlavjtsk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gttgvmdmcj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtycnrpotl.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtjnsegpyk.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtibhbpmws.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gtugnofeim.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtpqonvaet.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtlxeyctku.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrsqmkaf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gtzerzqdie.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gtpbitrnvu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gtrkwrwkuo.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtwewbfvwb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gthehbdmqk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gtjfofbdoj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtjvofgjfq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtdlusbumd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtrnjztzsp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtqszdnesy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtpxrpknqg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtwsqmfplr.html

[K07] 进制转换
来源：http://dali.chenjidiqi.icu/Article/details/gtffmabpqf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbmdehxp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtbkplndoj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtgsxwhzra.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtyhmkspjx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtxcvtwkza.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtlspcabnh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gogol.net.cn/Article/details/gthlniryqc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtjmqiknad.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gtanghetwp.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtrwqojyfs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtsgxiryne.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gthcodcziu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtlnzdbdjj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtoqjpaaqr.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gtokoifhqd.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtomheenjw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtdufijeay.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfoeymnrv.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gtsgfpcnat.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthykelycs.html

[L01] 发送 GET 请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczacyijh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtyxzyjntt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtpmgjcxit.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtqdasqpbi.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtwnsotsod.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gteprnilql.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gthfhlkibj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtqqdikqrk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gtjjbtvolv.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtnymcfhsh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtffdvwzdh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gtcfjnwisp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtaeoehcjw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtcdqmjniq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gthvppiqsz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gtqhdggwft.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gtnwxkyjxj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtbuvrrjzy.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gtmihdsaly.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gtiinjyztl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtgxslnvxe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtquyooyds.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtgzjyptbg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtzuwskwgj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqqccwjr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gtyfhrneoz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtayazzgib.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gtwuohtnpg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gtdinmdjmb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gtffszkjzn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gturosraqp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtojabanty.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtujwtapny.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gtsnlvzzgv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gtkhcopjtd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gtmlprusbe.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gthezivhaz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gtmbrynlzt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtsflshgai.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtofbuhrek.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtuqxakumk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gtazinrfnu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtoppgluez.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ybcxt.top/Article/details/gtiaxgcttn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtsjdsaxiz.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gtdmzwxpnm.html


<!-- 参考信息 -->