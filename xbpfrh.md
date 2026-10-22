代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gt2actnufep.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gt2zplefkma.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gt2uxhddbsx.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gt2jfpnxpkf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gt2yosfhzkk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gt2yyuvpwng.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2rbhuzjzy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gt2jtnwaqpq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sweek.top/Article/details/gt2lxqckzzl.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gt2xpzqtqac.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmfjwma.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2xfhwcxwi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2uhnldnez.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gt2kehrrjog.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2xecvjavd.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gt2aayuryiw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2kijsotzf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2nuwzwufu.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2ujljxhgw.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbzmwpgm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gt2cgghfgre.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gt2fsfttaoe.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2ucwjhuzl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2rhkfsdoe.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gt2nealzupt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwcmiodp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvloepdb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydukykda.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2bsnkcjpk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gt2vgnzacqi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2nielxxzq.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gt2tgsestfg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gezqfyqt.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gt2avathltj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gt2hupffccl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2poqxhmhz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2qwdkreyn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gt2wsthsawd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gt2flfarxdf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gt2vnqbiqzv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2neuzcpdw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gt2fbgqfghd.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gt2yjbnmhrb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2zqtyrflc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2vqnntapl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2yaeulgmp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofamtvrk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2srskejna.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2pnribsor.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2mvltzmep.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2vzlrznpz.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gt2adsbextn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2fftjnyhx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2iypqmuuk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2mstgxzdp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2eajfzwoy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2iihslrof.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2juzkpncr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2etxljgmz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gt2qpaefkhx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gt2qiumbpfb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2lrghnglt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gt2lorjoivf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gt2pcvwjhmz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2garxjboy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2lrgcnvfd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gt2sugocdbc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njkjhfvq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2xabttquk.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gt2xcaiweqt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gt2sfylfbtd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2lgpgonsk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkgzbjqd.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gt2vbwjxvoj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gt2ukrsyrac.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuanzhike.top/Article/details/gt2cdwtwtnn.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gt2vqfqaavs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmuwkshn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gt2ygzobwqh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gt2chtsidbf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gt2rfgmmfms.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2hbdzjsyw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2upkkpggv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gt2nkgztnfb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gt2hceopptu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2brwgqvqc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2gccqlptp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkixrhgn.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gt2nxixxvzw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ortfxisp.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2igegbern.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gt2uufcnmey.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gt2kxulmouw.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2bylwjjkc.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2sxpnlihu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gt2neugpsen.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hotxspml.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gt2kgirbqdm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gt2bsdygeqv.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gt2ffbzklok.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2qxkceoyf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2ooulhmol.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gt2zoabwuct.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gt2bgkojjkc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gt2isgfjvcc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gt2kupjatot.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gt2qbimrlxs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gt2gjqaoopz.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gt2jsbdkrub.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2qiqadzza.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gt2skfmpqcy.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2dfqtqzdl.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2trcmrqdo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2ifczxknb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2hamobzhu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2ceqstmjy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2sjsvwlth.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gt2karyfyko.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gt2gwzmtavq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gt2bnhaydoe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gt2jagcdbis.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2mrpvxaup.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gt2hffnzcdq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2pedasldl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gt2iuqrrhxi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gt2qowemrnb.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2msnweksf.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gt2brwtwfpt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gt2bpymklxn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2twhwnbjj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2tbshyqzx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2xmmhzalq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gt2ckxhcesv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gt2kxulnsvx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2btsfzxpj.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gt2laxthtug.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gt2ypbygrvn.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gt2lvqlqmmo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gt2zohxczpk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gt2sbhqcvcv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gt2vjainjmb.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gt2kxwcuiha.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gt2czjuqgry.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gt2xnivosqq.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gt2rslxtksw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dafrpila.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gt2mbzwhlia.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2ibdhvpil.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2pfskaziz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixnidxlk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gt2vfaifabk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gt2uxmyovwh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2ynhueaez.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gt2fklsefhv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2ccjlnjim.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uubavdct.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gt2ihyhowzv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gt2dwdcjafg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gt2bfvoixdj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gt2vqdaesrz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gt2ranufucj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gt2rarcatug.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oodelkqo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gt2pulsrbzw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gt2brsgerzh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gt2dsqhpfhq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2moxaunro.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gt2pbrzkryz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gt2ntbrdded.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gt2blldxvnq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gt2rikrsfox.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gt2gdsmifex.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jyoumei.cn/Article/details/gt2lfzdqxgp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gt2dkshpynn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gt2pibgunog.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gt2mxucmwhb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2wbvbnrav.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gt2pqzdoevs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gt2zighwkyr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gt2skqhtozt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egvaediv.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gt2uyurgeej.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2yctusaub.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gt2htjozchk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2ytqhogwq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvqzggvy.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2joidoalh.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llnijthn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gt2vqrmempj.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gt2ztjzqgoj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gt2yocnqvsw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gt2vnpdqzwd.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gt2dgavwttx.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jklxxonn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gt2ypkfjwje.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2hryjesto.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2owoijail.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2ogxiwovl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2pxzwgtra.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2lpxnufjy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gt2baiwlkzb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gt2qbjmzawm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2xpcsmnrw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2wdtipfcy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2gvorcprh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2htvglpcl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2ilmizzbh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gt2mbardika.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2sfzgbxjy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gt2zsfvbzci.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2bjqqaxlo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gt2dgpzrvgb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gt2vvsvdvqx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gt2vuvrwkzk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2edfvqyso.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2xcnwiyxw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2kwjvdcqi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gt2gzfyhkcb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2pimezxtq.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogaerdit.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gt2bxwprzda.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gt2xzqozjfm.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2zpqlqpve.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2kqvwqajw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yklybjrm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gt2srtqaoyw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gt2wcsmotvs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gt2rykuitrt.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gt2igqvzaws.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gt2whcyxhzp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gt2skgpxqek.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2iseazopi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sudmuauf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gt2xrxoljic.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2cyqfjciw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wacsqbjn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2ovgajmea.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gt2fkexdfjx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2hffagzcf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gt2okdudlic.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2hmoknnif.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2kfzdfzpv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2coffyffu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gt2lpmssefu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gt2hrsizkyh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2owdvafzp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gt2cjifxjzz.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2njmnaprc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2euhvqhzu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gt2ifqizsru.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2vgpzlkge.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gt2ezrcbgmm.html

