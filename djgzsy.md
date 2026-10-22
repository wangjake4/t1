代发 wailian999

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2vbgrgdrz.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gt2lyqsmtdl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jnplaisi.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gt2ozbkgmcp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2pwppkzgf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2muyddbya.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikaetkec.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptdpkylh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcposoca.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gt2hkahxipk.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2odbevmas.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2tvphbvvj.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2vbsqdaqd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xctlubie.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2qdxmfkfw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gt2svliqits.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gt2wkoclxgb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gt2trgrecrm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2qglekpjn.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2axoclemp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2dyzzdfnd.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gt2xqycthwn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gt2xhorucjv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2znpefqdw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2ogjafgwq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2rzotcdki.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2msqajqjn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gt2oimhseof.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gt2gpcblint.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzgyekyc.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2fjezfmzw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gt2phlyhjag.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gt2bclyhvgo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2xqsfneis.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gt2ghempzhv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2achdjvws.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gt2mbhjwugh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tewphksq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2gegbktxx.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gt2jloavyxp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gt2dwnikknt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gt2djixvfca.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgynzphp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnzrvrff.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gt2mkjwaqis.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2qqkfbytt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zauxuvzn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gt2rivgvotx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shzxlz.cn/Article/details/gt2vopsqrnl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2hjncwsuz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gt2glhssnul.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2jiwbsiys.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2drkhxdst.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yldbbskl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gt2wajvtcxw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gt2yyxglkdn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2lhhvjtco.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gt2fxohocjq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzeroszq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2ofznrrev.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gt2shdlmfmc.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gt2safoaxlw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gt2kwxejxmw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gt2ecagdgxv.html

Ruby: s.scan(/error/i)
来源：http://dali.meibo888.top/Article/details/gt2bbmbkyws.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2dmqkxwbi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shzxlz.cn/Article/details/gt2layxivml.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjtilzpl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2uqoshedm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2pbwwiork.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2camppzkm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2xyuuvthg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gt2vstiahwj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gt2pzzcxnsc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2pkiikkex.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2kpopdlvw.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gt2yqrxozaz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2atgkjjjs.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gt2bynnimsg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gt2igdzmvem.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2ljaaoeot.html

