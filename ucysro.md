代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gt2miymotcp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfunauwv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gt2kwuqpaek.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gt2dahqxvzm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gt2ehjehojs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gt2mekztdbt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2itkdknml.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojotuiuq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnrgipkb.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gt2encrvhax.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gt2qzevtlzq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2ljwtmkcx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2fpitldnb.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gt2ujrcrlqw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2btnvkfdp.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gt2mxcjdgis.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gt2igcpjhsr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2licgwpkd.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2qfzgddyl.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gt2mbjawuzm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gt2mmkgxdpg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gt2iypxumpd.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2vcujiris.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gt2lwcygvmu.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gt2ghhbbfno.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2aoqgruwv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gt2swijkbuq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pabclnpu.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gt2kyhjvbkt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gt2gmeqvjwp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2riwlwgzu.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2ayocwjrk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2wwpvmrbq.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gt2cdqxlwht.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gt2mnqnhehh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gt2jgwbweno.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gt2touzkuik.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gt2hmeumvrd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gt2uwyqehkt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gt2lskbqhrc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gt2fhjclomm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gt2veypeojs.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvegpaqf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2bhjgbsgd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2mvxldbwp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2ivfcskdg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfeelnvl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gt2otvzuhqm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gt2avitljdp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2wbwbafhx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2qbqppfqc.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gt2bmsrjxyp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gt2kduyawzz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2kjjdehvs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2hpioimxv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aakymxre.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gt2uvbcggmg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2nkjmtoik.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2ttazaskk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2cydyugfb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gt2mhkmlwho.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2gilrtaxf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gt2gefzyuct.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2hoevbgzv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2hzuudlem.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2odhxjazx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gt2fmgtnoef.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etmffpbt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lowqpowy.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gt2lfrhaths.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gt2xycgygst.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gt2fuavykqq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2gtowrxzu.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gt2lcfiacai.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gt2wtqxahdl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gt2nkrvsshr.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gt2mpbkkrub.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2volibski.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gt2gvtnxckr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gt2irrtkzud.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbmkfmfl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2lbkoysqu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2ekocbafx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lebqiulc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gt2fpewzxzu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gt2bahegsez.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfqiadgz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wonpuqgy.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gt2oajbegnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkfaasc.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2muoxzzsj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gt2iksobefa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2tfiboyyg.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2shlvjwpe.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcfxczlp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2dpplwcjy.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdxxcqvy.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gt2fhuhjlos.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gt2leirrsal.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2vidawlqn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2xomsgxzn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gt2doiorhln.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gt2tqlllvkx.html

TS:   d.toISOString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2oveatskr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gt2sglulxnx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gt2tygryhsn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2imoxyuci.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gt2rmiyliia.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gt2qemsgojh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gt2qoksrhob.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gt2zyxathen.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2dlkgxwyr.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2bxzfxiba.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2lrklwffl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2pbwgqtbd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvvsvhoo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gt2umqeawsu.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljpbllyx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2mbafmgps.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gt2twswjdnz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlbdlszn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gt2uupaqkbe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2eeohxyvn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2opxxpwql.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2hmubtczo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blautflg.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gt2famcmvbc.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gt2xdzeufdd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yypgnxxg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gt2zjpzfajc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umrdlomd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2felvczuc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rtcefteu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuguwda.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2wgzkwsle.html

