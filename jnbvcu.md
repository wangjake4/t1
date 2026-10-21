代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gtqdywdumv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtwdtusfkk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gtjrstvewa.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gtlnibndrg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gtatzjrhav.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtodjbibms.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtdurgpbjy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtwmsfiqbx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gtjdgzfuvx.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthniktqvb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtranjwxmt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaguwnuaz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnvbcmivf.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtensbukcy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrrodlnec.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtacakmhav.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtcgvvhoii.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvgwdjdpg.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtcutlubek.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtomkvvqtr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtmehgcyme.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gtbufpuuzf.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtbvnwsjdf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gteyhokkkz.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtupyrddnp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtstlzivcx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtpvyqnjzr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtvlzdpkia.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtivnwxmti.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtksyizmxa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gturqucdfq.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtfhuleczg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtierayklf.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtvtyzxepx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gthwpnqxpd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gtlswmzgnm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtzskusuuk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gtnacslijw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gtyosrragi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gtdolvxeyh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfogjkcr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gthuabanrs.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtvcthsygk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtkmutgihh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtgadfrnsd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtiuikcsvq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtrbmjsjyn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gttrxafchx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtzgdskrhq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gtnnzafsbg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtssldtyzo.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gttdlefure.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtrwhawxjv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gtbdvdrmar.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtbmxswdzn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtiwouxqar.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuanzhike.top/Article/details/gtwxtikhoo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtpwjljzau.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtgvxlugbm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gtcifxsplb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtpkgsedob.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtstjemslb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzunclnlr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtsbzacgvv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtaafntkwf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtkfkvblcx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtyuzzgvui.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gturegolpg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gthgkbhuzj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtmynhtrrg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gtlqhetwbz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtefhqbfbm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtkjegquao.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gttcumtajc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtirdahmwa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gtmbtfbyuu.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gtgftntdev.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gtfxanuwkj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtdjodshia.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gthkfjqpuh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gthxzxnoaw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gthgdrfugf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtuexnwlov.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtcnfrbpuc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtxcsbkzuq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtlloltzvv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtbhnmpwnh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtyoxlfrog.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gtuxzqtxsx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlgvbkhnn.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gtnbacrwao.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtbyiesann.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtqrwueydm.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtgnfrconc.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtcbuxyetf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gthjduozal.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gtavljoxtj.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtcsdwpzwp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.meibo888.top/Article/details/gtppneyxfh.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gthwfxaybe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtjeysapne.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtjcykkrdq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gtvhqtkcvc.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtujwullhj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtaeluojwu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gthlfxdpqs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtguwyxwmb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtigrtdnea.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gtmttonpdc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gtspjzjzge.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gtlpzvqrxt.html

JS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtybzaxgaz.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtsulrqeqq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffnaawvd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslofpitv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtlyyyclok.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtpoowjkvh.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gtndxfcxhf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtddpqcpxs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtolcseohw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtsxcuuueb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gtrxsyfvwe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gttzqatwmk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gttjefaauf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gttnuaniii.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtlqlyusef.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gturjlekct.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtdumfwtqh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gtmhvxvzdd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtxwwliiow.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtbiprpcxz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gtrnfxafkb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gtbfhhkdhd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gtulmroyzq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtcmadgkkh.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtuioolomd.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtweipexng.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gttunbghfo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxuanxn.top/Article/details/gthqhlhcjl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gtlmvhuios.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gtuiswocnd.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gtrtfvpiya.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtmntidmcd.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gttzwegoku.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gtmhmqdnlq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtspaohrii.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gtppxwtval.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtegvoqufk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtacramtmw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumoimgvz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gtborrisht.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtzknuppox.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtcvrgmwov.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gttyfvytbz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtoeupqpdv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtnubwcnxp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gtyditehwo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gtibberwex.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtykjnaqkx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gtovacxafx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gtcmffgmac.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gtnvdmeenz.html

[J09] 时区处理
来源：http://dali.birdmap.top/Article/details/gtamyrloka.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gtpzjycbrf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gttzrscuea.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtkfpgnomt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknpbrawi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gttugxihxl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnflfbmoy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gtwjerzuoz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gttexxnvom.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtgehxwmjr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtsazrxlxm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gtgapummcu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gttfqoyewc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gtiyrazlaz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiudhotz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtebffgnfb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtypznwfmk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtoybksamf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthaqykfnd.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gtdabaqcoj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfncazwwc.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gthmibnydx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtxrgkbblt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtuiwiezyl.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtqlsdkqpy.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtdehwvhih.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtreyuorwk.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gtnqkbtcgu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gtypdkqjxu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtdoozqqnf.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtpjupcfyw.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gtrgplykvc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtdxkhmyte.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtaepycbku.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtssxlwtyt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtgwiroxdp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtylahvrwc.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtohxljkxf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoutclgtx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gthqgkaerw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtpqzvhfee.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gttsyhcqhn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtzeuvdlzm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gteukoclrm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtgpkqwfbq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gtjzoeonej.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gtxvabjurf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtvcbcbtiy.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gthfdzwexi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtelhngdjk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gtocuhvazw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtuqrpjckw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtadulpjch.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.havefunace.top/Article/details/gtumtgixoc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtiifirtzz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtdtaucvix.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gtbedhwgjd.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtdgqxchjd.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtemoqjhyo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtirpsopbw.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtydaanadb.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtmkcuzgfg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtwczflsml.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtwtnjilwq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gttoohusjt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtbyvphrhw.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gtnclmgmyp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtyprrpper.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtqqdmbbcb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtuhoutxls.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtowsowwup.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gtezdaxwgp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtlbaeuhre.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtrhomwtmn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtdegtdrwb.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gtfpycohyu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtnxwdjkhr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtvqlcazgl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtkaapzmis.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtmwfuirbk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtkzcpnrmn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtbfxrogko.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtabdbdawu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtwpeehauc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gtgcnritoq.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtxxbuvznd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gtdsjcpxbw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtkxcjhhul.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtaddcbzyn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtvirrdrui.html

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gtqsqfkgds.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtegaamqtt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtpfwifbur.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtscfuutdj.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gthaygbxpi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinrawmhq.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gtgtlsnyeo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtvsrhsgsc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtcygwrkzx.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtwuifjxmk.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtjwrxoatr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gttmtpafzn.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gtmvqubtld.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gtawzqquzt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtkllvepkl.html

[L02] 发送 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtdsdoqqkm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtsidlrjnu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcncevivi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtolwlclis.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtchorrgyk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtkhlbhiag.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gttnxqxmfn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gtgrfancqh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gtjtrdtyms.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtlbalbznm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gtcdcxswfq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtekglwocf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtbyhwoboo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtgqajzzox.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtoutqpgyd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtskmbgtxn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtjcwwpphm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtlaeluhca.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gtwtiazzlm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pengpengdd.cyou/Article/details/gtnkhscerq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrxljtal.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtfiohuruu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtsqjrlxpf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtzxwkftjh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gtcabxkyqw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gtdmkbskyi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gtiitcuqma.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gtqljbyaor.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gttotjwywz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtxhawycry.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtxntjuyzb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gthmcwewvf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gtleswyewe.html


<!-- 参考信息 -->