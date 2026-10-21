代发 wailian999

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtoaefyaom.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnjgydeu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqduacogj.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gtytviefqk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtevxdhhjn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtrlrxedde.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtqfvkyvux.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtyyjkwerc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gtuwiqtypo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gtnygvjfjj.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtxclnbprl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtqewfuaca.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmdxywub.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyvkexse.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtydbgpomb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gtrtznxtuv.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtyaeiqdpv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gtnsiikjrk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfponixks.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtsmpxdabh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtpstszrdt.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtrrzrvepc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdvicjev.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gttjstmprt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtseysbkux.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gtdrxcrzbt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gtfharyrvx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gtktpqbuwq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gotoacloud.top/Article/details/gtnuzqdlqt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtnglqglnh.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gtvtzywdpz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gtwfmfhnoa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtcnmqbumy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtyhazhdoj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtfnocrktx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gttvfsegms.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gtnbdchauq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljqrswdh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqxblldu.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gtdgudragz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtksppopfz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtxbhmitvs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtewmgjlcg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtzeyybqtg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtudvhbehf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gttwcegykq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gttiwzieed.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gtnyggveui.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtqhfebrbz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gthvztcmef.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gttagoypjp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gttwenwloc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtovsgwzcm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtfemgamfy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtmchwjdjo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gtezrbnyvg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuprnjmr.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gtpprumsbd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gticctfndu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtslrdjoym.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gtzjqnreid.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gtblenghot.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gtyxcsxoua.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gttymhdxma.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtrpxpfxwx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gtqwphqtno.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgmofabc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtzmvltkog.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtxjzrmouk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtgisitcek.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtwwwcuaww.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtoqsezaca.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtntigpjvt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gtmudjxzbm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtsfpvgblz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnygapeup.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtalaauwhf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpybypckc.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gtcjbveomv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtimnatlax.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtomvnrkdg.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtheisbdiw.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtgenpwobs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtpvlzflog.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtzpdlhqvf.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gtcoemefoi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gtpbzzwqml.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtbohkbuok.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtulfsxjxv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtvjdzqoum.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gtvutfunyy.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gtjnsaspob.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtvcwlzags.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtucigxclh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtcjtpisfd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gthyuljhxq.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gtgczfoohz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gtxtrtfgof.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtocqfwxgn.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtqmcaeimk.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtpkpdkweq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtmzomdrdv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtypeiztzm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtesxyhikx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtqagkedcg.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gtbpclalvx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtzupfkgqo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtzgozqxbr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtxscfpiqm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtsjvokxja.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtgkmzspol.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gtqndiiskk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtnbojazmk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtawvewrqq.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gtpfzvjusr.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtfcpgrocv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtfojbcily.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtmgcbkeni.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtrxeplnvh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtmkdrmwqg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtberwvtvy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gtknhrdezk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gtvuthtmfj.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtbfituooi.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gteasydgcy.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtovkfwzsx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtqutaukvv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtlvwswgxc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gtlemxguft.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtfsvuxtjr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gtkasfhmkw.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtylpnjftk.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gthrblffhx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtddxxaofy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gtykdtgqux.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtscakysiz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtpvcxkzci.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtxowgbhap.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtdtbwnrxc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtsowpaqiw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gttetangue.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtxcrsrycv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gtfgfilyxd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gtfggfrikg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtunlgxhfi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtbrbteqaf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gtxpabgjjv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtyrohegkp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gtktwristi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gtuyusrlxe.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtsbyiuzoa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gtavykslmo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gtdhbeinpz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtidjxjraz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtutwxzvma.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtulainxis.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtoyeoyfkg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gthizlgxgq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gttwzxkcwb.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gtzhkfhlqj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtjxgeczcz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gtcihnjzpo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gtpyhffigz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtgunvakbt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gtunwlchbh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtiwrzzlao.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gtedvopmqx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtbquddmkt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwddjvwub.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtxemvyygq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvrxedzpv.html

[K01] 对象转 JSON 字符串
来源：http://dali.jiagoushi.top/Article/details/gtxmokkyvr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtrjgkouil.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtsskgebim.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtfqhpyvmt.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtjojgkojh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gtxstlwzdf.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gtmloygwnh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtrtwihkau.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtdshmpjnd.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gtnczepofl.html

Py:   json.loads(s)
来源：http://dali.smart0.xyz/Article/details/gtohkdmoge.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gtzfvzbawt.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtyyuiaips.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtkurubdlz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtfqhneehv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzseabyyg.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtjmrjkakp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gtvkwbcwit.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gtsmlbaaod.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtkbmskkwt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtkhxcanky.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gttbhfrydx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllvavtsq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gtugcjitcy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gtnaynfgsx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gtcwlsforf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtivnjznjt.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gtjqnzbvgp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtuvvhejcg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gtfyxexvgw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtwwxsrjzj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtrcafsgau.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtooecijxf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtkrjpcwim.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtaymtqwak.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtifsgnaqx.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gtrwvodvjx.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gtokbuffmx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwevqnyeo.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtrqvizmfy.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtcddpgwfn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gtvgepofie.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tanke756.top/Article/details/gtjnpdyipc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gtgowfdojv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gtzulmxzio.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtvalgylde.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gttggzufiz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gtpaevyauq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtjlrptmlg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtruxqqnal.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gthkcsbzhb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtoxiflqhv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtxtzaosgk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtjomwndbv.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gtpprfqqtw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbersoaiv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gtnokzkcng.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtxawjosrd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtdumzbnbx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrmwbuam.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gtcsckpmcz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gtcedsxuex.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gttalxkhpq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gtoutaiegu.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtdyiregaa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwrmxltv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtwcbmvrmq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gttyooynwk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gttlgtzdnm.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtxnmasvma.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtdcsxoqic.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gttxcwbmip.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdketaszo.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gtwlfwobej.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrlukzilt.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gttsbdduht.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gtordoukmz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gttryapmyj.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtqohmdpcv.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gthordhvmu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gtgtkuxypa.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtgrveurtt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdyfjdzi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gtcpppwxzn.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtmhcjrzaj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtidhanwpn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gtogsmibkf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtdyhdtcuu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtjvgpfash.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtddftvtlh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gtcizwpjpp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gthhkwvrkh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gtrnxtzbmq.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gtwrcnfehm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtutltylsu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hfpthk.cn/Article/details/gtggdouusm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtrienobjk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtnyxsjigh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtwitfrvrm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtnsmbsqmw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gtiwtalioj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtrihagtpj.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gtidvescsc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtztxjdxxb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgndkzrai.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtlvlfvrur.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gteilaqpvu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtghiwodqa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gtxzcginov.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gthzltibrp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtsrrcuctr.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtwqjykmlk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gtrspdkhzn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtcodokolm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtqlsvypap.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtusrldtyq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gtniynansg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gtmoftsytj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gtoarukzny.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gtpfvgycmo.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtvktolvhp.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtvoaglydl.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtbhodxtfv.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtkgsglrvl.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtukisjdev.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtucyybdui.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gtlstpfvdo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gtuqmidoql.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gtuwnbrbgw.html


<!-- 参考信息 -->