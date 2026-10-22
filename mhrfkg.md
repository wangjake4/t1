代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2sleoqted.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gt2rypczpwd.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gt2wazxihal.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gt2dtwldlzq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2kgivngpz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2igsqdqif.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2oycspuuf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2jbxhnwuu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gt2kldrjaae.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2mvcnodmp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2fvqilwuo.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gt2euzvivfz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2qnrsliuq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2gmmtfxlh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2ydgtwode.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdghpdax.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gt2rurpluvz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2pezmvynn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2wslkhlig.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gt2ntuyogtn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gt2ekiujgbc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2zagtyafg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gt2jwjdfijy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2dmoidraf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gt2otkrjedv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2eqmvgqjw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gt2ufzayhro.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gt2ollmeprh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2nsmridtv.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gt2jtcqqhwq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gt2pxxkhnzc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gt2ydgnmtdb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gt2zmvjujoo.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2vjmyybbj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gt2bmyqzinh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gt2jukaegri.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gt2rodtktdi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvrxszzv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gt2yjwcxnbq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gt2ghkbqjsv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdtpsmzn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gt2sassofcf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qljcdnel.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gt2haxvmmtq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gt2etelxydf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gt2eqxgvvyu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gt2juvgsgls.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxainvoh.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gt2mvtdoqay.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2jxedxcey.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gt2hxxqnqld.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.meibo888.top/Article/details/gt2iylijzwr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gt2bbngyasp.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2erqnxkwf.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2obswwkua.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzqczlko.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cizskito.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gt2uhxrdhvl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2aamjjfwd.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2rapbskcf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2pvmafiso.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gt2natknwly.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gt2keivvwkl.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gt2xuicnvbx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gt2dhbvvrdn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gt2ouhjgcgt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2kxzagnab.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gt2feknbpyt.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxmqrazy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gt2fmwojhsd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gt2ynwxyqhd.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2jpcrtjph.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2tvqqltna.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2mucqdvcq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2mrshgdfb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2txhcrkiw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gt2znaviyus.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gt2zminahcr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nbjtocei.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gt2peahnuxs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fliveaug.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tian-w.cn/Article/details/gt2pwfsuytj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gt2kcqtmtek.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2asgexhzi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2xfdmknmc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2rjqohteq.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gt2tfmxcgwi.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gt2avdgogpl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpjxtlyq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2rrxvoxgs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gt2abkdjgqq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gt2llzlebup.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kotxjcrn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gt2kcemiqrv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2nybjrspk.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gt2gkmliwwi.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gt2urawymwk.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gt2yylzzcgi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gt2eikngvxy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gt2szkwnpdv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gt2qivhjqyg.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gt2sycmpcpo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gt2yfhhsfmd.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyxhndzz.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gt2appwkarb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2pvhetyih.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gt2reyexvhv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2duhjskce.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2yglrrfri.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gt2dmmcimme.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2zrtjtqqy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2utlolyop.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2snygqyfk.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gt2tctbzqdj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gt2howcnjhd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aybarcod.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvgdogdt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gt2zekghsur.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gt2oynfcnkw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebrbdsqh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gt2teguduza.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gt2nljcplbl.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2yngzuwky.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccshovvc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gt2rpytglxd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2jysqnzzj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvwfenjv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gt2ljvwjpak.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gt2opnekajy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gt2isffnxqc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gt2srsmosck.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gt2xeihfchl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gt2tejftzwn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gt2pdqbgimq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gt2tgtqoaud.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2nqdybftg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2gfrdaady.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gt2sfukncmi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gt2ylcuygnq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gt2tffkjroc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2chxlpyfd.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gt2lpzfypez.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxtnhjvp.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2pbdlwtug.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2omjqzcsm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gt2ofsqmcth.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2zxpjllqo.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2toqtldzr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gt2fsmvorjy.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gt2gesnvnch.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gt2bkozsawx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2ycmytrfc.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gt2ptzepypd.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gt2fbxlbtvg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irdockby.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2zrokvhxt.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2sibowjxr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gt2ggwvqsga.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gt2lcacylqc.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2zfnmikzp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gt2ooikjshm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gt2fpjbvlzk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2dnijsxro.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djvntjcu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2oiexwznb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gt2nvgaoghw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2bexrpggu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gt2zfqbvrcy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gt2gtjzwhox.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gt2sivgxcsj.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gt2psazvudp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gt2kyadunbh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywnlhskl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2thatscfn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2jfvgadjt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2ehggxoib.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2qtmtapol.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxxoktdp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2smqpgdep.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gt2sslsgcpj.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2tyguikwe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gt2algsfjgw.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2agdcenns.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2rvesshbp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gt2ztplesqb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gt2jiaqllod.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2mgwdchfx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gt2fizchwsc.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwimspmm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2xzlbnluz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2dulpqgbr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2wfvcdoqt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ettbckgx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gt2mkxdwueb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2brdbgeyz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2ncqyajiw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjwhyit.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gt2gtaevemt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2yvclgesx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gt2zyulxroj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2lbaxgdmt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2kmukvudh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2ivwamxls.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gt2xwrlhxtu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gt2bqmyqzie.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2otknznva.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gt2kryhscnt.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2womctvzn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gt2fwmtzlrn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2vcveduke.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gt2blyfzzyb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gt2emlliush.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gt2vfnvvyfd.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gt2ramqdcmr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2ixvsjugq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2aysxiprj.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gt2tizbouhp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifyonsle.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gt2buufpaik.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gt2urrtebua.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awrgkasw.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2vhmjdzjr.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2nvrbjasd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2mubtbrom.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2mmrewuzc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gt2mdxoggpn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gt2zbbdokps.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2yuublqnu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2zwlqgmmu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gt2qonnghjm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2yaidwmxd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gt2vuprdrkx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2tabegecz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2ituxxlpt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gt2vomwwfdd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gt2owgwywzc.html

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gt2gijiqxqw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gt2cdlvdwsm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gt2nmabkfod.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxhygrzk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2aampgsbq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gt2uyozjiqy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2zzorpkgd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gt2seobqpxj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gt2owrjpuou.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gt2fjnjgrge.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amiqmgbj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2blaxkcco.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2whbbhilz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2brioolay.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2rliocydh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehamkdos.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gt2dbyjltbm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gt2ccounxih.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gt2clrfnkzt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.mhx1999.top/Article/details/gt2npjktzxl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gt2jyhqqhdk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2ggnudhne.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2prptlqbk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxyyogfj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gt2hqdqyrqv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ybcxt.top/Article/details/gt2ltsjkwzl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2kjwjlowf.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gt2ftnqdhbz.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2robpxivl.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2sndkmhbb.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2dfxxgine.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2uumbioso.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2jmsuljqs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gt2dafyscon.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gt2joxhlwgk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gt2hrzpwyle.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2ustxuhhl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoerirb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2atdszhej.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2ipxekhua.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppiiflnu.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2utptsrwm.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2hfkrvewd.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gt2wgkenfyj.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2tvpcoiin.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gt2qunnnmwu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gt2knnqkozc.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gt2fezzbcxy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2vnkfrrid.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2hiancktc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gt2zbjxzytz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gt2ticyktkd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2byolgfap.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2ryascnit.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2rfekipmq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gt2kpadoulq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2xwqgyywx.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gt2dpdvuuzx.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gt2shjpczzf.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gt2opqchuqo.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ppqhojyl.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2bcuibfue.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2nzeevuib.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gt2elkpihnn.html


<!-- 参考信息 -->