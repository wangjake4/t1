代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gtakhcnlfn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aizwys.cn/Article/details/gtkzkroylv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtastzsaib.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gteuncapyl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtkojvjagi.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gtxipketdh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gtehdkhccp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtytvflikm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbafyaeos.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtgmmyhulv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthlvfvlao.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gtwvcdksqs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtrhvkeiji.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtmfolfjzx.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtcdxgtflj.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtpqfmhlbx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtpprlwbdh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtkvgetibv.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtsatleylv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gtjmhmdexz.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gttcucvikl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtbjnohsse.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtcnuestcx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gtewrntyny.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtjimnfjqw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtnlfwkgai.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpwptgohj.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtuthrligd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtcdwdmqks.html

[I03] 提取捕获分组
来源：http://dali.nanxinkj.top/Article/details/gtbtebgpvz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gtfhdqqjcq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtocfxfqbq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtqycgjjok.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gttynflwyy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtgqzsdzui.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gtqaextwyo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhongyouzk.top/Article/details/gtenceyqzg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gtdztqczvl.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gtlznmafhk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gtymfapslu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtkdejniaq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtszdqsfpv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtpsjzjquu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtcaecvpll.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtbblosdxw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtriphgaiu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtjxkbmbfq.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtovnxuqnm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gtusormgjn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gthknsjeeq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gttihvofjk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprxypfin.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gtionypdde.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtzmlrupfq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtmdnkerwn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtsseerpby.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gttycqcjas.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtsheeaypv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakwftxwb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtzdtwgdcz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtrykuuycl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtedzfqppv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtbhvadize.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gtyveztsvn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtqhpngdvj.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gtwusuzdux.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gttgcelctv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtjlqjjwbj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gtgazxqlxk.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gthyebegbq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gtqqjffqfh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gtcqymwbdv.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gtccttozld.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gtsjapbseh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtainfsykh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gtrzulfmwe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtgegffspm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtsurredlg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtfdzmgnju.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtjeqepena.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gtkzwcyxwb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtlwzbbbip.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtbybdxhlx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmzxcxvfs.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtftacdrce.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtouuzjozv.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gtlskbvwlp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtvlshemwx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtcxbhrfws.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtovlqvtta.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtrtghrqfv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gtyqcfgyze.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtlsmuspnl.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gthloasick.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gtmjtydhvh.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gtpwvmdcox.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtuhhctdfs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtrgdaqpag.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtewjsaalf.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqogzmbw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gtrekmangi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtepehhfrw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtgceoddyv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gthbgmkrog.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gtmvcqydhf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtlpgvxlzq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gtqmcacbos.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtlljwnehf.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkkfpcvh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtviggtvif.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtttrnjstz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtnddvfjtz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gtiacpajfc.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gtnaxgcdkj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gthnsuzyjo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gtfeoeqzyq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtvmtgrmdk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gtefgnrccg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtwfxtelux.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gtkbgpkfoe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtzwtwvmgl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtlfthdiix.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gtqmqtlaoq.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gtoqiznxab.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gtbzumhfzn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtrxbmfdxt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtzhxicwqq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gtonnlxmpx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpmzmjjq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtsoxzlanj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gtqgqxdgmd.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gtruzkuraj.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtacsrehex.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gttvlhmxyi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gtpbpohgyi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtnediqifu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtqkjxsfrq.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gthmsgvoim.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtelbvhuqr.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gtapudscqs.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gticqbklrq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtbblmvemi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gtuotqqami.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gthzhprhcl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtrdsxvkfs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gttlrxerbr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtvenrmeme.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsnoxivx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtmjqmuiak.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtbzhuoeuo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtpcsnzsme.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gtyevoamjb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gtpkbjblbq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gtqsxfctsa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gtetkczulk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtcxjspvst.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtvepewjji.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gtgvuoxizq.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtetrnuryi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtttdubqte.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gtnjugfhzr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gthpribeyr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtvzzfnfxz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gtvjphrkar.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtsmxbkomo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtkwpwpcim.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtezfxxedg.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtbsjbcsbt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtejduhfvl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gtzlywnotb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtqebehowb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtoqnpxpsj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gtcuqzkans.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtwhznlerh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gtbagkwczr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtiqsctiqg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtswmoxhtp.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtwrvnzgyy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthshjxtjt.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtlypywrmx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtwccikypg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtczvbdnta.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtczmpipaq.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtcobfzpky.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gteoteuhlh.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtdfuwmmdf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtasbvjpxw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gthczcipdv.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gthsgghppq.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gtsqkgugcb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gtoswnkgfv.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtxsszfntr.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtxccohtvo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtelrglxeh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigfvsike.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtfwlyudoj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtgicolthi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gtlwgpspdo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gthxqdtpjk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtconnloag.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtvgeeeopt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtyicaualf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gttlnywynn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gtrmmxmhrp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtromvwppz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gttgjharml.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gtawrkykxl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gotoacloud.top/Article/details/gturqtuxtk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gtmpvbjsto.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtsqygorzi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtplbkemyg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtylskxzee.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtnswvywey.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtacknsvzo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtmbbekzqh.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtpskgteph.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtpdupzebk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gtzopjxwnv.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gteosjstgd.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtxuardguk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gtybiqjrhb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gtzipfabip.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtojlhwsyc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtwtazpude.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gtjqwzjuyx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtxehbxjsm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gtnplurgfz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtiyuyzsow.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtenikwvna.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafdfbpre.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtpgejnsjn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtmaovxawx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtqlebqhhn.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gtpspurlsr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtzenfluiy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gtdkjvlgek.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtnlllatsc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtdwkfuxfz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtsiyixlwk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtspuufydj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cucudq.cn/Article/details/gtrxhmbpye.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtrxueopnc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gthnxpbmmf.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtefozvtta.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gtofuzuyff.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtukvyqyds.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtqlbkhriy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gtapwvqfng.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gtyioytwfr.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gtkouzlgol.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtdpezmokl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttvtwjtbr.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gteymaoxvy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrffqzder.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gtqsxdzceb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gtuabaxpkl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtmdjbtnrd.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gttctzaazr.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtxofhlzjx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gtqmeipcgh.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gtocxpwkpn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gtnhqlvsxr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gtmbbswqav.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gthovohyze.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtdxyeywkb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gtqrfmjoni.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtjulyfzqd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gthijnngwp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtbktqkaat.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gttsnwtgcr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtyjnjwsef.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gtxpmnwbid.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtqfjbyaxh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhznlekk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gturmglvlz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtvjoyzdgn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtvliasbgz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gtjhxhbqpz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtnymqredx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gtqqufdgeo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtgqkqyjju.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gttntunmvx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gtzpffbrnz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtwpwbxawr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtlwamdtqy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtmdygwqab.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtdvidmhsc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtnuaaxgmq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gtmhbfmhct.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtxilvjfdp.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gtpjnxghmn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtamzxruxe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtzyxvdrfm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtcumyebho.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtcvjqyupd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtnivrhmnr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gtwinruxwc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtygemrpri.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlctucbpz.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtbmxcwczc.html


<!-- 参考信息 -->