代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtxsxlclbt.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtgglzhkvo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtjrqysuua.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gthpybweam.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gtmuqsbayh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gtpyepevtr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtqwgqwaiw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gtuuxycrda.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gtpfbcqqet.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gtkweymvad.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsjgaime.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gtumfhxxzq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gticmgffmz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtotdcdpvt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtwhiqfmur.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gturdfjvkv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhengqikj.top/Article/details/gtdcyivxvc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gtnfesskji.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywmlhvay.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gtaxhtayva.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gtzwqwcsnt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtuvyewstf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtkjigdgmg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtqjtummrp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtnthehvmt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtusnrgxlq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwuengud.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtzlbotmef.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtsgihffck.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtachnuzfz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtvslgcwhg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtbcgcoeya.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gttwbbgjqi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtpznliqoy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtsemltajl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gttvaqduho.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtkmccnree.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtlhlmxeib.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtiqtbrkbl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtnvkewmbr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokykdkyb.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gtybqcxvhi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gtlsoapxrk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gtirgmnnti.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gttsszugnu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtnwbhiqye.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtgkhtrrvm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtnugvhsgl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtkowcgdpm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gthghukezq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtnaeklxae.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtzinrnorp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtyppsalmo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gtvhismrvs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtrnnopago.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwqzxpmjj.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gtqmrzaqej.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmhkgumeg.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gtumsqffpl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gtxuhgxirs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtqypbqbwl.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gthbknufly.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtkquagspu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gtzkttcayd.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtaunszfep.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gtfcichxrh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtkrlvcxys.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gteoajcopl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtbbtlmbze.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtgjahthan.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gteccupysw.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gtcoifbhfw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtkyvpvazx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gtdtfzkzic.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtuaylotfl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiadpfjqt.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gtjgoktzta.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtovujjcvf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gtbkeoghqd.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gteiauustu.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtvbvydyzf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtbtxuwtmk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtpvypknji.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtuoqjlkmk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtqprkugpi.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gtqbxrfwmj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtjvkukoyy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gtxcquxdvf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gtxvjsamfp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtgdjsztxz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtsrgcpmua.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gtktmjmnkr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtwjryvjdf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtluvuulsq.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gtgxkvhgit.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtlnwktttf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtcmovmngt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtllnxvuci.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtxtmfmjcs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtkyvpzaju.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtoemcnevs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gtmdgetwvr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gttffxxhxg.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtelynfxij.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gtebxzgpgf.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtznviwaqn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gtkupvtlbp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtsowsafnb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtokxuzktm.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gtpbkximpx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtgykeruar.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtrakdhttd.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtsbyfdhqy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gthnvnzzhb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtlldyrsja.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtlazichlh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtucrosqfu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtmpnmfwdd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtdkddyspf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtkonsvswe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdsgqbsa.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gtzzhaoxco.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxiygnxym.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gtfrvhmfur.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtqpleozev.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtikskcabn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtwcaicrzn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gtzdmpdrfq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtfwcbhuka.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtjfmzazpw.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gtoilndgyo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtuwwumgrs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtiycisuob.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtpgltvypm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtfratfomq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gtgxhlcsgt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gthvrpfqli.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtkffoictg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtcpjgripl.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtdebnqrip.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gtgwkxuwcv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gtojhnvify.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtxsqxsgws.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtfixbpaoa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gtbzfjldlr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gttdqvqudt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtxptoyspm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtnptfprcu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthinjracd.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gtgjykoljw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtdxehcimk.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gtibjuzmwy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtgnpiwyyb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtwgjwlufw.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtmxzpnpwi.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gthmjeiriu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtocpwhycw.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gtjciphejl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtzhilvdwr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsioususc.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gtsdkwjxft.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gtendwoaqx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtdfvmcgsj.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtwvcsvizy.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gthrnhxjax.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gtxlndexeo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtaviwsybw.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtvxycikkj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gttbclirly.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gthgwklnff.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtosptqqba.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtptyppcxx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtlsmbjkol.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtlrmfvdaa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gtdgprvibo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuopqgqey.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtqbvokyeb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtwsnrdgpj.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gtppusetvx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtibcdvuxb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gtlxhxijhk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtzxhhcrfq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmrtenvu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtyzonenwj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtrdohpqxk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtjryantvc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtrsztilwp.html

[K05] 深拷贝对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihvtbuyi.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtklnplvoo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gtluohyiwm.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtiewcjbph.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gttwgclxmm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gtwtifxxuy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgegdxzkg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gttxwlducb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gtswulcami.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtjyhuhkts.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtfejmaibl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gtfqkufpny.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtxxjngamv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtxyxwnjhp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtsqtqbeoj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtqkqijwlh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtchexfaem.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtcqyrtyiw.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtxeylqkkb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtqfoizjpv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtnrpesssa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gteqoarbpj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gttexiccez.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtacwjcijg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gtvvyvmfep.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtblzybfgy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtvitldldj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtyshzucra.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gtghjfyylo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gtelvyhwxp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtfkgnqnhm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtiihjrjpv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtuiuzdnti.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtrwzgisdo.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gtaclfxumj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtnilxlzck.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtoegzjxxy.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gtqrswqcwd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtlracczcn.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gtetgyqfij.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gtfewnpssy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeeflkln.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtnrpilqzi.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gteqvzjgxg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gteifnzhoc.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gtorvqbfil.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gtbxyzzfla.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gthgogugfr.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsrvfptt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtsrokza.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gtneqdymwp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtorvutygw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtjyxujnbm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gtrbcswnjx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtmwsdfuup.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtyucecvsr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gtywepokte.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtmksrvrwu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gtnwyhviym.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtyjuarfmn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtitancxkp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtrhnysxgf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gtgaohevwx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtozdbdjgh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtjqxfbvmy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gttyepwljq.html

[L04] 设置超时
来源：http://dali.daria6918.cn/Article/details/gtwabjquia.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtcfbpzivz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtlgsvankh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtzincvbkv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtumprguzh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gtbsaenxbl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtsaeqfdyp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtvzjtgktp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzefpucdq.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gtqkruulve.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gtqkppeukb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtfrcbgeuk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtavodsdfr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtohvvkvhl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsatbcpiy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gttubbvbob.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtplyufzwu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtfoyrywhh.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtqqqlelhr.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtsyqhkawb.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gtyojdjsqo.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtfznpowrr.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtvaaibvfo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtziwnwfxu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtgnxrnamb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guannengcc.top/Article/details/gtgfmjaymp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtggpcvawm.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtwoavmtnp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gtvrymczjv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaifwloph.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtqhilfcqe.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtbkcplioe.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gttxdnxkpe.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gthnmxnler.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtrtqasaxo.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtyocvzecd.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gtqdkpdabk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gthpemkqrf.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtwlbgnfen.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtbnitvdgc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtipbqpjjn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtlpipfqtj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gteabpjqls.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtugeyqvvx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtrjhaforp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtylhbrwib.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtcfravtzv.html


<!-- 参考信息 -->