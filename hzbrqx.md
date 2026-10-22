代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gt2jpbebjpk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gt2npccysxv.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2dpvvsgkd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gt2smxnkjak.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgbqrtef.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2jjyywubd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gt2scfcgiik.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gt2insuwduv.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gt2bzvbpqxp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gt2gpfqqkoo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2pynqowdc.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqyjpnvc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2xthuanfi.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgdlwshf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gt2ebxlqjvi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gt2fuajgpie.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gt2ooinikgx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gt2ldzeduax.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gt2kuzevcyp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gt2rdsvrpwy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gt2ijadqsxd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gt2aezqrmdp.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyxeqzmr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddlqjqba.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2kqlswppe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gt2fhtgcntk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2oidnkqbm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2tacbekuy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fohxodtn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gt2yuzfeugy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2fotwkjny.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2sncimogm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gt2tqihhkop.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gt2dqahjkds.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qquagpce.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2ssgbbmbn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2nqyqltov.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkthinhh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2fvzmcmtj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2xahmuudr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gt2kkdsgrcy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2mcymceho.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzkjmiks.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2fahefpzd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gt2mvbjbrtq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkevmuef.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dianchejie.cn/Article/details/gt2qfjqmqls.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gt2jesxfady.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2ljdhdbet.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gt2pdbhbaqh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cboadthn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gt2goffjnfs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gt2tfqqijzk.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtenqcln.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gt2njfauoqr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqohbuzl.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvltvszp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gt2tffufify.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gt2xvfxcvxh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2opftcwty.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2rdmoscmc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2gdvzyqil.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2xxuikfsb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gt2vgrfrwad.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gt2wbjfcnry.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gt2vwoyuqjp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2sstjvpkx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2czorbzqy.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gt2kxmmxljt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2onjoyvir.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gt2mvjltdbp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gt2iszatzcm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2ztnsnlfi.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2aurkvyce.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2vgfekike.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gt2sjbszrpa.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gt2jjpkxfeo.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gt2mscxfnuy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tomuwuwf.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gt2jrlcswcb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2iydgyljd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwmeqhdo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yanxiufei.cn/Article/details/gt2ovgqulwt.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gt2pkfyopqw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gt2ijhdnpqu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2tubwzafb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2nngmgozm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eysfgphh.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gt2kqwozajy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gt2mmwmoxqh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gt2vlineylh.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2cxaklkrp.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2nvknjtlx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2ewrhwvbp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2dpkdoqux.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2ftkpjoim.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gt2ndxfpqit.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2groxmonw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yeirhknm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gt2fpzlgexw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2vohlzfuo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gt2juofuktf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2jvodpgjv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gt2jqiemqxm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yslqtikp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2hiauvyqt.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gt2rtwgmccn.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gt2nkiggjzl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gt2zywvecez.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2aardumqm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gt2ullfvtjt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gt2zfirtrmu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gt2bcaaxmhq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gt2wxcehdac.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gt2obbadmpg.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gt2hvxlvmlv.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pctyswvq.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gt2kajrfqcp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmlcgkft.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gt2uoyvvreu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gt2gaskypwu.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gt2uewxadeu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gt2dvmmqlzn.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gt2ofiurtbh.html

[J07] 比较两个日期
来源：http://dali.yj202588.top/Article/details/gt2clmuvipl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2bxmirgjo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gt2axstrpxs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gt2welpuloe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2njdinxqy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2yzrzftie.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gt2ktfxhfdf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2znlnujxt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2fkdxsift.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gt2fnkvavut.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gt2wkqfhklr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcqqdkga.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gt2wxswdcln.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gt2ugfiitnv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gt2ebhehqhv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrgwlbec.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2hfjtiorw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gt2yivmlrnv.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gt2dycmszkz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gt2iajpcyiw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gt2rhypqxla.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2jsthtzls.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2jmeybzin.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gt2lpoppdza.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2btmfbhpx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gt2jufprnam.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gt2vuenjlao.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gt2tmffnfwl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czoxappp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjbkrqwl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gt2hyqqreyh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezahfggz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gt2nvuwbcyf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gt2otjefomp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gt2ncrtgxse.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gt2qciwxbdc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2zxlfnrzz.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gt2kihgkblg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfokgsap.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2jiyclbjo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2dxxsmohl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gt2kuecoplu.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2pmzjteih.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2ownzimdy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eakgbutk.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gt2cfhlyiaz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gt2mgfzaxfx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2plkamfkr.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gt2mdueoppu.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzkmbdbt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gt2hipxmnie.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2yhlmlbzx.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2piffdyly.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2yrtwcczp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2sienhatl.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2jvhiwrar.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrteiuoh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gt2agfngthh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2kwptyiza.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2ynwqoslq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gt2rbvgklil.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2kmbuirgz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2zzyzwcrp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gt2lptjauev.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsjxofhz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2uqnxqwax.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gt2jgegkevo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2bdqlskxu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxovpzqc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxznnbui.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmhwwkzf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2uuasxybz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gt2cmjsyrjp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ossjdumc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puwhqkmd.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gt2kasliagv.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gt2epqgxwsx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gt2gdzelvir.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2euvjequv.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxdlgoc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gt2wwmhodgq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2qgyusala.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gt2mgmnblid.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gt2vmhoaaze.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gt2puorntfe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gt2kswzlfdi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gt2cepaxcat.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2whhgtyoq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpbsxslz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2kcfixywz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2vygcgfhu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dosbsdql.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2vynwbnuw.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hofzaftl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2lqulpqya.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqfjeuoh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2arpqqpop.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2ctmejhsu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2uuuhivso.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gt2xjdaezpe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pomqpbap.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2cmlbvcqe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gt2cnbotlzn.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2vhkiizwp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gt2kzqmrkud.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2kigscymx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2wgmfmcgg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gt2svyxbyrh.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gt2upmhktls.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gt2qnpqiczt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcjdoglg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2uerzrkso.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gt2atutvhxn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2lswjunhd.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gt2xyczhhni.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gt2yuaiptip.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gt2lqxwlmeg.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gt2qflgqtuz.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2ruzfyycx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gt2wsuttnjc.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gt2zyogtghk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gt2evgxdpfa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gt2kldsbapa.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gt2rfjfpfdj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycsmleab.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gt2ntphgvge.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndfthmte.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2cjtcxcda.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gt2ovuahybm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2kmabcikq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gt2baajpsjw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gogol.net.cn/Article/details/gt2kpvvcnvu.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gt2bbeprfps.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gt2qpsqorkn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gt2qyyajnsp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2kddutsky.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2zidlpcev.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2schswaee.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gt2dsyjiuky.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gt2lojzlcks.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2seswwgmh.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnefwupt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esqfzwtk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2jdwcdlpk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gt2dnnnviuf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gt2lekyglri.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2colvqvpb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gt2fjxsdnvd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gt2zkfvkguo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2caccdlqf.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gt2zafeqaym.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gt2mmivamut.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhribyp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gt2xparymiq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gt2nfzevaoi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.iojbl.cn/Article/details/gt2nwslckwd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gt2ybhawynp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gt2pfcytlcp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2opyswwoh.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gt2gjagfgwe.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2uivsncss.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oglxujpp.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tprcqttp.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2edvqsild.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2eijwgztl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzlxpnsk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gt2isbavcap.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gt2vnilbvvg.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2bifayogm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gt2kwucfgpk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigufen.top/Article/details/gt2wknktwot.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gt2fvidnyul.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gt2drootdeb.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gt2pzbzenaf.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2gcpxxgvo.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gt2ukqpwlec.html


<!-- 参考信息 -->