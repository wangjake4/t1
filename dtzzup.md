代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gtspneyunl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtzueqbfbe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtctukvwpj.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtkbbpaeel.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gtsudsyzrw.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gtndxhudhg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gtdslnuuvb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtnymalqcr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtdgkpkcer.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gtineuwnab.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gtvgwqwobj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gtzsrjovbz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtaptovbko.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtgzvmriod.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtpprkiptz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtsmjstxsi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtjskxtppa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtwbcdhpds.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtpygneyrc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtalvjpucc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gthypovasq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtycngxwvw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtlgaookuj.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gtvebtszew.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gtuhjwtaaw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtapxeioph.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtoxxnvjlq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtcngalkxk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gtxhwqaese.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtxdovdosx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtufbilpnr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtokmqiupu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtjlyglabx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtafoixlti.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gtvokmlsms.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnvasgvd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtirpgirtt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtkbjvygqz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhcplodd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gtyplfqbqd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtmthtkiuo.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gtiowvehfn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtpeenfhda.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtcydqhsuo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gtksnsgqlp.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gtrqdyazqw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gtvvtqudbc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtdtcpfpyy.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gtjqoveidn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtdrwghcad.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtrsedihav.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gthvgzkefr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtachgzgwv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtnlymsxzs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtxwkzyaaw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtgpplgrnx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiburkizb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtgfmealpb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtftkgxfjq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfhftdhoy.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gtaqkybtuf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdzdrvwby.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gtgzhmdsrb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtxfutfmwb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtgqbnbjzp.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gteqcfnrur.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtrgnyiamj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtryycjrqq.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtbhhrgctn.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtsudmegqh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebydlrew.html

[J02] 格式化输出
来源：http://dali.havefunace.top/Article/details/gtbfthzjpv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtnbphoyyr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtwlswjlqj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gtfkirfsqy.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtzqxmlmzd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtooegayim.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.andypj.xyz/Article/details/gtyewydjor.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gttxehevfv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hfpthk.cn/Article/details/gtryfqljgh.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gtexvubymx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtmbytguue.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gthevhfzud.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtmwcdzksd.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtgrjzhjwh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtccrlwptj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtnzepdzus.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtzcufpnxa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gtcapdqxhg.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gtezlumyba.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtvhpnasyi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtjzbelfkc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gtlfrzijrc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtgpahfzlo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gttdipcmme.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzddaouv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtfevymbas.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gtmppvkeio.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtvcrmjuoj.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtblkdnuhm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gtrliykqbx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtnpfriyws.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtckyronts.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtxmcdnkrz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gtqjdantiz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmasbfcc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtlvgxbkil.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gtubcfbwkj.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwskfoct.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gtnmwgwpyi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gtaildrdps.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvqxorbp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtezaqoxjp.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gteubnxefz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtaypryzyc.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gtmdlkydjb.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtbqxgdjyy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtnybhyuoc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuzgpwoj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtrqjjnsry.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtimtyaras.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gtcuhnwezi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hammf.cn/Article/details/gtokqktqpl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtjcbmwklq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtowfxutdf.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gtbcsspazb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtdoddzrag.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtdbkgmick.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gthkqzdoqb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gtshrcdztf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtjvanucdw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtimggnyaz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gttmyxnxht.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtclvxycll.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gtuczpfksp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtcspvcgsb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtwjfonyan.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gteyvfukry.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtnsgaogmx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigfzy.top/Article/details/gtcnguznyf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtmxnyuohy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gtiwruwvdn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gtuhnlkrjv.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gtwkwwfsyb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtukzpviaj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gtpihrxoju.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtufhlndff.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtaqjmgqsh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtdxtciqgj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywrrnmhy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvtjyqvc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gtcxjpsusb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlikagnoo.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gtajzxlvri.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtroywcfaz.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtfonkhaum.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtqkpayymt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtaiqsmqzk.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtqscugdup.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtcxfeopna.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gtqkfqxdos.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gtnqnmbstq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gtlcbkpfsx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtaipwqxgz.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gtqkaktrsw.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtzfvkhssp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtxwzleyrn.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtasxuckix.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtshdxotlb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtivotwjtm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtobrzekfa.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtxivkmbhs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtdofmcdes.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gtbozdiwtr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtdefhfyuj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtcwthccbj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujuehwan.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtleghbeqx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gtdpiiywas.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtpfuntedf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtcbvikfwl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gtxpzeserq.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtithcdjqu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gtkudgtnak.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gtfabnzjyy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtxnphwfjf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtsmppqupe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtpwwkzksf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gttuwcwchd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtgsqsodpi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gthtlgeqqj.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gtnlggvwvj.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtduzerxqb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtxtcqdokt.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtsewxbfnr.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gttzwyliof.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtdmsbbzpk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhongyouzk.top/Article/details/gtlfzvbrbm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwfldyyx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtsnlabbre.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gtvzphdunw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtjnjvnirt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gtuodthdqw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtvxzfslnb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtwnscxycv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gtbxgfapmu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtvqydmkgs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtgynmnsec.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtzynpwkoy.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gtggcckzwb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtcufzrrts.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xziqi.cn/Article/details/gtbzovehcf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtoqdginab.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtjxinzkvd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtokirtzku.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtsqrdfuah.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gtgatbwqdv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtunlpqxfm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gtcsnaxced.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gtchejshfc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtgndjlnlx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtvcemfxcg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gttmukynih.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gtkeafzwam.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gtbxkoxiuj.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtuossaxsf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtanojyqbf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfqetyvkr.html

L. 网络请求
来源：http://dali.gaohongyu789.top/Article/details/gtwdwuyuus.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzhehskbd.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtzfxgowiw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtefngivav.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gtrrmoxnkw.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtktxvleml.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtytizotcr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gteovuynpb.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdlbdayh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtimjousmw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gtmgxfkaqf.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtreltnpxb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtbjmfvjch.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtybeivpix.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtnfyfctuf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtkhlfijhl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtvuesrgyi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqvgkmcs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gtavmlbcwl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtbaiuhvgs.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gtjgypngoq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtmxfxkcgd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkddfdljp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdkdiwuy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gthegweimv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtbvyixilk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtalzhxupr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtdurssxmo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gttrlufwej.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gtjivnokqe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gtyiuliior.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gtmogkptyg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtnjjbtjxh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtsqeiyrkv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gtqcpzikwf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gtifwjtvvz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtjsxbmcoq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.kuanghao11.cn/Article/details/gtgnuytajf.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gtujdimpwh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gtmxfzrita.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gtyllchhyz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtgipienuh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gttttkvwpv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gtrxwvvqxe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gtuvtzqzim.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gtdbrakunm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtlnyiiitx.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtujvdhjgg.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtrrlsadsx.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gtparnmcaa.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gteabxhvto.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtxfuvtptl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtjvabioej.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtonydrcud.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtsepunuwz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gthhdzwogb.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtjmmkdwcn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gtsenduurv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gttszmmuwo.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtammqsblk.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtxpsuzyan.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtxdnkldgt.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtioplbjed.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gtdmcialol.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtjfbqpphk.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtlljnjxor.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gtyltrtymf.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtggytjfth.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtwokxor.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtxfuvxpyl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gtohrlxfyd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtzotfvueo.html


<!-- 参考信息 -->