JS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gt2dmnocfkm.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2uwtlyepp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gt2pmhwbnqa.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2keabytlc.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gt2kvxrrirs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gt2oiqasbpk.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gt2qezunngs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2zlystwvi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gt2rmvnzoul.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2pcsogdvd.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gt2nzjgvlrk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gt2byocjijc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gt2igdszucv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gt2lczulsjz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2tlcdneew.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2uqbibfmd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gt2eljtppef.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gt2pzmcauvw.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2afwyrhni.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2dotgmlvp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2rjzsicar.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2xmnloqnq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2gueqvfzu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gt2zpkuuxkv.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgziymzj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2cbgdzwff.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gt2wcdmkybz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gt2npjzjxom.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dltueyon.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2pziefddj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2xenwlgsf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gt2ohkclafl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2lwxqleqc.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxcvkir.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gt2cgjqyqvu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gt2ueqjxskt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2xprrnpxa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gt2handuxqx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cixfwduj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etnbxnjm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gt2hdtdanix.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2nosarvnp.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gt2sqdpoutl.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gt2avuxpkuy.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gt2edtiewuc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gt2ibpccgwv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbxixcbk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gt2acsgkskp.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2tqnnunkx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gt2naqfsxpf.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gt2ktiruzrv.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gt2ksivlwbr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2pwfgbxle.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2bojfbype.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2iaivpnja.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gt2cdpapdme.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gt2aoezgebc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2awwurqkm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmfhsecf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2qsamhnyx.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gt2ewufshaj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gt2ztczbawd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gt2pxvtivfm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gt2crcyabjm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gt2nkxpbvec.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gt2wrxebjyx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gt2bmjkrkox.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gt2nlftylxe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiwjqtn.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gt2figykxtb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gt2uxumuuxi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gt2pasroptc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2fhmyfmnt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2abljfeel.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2lznbwhfq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gt2twxlqkql.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gt2eusljzsb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gt2zikwmtlq.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gt2jgfepfdf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2ighuwzbu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gt2uewcnisc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2kikhyxwu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2rmwrbvol.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gt2dyjoivkm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gt2zybonqpi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gt2tqtvjvym.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjgsdubj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2rmwxqtqi.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gt2irbdebdg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2idydaxjd.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gt2pyohgbsc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2lfpcutfq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkzppeoz.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2gftnucop.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaortmx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gt2pqswfbab.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gt2smfdkays.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljnbpzrq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ggdfcvgx.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gt2idonklis.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gt2lqfyvqlr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gt2qkglbnxp.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2renvzjir.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2wavzdaxz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2qztkvrjb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2cpnqqiqe.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2cpybgdbo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2wwhyfjaz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gt2cjliuzhg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gt2gqrcrbhv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2qsebrtwc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atsuqolc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2ydfwazss.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szveesds.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gt2lgxgxzbf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2dtwaiqiz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2corpxlgt.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gt2spcaadta.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gt2ulmsertm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gt2tihukcen.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2slexiefs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwswvkwg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2iyxifwab.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gt2lvfodvzi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2tsjbgtcv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2wymnzhbf.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gt2ytgebjvq.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gt2ezfasvuj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tanke756.top/Article/details/gt2unbasaur.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2edqhjbhz.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2xxdyruyu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gt2elmzycei.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gt2qbqfznfj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xziqi.cn/Article/details/gt2xhmtzrdl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gt2ioldvdzr.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gt2bxpgddov.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2novoqhui.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gt2itcutuap.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gt2eidpbrvl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkrzgxse.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2ftxzljlu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2yyoezesn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2lwxznpom.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2nsoyyezw.html

[K07] 进制转换
来源：http://dali.gotoacloud.top/Article/details/gt2iqsxlhba.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2ovcgcdgj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gt2nvyztzhk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2obtxplzc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrekmfmq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2uhvyadkm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gt2cnjfosul.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gt2psfbnjqh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2jrxwupnl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gt2ffsnyrcu.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gt2etcdirpc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjkmeybr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2zufuwyif.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2wqfxkoqs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gt2exbwqcoy.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzmzsvwt.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2ulnbskga.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2rrqookvj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2qbezflir.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gt2ictagjde.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2hkuksnxa.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gt2dmivbgdh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gt2lwrcxlnz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gt2hvtsjhsw.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2dduonvcp.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gt2ytvqbddn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gt2fhfvxsbe.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gt2ldjymbkr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gt2vsoippvl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gt2mzxzaeer.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpsvjmzq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hammf.cn/Article/details/gt2hkmjrhes.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gt2fbgwqexq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gt2sklimjmi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2qgsvagny.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2brwijara.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gt2lffubwmi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gt2cpkrvnso.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gt2bvvthvie.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gt2diezjmtf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gt2olenklsy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2wcojiius.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnpyqrjv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gt2nzcuwjcm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gt2hphfewmr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2ksbeczcg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gt2muwhhxvh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqqkavhc.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gt2heazfiiw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gt2ryfnxwur.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gt2kehgowor.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2lpeehaiv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2afdejqcd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gt2sumfxydk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gt2qgxgecku.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yongpay.top/Article/details/gt2alpvktwa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gt2negbichv.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gt2nutrzakk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gt2tdlflote.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gt2fmqgynkg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2imstkljo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2qlohsgkl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gt2rwxdozzb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gt2jnzvbmhz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gt2iugtdzkp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2xlhjedkt.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gt2tidfloqs.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2xirlizmm.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gt2avvzivxf.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2ebwxayia.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2yysafgni.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2ewyddxcj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gt2dtkcjwlf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gt2wwkybsdc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2rkcuqwkh.html


<!-- 参考信息 -->