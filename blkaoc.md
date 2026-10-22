代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gt2xceoibvo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gt2dgdxheyi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gt2cwgpvrca.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnqzz.top/Article/details/gt2paadqxir.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gt2cjxzsjhq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ooerzkua.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gt2rpuloosl.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gt2vksqtyto.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gt2xorubjll.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gt2cjzlkjbl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2nzbxgenu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2kmenszaz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gt2gqjibhcq.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gt2ehrrsnun.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gt2uihirhrr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2gqcvvdyy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2orajvieu.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gt2uhunaftt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2lpghkvaf.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2dairwxii.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gt2mgflpsoe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2lipfrkpf.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2osokhead.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gt2cofsjzce.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gt2sgsmvfpr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gt2euqvwsok.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gt2yzudrbdk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymggandf.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2kekjjjpp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2gjtjwpij.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gt2irbiakxn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gt2xjlbgddy.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvqhlhzp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfoqzwps.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2sdsbobcc.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2dgnwnlhn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2kmrgruaq.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gt2szvdamzu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gt2avfpuyit.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxaotezw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gt2wtoliaug.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gt2labjcnsg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gt2qyonwrbc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gt2dvijdjnc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2eaydfznl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gt2nizthhis.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gt2rcaidksb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gt2fhqwrrpz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2uliosynj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2hsueztfl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvrqcrbm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gt2umapyzxw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzpdcqjw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2asvjwycx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2jzhjztwk.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gt2xgvlhxvv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gt2ngbggswh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2yjejxexh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2xxeixtbt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2nfbifrbb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gt2zzgpqzlo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2rtnsqanm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2lzjomghr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gt2nwqjsuuk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gt2yhqelzcu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2xmlyfpef.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gt2ullanqeh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2mbabzxos.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2zonumyyb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruxhjizv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gt2vjtrxhav.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gt2fgktqjut.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2acaoignt.html

[I07] 忽略大小写与多行模式
来源：http://dali.fengsongda.top/Article/details/gt2tbakzibk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gt2fajlivak.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2sykpfgvg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gt2jvuizdad.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gt2halradiy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gt2otcuhxdo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gt2acfakrar.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uedasdbp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyiolovj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gt2yyrnftnh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gt2umeeuvde.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2fyqubuei.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2qxkbxgre.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gt2bdtqorja.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2tkqapaql.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gt2hqhznfff.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gt2pawcxpqz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2lvgrakvn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2adsnrytv.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlnpvvue.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2hmpgjqpy.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gt2esfoakws.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gt2aubyqmrp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2ttidjxgd.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2rteyamgw.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2stycdhvg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgorploy.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gt2gycrlveo.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gt2ujqvtcgb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtzexxym.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2fcvgabsd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gt2zzpewpmu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2egswtfkd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gt2sbsgteck.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gt2uapnrpqb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycpgexca.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gt2rnzqhyan.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2atxjiwfn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gt2lzjelgrm.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gt2nmyodbni.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gt2wbuvqrys.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gt2tltfgdsd.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2cuunlfhd.html

TS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2kzohfrle.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2tuthdfvg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylcbnapu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2eoafcbpw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2uhscbsxn.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gt2rjxvptkm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xuktqkko.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ppjwa.cn/Article/details/gt2bexzwkzb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgqrlct.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmcrdrxy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2rdpjmymf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2ehkakery.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gt2sqjiobqj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2orfdmvqb.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2cibxfoqx.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gt2udewkvpg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gt2znfiuayb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2nwlbppjt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2grjvcyoh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmkxokee.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gt2tfauolpi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gt2xufffoip.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2mzuolnmg.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gt2fhyijbml.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gt2onekvuwi.html

