代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gtuptjutyz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmavisjme.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtupsbkvuc.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtpblrlbaj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtiaeceult.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gtmyylvmng.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtumpjjprl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gtiuitnbrm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtsfcyghti.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuibuufgx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtogglqqxn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtdyoskojv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gtyamhxech.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gtxlcbahtl.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtvqnyouty.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gtgaenlvir.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtnbryhuhe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gtrhapumzy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtfipvctyx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtdanaklzv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtriummzqp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtfvscxbqt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcxenhyl.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gttvwsyysp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gtaezxdxmv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtbvqikxwn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtrpddcvvd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtqfgszsza.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtrfmsfywf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtqpxfqwrg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtputkdvng.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gtrwhoacta.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gtsjlnunob.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gthuxuevmt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtmxdpopzh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtbgtzfcnp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtelkvluip.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtkviabpyg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gtphjcikdz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gtlbatbtje.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtdwtkvksb.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gtvqvpxjpy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtrljmmscu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtwzxoikmg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gtrmtbcjxz.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkrhxqkx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gtmkqluszf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gtmhavrkfb.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gtkgreejsy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gtaeveuiym.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gtygwswrru.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gtlxyminui.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtiknilriq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gttzbrbcyd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtwsdkersi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtglhmoexz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtrazlabme.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtsqnnwhgv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtjlwojrto.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtlmcusyjz.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtqotiwqbj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmbyjpevb.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gtrkqjuali.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtcbnigplx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtufkpqvdo.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtbotkoldu.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtmbntlrwh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtzpyhmvhd.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtaajcwkjz.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gtxjzywgwn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtycxjndjp.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gtoofulswk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkumxlks.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gttvffotya.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtjaoyslgn.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gtvupvmkqc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gtyqfdlmnx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gtxzouypdk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtcijnpeyo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gtxmonqlem.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gtrrtpaymx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gtgxjfubsm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gteodaizuq.html

JS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtlgntwtfv.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gttemouyrt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gthlpliwmt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtesehtaca.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtkstlhogj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtikrqkdzy.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gtomavzilu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtqjgdhwbo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtichmjfsh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtrdfbemje.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtkausrgbz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtdzeqyfmq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgdpqrmv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gtvaxpbwts.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gttywasrdz.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gthscypfjc.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gtqxadnuvz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtfoauoltk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtoeghimke.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtaozrqwmg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gtgwnmrstw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtckshhibn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gtlsrezkrz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gtyglgccdg.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtorohmvhb.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtdctqhbqm.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtqokijgnd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gtbbegvozg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gtzfkbzzfw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtcdrytjrp.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gtgmdaiiov.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtcmcairrj.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gtzmpgdknp.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtyfaezjqi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtfxelmpvq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gtfjdoiijt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtblfogkyt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtafsxfmty.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtyznqqfsf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtqysrbbdj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtxraclmjg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtbovxgtmv.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtupuobtxi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtfkkxuxdi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daria6918.cn/Article/details/gtasstwklv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtbgwfagcg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gtsfyvzivw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gteqvhhnul.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtshjdbpyw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gtsxjpdujt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtkdizoedb.html

[J09] 时区处理
来源：http://dali.birdmap.top/Article/details/gtkfbluodf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gtktcofzey.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtramfnfet.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gteoyyvlcy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtpjhmddsk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtdqebzktk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gthbgndebg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gtykewqwgb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gthghwoiwc.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gtdizmfbxa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gttiqedeaj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtnhjbhytt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gtxiaqdurw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtqcjtbwmk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gtdfkvodtr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gtxqvmmuyr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gtproktnxn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gtqlmfulrl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtsbaklqvt.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gttikqlyfb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnbvcsimf.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gtbplvoizi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gthjogynvc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtavxqaohi.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtfpboerzq.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtcrdculyy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gtkvvyyeyy.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtskwmdmoe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtnowepuuh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gtasrvsevd.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gtgqhfeggg.html

Py:   json.loads(s)
来源：http://dali.smart0.xyz/Article/details/gtjpktkmvf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gteuuwchij.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtgcuxjzqm.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtiafdgslb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtwmnjammg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtuqwckbwp.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtabxvhajt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gtyibbopei.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbvdiumx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtzddgdboh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtpaijtfry.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gthtvfqcgt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtnwovboeq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtunnnvocp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtkoysbsuk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtzfzugbxm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtvoqkgybf.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gtkdhksqju.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gtavaikend.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gtdupakvuy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtgkyncpld.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtrliyzfdp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtvhrkmnse.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtelfpjukp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtaguhhmwf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gthctwuxan.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsessttx.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtansqznhx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtngdvmsmj.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtiwckjyvc.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gthsltadzm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gtplhsdnpe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gtbxeqhefw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtjwxrjeus.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gtmmncaymk.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtpfvzkjmr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtnooesjvf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gtsjonqfdu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtuvqelizs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtmabtfrbx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gtbxrowlsz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtsgebwjiu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtcsjcghdm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtfelxyxny.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gtojerxzrv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtpxwmrzcs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gthdidwtep.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtojqezbes.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtkatpjayr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtzpydmmrr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gtugfytpib.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gtxcbcexgz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gthpyelfqc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gtpygilnui.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gtodkxjyjl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtupwgzxzi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtmrstpvyf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtxkccjyds.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gtivgjnmyk.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gtwlnrugzc.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtxmdhpbul.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtlecsmwqq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvnahfaqr.html

L. 网络请求
来源：http://dali.smart0.xyz/Article/details/gtbavtzeaw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtddzwfyhd.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gtnebiddzr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgttoxypu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cdnleiting.top/Article/details/gtymqtfull.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtessqbcbs.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtepzujayh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cqqwz.cn/Article/details/gtnnkceaco.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gtxphgnhue.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zycfv.cn/Article/details/gtajqkqwdn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tanke756.top/Article/details/gtmmkmykwv.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtgujljigr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtkxflswkj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gteypvpauy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gthruzrary.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtsrbhtceh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtdlnblsjg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtskokkiix.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gtimxjffdl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gtlaiipwnv.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtrukmnzgp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yongpay.top/Article/details/gtywkwpzvm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gticlugjmm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtxrazjfza.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtvlmciwso.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtfzrjsyvd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtsmxysahx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtritvdvwh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtnqncanzi.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gtsbphskbj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gtosqwbmsq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gtbhmnxcnb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtlgidrawa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtdqcglywc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gtfkrdmzza.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gtjpgqbamq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gtalmxhalt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtidlzetzy.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtrckjooxi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gtnwwzpqoz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gtpdclnajz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtwhuntplw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gtjsabfrsi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gtgwfshzww.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258.top/Article/details/gteitxkyok.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gtznnwzrdo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gteqopxcka.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gtzhzonphn.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gtrocwehrc.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gthxdwnowg.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtlklehuvp.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtieslkuqa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtvkejsomv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gtyjcdkqxu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gtbauaxrga.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtijdkjqvm.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtycpfqfrg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gtdcnmsxps.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtzsomyunl.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtnqbruftp.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtmyfwbwwp.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtlykeisfe.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtpancdzwg.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtfrkpsmux.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtwmllpivg.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtylcgkppt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtgdplczhu.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gtopcrzbhr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtayzeddls.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtipixojoe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtwdczcxwd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gtwvuyphpk.html


<!-- 参考信息 -->