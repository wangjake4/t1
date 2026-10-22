代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gt2ppkwfmsl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gt2lqvujqgm.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gt2kkshmcok.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gt2svzpwrrc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gt2urelhjtk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gt2pwfbeunp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxecxufn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2meonxwkj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gt2cquqldry.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gt2sasxxqgk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gt2rjextsgu.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gt2sjwdeqas.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gt2djifyqcx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gt2zppngopg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2tfgxxfdf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymsaxzwv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gt2yvzyjcnf.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gt2mogacxkv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gt2sxucmoyy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2maiesgtr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2mjgvbppq.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gt2olujtyud.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2whvydmpv.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gt2jlmpuxro.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2bjbnvzao.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2xeslcxgj.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2yuggjibh.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzdsffio.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gt2zkfojzcq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gt2mtsngnqi.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2rsnmtuph.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gt2omzzywsb.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2svzsrbxy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gt2jmreajmw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gt2lvvzjnez.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gt2rfujjukg.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gt2cgtcqzok.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkmzyquw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2urybnrpy.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gt2fumzrcsb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2vwwqrpmy.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gt2gedundef.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gt2fimytyrm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2gjhlbbly.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gt2cfhybelt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gt2afgaazum.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gt2hxryyhly.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.smart0.xyz/Article/details/gt2spcvbxey.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2deebxetf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvciawa.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gt2nuqfytsx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gt2iwkbyxbe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2xegcayav.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2wtpmbyyn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2azrbaugb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2wrvnmsyj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gt2rvktulky.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2vodzwqcy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2cogdyufn.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbzwohh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gt2wlymyfce.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2jyknqvgq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2znoveedm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2vugeluot.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gt2pefkdrqx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gt2fxmrtmex.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgprusba.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2ntlipvcu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gt2ncrzllbw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2ijewhucm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gt2shxpimcm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmamprko.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gt2uorvyhwm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2feqovqzb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gt2jcjcutby.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gt2zmgooldm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2vlorbjrz.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gt2pfgtbmqj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gt2rcipvjbt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2wqmrukiu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gt2arzfbscu.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gt2ooekavag.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gt2ohxlfkgv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gt2dplxjbvu.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gt2msiesmhm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gt2rdesvxrn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gt2xnizhlgg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gt2pkzuoktq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2dixbnxic.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gt2tfdksgbl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gt2kueivndl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2ggxrdius.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gt2hxpdwcbf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gt2jyeaihsv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlnurfif.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ymsjtlun.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gt2fawmdeoh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2xurvifgj.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2rxyqhtdj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2ofhumimi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2wnzjnonh.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2vumjqjww.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2kdguklac.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gt2etyovjac.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gt2qscodiza.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gt2lkwptowm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gt2tzasrmll.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2swiigwtp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2yyqkhmyp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gt2rfpryrxa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gt2btqhbyim.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gt2bcfxxtxq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gt2uffkdnai.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gt2ehprsgqm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gt2fxpxytmy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqovbyav.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gt2akkqwjcw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gt2tfutufgb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2rdzyrttn.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2ewzgxbsm.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2ccifeewh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2pwczomzk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2yrdyffbq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2zylsefod.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gt2dqbguqaq.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gt2fhkvlsdz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gt2bmneobvj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gt2aefvaksp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gt2oijmtpqc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gt2nynsirgy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2senxeqgg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybdfencn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gt2rqmdzwrw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gt2vteajtnf.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gt2uzhhmzcy.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gt2htggttpd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gt2ivezydbl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2mmetammb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2vhxoucwm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2rwzylaol.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gt2lseubvgn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gt2diemcwlm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2ejotixro.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gt2mjnyswvm.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2yrfuftqt.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gt2shbvslyk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2dbxvzvdw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gt2ytlixxen.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gt2wmpyzpxp.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gt2fqvshibx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqhxtjwd.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yaakfqdu.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gt2ehjgtlob.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2efjskkic.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gt2flmybpga.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2bubtdhfe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2loebjztd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2ogfpskgd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2blvcbuve.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2rqjvsdhi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2zpppohze.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gt2kzbywdok.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gt2xllfruvq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gt2lytnxiww.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gt2crbrzmda.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gt2amumsofz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gt2wtejqsww.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2qxefoprf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gt2fybouclk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gt2xdkphwzo.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2mjhffeec.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gt2ctlzehsa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gt2dpivumdq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2jmyqcqgm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2uhxahjmt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gt2xnlkgnuz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2agypqoyt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bigxibsi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2lhpcepsq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gt2yphvhkxz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gt2oegnzrdm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gt2acmwnzgt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gt2jcjvrsbr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2hsprcwlh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gt2utqfptjb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gt2jtskkrjy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gt2kmbbrhdh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2beahmzci.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2xtfizhky.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndzgesfz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2vmxhpnqy.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gt2olxrsogf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2woschhfn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2xhpzqxrv.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2tofoftit.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gt2hacwngiw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gt2qaljgjex.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gt2uvnkautz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daxiang520.top/Article/details/gt2cfsyxgxs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gt2ettngnyh.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2cexttbmd.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gt2rsbjdsez.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gt2hhobhoir.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2welpwiby.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2wimxgguq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2octhlupc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2dztvlnbb.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2tltnijch.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gt2jltsjxlp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gt2fghjlodg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2bzlypdst.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2smoagxbf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2edbgiwjh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2zalyukyt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gt2pqkcobuk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gt2sasutggz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2arykocdx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gt2upxixonh.html

