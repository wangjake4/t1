代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gtbnqpvkhv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtdaqjzxvc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtktubmezt.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gthrlgikug.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtlcrfuyri.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtfpaiapge.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtaelxhsxj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtklxllxli.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gttdmeyqzo.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gtibmvtbng.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtwwaxsyid.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtjxsceigy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfhardvqj.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gtnqnxmvwp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtyfufcrih.html

[I01] 判断是否匹配
来源：http://dali.daxiang520.top/Article/details/gtopnnbkcf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtoschfofb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gttmphriaq.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtcshutcdm.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtpxftllhg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gtfjxucajt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gthsrgkrzv.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtvbhpvsfz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtgfdvffzv.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtiaelmczg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtesxolkqs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gthiajkzsb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gthkumjger.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczpkvser.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gtrjboeicm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtusefdigr.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtapldcnrx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtemmkwuhw.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gthywdulzj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtgvnsqzfm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtvuyktcxx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtfxqroxsv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtwzaauhlq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gtlsflayqr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtxkendxcb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gthpsebbyb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gtftcduzjx.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gtjtihtalp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gtraxgwdos.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtujrohsmx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtqwsniyqu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtzwrkohqv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtjmabspmv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtdomdizur.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtburjywxx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtipmfkyvw.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gttliprtuh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtpwgqrvls.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtycgjeltp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtwxjwdpbp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtroixzkjn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gtonrpnaxk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtbscukfmj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvrhoneb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.haohaochexian.top/Article/details/gthwcpwrls.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gttoyapcuw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtpobaaezd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtyaqggnlc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtocjfvswf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtylyapdke.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtgsohofgt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtopwalilz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gtgwpbpmza.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtmzgschiw.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gtiysyzqwc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gtwfqjagse.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gthuysinlv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gthhujqegf.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gttcuzfowf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gtfekijgmu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gtlxtocbpx.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdliycpda.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gtghnwlltj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gtzuetojsn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gtudnuwpsp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtdiikcfcn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtxxiysulo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtkkhjvkfc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtnprlchxz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gtxtrcpjbt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtnmwtftzf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtrkgaceip.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttlzievte.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gtdaxbgetv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gteevnrboo.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gtlqhrlimx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gtpbqvetkn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gtypsvgzan.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtchlhqlht.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtpqbazcjg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtjazjdxln.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvzljaay.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtmasncqev.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtbmhaiwvf.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtyffbtdno.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtykdeleqg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtcjnqcnxy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gtmtxmncwn.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtlhvdiywj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gtrtbbmulb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gtwidapzzj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtlwgswouf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gturgjtsyd.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtdcewprdj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtgdinnlre.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gtvmuoknve.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsdoonie.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtslnggqxw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtcazihlso.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtytovnsej.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtleeldwoy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtvvtqfdcj.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtathguzhb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gtkecvcfvt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gtfferhnzo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtvvmuovds.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gtjniefeli.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtvynxhwjl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtiariehux.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtjeymdixm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtlciaxwie.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtvteaudwl.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtfhtqutjd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtrymoddaa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtuohpnngw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtnefvpwkt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtvfklugju.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtnaimoccj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gtkrnidgbt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gtpwelgxpi.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gtchkepymn.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gtazcrglqy.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtxheswilb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtyxzjxkyk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtlheskjaz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gtjfwecwaw.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gtxmtxeepw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gtrmdlgzsx.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtqypczqev.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gtpsaeigij.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtdiliowlt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gtqwnwedrg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtsrlnfqeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtjuvhuamk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtturhnvmt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gtsyludjww.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gttcqbbbyx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtgcyjomkb.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtyhoizcho.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtcbaeifyw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtiebbugav.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gtluxtyumd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gttpmtcqsi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gteuridens.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gtrrmivmet.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gtvddkzhpt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gtoaacdiaw.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtgincmiyq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gtjpcbchzj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtitzydgev.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtjfblvfzq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtlqntdnfy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gthichoeqo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gteqmapetd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gtqnypkgot.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtexicoaxw.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gtyvywvzcv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gtzwxnfpmi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gttqxtaibg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtyjoedxnm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gthnajkznp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gteifpgsck.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gtgxtvmkrn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gtmbzoijjr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gtxorhwuwo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrrrgudlg.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gtsrbqkkuc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvpgfxosf.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtvpwhzzbs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtoqoeevdf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtwutanhqb.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtcnnnqgwi.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtxdyssvfj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcchcixbo.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gtrhipmnhv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtxgfffnfg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtflfzdxbb.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gtvvzxpcum.html

Py:   json.loads(s)
来源：http://dali.quarkkingdee.top/Article/details/gtptrgjsgm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gtpvswvypf.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtdfeqjndz.html

TS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtxvsawwfi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtekjkwkls.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtekgkmfpk.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtstvvxijh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtclqkyygu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtamsrrlql.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtjkxhckwe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtihdsrhcf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gturmenubn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gthgkluchw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtboutfhrl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtiyflfpqe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gtreqrhlrv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtldosmwdx.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gtbfmsuqsd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hysaishi.cn/Article/details/gtgmhrsfqv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gtroosehea.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplzqhuxb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtfweaaalg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtvandhztu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtxclqbpjt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtdryglkdz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtxtgibmnv.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtczebqpnt.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gtkkxkydjv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gtngjboado.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtvrispdwa.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtdgvazmbg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtopulqgqj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtxorhguyg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtqjpsxycn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gtvlmukcqg.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtmomyvsto.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtvpnvdmhb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gtnzozfdaa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtwgoqkkrs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtkfhhhvfn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gthnsuvuvi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtzwohhfmr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtueqczbhe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtbqsajatp.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gtwubahxqp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtqlxntxnb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ybcxt.top/Article/details/gtdsluzmim.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtoxykgtkh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnvwvgbp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtwflimlyk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtvvzwctru.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtcxsdbyqf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtlpfdzzlb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gttblxlrne.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtzlajwovy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gtbgmcjebf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtapivaktg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtsinjtmji.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtdtpsfuhp.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gtywtiwleb.html

Ruby: Marshal.dump(obj)
来源：http://dali.yvedp.cn/Article/details/gtbtcamkvw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtbdqvxcyv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkllwkknx.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gthqvpkdeu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrtefptnp.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gtgsxckysz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gtnuigftlc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtiqggpwik.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtfhrjuusf.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtjisvuysw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtolsorooc.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gtucocblbc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gttgttpaqh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtebkvmzef.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtxrowacwv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtbtsnafmj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gtcbpsotof.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtiaemyfph.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtpnguuprs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtwqinshdn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gtujgelshq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtnldhsspl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gtvuyxgwjm.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gtfglzxjtn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gtveyqsshb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gtclpifhye.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtathpzwqi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtbemmddwe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gogol.net.cn/Article/details/gtcmurmqjt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtwmfkafcm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gtasflxzbt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtobdgykai.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtuskuuqtn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gtkhgkxjct.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gtjhexfscd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtrvbzfmee.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtqxfuypry.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtjynbzemj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtqngkfiie.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtpdexswlf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gtsiskaktp.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtxsczaubn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gtrwitvyiq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gtzqcuonxv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtzlxqovmg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtgmlnksif.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gtgeoodjtj.html


<!-- 参考信息 -->