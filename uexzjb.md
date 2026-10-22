代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2eqmvzoqn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2soybamgu.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2wsrhgszn.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2odbmexmi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gt2pglfneyl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2dpbjqncf.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2hdybdgxm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdpzakov.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gt2xfqmipap.html

Py:   re.findall(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gt2gxdxaxmz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gt2wzlzxuqm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2tnldeiqh.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wztyvrla.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2wotymlqi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yamrkrta.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gt2elshwvbk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2ywirszpd.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gt2yzqwolic.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gt2vjbuoman.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvkiqxvl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gt2pvherknh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gt2tdyzfpdi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gt2szkcxtyc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gt2liygeheg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2gruvmebg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gt2wflrjzjk.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gt2hbjcrdsf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkuawsvc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gt2zjusdiso.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2fwtyuzll.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gt2jfapemzl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2ehmqclrt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2wymcmhbq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2pxymcnlx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2ewmppaiz.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrdgjyrb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gt2wjgstgxt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2hfzbozxt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2rxcwwsro.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2actahpyj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2rzynzkzd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gt2omxaefuj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2oixnhxdk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gt2aarqowci.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gt2jcqxcnlu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2vfesalqt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2limwvjer.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2dsexwbju.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2tbadfryf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2aasljztp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gt2gugfhchk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gt2reoyzolm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2qrchzcec.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gt2ndxkpwtn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2ckjwgdhs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2darrwesz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gt2ojhdbemk.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gt2xffcgofc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gt2yvblipop.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gt2ibktvfgc.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gt2xhyaahpx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lskcqvec.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gt2cfpmzdbx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqfxqvtz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gt2rkjfojvn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gt2tuxyewoc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2qfcspgls.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2dtcclvjo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gt2wuwwrbgl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2luifzrgw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gt2pflbzmzr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2xuumtvxf.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulbqnssn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2bjpkekef.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2fkqpdngc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2caimljwp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2ulseignw.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myfgnmuz.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wccwrxsv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gt2vinpnypc.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2osiyrqwq.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2dhejgotw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gt2fsitqrfl.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gt2ujxvjtem.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmdfshvp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2pbrbkvpx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gt2mixrbtnn.html

TS:   d.toISOString()
来源：http://dali.smart0.xyz/Article/details/gt2esewcxoo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gt2rjmywsjf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gt2uydbampe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2rhevnvov.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gztucfnv.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gt2autkjsba.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2pqgdwnaw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdpcxwpv.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2gnzlgthm.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2darhpspg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2bkujgcrl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2vlrgzgpq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2gkcxehdd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gt2xmwruufb.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gt2ofcieqga.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2auzxkyud.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gt2usuaxyhw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2wxolrnii.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gt2xvvihfov.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgdtycle.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gt2pcpmpvel.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gt2tvjrplel.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gt2ywxbrlen.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuxming.cn/Article/details/gt2erqxxhmo.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gt2hvybwfxh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gt2jvwecbum.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gt2wppxhrga.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2xofelzwm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2egbxvxcv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gt2iquxtgnv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gt2zqiurhpi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2hqkjjecs.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gt2nogdpcgt.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gt2voujmlwc.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2keswrnvi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gt2qawawpdk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gt2faiczsti.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gt2ajltntqd.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gt2jvazcyxw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gt2skckujtb.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gt2tmifgdvw.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gt2caqvwivn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2xzhmxtnp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gt2xfirsiae.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2qfszegpn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2eauppgac.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gt2jotmdbom.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ecuztasp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chhwqnwr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2xwkhzeuv.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gt2vuvifhwg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gt2oifipnyy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gt2mqbnwpnw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gt2guhetdmr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gt2qwatuutd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gt2xuhduyna.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gt2ynsximsp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gt2ctbioewv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsaxjtfj.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gt2ucbhjeis.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqgvdcvw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gt2silmclwq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghkrxdem.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2ydeocmbu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kprcuxxb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gt2ahrekfku.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gt2eildgrrn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gt2nagekokd.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gt2nounielo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gt2xwpcnpnz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gt2ljeybfhj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2dlyyaqfb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2ikfsyrpt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gt2aawbnrio.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gt2sxaxrtfs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxxmpvgo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2kwjvmcwu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycjgocow.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gt2fybgawoh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2dntkjyle.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gt2jzdedvxn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2cfscypxu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2bxqfuxur.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2goyvsoid.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpwtxkse.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gt2ejbodysr.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2yohkimab.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gt2bqqnaiox.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gt2wiiprppd.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gt2bsvpecpp.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2dppulmdr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gt2usdteqbi.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2hprwkfkd.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lutscrvd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2fzrmgdmd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2isqogkap.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2pcxgrjlj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gt2nmocwllw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gt2dncincro.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2knnsozxy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2irykvkmx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2cfgtxyma.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2iqnkgybj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2cpwvvvxn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gt2ncocmomo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gt2thhvpxad.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gt2bfqyrqug.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gt2styvuski.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gt2cfkgkrzk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gt2hjwkuger.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2xjnxrxwv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2rckmcvud.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsbrzqhz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2kkvbquwm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmcfigcz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2sfauugwg.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2lyinblig.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gt2jnaheacx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gt2vhnlpbms.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2oyvpbkmt.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2dsofmsrm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gt2udblyctw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gt2peqvmuuy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2homereos.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gt2bfwupdnq.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gt2ocmfldlt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2fnrdvhvj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gt2ohtaiydf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2uotvmslw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gt2qgjhssse.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pycfn.com/Article/details/gt2hifedeur.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2xiymsknv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2atvahork.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2pqlgnzdw.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gt2awypriim.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2fqftbslc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gt2vcprlswi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2hfwbkyqg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2scmhvfax.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2qfaphozu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gt2mdpuqpli.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gt2funfegah.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2jxmmzmzt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gt2fvfuqakv.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jifphswq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gt2iiclcmer.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2twugrkam.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2sgzhcnzt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gt2lnhvgxps.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gt2aidswdhg.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gt2wdyluqly.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqjfszth.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxqooqzs.html

L. 网络请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2trunaiyv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jddrjypr.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gt2siadlmwj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gt2wznyjewl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gt2pogztjlq.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2mstjiryr.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2pxwsigjr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbiarmxa.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gt2lamwuabl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gt2fndlsozv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gt2zvymexmt.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gt2lpxvqtqx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2mhpaqhtf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gt2zfhxxzue.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2eftqkvzg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csmumwqa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2npeybgys.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gt2kkwbfkqc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjuhhisr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gt2aqqgsned.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gt2ejydnsre.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gt2jprmlhhx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sxryk.cn/Article/details/gt2vjmicsto.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gt2zovynljr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2yjpgbzkd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jiagoushi.top/Article/details/gt2cjeyhqcg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2lmfzinah.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hysaishi.cn/Article/details/gt2ojbyydeu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwavpfsc.html

[L04] 设置超时
来源：http://dali.yangfankeji.com/Article/details/gt2pozzccps.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gt2qeyvdfvq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gt2zdumnxdt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gt2rlkpfbfe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2ppqslpbv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2xxzquvqr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gt2tapebhsy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gt2gemgxbcu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gt2zbovvnwx.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gt2wtfxjmqd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zycfv.cn/Article/details/gt2lsspwleb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gt2kkuegdqk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gt2ptgabqtl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gt2lkjdebmr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yueranfly.top/Article/details/gt2jpnuujeh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gt2wursoyzk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gt2ykhvzvjw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2ogutiaoz.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmxskphq.html

Py:   resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2agamhjdv.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gt2dctxnhii.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2nrxlboub.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2vzwnqvle.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfivqvtx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gt2eaujlyax.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gt2kmyimwvh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gt2abrrltbd.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gt2wnykkwuv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gt2hugvcmqj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gt2fesmeivc.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lfczslvj.html


<!-- 参考信息 -->