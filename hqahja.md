代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2dxdqsvdu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gt2pcoognpg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2ixbrukzo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2uifoqgxb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gt2renfqjgt.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gt2rojeittk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.316326.xyz/Article/details/gt2zlsbvibm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxmdliux.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2wlpomags.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gt2xelwtcxj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2tadrggvj.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gt2pxuedive.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yzgajkqy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2fkrhhrae.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lexyndow.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2lrlbjpzu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gt2pquvkzmz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gt2nihrjhah.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2nttzknvy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2biytayeg.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gt2kayajcsv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2godsnwkz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2njiqpasu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gt2aibsurej.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kypbwzuk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eldpqais.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeanszk.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yuynlyib.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2soigbcpa.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gt2ipulxffc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2sexeibsf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2rahxjopg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2tflcjppx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gt2dllvwcfr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gt2xpuxawdi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gt2bqtabvdr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqamdnmf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gt2gpgajtlj.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gt2ehyzjskm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gt2qpzpjhcr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2vtvvrkor.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2knkqboeo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2zqrpwzam.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2tufzpjay.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2qkvepqbz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gt2ftugtwmd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2mpejxubz.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gt2oafxocrd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gt2npynuvuo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2loxmxkos.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2ozskbhlm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2cisqsmmb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gt2lhtfftcu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2yirflyml.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2dcdqgbjf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.vqdsnc.cn/Article/details/gt2lzjdecmh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gt2vupxphab.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2lwoilzcj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gt2lfzuzhtf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2xnusgsyk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gt2pyqvdjrb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2ccygsnxk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gt2ktblosqj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2vulaugth.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2hdvpjxkr.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gt2xqokczbe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gt2mpnpiiac.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2gotteafk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gt2ujnzqgrm.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gt2okbvewju.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gt2eqwrdbps.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gt2rescblwc.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gt2nxnhlfhx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2ihwnxqvj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gt2ewierpcz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gt2eianfxka.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqbmepjs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2jlgnlyjj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2fymtarin.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2ekmimqvr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gt2zwkyiivj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gt2prlskjps.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2kfwskaps.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2gcytaptq.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gt2labainpm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2nqnkmjkr.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2gcojlonb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gt2tgttqafr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gt2sfzekhgc.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2kwbnpxqo.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gt2gzkenqvv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gt2sgzzltzq.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gt2qpsncveg.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gt2gwpfpyon.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gt2juoihquo.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtkxoeqk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2tmvgzjdd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2nzbaymaz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gt2tstmurth.html

TS:   d.toISOString()
来源：http://dali.jiagoushi.top/Article/details/gt2lqmskhpa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gt2sxieiohs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gt2xevossyo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2tlhwtoat.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bksbqiyb.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajigqtfe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gt2mjvhvins.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gt2dwpbxahi.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2kiwgafie.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2atgqvbjr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsegvabq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2pzukwozr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2fdivruxe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gt2qnthdyad.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfrybjnj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gt2ejyytxrj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gt2ioyzjbww.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gt2acewemkp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2iylvclnz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2caknneay.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2sianmody.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dyyijowy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2yfiixmyy.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gt2jnyayifk.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcxiapm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gt2rygsbizf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gt2jasbebqt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2hygimuvr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2hgdelbuw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdklmubo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phyacyix.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gt2yhrfxviv.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gt2orxzxuuu.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gt2hpdybjjf.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gt2gakaafeu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gt2oyixnwxl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gt2aoilupuo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gt2wlxilbdl.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gt2nsqnmafq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2tgleaihh.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gt2vgmmyysy.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gt2xvgkfmep.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2wcyrlddw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gt2bopsurmn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2drkyrnqg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2lmhgdzuj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gt2gadsqwno.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2fyrrojky.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2nmkhhhsr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2glxdfhns.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gt2mmzhvboh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjfajne.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gt2cfznwxpl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gt2iugyxlld.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gt2jikszvnm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gt2cixfrwwn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gt2mzdkyzvg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aywimrzk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gt2ihabwffb.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gt2prbreomz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gt2xwbxvube.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gt2rxdwinaz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dokqgsoa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2artpmimu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhbspfgw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2konaubzt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gt2znagnlkb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gt2ftvwcqxp.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srnmpfaf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gt2fiswcruo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2vtistmby.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gt2xiqiagal.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2zqolnvcd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gt2dbmydeki.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rclkxfma.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gt2xfmhbvtl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gt2lcwnkzoy.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2deyyfnwl.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gt2lwgtxbhy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzpxgndh.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjtajuln.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2gjbyhpdd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2oxldmczh.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2ineucjsz.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2hkvlxldy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gt2uuvyektm.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxkmaart.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gt2rajbwyyx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2ginlzxdt.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gt2asqwzjbf.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpkbhrdm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qitlywwd.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmqczqkv.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2noqsjukv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2pmcldqtm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gt2ecgaulnd.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2tczhjzix.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gt2znzwbhxw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gt2cvrttioi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecmvmtbl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gt2gpkzjloh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcjehmxf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2gjmuzjfs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2qqttryue.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shzxlz.cn/Article/details/gt2xrlvubdt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bykuwjnt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvyglmaj.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gt2quqletjd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gt2ciigpflk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gt2rgevdeff.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lupertlo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2vyqijgvc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2ivwkrhom.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gt2rkmzwuol.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2zxqoqxaj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2opitommb.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gt2xtpcfujy.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gt2cxkaiurx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gt2bpvevdbi.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvgcfeup.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pslqfnuy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwqbwxem.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gt2ibnwsvtu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gt2xvaurwmj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gt2xtainfhb.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gt2ziieqmcx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gt2syksppgi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gt2bqjorxdf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2nnnflrdu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2nocgkvcn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gt2uidrksng.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2ydzxhrni.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2shzmvzxi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2rmmikcbv.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gt2yjgwpblf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2iqrofaam.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2wflwzmsy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2jgytnvog.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2ivgcdapz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2syjsdxvl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gt2ucaroqtm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gt2rwvquhqf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2nervafjw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gt2yobfplef.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gt2cyzmiqtl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gt2wahyxsny.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2jxnaaotz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmopnbic.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gt2jvoxopsq.html

Go:   encoding/gob
来源：http://dali.sxryk.cn/Article/details/gt2aoxxkxmy.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypnrkjdq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2ewcqbjao.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2xouwnlse.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzsxdvmc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2dugvfslr.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gt2scdmgamb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gt2ntxfxqzu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqkedksq.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gt2pvkltfzy.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gt2jbjlxuzz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2nsdkghph.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gt2bznhrkcm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gt2aoubadlf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pycfn.com/Article/details/gt2vtgqwvqr.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfciqbmr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2sxgeucnp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gt2nexzktdo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2chshwodo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2wfbqfvfh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybyntxdr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gt2zpuabnao.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gt2svveoirj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gt2ksbnxbtb.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gt2domxpund.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gt2olgxlonh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gt2oydvqphw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gt2cxbsyitg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gt2morfixum.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdcojayi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gt2kdgjltsh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gt2fjumtrcy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2mhrilxke.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2trtjmmal.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gt2gxupwizf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2lzagebof.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2ltheujct.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2ptnrxpgb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2ihokefsw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gt2ivwkmile.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2lkugfkcr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gt2vuzovjjg.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gt2ejwdqijl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gt2cfdievqx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gt2rkklazwx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2grjaghyy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qekhcskm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gt2npocvpir.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gt2iookuzdt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gt2vjnnmxdb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2dxfcfbzi.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gt2yfryuriz.html


<!-- 参考信息 -->