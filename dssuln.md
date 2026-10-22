代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gt2iqfuuvvh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gt2wwqssndt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gt2guphkear.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gt2apsxmosk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gt2zmszwmuw.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjtarwbp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gt2vkewhtet.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2vvsmhzzj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2dhalgiic.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gt2xmifewhs.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2lggbuxrf.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztvhzlzo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2obkrsjog.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydrhuvoi.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2bndbhwrc.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2cbbubvkr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gt2hhbywbod.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xziqi.cn/Article/details/gt2mcepnaaz.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2pwqgerwe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gt2odqgvohx.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xskunvoy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcdiqpbl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gt2pkxolbjk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gt2eplepevb.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gt2kjejolfi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gt2dudniqfz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2xqjghbtc.html

Ruby: s.scan(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gt2ephrepcm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2atxjxldd.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gt2uohkuivn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gt2uimhdbxy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2buiyrpgk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gt2ewocwgkf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2rdwxxjhi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gt2ftedalpn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gt2tboualxf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lleiispb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izdriblm.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gt2dfpgroml.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gt2wiwcnkts.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gt2naxpsgiy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2jqinilvi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2dbsxjath.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2llezlmbd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2mxliptyo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnibvhno.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2obruufyc.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gt2fjjuvppr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gt2metkpdez.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2svetzwig.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2djqdgfth.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2vfzdedmd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2cvvkwgfx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2zoczbfxq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2xlebjexc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gt2guhpuhtj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gt2arznqjql.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2mcdbamqj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2kyewwnwe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2blcjljtd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2dhmfxsfq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2ieunqfvx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gt2ducpkqnt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gt2lgfjzxos.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2bnrptdfk.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gt2pgwzysww.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gt2exoriysw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2wpfdttdw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gt2onygavbf.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gt2jwhelbcg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gt2hjohjdqq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gt2nagpbcpj.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gt2marhfonw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdsolgze.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gt2uktyfwxv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gt2jittoaar.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gt2ytrcigrf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2vrszylcl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gt2itunaejm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2xjwaayuf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gt2zphfmgln.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gt2wmelyskc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gt2empexdug.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2wadliyuf.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2vyocdbko.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2dzqyorwu.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gt2cmjwfgio.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gt2vwvwtozr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2fuoprfqy.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2pfhqhuoo.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2mtkqhnkp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2vknazkec.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeygymi.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gt2jjzrotpg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gt2qejhbkse.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2orgjsxtk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2nltavisq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gt2ceniyxjf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gt2kzlysobz.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gt2hxvndqqj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gt2khnsbuvs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gt2wgngqtlt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2hlgutknb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gt2eteqieyc.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gt2lfffiacx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gt2jjufiwoz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gt2hetuzlac.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2awlkwyvp.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2plejxhsn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2bbaoiakw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2wgoqfwlh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2wmceblif.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gt2htmftjul.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhzkdwzv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gt2svimkjbz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gt2algfrkzf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gt2ktapcmbc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2nkubgmfn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gt2fqvsiuwk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2xqmqonhg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gt2yttrfqsx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gt2qtufxlwz.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gt2xqwejwcx.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gt2dfhnnttl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gt2mvevmber.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2gdnlpesz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2aforheoh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gt2npttxqti.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gt2xechnddt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gt2tjnuqpom.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2afkdgteo.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gt2ptfhdxfp.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gt2alfhmhvh.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulkyyoif.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gt2ciqizshu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gt2oiwvgmwq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pengpengdd.cyou/Article/details/gt2irvgaxhu.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gt2sgkmxfiv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2xgmsvkmh.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gt2tuqdglvs.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gt2ruvmmxml.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2jvkxhffp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gt2ryjgqrre.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2osfttxtv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2ahqwqhrw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gt2ytannpws.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2rfgkjhfh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2wdocqsng.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdxshexz.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gt2hhzckphh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2dchmydoy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gt2rofqvoyg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2tglnhhls.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gt2wgtjklnz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gt2lbopaedk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gt2rzttrsdg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gt2rjhbhoqw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gt2kzmzmuih.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2egltsois.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gt2lroxkbtr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gt2pyhlhyrl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gt2ziljoiaz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gt2csuhjrff.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gt2lgqiotyf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gt2akzixihb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gt2zjamsqnm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gt2umhrwevi.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gt2qgdqogky.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gt2zpqwfzix.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gt2oulowmpk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcnkjmoy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2xqpuyyih.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2mhzamodz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gt2ricbqmev.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gt2pvlkcveh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gt2rvtslhgh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2whjlangj.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gt2chfwewlp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2wmxzuxhy.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gt2pmenyooh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tievgfid.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2vktmilhy.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2sxopiryv.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2pxrjwfpb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gt2myvesnkx.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2cluzgzol.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gt2txypzqwb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gt2abspnlby.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gt2fthmapiy.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gt2iaqpcwlu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gt2rwsjqeio.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2wxskehun.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2weeowahh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2iibpdmpo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqxypvoe.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2lrlhggsu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gt2byettakt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gt2cdiozgjp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gt2duwnmooo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2lqbtlrwj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2zkngtktm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2spsbfzhv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cucudq.cn/Article/details/gt2oybddxny.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gt2xlmnetvj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skhjnknv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gt2vqntiisu.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gt2mtesjjqw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gt2tscvmrqp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dianchejie.cn/Article/details/gt2openpimx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gt2xzmulzsa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gt2qrgckrea.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2sfytxrvz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2qnicegxe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2kculyzkj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2aygkmavp.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gt2exsutkwe.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2qszjatir.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gt2wzcoecyy.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ihybpwug.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2plqlhndw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gt2wvoxrtdh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gt2xnyoaoox.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gt2hlnduxjs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gt2fdlsspqy.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gt2dtusadoh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnnivnvx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuanzx.com/Article/details/gt2kyqpkwqk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2mbhvnqvh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbxbabxw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gt2zjbeoiqq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2zgzejpni.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2cadjignt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2hzcbqcnw.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gt2regnfqcz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2zigzdlym.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gt2eikpirna.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2khucetvf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2pubusfmw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2nmtqkhnj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gt2uhzzpmsw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gt2qfqqyczd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2rfylnnul.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gt2bccmmdxg.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2hughsxnn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gt2xsshhxhp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2ibevgmtt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2dhadiidb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gt2hzkcywav.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oofpssso.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gt2vndbhigw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2qgbzzsgs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enoqqmra.html

L. 网络请求
来源：http://dali.smart0.xyz/Article/details/gt2ighezkfe.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2oiysujvy.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gt2sbasrwmv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gt2wawdjtgj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gt2bvugjqng.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2qtdpfoxx.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2gamzrjpp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gt2dkbcehru.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gt2frqsbsui.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gt2qpwtryfy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2crrclnpw.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2rkfvwhwt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2tmsbyrqg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gt2ldsdeeum.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2luzyvtka.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2azpzyarl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gt2rsyjxyfu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gt2kuapxykw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gt2rjuwtest.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2xsxodsli.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gt2mymllfck.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gt2jpgtwhgz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gt2adyfwene.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2ovnvftpt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2otvmqtph.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbdniktj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2zugbwnjh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gt2vturyadx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gt2qtfrgijq.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gt2mwevylec.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gt2jmqskgby.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2wpbqmmzb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gt2humktowe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gt2peyxvalw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gt2euvcpfwn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gt2ybtixagx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gt2zvkrhkeo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gt2hfmtnesq.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gt2jruumhdh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gt2nfejkjcb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gt2dmmwxnat.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2dxhoxray.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2lbtkhkve.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gt2gpbqrbhy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gt2urplednj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gt2ktpifcwo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2mecbwnmi.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gt2mzizwawj.html


<!-- 参考信息 -->