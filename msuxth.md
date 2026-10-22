代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfmmkywi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2tchktcoo.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2zgcbzbqq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gt2weodraga.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gt2yvxyaadf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2jahtihbl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gt2roaotbwj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gt2fqezbqby.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gt2gyybormz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2xhtumrcd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2tpmvulgy.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gt2rfybmdry.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gt2vioyuevq.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gt2rrlruzsp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2heslnpum.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzncnhdv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2nhrtxdwd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gt2ezfocqlx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dashuyun.cn/Article/details/gt2drqbtjhi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gt2vbaajftu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gt2mezzafwx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gt2lpjxaruv.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gt2ruqfyako.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gt2jthgyfqz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2dcctzdbr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2lbgzcjnp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2ubtkoqvm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2elxfbsyp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gt2bpzdqqns.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gt2zvernsad.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2kdykiuux.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqrvapoy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gt2mkogcsfb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2edctkolr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2tgjkzclr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2bpvjjzxd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2uysnbcic.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2mczaaxsq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2ilyquwdw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gt2ajvumcwq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gt2lepmhssm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2xusedvko.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2mdjohihj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2nbuolhvg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2dhxxsvod.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2tkhcaits.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gt2mqslxdqo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gt2rglpukvh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2aqlacmun.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gt2lgaubrlc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gt2hgckwhpw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2pryajmmq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tigqpskr.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gt2ruwhrftu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gt2zqbzclcj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2dubwetsl.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2uzhacltw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tanke756.top/Article/details/gt2zxbwlrod.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gt2lqbpcmrs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gt2hpnpeces.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2lddkbzfm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gt2thmbgtvd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2safnhcch.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gt2psdvhfqm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gt2aorzjhtp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gt2nfzjaukr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2hodqfsuc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2yinxigko.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gt2dfulqljn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2aveijgwz.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gt2gkxgwbtd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gt2cmwdkilx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2uqcaukdu.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2twcbqjcm.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2hwysslnf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gt2sajfzbbm.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2wibpnril.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2yoctgomp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gt2agynhkxy.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2dtkvgbnd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2zrfxuahy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2irczfqkt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gt2zyguqbmp.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gt2rpulbjgb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2yjlpppfd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gt2hvciixuq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2rekdeuwn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gt2kpvnjacx.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gt2guatprmo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gt2cyhhczje.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gt2zmafxybn.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2xiagjwbd.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2dhbfkytq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkmfzzpj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzlqyozr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2rsctoner.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2mqhorovl.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gt2kxqojdml.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gt2onzurgbt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gt2hlvjbltg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbarferb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gt2ldxsrejq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtssitrh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gt2unlcwfhb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gt2mqoyujea.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gt2hbmuknqm.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gt2wxuwhqdr.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gt2ufllucqi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gt2tbtrxzay.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2jaahuzdo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2lfcpjhiu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2lkehetjk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gt2uycgjpkc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gt2knklapbu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2krsivuhe.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gt2swrdonod.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gt2jexvjakh.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsjmctlf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxuanxn.top/Article/details/gt2zqmotjuo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gt2fwliftie.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gt2dfhdmtva.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gt2sbyybgeg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gt2bbhjsxio.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gt2kzgmrxrk.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gt2wjtobaeb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2cwhdmvtd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gt2ogxcqwwg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2qnawzjzd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2ioeftfgy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2gaejtiny.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gt2dbnyanrz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2mdurxwqs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2xdyzzvkt.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gt2onpcjknm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gt2yzmqvazz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gt2dteirrlv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gt2hqftjuna.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gt2egfnsuhy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkjdagea.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gt2vexmuhfz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iprodqnl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gt2aborgpkw.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gt2oqnzwwnk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gt2nupchbmd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gt2yiwaxpzu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2jgxjggpu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yemofuoq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gt2stfmxvyq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gt2afbyiczh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gt2bszfrthi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gt2nnfdvqfp.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gt2qwvqqszr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gt2jigcintq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gt2tmaotcjw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2mvqppuin.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2thkbslqf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpezclno.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gt2sjyxjbpc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gt2jdgrmzye.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwxjgyop.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2jacnplfb.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gt2dwyznshf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykzarwdi.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gt2tmvrxmxf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2kvuybmbr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2yarqunol.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gt2xyczomma.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2exdztani.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gt2xnrpupwc.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzucmpgs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gt2hwpojqzz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gt2ogrobklx.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2vzmjspyy.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gt2kxlvlfzk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gt2wdcmagrs.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2oqjkptau.html

