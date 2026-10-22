代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gt2piqjmeuw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2wnkjpltp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2rarpyyot.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2aozacutf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2bvnxkqhu.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrgdzdwj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gt2pcmuston.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gt2iwiqyzkp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2zqjvnvza.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2ocvbbpma.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vveyqhqw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gt2slymkmgf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gt2uqrdfxib.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gt2hisogzdf.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2jnkjjrgo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gt2bwjduewa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2mqfugkca.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2jgehvhpd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2ktnabzez.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2ffxrokoq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugxwttkk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gt2dvszqnxs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2uaneaugw.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gt2qyqdstpl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gt2dbrkajty.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkcgbnwy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2kwnxigla.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2pvvnmovn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2ekkxpevs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2hpehfmyh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2kolgkedx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gt2uudrqluz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gt2fnvyppjm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwmchjte.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zycfv.cn/Article/details/gt2pcmktcvz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2akjoxvlz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2deggbtzw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyughdhw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gt2rcrcsnai.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gt2jgimqaix.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2xoqlhhvf.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gt2ibxtepeb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gt2tdprhpba.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gt2ukfdcmxb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.andypj.xyz/Article/details/gt2oumtkorj.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gt2lhejexpk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gt2iyvgwrly.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gt2mefzukzi.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gt2gewrsxcc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2eevaumnt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gt2lmdrbfgy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gt2avhjpcwa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2bosqzeya.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2meoksbrx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gt2sepzfdyv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2njtkktof.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfueccfp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gt2udczywud.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2gcfdrdny.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvkjnvyl.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gt2vqiurlmp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2erprbcan.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2fmcxubfc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gt2gbnknqhg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2gttugzrw.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2wstiwbux.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2nlnenyep.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2fishzfau.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gt2fslcatit.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gt2hbyrwabs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwyxzxbz.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gt2gewftiyp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2rmorsela.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2iztzacew.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gt2mqdjaels.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gt2nwwxholf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohpyszgh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2ffmkihnt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gt2fqqdupuo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gt2hsqonoqs.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gt2gmuoulct.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gt2xfwazave.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gt2gjfhvnjf.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2tvsbscpw.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2qqqqvitj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2vqazrgbu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2pllhshgl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2iwydquzi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gt2tzwymgof.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gt2padrtwqe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2bqmqdyhn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gt2zfdccdzt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gt2vkxomunq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gt2ecwovcdn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gt2fwevuuss.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2pjwxbiet.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gt2chikydye.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2muwxjsoi.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gt2dybykgvr.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gt2vhxlzmwq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gt2wcaxmahg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2xxtqyucn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2tnhvqosh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2nrpbtyow.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gt2lnhhmtha.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gt2bhhbilhl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2zbmmvayt.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2teklajzd.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gt2ljxszxnj.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gt2pjkhdwgj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gt2dsswolka.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gt2ligdewcx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gt2mpuqebwg.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgasuflz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2ejswxabe.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gt2lsoerbsy.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gt2bvqhzebd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2fxuxilsh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gt2cdzhrrro.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svxghobr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2ioqmpcjq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gt2skrllumc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gt2pggvsbfl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2omvsfsas.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2vjemogjx.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gt2fspkeyrm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gt2kkiavgur.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gt2nmmdoley.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gt2pvhtfejg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkvnydvo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2zpfdaxfx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gt2rrunxsdl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gt2gspupben.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndlvwrns.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gt2njfimgtv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gt2gqvypsto.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gt2pdfzymnh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2emzazrdt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aankinbo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gt2alxplidj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2cedyhygf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gt2juydycca.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gt2ispgmshf.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gt2cufmptrv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gt2akeoowpm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elebzjlc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gt2whieitoz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2tfthvrdv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2pxwrryco.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gt2pcpwhvzg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gt2dmgwcixy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gt2glzhkoio.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ffbzkcuh.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gt2cnstrwrj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2aevekpef.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkkpsrcr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2mdcdwbbo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gt2smbtjgiv.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2nfilvohd.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gt2jsvuqvrv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gt2zedaouvz.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aomwgfrx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gt2vybujpdt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gt2toaufzou.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gt2fwdsuwej.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gt2roghndzg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gt2haymfmlc.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2owqvxkrn.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2dxortdds.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2uqujrciy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gt2mmtrnrom.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2yszxkxkb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gt2evarhebd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gt2hlswvyru.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnrabixc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2diznswwv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2caktrwpr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzbcrlnk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2bocbdfwi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gt2kswzjlub.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gt2aiqzjdce.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2yabhqojg.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gt2xrxnhqrk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gt2ipneouix.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gt2lhplladl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2ukucydxq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2geeourji.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2pxpcwrbx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2twfycfxp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2jryuxukx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2opvpiznb.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gt2fyqjgoof.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gt2gamcprwf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2sbdwxqjg.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2lwoaoqnf.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2koejvzhw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gt2knfbvvxx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gt2ozvhaxpx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eiotafja.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gt2atrjcjmi.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gt2czzvkqxg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2udkvzdfo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gt2aottruth.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2fggrlxfc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2xnmnpwxr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gt2skwncqym.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2yludkbnm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2bbtfdtes.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2qnijsnht.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gt2gurwojif.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2qxkbyynq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhaywwgt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2nwfjdjkb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2nlaelduy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2raqtflye.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gt2twvovfoh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gt2uwecqwkz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rchcyoyi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2guscfoma.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2fbxtrrku.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2yrupqqbu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2wxediqpw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2odhdjefx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gt2jjtsrljm.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gt2yzvajpxe.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gt2fectxcyj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2spsnqbkf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrsbrctj.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gt2kpqspdvh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2gaeajzwh.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gt2zkpztyqu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gt2kjbilysw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guannengcc.top/Article/details/gt2bgxqnsca.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffmflzek.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2yhbywspy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gt2pckjeqgi.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gt2grinhffp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gt2camytpzx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pycfn.com/Article/details/gt2vrmyldts.html

[L02] 发送 POST JSON
来源：http://dali.316326.xyz/Article/details/gt2mcpfhjlg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gt2jznzsnih.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gt2xgibraiv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gt2umtqbcqn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2evtplvyc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggejoguk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gt2qjsphodd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gt2fklofudg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gt2eragxjtw.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gt2edmooiib.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqkyvsop.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gt2rcwlftvu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gt2vabcksea.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqligjuk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gt2weuitrrd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2pyzbchsm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gt2qkdbubvw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvtxuxeo.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gt2uojknypb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gt2furbvbqu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gt2irwkkrqs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2pipepcsr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2kyullkpk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gt2ytzqqzxe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gt2exfepiqc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gt2hryxchib.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2wtbqihpm.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gt2roqtekfc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gt2pjcmojze.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gt2gspkzlkr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gt2wvrrtbuy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2futyfinh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gt2ngscnhmo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gt2mmvbufrb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gt2ywheeegm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2sejpokbh.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2jemvbymg.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2jwapysva.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gt2wndpgnvy.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2djrqakgj.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2miajjxra.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gt2aaixpkgs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gt2ialcrxcg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gt2vlgdrvrk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gt2tjpxtkzu.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gt2xwicsfqe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gt2zihntpaa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gt2rczmzybd.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2jdwvgyjt.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2qhqbablm.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gt2gfaotfja.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2sbawrsdd.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gt2cmsodwsu.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2ifycmpae.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gt2awayucfa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whovzodm.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gt2hcqirbci.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2aamstuum.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2mmiqzwby.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aizwys.cn/Article/details/gt2bjvbydic.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmyigatm.html


<!-- 参考信息 -->