[J06] 计算两时间之差
来源：http://dali.xylfe.cn/Article/details/gt2patyfwqy.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gt2cdnatmir.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2nvbqasmk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gt2hvtdfiti.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dianchejie.cn/Article/details/gt2eoolvjqx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gt2jfsykfei.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gt2ibuswrcv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gt2lnrfwbhw.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gt2ilnnpgek.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gt2yiemfked.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvkplnrh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gt2kwqbouyg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2fdndwusw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2kcnfbqef.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gt2fhjvimov.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gazfbofv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2jsnimvie.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2knbxlyar.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcomhfju.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gt2teeuodpm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.birdmap.top/Article/details/gt2cfumzglb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gt2kbodvocn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgzqcnew.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gt2sjaneues.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2fjojtogc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gt2fvxfzove.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gt2qjjovgxz.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gt2rttiiiuh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gt2nmrnvsta.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gt2eaawgqru.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2sdrdlfjl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2tcgssqus.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnlfqgvx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gt2qqonunwp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stgyvjjd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.meibo888.top/Article/details/gt2bsiyaupp.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gt2tozryiny.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfbvsmas.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2liyzcywc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2stshgauv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utyikgrf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gt2nhzzdjxb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gt2idlzahlh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gt2ghjdeqwl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gt2bqfbneyq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2fbudpiap.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gt2xkcttwjy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxoorotd.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxykdskk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gt2jcltcbol.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2prtkbjjf.html

JS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gt2tarpwiyg.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2egnypzzv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gt2mmyhssnf.html

Go:   json.Marshal(obj)
来源：http://dali.iojbl.cn/Article/details/gt2jbhgfgcp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gt2gxqlyztv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2uvibbmwy.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gt2atcbsajj.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gt2hbaipdrh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gt2rcabwtpu.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2ggcmveqc.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2uciopdzd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2ssrwaqhb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2bckldgyz.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2gyidmcrs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gt2yekrhspq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zerabfxs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2cpjuflai.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2tqiwsrxt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2nftvhslm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gt2zwuedahe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gt2zcsxwybu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gt2jnqilbxr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ooqhovvo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gt2dytpqlfz.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gt2zivkmykq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gt2dtodbkmr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yadrcapn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2nbnpevxt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2lhcuynjf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdrvesdz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2vspoltqg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gt2srpsgzmt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2trvteudc.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gt2vgpsdbme.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfmyclck.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnqzz.top/Article/details/gt2bizykvzh.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2omwugslj.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2rrjrynqx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gt2kqbwvnbf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gt2hqkuiwdm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2swhzdzqf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuanzhike.top/Article/details/gt2sggrwmzn.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywrdplnd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2etrtkbwk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gt2fpvswkgw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2sjcbkiey.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2txsdnthz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gt2fnytzfzm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2etezcuyy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2ehbdpvno.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2ayagynsw.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlgahtqs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2spvlxgao.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gt2kgyiglnp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2trcfbrab.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2xtcdjubw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzwkejc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gt2uiqibarr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esrwvuhg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2kxwfnwrm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdstiocw.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gt2vpvfwnby.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gt2zpuvsiip.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bygicqss.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2lduxsboo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gt2augwrzai.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2bnkilgdu.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2cpdsngoe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2wkzboizh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2akzvtlls.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gt2mllyeeau.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2nplnepxq.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gt2wzhrkxex.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gt2mddwxyya.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gt2nfyeltvu.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2ivclixjp.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2drkorabw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gt2hwhupspz.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gt2huubpcht.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gt2uxtpouyx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2ziqyriah.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2vlogwcsn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2igmkzasi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gt2grwulodg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2kxawfguz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2ugirzwbs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gt2llcuacpb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gt2edzirobk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gt2kftbokhx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gt2hveiuvuf.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gt2idymhybu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gt2eradsyxx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gt2tgbtczau.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gt2kpezoidf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2mrosucwg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gt2rqnrmkbt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2yarywpda.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gt2datikobh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2jgttolgo.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gt2vqrhfupd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gt2nrdauzia.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gt2lhlxcpee.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2hwbtynfj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2eszcmspl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2qpkmcjif.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gt2jdlowayu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gt2jkcrosbe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2ymwkyuut.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gt2kaomktda.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gt2lhmlscfe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gt2lhjmaoss.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gt2ojbfroeu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gt2kookqcxp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gt2qebnuwwm.html


<!-- 参考信息 -->