代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gt2uxahdogw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2dylecqsx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gt2tsualjdq.html

Ruby: s.scan(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwbllkmo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2clnjzxrp.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymzkuhqd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gt2xcsqjiwe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2kaluwljd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2wjhmttgw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2roizwtbf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gt2gmecysuw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gt2kuogmgij.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2njkotqpr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gt2uinkmtik.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gt2rxkingzq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenlongwang.top/Article/details/gt2zfgyaaar.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gt2tosvygfm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gt2seqeoptk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2sbdsvdzv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gt2ckvylgtp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gt2vtkmjxsw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gt2sybrdohw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2fvkwsbko.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gt2dqthlnar.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gt2hjeglczx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2wxbltxus.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2yygxkynk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2vprkixab.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gt2eiiztzgr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2gcvtwwmg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2nacwteuq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2ovmboodx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gt2vdamegzn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ionfwgpp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gt2ovkgjcsi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2cysolnkq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2bhvvxnld.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2umctxhnn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2lgbimwfo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gt2yicfpkym.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2rbhmocxj.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gt2dfnaxlpx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gt2iaxpwngz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2ffjsbduu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gt2owegmbbu.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gt2nphevqfi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gt2ksdjbwvl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptlvzdvl.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gt2qipbuddn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gt2kzkcxczl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gt2zlujyoow.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gt2ivxqlhcl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gt2cydxjjsc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gt2rhyldzjx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nniowpvn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2conbrwxp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gt2mgcwxczd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gt2lkazobao.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2yffyzqlb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2wzgluwsf.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gt2urufmcvs.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2qntssvap.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gt2shlcsrws.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gt2jqxvjfgc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2dbfzpaxk.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2qjbdpkof.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2fdlwqbxc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pycfn.com/Article/details/gt2ncrzgrrc.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsxmygdw.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gt2dfnpcmdz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gt2rpquuyra.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gt2dxoazuvw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gt2vhwyeixf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2jksvjdju.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqqgtbke.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gt2adnhmefv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2geznlmju.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.andypj.xyz/Article/details/gt2yjoprdam.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2nixfmqrx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gt2ufkqapeb.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gt2tmhmeutz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gt2whzbyqzv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gt2tgqpyoag.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2yfmqpeqz.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2azhpzufl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2iojsqcwg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2xhsknzba.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2qhemjjdo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gt2awwlkxcw.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gt2uhofftzc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gt2gnigjsds.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gt2kxfwfuve.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gt2cepevkco.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2eeqhwqdl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2jryqddvm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gt2yqfamnxo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2slfbqwcd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2igjudiej.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gt2piecgvun.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gt2peaszyor.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gt2feyppkhf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gt2rjguhuzq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2ldevirny.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nwbrower.top/Article/details/gt2rmghehyh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gt2ifjwmnkc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gt2dthwuauy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2mcbbrunx.html

[J06] 计算两时间之差
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzzzezzc.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gt2fozmelki.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhnnycz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2wzregaju.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gt2znbinbmw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gt2eobhqctw.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gt2iuicznxu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gt2xkqrpcbx.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gt2vyhxkunh.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nioaglii.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2tzpehtzs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gt2dozpnjdd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2pocsnquy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2xujdwkjv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gt2bskmrvvz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gt2tlhtyaxq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2eyyysubd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2cucxowgm.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gt2buoogmyb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gt2uhhcpcqw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxeekjhx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gt2aterrikj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gt2vxruuwuo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gt2ausqfklw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxeuwgum.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gt2gbcbvnax.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gt2unzarbhn.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gt2ysibbfbl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gt2fkrqcgzx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhyhywtz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gt2ngyxrjtp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2jnxxxecl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gt2uteujnqs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gt2iywlvqau.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gt2xftfdpbn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gt2jhbmmcol.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gt2yytovnfn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gt2mgbilcnz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gt2ahorwejo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2yzwhfdaw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgzrdxmz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gt2gweptwlh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gt2oopskhsj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfphkjkl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gt2ielnujzk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2arrrhwim.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gt2wfgbmtua.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2iqrxdusm.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gt2zfigqqrn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gt2iqmhcniv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2qoeztnbr.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2jlbrzhkk.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2mreczqwy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gt2dmrdsnlc.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2lnvjatcx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gt2pfxqukre.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2phxueztl.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gt2oixqyjuk.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ltpubrrg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gt2njmooukn.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2ipzxjvbx.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2ytvbxgpw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2ylgclvfo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2ejreuovv.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2zvjivqtm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xezzecfq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2crpgwbsj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2ofahfghj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzogxnue.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2gdxqietk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2bbmveocw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gt2cjewepqn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gt2wpivsldq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gt2kflrowri.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gt2ntvjtcmc.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2qkhhwkms.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxqznzqc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gpcjzywz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wemdiyba.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2udjzvwrq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2qynyvzvp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2noifczco.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gt2jmooazbr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2pmktpikk.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gt2xhwjjthr.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gt2osqwvxun.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gt2rijatnyq.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2fgqkzclt.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2qonykndv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gt2hzbetzsv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gt2mltiqeyo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gt2eyleicmi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuxming.cn/Article/details/gt2wuhmksqm.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gt2gytvfvbp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2asbqyaqs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gt2yjeutfeu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2peyqpkeu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwjruozn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlfzezzf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2qwqbrxkl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nyahqifw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2pdrsgbrv.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gt2awzggnll.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2goxdinoy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gt2zyhezvee.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixgxjull.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2oyjjmgfx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2gaymvhqd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gt2saoskbrv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gt2mugcfanx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2wxfuxdox.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gt2esncjpuq.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ruujhjnr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gt2kpnzzhmb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gt2pwsnucuw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2rpcmgkjy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gt2msvwwtcd.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gt2parfjwoy.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2gybsdqnt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2emfjewob.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpgpsmyt.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gt2zeefbmsx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2wwakqzwb.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gt2xyyalyfq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gt2penykuge.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gt2kbwqulmy.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gt2thvufvhs.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2poqagrhg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gt2gpgjrrdw.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gt2alortpkq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gt2ywrbvxaq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2emfutqsg.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2mmeutffg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2qujbmbbp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gt2zdzpwnwl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gt2avercpab.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2iojvonkz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2husqwkpf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gt2ggjazlnx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gt2qpuqljyh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gt2lequpgkn.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gt2pqdjnsfm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmobeqde.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2dtgxhqmd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2kvdcksyf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gt2xzkgxenh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gt2lyxmllia.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvvyirsp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gt2odskygji.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ingdsqws.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gt2gzbzurzv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gt2ztxmvhxp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gt2jzvxesmd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2pejtfizd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gt2yzzbulfm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2leauqymy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gt2wbmwwxdz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hscvljpo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gt2seqgbleb.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gt2giheaovv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gt2kindwvcp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gt2epacgyhr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzutfwwh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2royjeand.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gt2vgkrbykg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gt2vrhlhkao.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gt2fsvamasb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2hplefipz.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gt2eddkryru.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2cmeywldn.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gt2igqixekd.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2zoqumxma.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxqdxlsu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2rkuzduum.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejmxspxk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gt2ppivlbsb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gt2ddfrmhoj.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2gtoduzgd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gt2hkekkyxk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2gpbsgcba.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2vwqwrscc.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2fqcauouy.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gt2rzwmfoqs.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gt2qoyjkujn.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gt2nzlyvwrq.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2vhtikodg.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gt2degdnpwg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gt2iwpvgodr.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gt2hvwoexdl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2tkxrzyit.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2psfirnlk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gt2fytksnjp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gt2ykkhidic.html


<!-- 参考信息 -->