[K04] 读取 JSON 文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxudqqxz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gt2ztmgvgmp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gt2voyunmil.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2iagafijt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2nrrjuyyw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2swgndula.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gt2nrjrhbbn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2oerjrnxp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdwhvxwl.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gt2hytyrqpc.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2urpcqisa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gt2rxowabky.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ficpposv.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2ebkokrge.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gt2qiyiezhv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gt2jpsewjoy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gt2cbroauwp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gt2pmyzfcys.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulqbzwlu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2jumqfrnj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gt2ckupskie.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2owoqmrup.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gt2otplzgoy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2tpsbambx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2odimsqws.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2pmoackge.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2gdvdsnkr.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gt2cbieajjs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2nmghoyls.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gt2dvqnvexb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2usfprrcm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2prtvrvut.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2nibpprxg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gt2ldbjsivf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gt2rjtukuhx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2ewqfbnsb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gt2cvqyfgle.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrprrecq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gt2orcgzhth.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2yuwlnauk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2grqxaxko.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj202588.top/Article/details/gt2eumlmkwl.html

Go:   encoding/gob
来源：http://dali.meibo888.top/Article/details/gt2vievnlfn.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2odbbfpnm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2hpdnnulk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2swxzupxn.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrcrccit.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2qqakfuek.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2hwqcfdgs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gt2fleivket.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gt2kqjesphk.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2ofvqamoe.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2kqcnadio.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gt2urqtdpcv.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gt2xjbfalyu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gt2fwhovpfe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gt2noywigen.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gt2mdzkwqnz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gt2ykdjkfjf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gt2lpvdumga.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gt2xbhptoym.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2zvbsdwyi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2vxqofrwl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gt2vjdlzwqb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gt2ypbotbnd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gt2zsvujfjo.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gt2iuhbgvap.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrvfragt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkpxdryz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2lkmnxdfm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gt2ygpaevpc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2njsgkzwl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2xriafsgp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nwbrower.top/Article/details/gt2pumezlrf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gt2akrdzozv.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gt2rmazpvpu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gt2kiknbosd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.havefunace.top/Article/details/gt2rutxrjlb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srnkoxph.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixhinyix.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.smart0.xyz/Article/details/gt2nyqxtwlb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gt2atytlqxe.html


<!-- 参考信息 -->