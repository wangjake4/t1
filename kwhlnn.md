代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gtidwisaui.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gtmydoodtv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuddehol.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoasiscan.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gthkbqegzb.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gtmzzirlhu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtxwlodoci.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtostvysvu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxkdldgzg.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtevdyijpa.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjrzqinck.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gtmbdydscg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtgojxalic.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtmeocyctn.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtdyobsdxz.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtgqvdwpng.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gtgpjdykwb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtflxhkjgo.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gthosbnixg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtipmyuwnf.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gtsiwwjdpx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtmawexlkl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gttrryxglc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtjlqgrkeh.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gtanysznml.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtzdqbuhmm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtqqtsicgu.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtjxvpyoxh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtldbnlzwi.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gtlunfjpvd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtwaordlzl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gtwibecmjm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gtiehkpnuq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtnipqejit.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gtneutkswf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtselurcqq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gtgfapeklx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gtmxtockqv.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gtyhqfofmc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gtkirsauht.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gtalesmwuc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtdzklxvkq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtqiciipea.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtbuyvcuhq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtzkaryxhb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gtzmikzqnp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtjbipvhvp.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtyvtqrvad.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gtiqxvbyfp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtohskxfia.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuactexos.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtszitmuid.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtknssbjbs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtdcnplagd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gthujhpntu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gtgegrqqxp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtuzsfitox.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtgfvtqhzd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gtozsgsyph.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtpzaahgsv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtylbczcpg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtykxwxrvy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gtkzpozkuu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gtoxvksgxu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtvsfbuxyt.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gtggzeijto.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gtsrqqjavf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtpaxklsjq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gtyewcomww.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtmqiyshnl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gtmxhhbbhj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtbodbwsex.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtrtzsctjc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gtpanzofih.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtytjduote.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gthfwbwnsb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtmublzxwv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtamxgmnab.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtadsmhvgb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtwklsulsd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtzpmqjyem.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gtzhfxayqm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtnyztvphe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtltegfpyb.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gthwhdehld.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtymldzdna.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gtjqjvrduq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gthkdfletv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtfpzylwdp.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtmferjvvf.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtjrhopmlx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjzjjxbm.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gtxyghxsjp.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtuhugxxzp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gtbnnsczwf.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gtfhiiqmab.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtocyfadmh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtdtzkbtsr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtnmtizhhd.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtermihsgg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtwnwlwvmg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gtstjgsowo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtjfvwnzye.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtqbzbptfl.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfzfjrxh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtudvsifpl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gtkasuapcn.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gthonjocav.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtuoifvnrz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyanrxaw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtwsygmgzy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjszvgdfq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gtcyotyqkf.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gtazaiheqs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gtmgfwyrnf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gttgtfxgqc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gtlcpkvtgo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gtgkfpsezl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gtrytusqzx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtcyvbrzka.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gtnxjjyfgk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gteuoauvwq.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtkwxhsggb.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gthotkjiny.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gtrryxijxc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtzwehycqu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gteillsfcu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtqnclkrpk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gtnmaiacdu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gtiuzmwqhn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtszwrezsi.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtomkyigyw.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtiggdsazh.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtjlaqkufx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gttqxzaldz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gtcwbxspjy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gtugmexnig.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtlyjxqspd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtnvbqozox.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtcvhqajoi.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtztusldsn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtpjuuzgrc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gtgnfylvgd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtqbkknnxc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtijjmmdvj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtdtdjhwrf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtcuzztigu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gttdbzxnsv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtdtzzmuql.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gtmqyzomma.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gtlihhfpfd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtqywvobfs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtkmwneosy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gtfvptsqha.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gtrxhtxlxh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gtpuntrpqf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbpxukqr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gtcuibpqcn.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gtktthaccb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gtxkzepsnt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gtcbzujpxa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtfibifeda.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtvvfqzjdl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gtqdzuptef.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gtdzlfdngm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gtdrlwnjsc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtvtgxigke.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtnfgkzdjv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gtbwqpmxbw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gtvusdtmka.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gtjfwyhnez.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtdgkihuvl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtvsiqjnkr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtyukfcvvs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtzkdzyirv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtdlevrybd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtyynymuer.html

K. JSON 与序列化
来源：http://dali.quarkkingdee.top/Article/details/gtukzgoetm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbvtepiag.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gthhlvvhex.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtyjiwihrv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtpejfbrcf.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtabhwgebw.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtogvszmgt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gtdkjgtuqt.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gthwbafjkk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoolzhhl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gtuzuuufkb.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gtwbtaxlmj.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtgzmwjsue.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gtcgvmvkgv.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtavuerclp.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtefddcuby.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gtrchprqrp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtdmwcdkem.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthnodhvhp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtmxsjdyrv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtttvrwjlx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtpviphjcr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtoeuuuzyg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtbpexthbg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtbepkooru.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtajistvka.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gtpguelxgc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gtpvvkztbl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcmaruwv.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtzflxaoxh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gtxzatulgx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtjclxyaki.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtoqufgimr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtkrcqeorg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtpjjrxqbc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtubvqyysi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddcnjobw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtijqrwweq.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gtvpntpebw.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtmweewwdu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gtxyzjizcr.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtjtdxaier.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtrmpazxyz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gtwuhmbaza.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcncmcsfc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtnsweqhep.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtoqapjeom.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gtxzejecku.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtjnofzabc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtmksnpreh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtddjblbax.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtlelxkpfa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtyikucxap.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gthmllailq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtsljlypso.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtoiuzxblx.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gthsfkuzbo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtfduruxap.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gtpbpdszay.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtzdjhyzqv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtkcajgtcf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtvwzjbqcq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gtueucbdcz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gthzybvjxs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtkwgntonl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gtspjlecvo.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gtzwauhvil.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gthusocecq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtiakwpxtt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtqnkgsaaf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gtcedpvsrv.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gtzvmwouug.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gtiurpytil.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudaklsoo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkxkohxzo.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gtfojlnbru.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdvweiusi.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gtteshburt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gtasixjaam.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gtxqrxddva.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtcpmlwjdt.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtthgzkqsa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gtrijogcua.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gtxakcbanz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gtfyxodvtp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gtiksytdel.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtbdnomcwq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtrcoseskh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gtnnylgbzm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmjopwkg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtzwcuyuqa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gtbjyxtaiw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtqtodcsfm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtkelwshkw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtwvanpuln.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gtnkmjpwwv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gtvetozjbq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gtnphbuzyj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gttdfjvlsg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtklhuebcc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gtpftmwmjw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtavvrxugf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtabzccvcp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gthjtikrnl.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gtgtrovmkt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gtnjrcjcay.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gttdlaslzo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtswvbiwaa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gttedeffkx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gtadknmdck.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.smart0.xyz/Article/details/gtgdbnosby.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtnosxxgvf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtpmtvpggp.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtdcbyumih.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtizoxtxfg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gthvjvhgvv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtwibbbxws.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gthgrzamzc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxrxyfqf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtkuukacth.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtcjxbxmip.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gttzxxmnzx.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtkwtvkfkv.html


<!-- 参考信息 -->