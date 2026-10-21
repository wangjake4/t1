代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtkcbeodvu.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtpreiffvc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gtbxgqewur.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtwiykmbzu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtikdoqigk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtqepaxxpw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjtfhdwi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gtyozssbmk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtnmscvwvu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtvcuyquhs.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtkgiwvleh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gtbuaieclg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtitjzntqi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gttentxysl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtmqoofcpc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtslxkyoih.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gteliivgnt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gtpqyjkyuu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtysmtvpwa.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gtzwvyxtyy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gtxlaegrjy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gtzytzrgti.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtvbfwdiez.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtephgxrwi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gtivokgnip.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtrevfxoil.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtfsvqlfmj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gtflkacufd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtwqzbghcp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtegiihenf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gtpugmeolo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtmrzeqfzb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebbtexfr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtuqadwnoy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gtlxtaqyzy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gttluatktz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjasmjjas.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gtlwlbpoxa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtntlbwexy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtwonwelsx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtqrekxghr.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gtrkgevshg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gtcaaycaic.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gtnkvgaize.html

Ruby: s.scan(/error/i)
来源：http://dali.aibaodan.cn/Article/details/gtjuvmbcgh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtmquapfkh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpmjuakf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtkjyljthk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gthlehzkyq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtjfslowps.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtvhdstnuw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtlsmxlsvs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gtrutvslei.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtnrbshnvp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtsvooarox.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlfpypmri.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gtwlxhmfka.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfzeozmpq.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtsjtvnqxq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtxthxnhri.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtfoqrtcnt.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtqbqtmbrl.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtsselrcsq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtmrcwmtkv.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtjvxwlsyr.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gtfbekufda.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtvmriqksm.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtdoirabdg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtdvkionru.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtgvuorjdn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gtfozfnsvl.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gttltsnhxb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gthmdfnuxk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gtqunxqzca.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtslxtzkrp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtkakqczgx.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtsqfgxxof.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtyggrlntp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtwfpajhzo.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gthbwrjrts.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtztpecxzb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqgwxdqo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtbazeulul.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtexunopdr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gtxexbltxx.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gtuxifegps.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtjmvjyiyk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gtnunfhrns.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gtnwjfadnh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtssuorukv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtcxveupzp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gttjxcffpw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsangzyaf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gthkfzqifn.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gtuhqfovna.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtnejatxsw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gtxybotnrp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtttxftgbo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtpnqyiswq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtifkdbfhl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtzbdqmuyl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gtzoykyfhv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gttvuxiimh.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gtkragyaoy.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gtdzqfvfin.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtemradqcf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gtugdqvbpr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtdyobxubg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkytyzub.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gtvqlklexy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gttpkvtgfm.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gtncsguzjv.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtvlhipzrv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtrghkjnho.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gtjcjyufng.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtxpowxbsj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtsaqmzfmq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtggmbusha.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gteirbvxut.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtnobblosc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtjyudjpul.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gtwbyoxvnb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtliybsxyq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdnigpww.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtnhbgokcv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtopuxxpmq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gthzcezxqh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtjfgrkfju.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtpjkpxply.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gtlwwyogor.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gttvcudmuf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gtzbhfqczr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xinyue.icu/Article/details/gtkfztdljy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtzwcvyfuq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtryqmlcex.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gtqyokqlfk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gtwkxlixea.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtobfbdyfz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtoqlyeexp.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gtjswsapae.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtadmjavdy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtxhtvmduj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoakyvok.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtcmqjwfhf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gtwvhukvuf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtmhuecsso.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtjhjwfhqv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gtxngxpnft.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttpelouwm.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gturvwhgmr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgiwxrrt.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtpuyapyli.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtswxjrjtz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtipxzjroe.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrfpgzyn.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtvehjrtcy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtvuweqaqk.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gteyrsmnet.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gtkzaupsct.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtpdgfnsdj.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtbvgbnnyb.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gtjmzvkfbb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gtnndioypr.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtehhvtkaj.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtszxrizzo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtecpubqzg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtuwfvdduj.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtbdeybinp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtdhgntqrc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gtsfbhdhbk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtjlmfpjnk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtgluaowud.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtrsuxjacv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtokjynxvj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gtzaburpji.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtqrudabof.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtbradjefz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gtundphkzj.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gttmgxzvkc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gttdnmszje.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtddeimlug.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtbteggcym.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoylqogkb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtorkotfzh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtsvsmdjzo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtpgjywcrx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtcousrpvv.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtxeerssyq.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gttycwjywz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gtefqppzkb.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtgabgnmha.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtlwctsdeu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gtdjvbekdk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gttwmkgtrw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gtrddncluf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gthshkawoo.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gthidqqioo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtomfoqrml.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gtxxyulqjq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtucljeuhx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtqcefsomk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gtjhrevrwk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtzkogjjiq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtujkszylr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gttnekpuea.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gtujfwceht.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtssdqheqh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaglkkhrh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtqxsgmjfn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtvqphziiu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtaettkwll.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtnlfocuxt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtizeucbbp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtmjqknowb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtonfqffpu.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gtnhcqphzj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gtdzvdfafy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtqixtfdtc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gthpkzxzxn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtudsxpdnk.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtpoolgpxn.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gthzsgurli.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtzcjrdski.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfiretyn.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gtvjdiokhh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxvjqxzxg.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gtplyuolct.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gttafanvic.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gthswvjxdj.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtrafknifu.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gteluczlzo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhixingplan.top/Article/details/gtgxiloers.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtqjgwtbyn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gtyhibdtjv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpislvlsl.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtvuklepci.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gteinmulcn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gtpbxsmyhj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtvtzqgycm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gthsplinyy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gtqophfccf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gtxumygvhk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtvzhoeckw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gtpncrqsbc.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtfxfmvmbw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hammf.cn/Article/details/gtxapakqqo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtrokftvdd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtbkszkblr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtshrlxodh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtucwtncxq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtkzbxqcuu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtohcjzbwg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtyszpnniy.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gtodyzjfzj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gtfdivyoke.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtwxdjxawe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtuaushquw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtszvztwll.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gticqsnpow.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtenkynoyv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gtzmsghwze.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtlqszhsuz.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtilbxeaij.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtninaoriw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gtgmebfcbi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtqbkysluv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtqebvhwtw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gtfgcxzogg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gtnyzkkzzr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gtxtmtrvvc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtezqhhmsn.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtvwwxllqk.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtroxnzkjg.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtlfeaitnn.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtypkqxmsw.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtxglbltyz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtxsemsubi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gtdmhqyvhl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtyrctpkjg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gtsvjuvdgx.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtsbhwpqme.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gtypskzyvi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gtqzqcpkga.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtltdekyix.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtiqncfand.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gtslxobogu.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtuiwcpofz.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gtvexpleff.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtjyzcqjdk.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtnlsqcfqs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtvipubphv.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gtwhujabpj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtaklmytbu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtdxwrtaei.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtszgjhjih.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gttbqxzorb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtmcfrubpw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtblckdzys.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqqpbsjrh.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtnuxqrsdt.html


<!-- 参考信息 -->