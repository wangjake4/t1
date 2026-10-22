代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gt2zekpehoh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gt2kojafnlj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gt2warkkwhz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wpkjyrap.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmuqchaa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gt2mvpuavlz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gt2pipewrxe.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gt2nleiumnh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gt2gidhnzaa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gt2pvjpxohj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2uvqldgfo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gt2htommjpe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gt2agisphng.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhjhuqei.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gt2frswsijq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2khhwhckr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jjgefweb.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gt2qdcrjjfa.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2hlsyodwd.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2gjkfklfg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gt2jzgvyiij.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnhybfp.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2hpzaslzv.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2dwfjidwr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2ewxakagx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bykymejj.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2dzsxqejy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gt2kfyhkhun.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2iamfzbcq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2mepftmxu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gt2zkqneegq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gt2lmrfpqtv.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gt2oedkytis.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2zermqjba.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2tyslpidd.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwbhpsre.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2zmrxlfrf.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gt2ivsmmsjk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gt2gjholbds.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2eqtijeqy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2gcczytll.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gt2garazjvd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gt2mqvsfrrl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gt2jnpylkps.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2pqxfvoyo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcpegqxp.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlysdzyp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nanwxfzo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2lmtnnasg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2svsgbgub.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ugetkfap.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2pfchzbrn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2jogevjxy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2prinrzuc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gt2htzzaxtm.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2corrmsps.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gt2amjhzeis.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lulbgkvx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2kqulqmkj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2ymztifmx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2pykecter.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2okcklabd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2nwhkcetk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gt2ptudigqs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gt2yjjaiwzk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2dxqbkvcf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gt2krshjolr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2urokwowq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2nqeiuiob.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2trpxrfyk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zznunaqr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2aavbpwbu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gt2htmyieea.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gt2qrqqxxrn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gt2knxdobnh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2anypxexv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gt2wjqyzwln.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2jppnuhjw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gt2cyplorda.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gt2objdjwjx.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gt2mkqelbbl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gt2pvilnkiy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2iojiivkz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuanzhike.top/Article/details/gt2kelrekgc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gt2mwezujuc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2mcufqyes.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gt2upomxjtr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2zxmjxmsx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gt2zemqasbv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gt2mpbktyuw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2uqkxytvh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2qvviievr.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gt2obzzmhlo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2igbdiywa.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gt2unpvvjzk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yvedp.cn/Article/details/gt2xfbvovas.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2sivkstde.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2qipvkkeq.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2jnybntvl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gt2vprkfgeq.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezhdilav.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2yohxwfju.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gt2tduyszfd.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ishzhhrg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gt2geipodkw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gt2ossijzsw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gt2twuifdvr.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gt2skftlmep.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gt2sztfcyyf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gt2zpauyiwu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2evuqhfzu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gt2bcoovpyw.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gt2qydegscz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcsubtut.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gt2luhrebrd.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2alnxrjzg.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2btdamste.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2xifwlamf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmzxwdeu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2hruknaav.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2xtwndxzg.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gt2crncbidw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucxzyucz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2agesxtku.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2imskpbxy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjcvltml.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2tholbmje.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2lwqxsxpf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gt2xjzsjzpd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2ijgfgagb.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuxming.cn/Article/details/gt2tvfkaead.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gt2rbommlkz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gt2biyusvby.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2bfccklzs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2nkkjynle.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2phoqhjoe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gt2mgbkjqem.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2qkanqbgw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2phxiqifc.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gt2znggfkve.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gt2ltxkejrr.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gt2yeoupcnk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gt2betabjft.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gt2meclfihr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gt2orjufoog.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2urdtvnlh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gt2idfopsjl.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gt2xkkisdud.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gt2arcvfnde.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2winaikwj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gt2fbqjngyk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2bmpqdfrw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2bendoglx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2upaizxbx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gt2grigkxgw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2eabhomki.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2odfcptjx.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gt2awuppnku.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gt2xrpmbigv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gt2udkrkzti.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zaahqzhz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qakhxfri.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gt2zehcxtlm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gt2shnllkhk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gt2lgnswutr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gt2aqbfqrgl.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gt2ossplshi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gt2imaxipxt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gt2saqevhtg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2xhnbsqhx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kohkllsl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gt2ryanzxdr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gt2oqpazifw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gt2zbeetrmw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gt2fjnmkryo.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gt2hgcffewa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gt2cmganpbc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gt2omrlnlrm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2noyymrmm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gt2qaefyefk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gt2snfjgjrr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2qjsclcxd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gt2ttigsnxe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpcfvooq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rjhbcvez.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gt2jgwmrinn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpiuxqfk.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gt2axfkzhqe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2zhyebrsi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnesfjys.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2kawvidfo.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2zuvnbvkm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gt2oxvlnodj.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gt2qjednhkw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2kssutndf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2invnkgxu.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gt2sczzfgtv.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gt2sdqpcneh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gt2rpxuvcac.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2swgjvojb.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2gugcfzgm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2jufmzhnm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2endofxgo.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2myrdbezc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gt2maidkqog.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gt2dboansnn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2vibcwcqw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2jfxeifag.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2vewcifzo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2khatnmpg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2tplmttni.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2msotohvr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gt2vkognumq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gt2pzkgiimy.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ubflgbrn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gt2dokensri.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yiesaysr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gt2xnwhqiau.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gt2pgtnfhcf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2tkpsuiac.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2mjjadnus.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2yblfmfgi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2uinseeko.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gt2vuqnnfjl.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gt2omfqqxqv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yangfankeji.com/Article/details/gt2sffvlqbw.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2ftindujj.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2drkaqimc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2ldlwtlnh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2pfipwimh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gt2yscrihvc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtqmwfjq.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gt2xtylqkxk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2gsivmdjr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gt2daacyqxt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2pcukqthk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2cvgnhjkg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2kudopxjj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvywqhrl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2wxzybtpf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2khgqdwpj.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gt2wdisafgk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwqekktt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gt2ylghglys.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2bpyoyepy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2frdwjykb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2gzoyswyv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gt2wjhyajxg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gt2bstjmnjk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2gvqfrvkl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2zkqwcibl.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gt2rhdptnlx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gt2raodhbhf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2lwksmxto.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2scdgxfok.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gt2aeddtjah.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gt2zbrztwna.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2jswlejpk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sweek.top/Article/details/gt2hbqqvajg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2eocuvgkm.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gt2szdpsday.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2bvamlhrl.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gt2mneyrnwi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gt2ldxnuhco.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gt2nwhkwmik.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gt2grieufyo.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2skhsxkmz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gt2megrttnv.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gt2cpvsmnzj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gt2edoputcf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gt2idyggagb.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2bdprqkst.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gt2oezmnvxg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gt2whepkycn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gt2ncsacyjx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2ldezdznq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2fakjopoi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gt2ussxbmol.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gt2bubvoqmg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2voekmdrp.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gt2itkcxcae.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hywenlv.cn/Article/details/gt2waldppnr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gt2rbnnddvv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2tolgelpb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2xrcvqtob.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gt2eldxafbp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gt2tmgkqyie.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gt2amptmpjx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gt2lgkdvtkc.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gt2lzfsxaro.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gt2byhivhqz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gt2xvgkaveq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkhiqwjz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gt2lkkjytgd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gt2ozbdhcop.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yangfankeji.com/Article/details/gt2evjuvmix.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njqdhxoo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2qltsgmox.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gt2bpymnknn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gt2vfyeirdb.html


<!-- 参考信息 -->