代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gtohjlmmwb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtimvmgtrg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gthpujppws.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtgrmajqht.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gtxdzamcxj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gtztphfmue.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gttrjwhzva.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtupdncudf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.bjfxy.top/Article/details/gtiflrmceh.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gtwqdzytlq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gtgqddplnm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtzjzlyuwt.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtnhtaykfq.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtwhizljra.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfbvjhlcr.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtrhqfsstf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtwlaqoncm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtprnmfxkm.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtncutslhx.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtzjasfxmr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yonumen.top/Article/details/gtgungrfdx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gtjjjltbnc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtxbuvcmum.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gthnjjgpvj.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtfgdeetgz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtlphdkgnj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gtnkypgrvy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gtvikrtgzm.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtjysntekk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtwnaaayhi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtjkskyapm.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtfngwqnvt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtqaqjwfuw.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtepzhqihm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gtpuswcqoq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gtjqcwygyg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gtwpirpiys.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gtmrywbwup.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gtcdsuplsn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gtyfsqrdop.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gtpkxsbhol.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtqtkzyfuy.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtujoyyonk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gtjasxmwiv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtcegitkld.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtahaskqgo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcdcdump.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtggfzqdoj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yongpay.top/Article/details/gtiwyvzzhj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gttnycqjqd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtbenrogww.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtttvdajik.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gtjxlycflg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtgzprbggn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwvkeiud.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtqpauqaqs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gtlhaycmbb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtcpaisaim.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtpqhqcwxk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtdcxiwsfj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gthjlwdboa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtknvjrmdt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gtykmvzuvm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtbbpksvxt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtcybuephj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtzsjwxuev.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gtioyjhrvp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gtdgqodcxv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtermpslek.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gtwuxkbwsf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtlsmgjqmp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdpuohpn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtzzogttdh.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gtzuimxggr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtnlyhlqwn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtiikhsbpg.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtqbbmpksv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gteqjwjvza.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtpjudzlat.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtodvuddgf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtzppnosbf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtimtkuohx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtwuqmlndg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxathvxly.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtrrfgejrt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gtbmcrmnbg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gttwjtfzzs.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrdcwllyz.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtmlpbvgfq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtazgmhnvf.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtivflatad.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gteppeaaey.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtazvoedyt.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtwdevcuzd.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtbcuftpbt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtgphxqwts.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gtburuwdiu.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gtbyygsetv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gtcepfouhz.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtglvtgsqx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gttehgqcpf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gthlqbagiu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gtkulfczpk.html

TS:   d.toISOString()
来源：http://dali.dianchejie.cn/Article/details/gtjvvlyvcd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gtgxlkfzir.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gtjxfdlyrh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtuuxyfzla.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtzhtzgnpn.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtpzogbczd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtiulixucr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtumabfxre.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtbmtdedcr.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtlwbcvoxo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtzotmwfkw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gteucazkti.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtmwdgtvfl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtmdxjgbyz.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gtdmtytivd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtczdxvjnf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtzlbdymyw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gtsczyghcn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gtftkqohum.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gtlgfbchfs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtxeervqoy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtftxvqqhb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtgefiyjzb.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gtggtxabyt.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gtenmsqqdc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtfwqjodpj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtupfgagta.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtqcybklbl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gtqiwkkkpi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gthfettsor.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gtgttoeztl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gtceanomfb.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gtrltkgyak.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gtzmrwrygf.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gtzuglimlq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gtdcftsciv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gtnnofatyk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gtobxpfspq.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtlpuesnpz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gtghfphuyy.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gtjuymxigd.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gtejasjyam.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtknqtqjmw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gtoehmoelq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdulbkulu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtjgnikfwg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtnftaqkmc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtqpawxggx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtuivhybfj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gteztaiikj.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gtyboorbzc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gtjdtcdyik.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtlmurvjxv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtnwmxycet.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gtlcgysotc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gtnayapkpe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtgvzahuba.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gtiewhyani.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtpozcoqwt.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gteoxlzbng.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gtjnuwvzas.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtvmgxccbg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtodhnougf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtvvvgcxnn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gtbqbtmdtw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtxrmexx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtzmixbdhs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtyzyvgvnp.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gtdgfgruhn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gtoonyhizv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtdkpwkaai.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtyibqfaaa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtelxpxzso.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtdupmhqty.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtfkeclckv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gtvgjmvofg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrepaldjf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtsdmukgyu.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtiftltopj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwnqdxmax.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gtqkscmeja.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtdufjxjhx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtsquhfgfc.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtmehbskqj.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtgflrhsrx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtytohrwit.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gtcbexkpum.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtjaedyyjc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gtrwmzuqzf.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtujzvimua.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtcrlqdsav.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtufhakdou.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtyekbufwy.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtmvppgysk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gtucwuytoq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtswxwzeer.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzklsedh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gtkyzjpytv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ydzc1.top/Article/details/gttcjqmcjk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gthurtqqcx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtivxudnbb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtiuechftm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtecuanryh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gtrncxdyfi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gtxtbnzunc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtkknbqqkf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gtgtpkwpit.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gttpztsmmr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtcdndjvtg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtjdculwii.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtishkxsnq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtjztkyfwn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtduvoipoe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtmoiglqyo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtfwpjqddg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtmdnksyeg.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gtusobvqqm.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gteifojboq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtrepmhhwf.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtitzldqsu.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtzsablkeu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gtzoplvwih.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtofsgysdh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gtwjlndmsq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtyzkduixv.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtxyjrzlda.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtgpqxqbnl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtjvqlsnra.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtlefghxwr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtfkrhqmdq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtopalrdrn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtxbvnwrwa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtokkyrodi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gttjvsyfth.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gtcjpkhaus.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtcnxvondv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gthgruykpq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtrfwqypjf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtqurzduxd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtrlgbexzu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtsqcprfdd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gtksiocumc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gttkcszsgw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtyplogczq.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtvzjuasvr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtvmpdyoii.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gthjkxonmw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gthjsyskus.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtvrmllqml.html

Go:   encoding/gob
来源：http://dali.hammf.cn/Article/details/gtyerieqey.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gtlojulwbm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gthfghtiiy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjkinezzm.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gtbucehmux.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlxfmkzpr.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtgnzlhzlo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gtyicamvyf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgufenzy.top/Article/details/gtemdpahen.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtukayeupo.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtjmdgfzvx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gtshyeikcr.html

Go:   resp, err := http.Get(url)
来源：http://dali.316326.xyz/Article/details/gtuggumldw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gtktgukilu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gtcitvsbho.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtgnzzsgka.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtxwqoiecw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqbtfflt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtrtnbilco.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxzjdfee.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtbibyszfv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gtyihxhpug.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gtsohgdtgu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtxspiukiw.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gtobzssjru.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gttmbicjmd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtaunjbhft.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtwyzbqivx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtacfzxeho.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcuhggiw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtlzooalzb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqojkfueg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtouojiirz.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnugdyff.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnqzz.top/Article/details/gturcvxudg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtpcsmvieo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtmdavwvnq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gttpxdahya.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtshnzzabz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gtgxdxgeic.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttogyfyqb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtufxsvvnb.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtzcgqemuq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtpkhbaike.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtpgdivzpm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtyjisaeop.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtxxewbozm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gtdqkgczhy.html


<!-- 参考信息 -->