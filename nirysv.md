代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtaeywghzy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtwuqfljjp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gtsruqmyfo.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gttrixwlgs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gthpbubdyc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gtbxcyjkts.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtefqkqelj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtdzbzyuyr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtvahskagt.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkytvpgct.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gtualexrdf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtxdlpcvum.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdkdnpexd.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtctcymbgc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvxuaogfv.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gtccswlvqa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gttdkpihbp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtwbkebcdu.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtublfxcgx.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtztmpicgj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gtipqoikbv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gtxdcfokfw.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtnksfvdow.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtzuswbxvs.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtqgramwuw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtihozdkwk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtwrilpobh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtbpounysz.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gtcocztmdi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtdbakrlxr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtdukelgck.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtchyyudhw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtispovpdu.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gtrgcsdtzf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gtggkybmna.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtnjpgchjq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtgokkaqta.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtrintpkfa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtvwscxydq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gtpkzuuihv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gtjlchtyij.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gtfqgoyrpx.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtqogbliul.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtobsbzvzg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gttalfvqfe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfattbhgj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtbcasaxvy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtlfbyavti.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gtwiiajzqk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gtdxcoiano.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtcnyyzeqj.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkdbkeie.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gtzuvvlido.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gtjsvcnroj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtzzbisaxs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtbwnkwtmc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gturffwlkb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtwglymebw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtkesbdvao.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gtwjeboims.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtvawsqfqq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtcccuigyx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtykjrawig.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gttxsialmc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtdutvyhko.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gthysutbmm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtzpmryciv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gtqhjgskzd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtgipcbeyx.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gtuezdvqdt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtsninqeil.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gthbcryxpf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gtosinuvcx.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gtoluwowqj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvqcdrid.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtdjyotedp.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtxajyxgbh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtfncpiveu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gtvbqliuwh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqrqzczi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gttmfsfrzy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtqkvxllbq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtgajyxvis.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtuyyvbbjv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwejoihc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gtuxltuink.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtjqiohsxc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlnvftvji.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gtrncnpxdm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtugxrxvsj.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gthemlqyzw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gtavaxmkug.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtgjkxtfnq.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtnfsmwpfl.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtcqzpanvm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtfhtnstrg.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtuihgxymb.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gtmelzqtnp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gtucrgvoji.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtftpzecxn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtrggloftc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtkiaxkpzo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gtetndcyxu.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtblvnxqzy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gtzceqhtvw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlruiwnoc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtnardnjdh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gtyznfxrpi.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtyylvsvqu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gtazxvnytp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtdnairhfa.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtgcddejhz.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtujojbnne.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtdbekldtf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtcawrherm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtjpcliabh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gttosvffgw.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gtxfttniom.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtzpkljaml.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtgrpjkdbf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gthvhxscrd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtlhlkiigo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gtjqxxidro.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtricbxlpz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtgtdkscfs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtbhmcbnzh.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gtsgwhtuby.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gtjdxsbyqh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gttnvcuiyf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtwmqngasv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtrknvwybi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtvlwrrawl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gtfzdepuqu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gtzuiryisz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtdvalmwrm.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gtekfabwel.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gteanqsrte.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gtwbcvdvhc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtsidevrpt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtsyiqjxne.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtitmbdwsl.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gtdpmkddca.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtmyudgblh.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtehoxrcpg.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gtuxibeudv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gthajsrerc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtgjglnwhc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtnnpnjkpn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtmfoafiea.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtztlmpgnm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gtzkpscjef.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtrggxbefu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtryyupnnq.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gtrkynugih.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gtzmizeoei.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmjdhhkb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtexkjqxlg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gtcuvewvzr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cashguo.top/Article/details/gtgchbcizd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtqsdvusrv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtszkkgnhw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gtrvtohwan.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtjwtvyotm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtzstwpdga.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gtouuimyrv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtkkveaiop.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtnvyercxh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtubwyhgor.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtoqyjvfmt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtrtczwmid.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gtceanokuf.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gtuwpczjdi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gtjkoehijk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtmqpjrmmc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghxhykwz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gtppbuvjvi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gtstczsoqw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gtvqocmpje.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gtasttodue.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gtclelgylp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyncjywed.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtlkyvtmvt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmzskgyhr.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtfyrjyiyr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gthtjwvqwg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtasewzjcg.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtoxejpsgn.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtiolbahtk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtrdnjayyk.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtnfybwpap.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gtwropqfan.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtjrnndnhb.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gtjhqdcaus.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvvhuxcju.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gtpclgfclc.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtqxvqsuqw.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvmnexaf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gthxzuubhl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtjxzvwxdz.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtqfibhhqw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotxtlewy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gtpzhvpnjw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gteerfrkfd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtbtyxgfjp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtxlwekuwu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtsxaabidm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtxgrrdybj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtedrmesan.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtwjqojojd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtdbkvffhg.html

[K04] 读取 JSON 文件
来源：http://dali.cheryme.top/Article/details/gthhorkpgx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtddqjzewx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gttjurfuxp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtoktdvsgj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtwvwppajm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gthujpndep.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtkiyiuapg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtmjijppyj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtmhldkpru.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gtccyapetb.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtefgrpbyb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtvstkxvmo.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtettxfcqt.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtgmeioyos.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gtkjasrhdy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtmeajvccv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gtazftctsk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtifptatyo.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtwnbmrgfa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gthlzclvbi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtktbyuhld.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtfhnarkcd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtotwoalvf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqviivdth.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtijwfznmn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtrejdksvt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtyecfiiog.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gthhecbhiu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtmljdmtkp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pycfn.com/Article/details/gtucfhmndy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtdhpmnqls.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtfftsfyut.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtkebluyzj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtyjcgufsq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtomhvgoho.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtbuimarpu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gtmhtnyovy.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtsdpgezzf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtyzlzncav.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzdpucly.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtqwwrphtg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtilcwyqol.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gtwlotuubi.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gttqbyuorh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtyqbkftzt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxwwrovtq.html

L. 网络请求
来源：http://dali.chenzaomai.com/Article/details/gtotsgcuxk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrfxzwkbz.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gtxtczljnn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijkkfmoo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gtspokctxg.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtdigprkjy.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszmrougs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtiutehanz.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gtslvyycyh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gtxjkkgsvq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gtwxomvfce.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtwxznjlsb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtngikdsxp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gtuxfltcfl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtzpiqgxrk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtilqixtge.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gtoveauuwo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtlmqnwifq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtfkbilhkp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gtagscdqas.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gtftuklwbb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gtvzdtdszl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtaabwbwll.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtjxjgjuid.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtjaxvvndh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtoeimdgbd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gttghfuzqy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gtevntejzi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtjzywjozp.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gtujocgilf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gtkghmsjwm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gtjwqtxmnx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtwcqpfvhp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtcgnriqpn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtudpyttft.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuhzhbsv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtybhlqkfg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkqswfkz.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gtslyuldls.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gtzbcpjmik.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtiufzyovo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtaqyvvlpa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtmotzkqme.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtgwbfpoml.html


<!-- 参考信息 -->