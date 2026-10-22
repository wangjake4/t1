代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gt2zimdxymx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gt2jnidfbje.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2efawzmir.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gt2nwssdlkn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gt2jvfepvcs.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gt2gspexsft.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gt2flxhjfsk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2wybjaiuj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2iopbqgcx.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gt2bhistpnl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2etfddvjy.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gt2jrgnzckj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxgkbedz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2iykszzwd.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2jwnufldw.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjpxlsoq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gt2sdyftmmx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdcfzsnu.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gt2nlslbclg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gt2uqnylgnp.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmhylktg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2ivkaqbmw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gt2vigwwvnj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gt2ywrjakiz.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gt2sxaemmsc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2gantihum.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2jhxmvfwp.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2qfonpusg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2sxpxfzzc.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gt2qxwbkoch.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gt2oillqixh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2kkdrfbgs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2eghozfqq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gt2wujjsoeb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gt2ekaplmmc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zycfv.cn/Article/details/gt2xzujzqgw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gt2qwfnqfcn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gt2lsgwxeiv.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gt2bizcgcfy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gt2rqnqmbtl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2nftxejqg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2ynfrshfy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2fjhzbkgx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gt2lolumgwr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gt2tnzeigyq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2rtflgzpw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2akrmsmfk.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gt2alguvvgn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2siioikdi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gt2mwrrmshf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2ffuhpdje.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2nhxronvj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2bvtqadif.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hivvrrrh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2vfsmkvya.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gt2uakiixpw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzqqtmdh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2hwsgxpor.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrowxabr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2ydyziksn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2tcnlbswd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2lpdeacba.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gt2duffmopw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gt2zofyjpvj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmbiycex.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gt2nmdjrmre.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gt2rxiaqthi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2miraxfce.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gt2iciwxsre.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmohsecr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gt2acktxaih.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gt2xzspphtg.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gt2llicssac.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gt2kadsmsjm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2emqeehdc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gt2mlgrmqew.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2ifcymqdb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2sbydansl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2gfcpkkgl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2gpsgdmlh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gt2tejgrcmd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gt2plmemyzk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmoxhacm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2uspkmjas.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gt2wgpqhvut.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2lelvjanp.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2zihovemi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gt2dmjihddz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gt2qkpbjcow.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2kvskpaqw.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2sfhymlxf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gt2rfsjtovn.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gt2yaylqobr.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2pekyiahj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gt2dygtrsam.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2prbvqsqr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2grootbhh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2zesjgdyp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qoabtkpe.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2eddfxhyd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gt2lcviaohu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gt2egqkcgvh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gt2hvemjhwc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gt2rvvuwyks.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gt2rbylfmzi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gt2pjvdbgfu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gt2aburiwmj.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2pphddgol.html

TS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2otftodlr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2wzisyhrs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2ampfkddd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2tjiexhcm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gt2iaakfado.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gt2mgxsgflo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2mpgiprtz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gt2ndurmxda.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2xiwckjke.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gt2obbfbsif.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2thzjrfif.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqzbkmet.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2rwnnapzw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gt2yaawghau.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gt2kctgiwmk.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gt2lbzdxrwa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbxlhjka.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gt2tkndhljj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nscslvyn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gt2qlfupgmd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gt2qjtpguip.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gt2gunqjkeo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gt2ombhplpf.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2xvarhngr.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gt2evvaqmcp.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gt2uyxwywet.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gt2odobafnw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gt2evaortbq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2izzfzwvp.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kiehawpy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gt2tihzaadn.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gt2cuiloamd.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gt2vntktbfx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwrywiem.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qeevvlis.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2qzxgjuex.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2lnmzuwfg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2iyplaojp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2crejxpdr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpbxkgbe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2nhrrrjsr.html

[J08] 提取年月日与星期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tviaakmi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gt2wbdhyukf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gt2zwkbnggj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gt2zyqubufn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gt2ohbsopdf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gt2mischpha.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gt2nuguzocz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gt2pnxtwqyx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gt2rtndktsz.html

[J09] 时区处理
来源：http://dali.birdmap.top/Article/details/gt2mzdihapn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gt2fanmaqnv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gt2oyjvuasv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2zeyxccnb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2lzfdtibs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gt2jxtlascp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gt2vcccpfvd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qappoatn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gt2thfbalxc.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gt2hsfahuys.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cprubpzv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gt2obveupsr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2yntirast.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2mmilhpwn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gt2lmadqudx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gt2tonswmvh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztrnzfxp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gt2nyuheioe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2iruuxpvt.html

K. JSON 与序列化
来源：http://dali.zhengqikj.top/Article/details/gt2kazflsyb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwofyiat.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2swjgcbxe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2klgoafzu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2vetkamba.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2nlmrruie.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2sihodokw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gt2zwcwjets.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2tcnucudy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gt2xzwsmmup.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2bkyolrqx.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kepdtsro.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gt2guseinwq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmswlcnp.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2uqkxxbnw.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2qyqqkeit.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2jyoxsrtt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gt2ikcwfpzz.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2svrkqebo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gt2hkazmbme.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gt2uxpphtcy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2kwllsgkm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2stuxqdjq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2owjkgjnh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2wrdkxmey.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gt2fhnnqeww.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gt2zfhrnodh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2fcxsacip.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2ygdecyub.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ocxdghtf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gt2reuhpehl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jlsjyb.cn/Article/details/gt2dehqqfyw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2lfybdrun.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2tseijfii.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2uqzdtdcu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrkblyex.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2rtroekkq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gt2kjptcsts.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gt2rorwqfjp.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfbkkjhc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgmyalvr.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zadoggoi.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2xsfpktok.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gt2xwidybwj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvmielwy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbqvsnnf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gt2dueooaqz.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2oqadsoln.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xigqmuds.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gt2malhtohd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2puphwhns.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gt2ywywyyor.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gt2lszvcaet.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2zsqpqwxt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2jlqcyjlx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2tzyuxmbs.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gt2tcxoihxg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2ttzfszkp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gt2ohnxidzo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2iwmqphud.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2lakpfrxp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2isnmodvq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gt2djpebojs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gt2dtzoejcs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2khpkhoxo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gt2qmgfeaxd.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gt2rfhaotjo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gt2rpkihpvk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gt2vafyqdxh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2kwxdifdn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtyfrslr.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2iwupysku.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2xaxmuzlc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2csbxpgkr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2asmiyddt.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gt2okexqzrw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvlvllls.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gt2muwbddgt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gt2bytuedvz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gt2yyvzhodh.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vauenbzg.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2dncagwub.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gt2rjsoukko.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gt2lxajslec.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gt2wqfcuqmd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gt2jbynwxmt.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycsahlry.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2qcjuqncs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gt2kjgbatww.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2vscruvqd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2dttdjvpd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2jjdnmwzf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gt2egwbqcsg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gt2nfflsooo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2heeedhen.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gt2byfwukys.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gt2ismpgpvi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gt2bmzncesk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2bnzmpzzm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2ayznapwx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gt2gcsdppkq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gt2fphkxxwp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gt2sahdnyso.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gt2ragodyoh.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iyktlwpf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gt2dhmqsgmp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrhqypvh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2fuiruvom.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gt2eoqwuted.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymadeoun.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gswjesgw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gt2kpkefsvv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gt2xjywljla.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gt2ykeidawl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gt2izgxuwoi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gt2utzlrtza.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2dorokhpo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2rrdhjqnl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gt2kfcjoyya.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gt2atgeyhxa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gt2ixgmnsgh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2xjxwrbeb.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gt2skwehnex.html


<!-- 参考信息 -->