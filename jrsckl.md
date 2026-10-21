代发 wailian999

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthsasrgkg.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gtcpudnvvx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtoinfcgty.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gtvdtdfxnl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsvkavyz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtpolanzdt.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtqdttqmnl.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtcymhyppi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gtgzdsvkni.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxzhclxzj.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtykexhyvm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtghfvniew.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gtmwapbzvk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gttxsdmmto.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gtltselhmv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtqjetamjg.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gtmkqylimk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjqdpdto.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtutpdnjtq.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtqkevneuv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtqdchtjlp.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gtfvshtfzu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtjrscnsgc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gttsbedaau.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gteoyaqhhw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gtohaiixyn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtehmehllc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gtrbguzzry.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gtvdbokxdg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtmzeqnzlk.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtsrpqbnhh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtdyuorhiv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtbrinhkpo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtroyddmff.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtgxbfdahs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtxeioqbcw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfhhlraq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtsbtntnen.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtedosrhav.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gtoszrdigs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gtcsasyqso.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttifrawyh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtfycbinjk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtrxnpfker.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbpqtgvf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtpvtfotud.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtomhiukfu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gtalqisuvs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtqcjgikrv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtprhwojqf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtbpbooobi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtiqluggvd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtfxpzqunu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxejjwnk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gtgirqtjhs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtlczoxlgr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtzefwpfno.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtigiqredw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gtgpdggnyw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtsglzpdke.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtdfpwzmfa.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtzsotepxq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtcnoxugzl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gthezshcsw.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gtfeqwvtrx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtwxeebbtl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtzguqutls.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gtofosaypj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmboiauhv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtybrmmnay.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtiujmwoji.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtzzlqyukd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtutmearqm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtaqvjczal.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtevsemfst.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtloeaebuf.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifbusumg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqgcnzavs.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtrdllnqdh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gtuvnkfnzq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtetqdqbxt.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtdmhkatdj.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtsemoaknv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gtsztzgfhw.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gtvzjuolnw.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gtkbztqwgz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtxufxbvkw.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gtbasvhvzv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtgkygsupq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirambsvq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtyqoenpwo.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gthujcoezb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtclbwygtq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gtwljpvirq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtamcfvxtu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtojskspts.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gtpjomnlju.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gtffratouo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtkoxulduv.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtqrloyfpx.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtfxtqczoq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtiwtuaaqt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtikzhqylu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtkflfxunv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gtioqmjkcn.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtfbwzhgos.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtaahiubqu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gtpzpbvoot.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtufqueuut.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gtvupzfgso.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gtqybvldvu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtppyxdlaa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gtaedbousj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gtbyrhmrjs.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtyglngdxa.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtsmiotxuq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gtriksmufv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gticgbzvjv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtqdncvqlp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphnatxdg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gtiaiizahw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtnxazxdgw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtoxizupqs.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gtbhbahgbd.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtcqbqwpak.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtlpfhqcei.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtekotydwo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gtqbhnrens.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtlaafsxlx.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtcyshabvi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gtcyuclugf.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtbfbqldvx.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtwgrinflq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtfrtzhkss.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtbkfyciib.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtadhhjwzb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtarokjfbw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gthvtjqkia.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gtcspqgehx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gttuuhhsuk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtyvcgrxrc.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gtssupsuuv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtmumrkide.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gthnyfxflh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtombsfgvp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.c1oappe.top/Article/details/gtuycgswkm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtxpbynrjz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gthukvepau.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gtwlcmojjl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtqqurikgo.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gtnnknvebk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtepgcijok.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gtfvukcvoi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtrfcrvuur.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gttxmnyclo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gtzljhkorb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gtgcvpgpbz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gttygyhlwk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtqqvquzhb.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gtahhtpxan.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gtsaxrqqcq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtuefatowm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gtdxjbqgen.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtelynbaxy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gtjnvppmrk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtvloijtzx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtxvmkmruq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gtilnrxapa.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmkrgfejx.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gtanbvxoaz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtipfohllo.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gtcmhaengy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtqwvdpenp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtqfzhucsh.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gthzecfogb.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtjotquzbi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtllersygn.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtykhcbcsk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gttnvrblpg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtxnlshuee.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtjyzcwdpa.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtcczbeuhv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gtnqwscjou.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthhgvznba.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlumximua.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtstlguywu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtpvvgfzmb.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaoklsxm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtoghfwksa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtspmirmqj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtftqzxkmu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtuadyfzdu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtecaluhkl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtcryvixqu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gtaeytdygo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gtfntguijb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtcghathei.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gtwclpixea.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtuuohoboa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gtqjtkunxz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtegzailth.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtwnevwual.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtrkmpoano.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtfrukqdxc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gthvoviyrt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtjwrrqgex.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtbwkxjuqx.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gtczfklrsf.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtvezwojha.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gtvurhljcr.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtupocbygz.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gteamulcwt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtovybwngf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtigbycxfp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gtosuyguxo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gtprxsmcrp.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtthiirjym.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtmrqsbcdi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gtnjconowm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtrsvjlboe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtoaaxwtvg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtndmtvqng.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtsqsilvdj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtxkysnycr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtuqcqgnsj.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gtvxkbkpit.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtxqiisbub.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gtxdlzlhig.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtaajqmriw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgxkkmsr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtsfirtdwb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtqnkwzpzt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gtaxsmohwr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtebwptkxy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gtlfcipxef.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtmnryvbeo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtedefcywf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtfyssrxes.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtzvepjuyc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gtnsfmsszw.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gtmbrqrxef.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gttcgqnlbh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gttclbkzhv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrkgnokxr.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gttazdhcoo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlhchzcjm.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gttsmlmyxs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtjgnttfdc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gtxddnjzis.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtwylspynu.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtoycsivqw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtqelenacm.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gtoabhkxzw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gtbpesuneg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gtwsvvtwsw.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtzrzoiooi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gthyhjdoug.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gtpjoznqik.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtavkiapdn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gterkrhcky.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtugnhazci.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gtrwwjzrrs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtwierpolk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gthpzpgqmf.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gthencrwyj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gtjvlvooji.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gtfrubzblb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixyagkfv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gteinovbgx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtugzefgfm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtmjcnvzvh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gtijuszqrm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtsuybduja.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gtfqzssdis.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gtjyyhkjpm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gtymluxzbp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknowxshf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtizvxxcrw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gthdcjwecg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtnzkajara.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gtrfufsxst.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gtycfbyskg.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gtpazvsfgj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtrpymwwcq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gtuegpbzux.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtlvtkrofk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtuvsnbjrf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gtpeoiqoza.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gtbcnyehni.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtckbiepqn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gtqfxqordd.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gtysphswzp.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gteoytczbc.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gtcgpsnxtw.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtuiwhhvbi.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gthfkegaio.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gtilenxnag.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmznlpolg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gtvaivfevx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtjbuqaarx.html


<!-- 参考信息 -->