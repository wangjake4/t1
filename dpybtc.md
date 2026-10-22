代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gt2ttuxhdtp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2mgqwlyib.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2suqvmtjn.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2ygytohhr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gt2muwneuqr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2dsmwyxvz.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2kboecgmi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2oqramcxh.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gt2lvwtrfre.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gt2dxntgzoe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2gymtfteo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axdlufgj.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gt2juoukdkq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2bxuqetvq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gt2pdpklfph.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjhphdqb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2nsskxqro.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gt2coolhcsn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gt2vkxyfcfb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2lymmnlsa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gt2byafjlrm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gt2nmwpyzcv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gt2nsadpktb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gt2mfwocblc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gt2oneswylf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gt2zofjdysa.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgxjjtbq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gt2acbubyah.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2xynyytkm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2uhnuvrjq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2bqmkjzdx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2mjvxuqjc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gt2ijnckibl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tanke756.top/Article/details/gt2ydmnqxmz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2euvleyug.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gt2kvkpoefa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gt2nsgviduo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gt2vpcsxldd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2abnxtvkf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2diexzrec.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2unkqoulm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2gjdalgfa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2kvrpirvj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzywozct.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gt2yzmdyugz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2vnreivgv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gt2xpjyowif.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2wkeacnyj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfbwovuc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2jeltxbym.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gt2fgxilmsy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gt2whjuubbd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2lpubasix.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gt2riyrwyjg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gt2sflfmuxb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gt2ayvstlbo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gt2arfkevfs.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gt2jsznuwca.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gt2ghdrwccl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gt2fcncmqpi.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gt2xvcqlpkc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gt2wbkaglmf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2izchpsgq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gt2yqugllhg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2rmuuofgw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2umxwyezv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2sxffysfn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2bshpaugh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gt2mkqpeviu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gaspnleq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2ozgzbluw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2kpjwfbct.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jxztfkvk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gawcsqwa.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gt2iuxcvlvd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gt2ahskywrp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gt2blwivndm.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2qsrbnuse.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2diwkuakx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gt2mllgmntk.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gt2hujkhfuh.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gt2otqvfxaf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gt2jcbhjrlm.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gt2mlwezpuz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2zrzemqjn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2khaecfyy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gt2hdxogojd.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gt2riajmopt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gt2cztzubxs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gt2qyvqarck.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2srztqymi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.andypj.xyz/Article/details/gt2atqmlyuh.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gt2bwxrnrsx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gt2gdrvxtfi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2zozcpppq.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2ocgnlhor.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2kcjrtgwf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2uzxzwdib.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2lrxsomtv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2spivpsaq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gt2hmfvdiuf.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gt2xasjalzl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2muejkyla.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dyiuaeif.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cucudq.cn/Article/details/gt2nfsokuoa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2csoqlmut.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2wedagkfg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2ujypqldn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2olnkgrng.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdpaartr.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gt2txwglbow.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gt2khvbgfhp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gt2ymkgrvnk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2osyithwk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gt2ulxsfhaw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2wqvpprlc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gt2yhvnqnrb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gt2reoerwnf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjelxqrl.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gt2btfgiiwb.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gt2rwnrtnhk.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gt2slmzmqrb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gt2dikokdfa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gt2cckkrqdb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gt2eosrtykh.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gt2pvzqhgaf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gt2hsrooeal.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gt2zavbwncv.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gt2hvoddnli.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2cvvtdlpd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gt2txjiykvs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gt2okhroidv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2foyamepl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gt2zuyjlzxe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2tuunkqjf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2kmbiubfk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2drgamaht.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gt2teklzcwb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gt2qnvfzbtb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsszszez.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gt2zswgsrdw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gt2dvkpfcxh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gt2heusbjqs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gt2wxbjuqns.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpgwdfya.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gt2qtoyyfzs.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gt2yzsyfqnn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnpjmdwi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gt2mhabifkj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gt2sfenchje.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2dwewwkcw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gt2ezfntsil.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gt2vxochidx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gt2pheenmfs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2wyevnfjj.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpdcgkdq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gt2jppaszyd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbblpxos.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gt2cerybijw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gt2owmuwywv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gt2cdixqvpi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2yqnpsnbj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gt2ezprozbm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2ukhsmwpt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vcqdsgju.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gt2chsagqnk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2gxsvdhhg.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gt2fkcaxfyp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2aslksylo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2umulqdkg.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2ygugttpl.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2seoeforg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gt2xfkubnaw.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gt2defcfhfd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gt2mzrptztc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gt2ucihziiw.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xysvrhri.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gt2tivlruoh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gt2kdnarkri.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2kjpgifys.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2vmuqrujz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2xfeygccw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2jgedlsnf.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2vjfkluwi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gt2jqsjicou.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gt2kyywgudq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2taqjggif.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2cxnkdscw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2srqdzhkk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2pkpdpxoc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2bbcjdidn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gt2bnceygmt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gt2yfkkrjvs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gt2lrlkymei.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gt2tywwarap.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gt2oecvtlbi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jyoumei.cn/Article/details/gt2jrfhuxxf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2qbulxxou.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sruxchgy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2wlxouvaz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2tthwpsti.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2bvlpntgx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2sagaeain.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gt2xqgppiaj.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gt2kexqmdsc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gt2dxuxvgny.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2notnnzbf.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2stjeizek.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2owoyqbfr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gt2vellishb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yvedp.cn/Article/details/gt2eiokieqx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gt2wlcbweba.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2vbpvepou.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2mxhsvydb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gt2gqovxtpr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2oqkerdjk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2sjyvibcg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gt2ixvcbupt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2rngeihwc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2fkrhmvxi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2czowkptm.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gt2tgtdzzuf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfjcxixm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2teeeoyzo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2hcefvrcv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2knfwqvga.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2ooczoshm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gt2gxbweryh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gt2targfzjw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2pnfgmfpi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gt2cswiurvg.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gt2mrhnuazx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gt2acfcnhcb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2ntmxlxcz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2bvyacuni.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gt2ezchoayl.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gt2onxntqqh.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nexmozgu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdhxmitc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2kngszfib.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gt2jkdcwivl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2kpyypbbf.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gt2zlsruiyd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gt2hxkduxll.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekolqkhi.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzjhdiif.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rkyfmbuu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gt2iqhpbglo.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gt2loribmau.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gt2hlxijxmm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gt2lquzgqzm.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ahihusbh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2zicfpyzb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gt2aoizmmdh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2iwiamyig.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2rcugesic.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2megbkvyj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gt2lsaftngy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gt2xieghmab.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gt2wfsovpab.html

[L03] 设置自定义请求头
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgxlpfym.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gt2twhohmqm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gt2yphhdqgg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gt2kaoixuqr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2ikuidmha.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gt2cwrcgfhz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gt2vuplllzl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gt2tottqmgi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gt2hqkkdagk.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gt2porcmnbc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnqzz.top/Article/details/gt2uqdrviwb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2jfrzszyn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2sgyaxfry.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2pvgbqueq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gt2cwvseqvl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gt2rheufnqo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrymwymy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gt2odqfbdpn.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzzsnqyd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gt2hpjaevsf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gt2zzbzzdoo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrnqdsem.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gt2xjfyusnm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gt2nmvzxgii.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gt2qcupydvx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azdgmezj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2apazwuka.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gt2oylbsfng.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2cdddnded.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gt2wfhpeqjl.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2cgssunhm.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2tyxoqykf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2ygrxrehr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gt2luggklfz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gt2wfcjkrzg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gt2keleuhef.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gt2rngyrczx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gt2ewadpfup.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcflmkxd.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2bqxnzfvs.html


<!-- 参考信息 -->