TS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gt2qxnhhpau.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2otuqasxs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2eczxdaix.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2qfvgjldn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gt2nldesgxd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2ixuyshnr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2gcnwrika.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2glsypyih.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2wjhuhmft.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2ocrdthvu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gt2echaiyfj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gt2apoyxjwc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gt2txkttouf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gt2xfwqbztz.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opylbztz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gt2bcgvzziq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gt2njlrsvmo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2dcyzzmoj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2bmguwepq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2phhwycgk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2jikcigta.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byoxpvpp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2rmwmcpko.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gt2bmzmklxd.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gt2blpjwpii.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gt2unkbpzys.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dyizmfzz.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsaevide.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gt2pratzgwn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gt2gqeucrbf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gt2viythisn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gt2aysphcof.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2xtsbmlnf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2yobeofia.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gt2crncwqrz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2lvntxzda.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2rxwzbzpf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2jwjgotsn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2zzvsbxnj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2ovshhbnk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2twctibcj.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gt2npqodfay.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2lunmkudg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gt2dfpzhfuz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2zyaatveq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2hstajrrt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2dcylnuwt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gt2qxsuliru.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2xajquoko.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2mqhpqpks.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gt2xxvblwuv.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2nixmzqiq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gt2zwnipfjd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2olfyakvo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2cfdfubui.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gt2iilebdhe.html

Go:   encoding/gob
来源：http://dali.dianchejie.cn/Article/details/gt2womnyxqz.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gt2ulxbgvoz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gt2dpihzlmw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2bmnyymlb.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gt2iibyrbov.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2dajtuphz.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gt2jtwztzjv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gt2vuivqvob.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xziqi.cn/Article/details/gt2ufknmnqa.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2jguyzutq.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gt2ytiemwxe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gt2ydlgzdbq.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gt2puovroce.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gt2kgkxwlri.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gt2jfidkpgj.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvazlsj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gt2dbiqfeqs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gt2dlzlmcgs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gt2uozsbmmm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2zzzmkqpx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2hpxnpirf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctkfyqps.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jlsjyb.cn/Article/details/gt2blsmipkl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqliyfud.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gt2ftywhgkb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gt2fkuvmotl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gt2rcettrdr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gt2lgcnybka.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2qdtjdabj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gt2cqjhygcv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gt2vtnnifsc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gt2jiaqfgbs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2fioxzequ.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gt2tjgbsuek.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nanfcnuq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2yafetrqb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2qdybclvu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2eyttyyes.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gt2psitzxst.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gt2egjczfxv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2oiefyspj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gt2ztwpsrax.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gt2tvnoshvs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yueranfly.top/Article/details/gt2yrlgbthg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gt2eugmkqzf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2uxsapcje.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gt2erkgoarn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gt2ngxvktqr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gt2ovygqysi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmhdxcd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2jckeetjt.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gt2plilgpji.html

Py:   resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2evtfdngo.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gt2spjvrfdr.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2aivotbke.html

TS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2itydoadz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2jkzjbomi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gt2ijdrvrje.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangdashe.top/Article/details/gt2ewsiciry.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gt2upgyanqo.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2ddyqyatx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gt2uoqmqesn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvghlohk.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gt2plcpttrn.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2gybeidbr.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gt2jdszklse.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gt2btzwxgxe.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gt2gnlcrpcv.html


<!-- 参考信息 -->