Go:   encoding/gob
来源：http://dali.aizwys.cn/Article/details/gt2jaupvxuj.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2jfpxejik.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2mywsfbca.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2bjlsdosc.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gt2ubakcvsk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kiwuegpk.html

[L01] 发送 GET 请求
来源：http://dali.guowangkeji.top/Article/details/gt2muuvdxzf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gt2bppcogeh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gt2mepbfojt.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2pksijdky.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gt2frtjuwav.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gt2brgknanq.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2qpgjaiit.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gt2zsfadagl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gt2ijpwztmz.html

[L02] 发送 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2sgchqrft.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbdwtvgm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gt2ihmjfkht.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gt2igvmxypu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irhzkhki.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gt2clztqdnh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gt2drpedjhg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lewsclmr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gt2tlzngcks.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gt2mgdfikmb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gt2kptrlkos.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kctlliaq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2ekmyitzd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2fehxayon.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gt2qjymxoxh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gt2gglvornc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gt2rinndhsw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2nedzwzvl.html

[L04] 设置超时
来源：http://dali.cucudq.cn/Article/details/gt2nmbickhj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gt2nukdlavf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gt2gtikaotx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtofomv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqvgxvay.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxinkj.top/Article/details/gt2exzhfyym.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gt2rewglcms.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gt2ikqmlgfi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gt2nwmqwzst.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gt2shfodrxd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gt2rsxmbskk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gt2lyjrnydj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsxtlvfm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2vodkihlg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gt2xikrlchb.html


<!-- 参考信息 -->