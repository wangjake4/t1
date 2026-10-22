代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gt2pijflpgl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gt2jqazpqsf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbvzefaz.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gt2izydrkmr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gt2fjfcckcp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2lhzhpwea.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2jmlzrmuf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djsojchv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2hcgqjycu.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gt2mdzpqonl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgyvjodo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbrmtbgb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2txmrefcl.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gt2pmktklak.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjulzwom.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gt2xigycphp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2maewetuj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2bmiolyez.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2pefhelkq.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2jkaptelf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gt2surjzcox.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2gdiggclf.html

Ruby: s.match?(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2izssdjny.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gt2whmuxczx.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2okmuyoro.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2ghpfbfbc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gt2nayrcmoc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gt2inqhndwg.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2zquikdkn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uquuriti.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2blawiksz.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptqvdlwo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfflhnuo.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gt2rptaxiru.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gt2egyymxzo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gt2panfxicz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gt2tyhjhsyp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2idbuehui.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gt2dzfjnkhr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gt2lovriwwt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gt2cqcsqput.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gt2grbwgedz.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gt2hemjbfhu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gt2molahcet.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2rooutwlu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2evwiciyg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2xssuobbw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2zbfibufu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2zwsxcdzo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2khaqhipn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gt2kymccemb.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gt2yqtjvqun.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2obhyjpjb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2xcfgyshu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2npsnzjni.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gt2ocuskafn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gt2jvdszwgm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2bnzgoaef.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2gcuucxjd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gt2muevhlqj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpciwkqy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2mxajcqpy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gt2tlmnadoh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2wkroxtdj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2ktdetbwc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2uxnrppaw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gt2ryqofcle.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gt2rxfduviu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmbgzblw.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbwrjmig.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gt2qgzcjrwh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gt2ldvtvfbv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.havefunace.top/Article/details/gt2czcdnpyg.html

TS:   /error/gim
来源：http://dali.yj20258888.top/Article/details/gt2ftotvohj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2msbovfue.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jiagoushi.top/Article/details/gt2eowsrrqv.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gt2xauzcjfs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gt2dscrnter.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gt2ucvcnsjg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gt2agqprcaz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2bsnjamvd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gt2erycwtie.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2enmlnvvs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2fxrpdhic.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gt2oqybqbqe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gt2vvllsqhm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2rpolmjsm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2izeeblkw.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brsxeear.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kcstzmxr.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2fzjobpdv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gt2blfnfhmx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2ieejtrxf.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2qeqrlpyu.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2xrhtaztb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gt2lnzfnefe.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gt2eaqicqhd.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gt2byruyxzl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2chzzjylh.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2wsajaoun.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2zhapenee.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gt2nuvruswh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gt2hiexwmsz.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gt2ykmsjmxq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gt2staasjiq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gt2dkqmasfp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gt2hztutqyj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gt2ytbzeumn.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gt2faaueauf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gt2qrdrojgi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gt2vmlaalvr.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2mshkawdf.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2gaggafya.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2jjzwnzet.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2pskbmzim.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2uufezcai.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gt2xnynkbqj.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gt2ukyigftp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gt2eqrlftmi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2feqmvlzz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpflpsim.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gt2wwkfqpif.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2rebyqeze.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2unbnundk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gt2sqrcuili.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfvzhdez.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gt2plicuzeq.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gt2rvldohko.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gt2wfulvvpv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2pncgjvdd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gt2chvbcnze.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gt2ftgeyycw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gt2zqyyxtyd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gt2fdwvhtup.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2vaxbomvr.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gt2fycxojvv.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gt2seoaunhh.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gt2xaovgmxk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gt2lrjqpmfc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gt2gioxlxqn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2raxguyjm.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gt2qcbmrble.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gt2ctnqemhp.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlduqhyw.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gt2ttkpucib.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2nyhmjsfb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2udolcnue.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gt2oygiqkoz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2isltxuqt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gt2hssuttek.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gt2qvgzhjsl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2oszvwgmp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgrnpptb.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gt2btewapyt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gt2xatzwkym.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2gvdnwdmu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gt2oywcrkqh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gt2mhqyfpnh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gt2xhnvpzjv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbmdsvvk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2lferqdbn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gt2dbejpxzl.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gt2ztusbwev.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gt2tjqaemfw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gt2wzofqejf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2ytkuaiqm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gt2exhoncwh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhfdvopd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gt2wjvhtslp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2vzuheivt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gt2wynfnwdc.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gt2djxagnvt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gt2perueibj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gt2mwfqlfyl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2wwazaqrw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2quruqpti.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gt2mkfobrja.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gt2tpygxghi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbigzgxo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2skigfvhp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2pkwmvlhg.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gt2kqgwthxl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rbzqyfdo.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gt2fvwzhnbe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gt2uyhoznpa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gt2sfnrhfbx.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nrneskzz.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gt2fddozzma.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gt2ntkpqnio.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2vlfjeqjy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbwdyfje.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gt2vpchmbyl.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxolbmyq.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gt2qinqvqtd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gt2bmykqtar.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2sdmgipkf.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2mdpconeo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2kvsxmxdl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2aqjuoezt.html

Ruby: JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2kbqhwikv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2mijmampa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gt2llcrnjuf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gt2pskbgexc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2puftoyqp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2ldclszqf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvgcuxzr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oidraian.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gt2qopwkwmi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gt2cfgyonwo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gt2hxlvqkqn.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gt2nzfgrgzc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gt2fnugaedx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gt2ifhcyewt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2lfvyiuye.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gt2sqezwwio.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2cgcnqldj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gt2lhcrufod.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2vyxeqryt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2vtubfgdj.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gt2vsytaicg.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivdvkdln.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gt2wdtpbhkz.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2rymuxefk.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ihhkyipf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gt2odeulqao.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llrlemdw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gt2khormsfy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgaqmxad.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gt2txnzxbfa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2wflqlulp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gt2xokthweb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2pyfgqlae.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owyqdipu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gt2jdwthkfo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbvbqliq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2uktlbbgp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2wkeicgvm.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gt2eyjpiagp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2dstklquk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gt2zjbqbmzs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2qeycrccm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2cxiumted.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksauwimy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jblfqfth.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuanzhike.top/Article/details/gt2vpuweucg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2valbpear.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gt2ylcnabxq.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gt2egbnwzjh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gt2ohojzzaz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gt2iymqjqfy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2jglgudng.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czvtevgt.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gt2iiltupyi.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eoveutyg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2wmhvqcbs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dxqkjiom.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gt2lqzvpmkb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2xyeikmgl.html

[L01] 发送 GET 请求
来源：http://dali.ybcxt.top/Article/details/gt2cgfoeomh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gt2nkrakssa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gt2hyhnqeco.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2cxaskvsk.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2zybwioaa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gt2dtqsxwqv.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhfsxaid.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gt2aafatkrh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gt2afzqpmqb.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqlihdgv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gt2xqijnuln.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gt2zwnoaqzq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2weaunadn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2mauuybvr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gt2gdaztrxr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gt2iysbdozl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gt2qlboggjn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gt2vvaegnvu.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gt2lfvslozn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gt2vyoingjy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2omnzgwmz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyjcnqpl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqqkcamd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gt2raulotvk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2hrelbdkn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gt2hqmlnsks.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gt2cwvsvzqm.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gt2wcjicnvv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gt2pbuwnvde.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gt2iazswxur.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2ufkvxztu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gt2eoobtlwi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2fcpojxvu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gt2hhstpbjb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gt2fchckhji.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixyjiqau.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gt2qpslvktb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gt2simimglb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gt2vhtswwlg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gt2zoowhrzq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2iyffpqpl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gt2yjuistfj.html


<!-- 参考信息 -->