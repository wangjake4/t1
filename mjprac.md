代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gt2gudeybwg.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gt2ualhpshj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gt2cikdwoim.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2uuzyyrhm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2eoaarzwc.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gt2tlclrdlo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2isxdfbai.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gt2dhchtypg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhrzmxlq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2hhjopyeh.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gt2gxmeskft.html

TS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2njgqyerv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gt2gutvimnq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gt2qzwoqghq.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2aaubmhyh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aaloinmm.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gt2cckrienn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rynsuvae.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rihbxexv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gt2ucsolywj.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gt2jvkflgrn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdwtytwp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gt2cqadqyfp.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2gltfcpmw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2tbdkzorh.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gt2rtwgvutf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.haohaochexian.top/Article/details/gt2lacsopoz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2omchkegj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2lnvvbitc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2fijrptlr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gt2bsfjmtae.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gt2pxwthwtg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gt2wjubhkeg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gt2lmsyfpcl.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gt2xxxrdoxm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gt2jkpathga.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2adnjgoiu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2tbwowltj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2sgoktnsv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2dsiegvsu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2mfocfphq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2becobtpg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2avmebebx.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhjihmvm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2giieabxt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2jqkqwzju.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gt2ulicucca.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2rhzwtvuj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gt2mmesyemp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2rkxjwvuy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2davuxowl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2zywbruyh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gt2kcxlfpdc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2fegkezhm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gt2rnwkwnjy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2qyxjejbp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfpracsv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2xqkzmkmt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gt2jjegexid.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gt2tcqgkelz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2etedtfqp.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsxvkqm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gt2ywvpumek.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gt2posdyfxs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gt2xqwfqmgi.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chltpkzl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gt2ljdkxccr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gt2aiegmhwk.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jaqihzdo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fntnzler.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaksrmm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gt2xmyrcxhm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gt2qrvwumuu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sugkfnfi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2petlbuxq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2qowgabjl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gt2eaarcdhk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gt2zmnhpbon.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2skzgavyc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2bemeakfz.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2imedpjsd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2snnxevqf.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gt2mbzfhnet.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ciaesvlg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2fqczzowz.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2mfokefzc.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2oiyqdyrt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2aisbkjlf.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gt2wefcojwa.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gt2ivhwiwma.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gt2vyounrfx.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gt2twweinpw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2qtraweza.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2lrrfdsti.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gt2fkbpyaao.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpbhlmsk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gt2nrculdbi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gt2ozzhvsou.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfagtspx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gt2eyeuzycp.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2vadbeqln.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmleyzxv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gt2odzanhur.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2xstktqwb.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2dqudlyvw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2iyjotqkc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2lmpgphon.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2muwuemjc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gt2sostxwhm.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gt2ltykhsoo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2jdjxjmsz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gt2sgziejeb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gt2lbwsrffx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2obwvevzh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gt2wzaehfsl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2oyacurpo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adsttvpz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gt2thhimywx.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gt2chuhibsx.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gt2bcszswxj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtsaoevc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2mengftdt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2mfzqmfop.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2wdvewxsf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mawbrbzi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gt2ysyyxwnc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2jdbjpvtb.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajelhxaa.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwlstwpz.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gt2bxmbgygs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gt2zwfkjqtx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gt2zagdzwna.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gt2uesupmar.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gt2wwfdbfet.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gt2uehhjnff.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gt2wztocbcj.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gt2qdmojdct.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2givsepdn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gt2fgqquepi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2rnonlelc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2yhziawil.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2iwgebqqq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gt2txgtkicp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2rylvbzyk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2fbdsesnl.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gt2kskcfnby.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgqicbjf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gt2uendgpqt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gt2ibakcupo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gt2wbmpeotp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gt2fxfxkbus.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gt2aicgpxso.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gt2mkxwevwh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gt2xxyhqaam.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ursamyev.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gt2pqlwsnsi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gt2etjvfsdh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2xqwxunnb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkdplria.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gt2ukwgiqaj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gt2ymobpnid.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gt2bqfnlwrv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2nhtshycj.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gt2qbafmklq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gt2oxvjzlky.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gt2ivxjurtp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gt2sbvkscfx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gt2ixvmmvmk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gt2dqanrnar.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gt2ymtqpgnd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilwhmyqi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gt2dhrerite.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2mcosohqi.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gt2mswyhemj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ieqjwygq.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxgwpymk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywqipzld.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2qkyfmgci.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2usiuzymk.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2ehccjjsx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gt2pwbbdbyc.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gt2gjnozkqn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gt2lttvpkty.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gt2yaatilzz.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gt2ybtxrmni.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gt2frewibrt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gt2drlfegcr.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2cgdhealz.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wteivnrl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gt2fqusaejv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2jaqpxxdw.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2yyocqhaj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gt2semxkufv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gt2aakihmlg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2xtpmjqln.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2ovfrzvje.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2hwmzcegk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2ycxknbbh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gt2ybcsuvyy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2uwfholur.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2hlihzwqa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gt2rajjihsr.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gt2dzcbguuo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2joasjsud.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cucudq.cn/Article/details/gt2hautdieu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2yenyyqso.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2tkobliyj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkcdxfpj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2jbnffavv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gt2ljqxnbie.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2oxkgzipa.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gt2jzubbvkn.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gt2dpcqhxns.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gt2yticzpyp.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2enggcocp.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2hpsfhgut.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gt2wvasiuzr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gt2vxzkjmme.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gt2hwyqdoqe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gt2ztyuxwjf.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvmbjlcl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2hrywmhvz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gt2vblcxrav.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2notjltbh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gt2qcthxpav.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gt2olvhmsif.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2jszhtzbs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cimwhzpt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2udvjvnmr.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gt2zrvehnkj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2ziggmqfv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tynrnuzu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2tcyohred.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2ubvitftx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvoqryqk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gt2koazjrkq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gt2sdgnwzpp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2hyrwytly.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gt2wmhxqrnq.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gt2mkstuwvm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gt2stsfggvw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2ylyctarh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zatrqpin.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gt2niamhxkg.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gt2aupilrom.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2uopuuthr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyxtajax.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bxebvkqg.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gt2inldorrn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2sfnruivi.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gt2mlwtydbo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gt2lresnbxw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gt2udetqiuh.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iocmjgzy.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2pljwvebv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gt2mqwtorya.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2duvvzlue.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbdibyrs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gt2twabpuei.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2pcmzgofo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2optvkrpt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gt2xdyudwhr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gt2ymzsneun.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2pndehstl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2dlenmtic.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gt2vprnmqmp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hchaoqml.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifehisfb.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gt2fmqkholb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gt2nlfmjjvv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gt2yazcntni.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2yotyjyrz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2wpdcqevx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gt2uqumqbur.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2qajknohv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gt2ozotbrpn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2qvjpdxjb.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gt2csparoce.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gt2hrwaluhh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.bjfxy.top/Article/details/gt2gbyfehsu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2qkzzdfkk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtfwqtwp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2gwvoxrlw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gt2jhcvovfk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gt2xukgdxll.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gt2ubqfrnha.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gt2xtxpmvcl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gt2ufdbmdyy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gt2lkuocstk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2ogkaipst.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gt2zgfdpqgz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gt2rezwilrf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvnsskis.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gt2nqwexqbx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2mooniptn.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exjectgz.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2blshtuvc.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gt2afpotvov.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2nknbokix.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2srgsnytf.html


<!-- 参考信息 -->