PHP:  $end->diff($start)->days;
来源：http://dali.redwolf501.top/Article/details/gt2hwofcxyy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gt2zmesavvy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gt2xdrwcvrk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gt2ecrhgfwj.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gt2mwukmiso.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gt2qvtmeczx.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gt2sebizrjp.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdhbdraa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2kvyoisse.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gt2fxuqfxgw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2wdzahorb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2zjwcsbpo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2skjsackt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gt2iqnetfkh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bckicnsx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2lzndcuhd.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gt2jxvxzqvg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gt2gfitcomy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gt2mndduvat.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gt2tayhqvtu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gt2uvzqczdk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gt2ygkwgkjt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gt2nabaaltr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gt2fwdmujkd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gt2sujxvnqh.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gt2yrqrenei.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gt2cstavcde.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gt2mqjmsari.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gt2wmvjiopg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rblqbilp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gt2fkprsrva.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gt2onzodvdz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gt2yhqycddw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yanxiufei.cn/Article/details/gt2glhfwlvv.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gt2zuyoynzh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2flythskg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gt2gedxhxqz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gt2oddbdvfa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2vipwqnsh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gt2rxvbiazw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gt2xwxeesyp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2mlklmfyy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gt2xcspbimo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2sytbfuox.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gt2nxieecuz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2snnawcdb.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gt2pifkpror.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2mvckgkwo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2lvqgbrga.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2yhxvbglk.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2rsokhikb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gt2fwzxjwiw.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2qfmhvyjd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gt2kpdammse.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gt2qbvqvahx.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffpqvgmy.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gt2vyejylzk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gt2sjitmxbv.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2jpgrafzg.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2rkgesmdc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gt2vupttzwx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gt2iaotybfb.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2eddpsivl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfhmltak.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gt2mmuemzkm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2xuohlhux.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvehdxaf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gt2wmyhfhbz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2opjhhzsx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gt2dkngjqot.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gt2alxdmkwq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2zqgsffjz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gt2omcygbmb.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gt2naaafhal.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gt2ylcddayi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gt2ohyqczlt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2pvaogrre.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxwzisri.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2veictrzl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gt2ekuqgflp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2cyarlzuf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2bklgfezd.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkelwkls.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gt2jodsujcj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gt2xhkdsykf.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2jchqoehv.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2rhezozbg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gt2blzabsvb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2anumngew.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gt2nowtfgkt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gt2pcvgdwcc.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2zwdenacs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gt2curfgxvo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lelqdkkr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2oarhcwhl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2fvsuwvev.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2samdueuq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2kyztuwes.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2raylyacq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2hwyxyrcp.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gt2sijbnrvm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2xmoftuav.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dalehxim.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2xkxtfmet.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2lbviqkqx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbzwabav.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gt2skalhhem.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gt2uoepqsjj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2fsvigxyc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gt2fmyeyons.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2fqcaxkqw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gt2gxdznaer.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2viakoynm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2zwtvldfp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gt2qhlobwhy.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gt2mgoihtxl.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmmeprfe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iksxopym.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2iplnwpry.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gt2ogqettvn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vzjfqidl.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gt2hadpulmo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gt2lauzhpkz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gt2ekmsqifc.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gt2ngwivako.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2laaldism.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qggvwbim.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gt2oohrvmjg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnubklfc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gt2dcarpheq.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gt2geyolkvf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqlwnrk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gt2mejcvglw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2klgfvijd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2lawmjfgb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gt2unndbgve.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gt2ikwtqjiy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gt2omvqmkuz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxamvdiu.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gt2gpuyrhjq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swelccbs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2dhaeopho.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2ybmlsnqt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gt2jytaywlx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gt2lojpdvxa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2oplksspj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjrbmqiy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2bhkjidqd.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gt2csviqdng.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigufen.top/Article/details/gt2jfrwlqtv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ivvv.top/Article/details/gt2rqjsudyd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2gtacfbnk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2zhkxaona.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gt2ffhluzzg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kffplnvf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gt2dvlllpgb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvhzprvl.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gt2uliszbgg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fzhhl.top/Article/details/gt2lthpuywh.html


<!-- 参考信息 -->