代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxpsfppp.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtzfhvcsql.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtunttpfox.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gtziqpsbsl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sysykeji.top/Article/details/gtssspvoin.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gtoyrlnqre.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbexgeuyh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtlvuoxucv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtyqzhvexa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gtvbfxiafb.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtrvhovmqk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gtuwsettlj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtcvynpkmw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtgfizihzg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtjfayyana.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gttutwidlb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gtadjmntjg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gtqamwanne.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtrrtlceut.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gtbgebxcsc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gtuushbkqm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtwnuceqyh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtdjgktxxm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtomxspnlv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtyoijnpnk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtarhkxgct.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtazcdzwkq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpktzzvqp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gttcycaeba.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtvepvsdlj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gtxvvninun.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtdmvehoak.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtnehphzlq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gttrqcvjsw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gtczmzlqzo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gtfidpgobb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtphfgkgsp.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gtjgbnkkhq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gtmrvxbyef.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtlccrgnsl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtdefftibr.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtkawmfznr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gtyadrnmow.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gtxwvdxwbv.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtepmsrycq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtlyindxvl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gtdxchvozk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gtoaeicjey.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtlgabvjsi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtrmofacvm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtbiwbmwms.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlduweit.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtvhgfdadl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gtcjcrnjel.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtrttgtihv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmvycbhwo.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gtikxiuimh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfimktocf.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gttwuazrhz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jyoumei.cn/Article/details/gttvcfzyfp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtgchinopk.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtbcxyvzmf.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtbkwdmxhq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gtmsakekea.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtsubimwfm.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtiohadkvi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gtduhbwoky.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gtvxhedrch.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtqgavwczx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtygcwktwo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gtrvocuvkw.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gtztuzsfae.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gtomuxusjy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gtwrrzfqcw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtdkqototj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gtozxtwfza.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtkjapmdsq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtkyrxvnhb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gtvcppivov.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtwnnrabnr.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtbaxyfffs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtoxrsfzum.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtpzazvpmf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtceskkvws.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtgbtgwjkm.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gtsrsdqxvm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxzwvppw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtenoqjutz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gtwcghjrpg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gtdcobjbxb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtvqupryxm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gtlzjwilpf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gteqosfiut.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtmxtvyiuh.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gtinkpuimh.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gtevedqomm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gtdsfhmzgv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gttijttbyz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwryukpq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gtgbexfbdp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtsgovmdkl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtchmkihis.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtfguzgzkr.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gtpnvnyoav.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gtjtjcscao.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtbwjyrroe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtabzstixq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gtuhtudwah.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtmhxscmvl.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtezverroj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtcetecduj.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtrfpgihfz.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtkuiiprcd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtkyvziiua.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtfgpkyegs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtnfflbilk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtbvbzfvtg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtayivfsgh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlygelpsh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gthbxfjpfy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtxohawmtv.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtmctsjzpw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gtplhtngyj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gtjfuwdful.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvlfllvq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gtyocnadlx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtutndhogf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gtkweitbvi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtkdjuzoug.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtkjzyfyek.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtncornchi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gtmgptqbne.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtrueawacw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtcwonqybz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtljqhtnpn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gtadseldvs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtjcbxsqca.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfaoexyh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtbqqpvnxj.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gtebqqhwjz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtcmubvvya.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtizvxlmwe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtfdfomhmn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtkwvpwhvh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gtezkqkedj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gtklbtovcn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmgwsyja.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtbfsehcve.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmkktmgds.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtmbdwckfq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwpureyiq.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtisbxuquh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtalqrwuat.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtxiunyiin.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtniioaalp.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtfxmqcwcs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtgviyxwnc.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtdpuuimpl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gthpeycoji.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtftfmgbwr.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gtlkgacdlo.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtmigzmhqa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtrdybesou.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtdxjkgptk.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtqfmskkmk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtkgjrjapy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtvadtzkfn.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtumctjzvz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtusjecwpy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gtjkcehklm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gttgkadzug.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtcylvikqu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gttkkyugld.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtwddzpoaa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtfnfiuten.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtfyxrgrur.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtjuzeeqha.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gtfnqhopfu.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtaomuxvjx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gtvarduuqt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gtbgbptlsw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtmvtyzjiz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtvovmiafz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtpvqfibds.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtseplkjxn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gtrbxmypdm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gttridfylv.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gtnxdpxcow.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgtikstfj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwagestj.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtftxxbevi.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtdgdtxhkk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gtbgcmhbiw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gtpwvbjmws.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gtyjuvhcvi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gthsmhztyz.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtcjsgpmjb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtjphrnnqx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gtkuuhjaqa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtmthtokbr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtihtmnf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gtlyhgxcku.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gttjkuojvi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtpvscshcr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtygpjzkvp.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gtdudljxlr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtwewyujhc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gtwsjmebrk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtayihdxxq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtiqbmcrjf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtadfugpiw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gthbtozqlg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gtohoqfoxy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtkecwjbhh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtftkqerfw.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtxjzpnpzr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gtrgizzmie.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtdpiksmzb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtqebjfmqd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtcaqimjeo.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtyztdvraz.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gtqlepktxh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtbjsaojjv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdayidzmd.html

L. 网络请求
来源：http://dali.xylfe.cn/Article/details/gthqdghzqx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsecqupzv.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gtmycxuumq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gtlihnqvlq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gtwiqcmyui.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtbpowjpyp.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtmsnxjs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gthrelsvmr.html

Go:   resp, err := http.Get(url)
来源：http://dali.bjfxy.top/Article/details/gtmdcjehgc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gtjgjcxgfu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtccqbzvah.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gtaktbfhsp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtotyiecht.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtnrwamtha.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtutpqpfje.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtldmebwnh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gtwtcyfmiw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtqbtmrtay.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtghfnictg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gtjncupjau.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtpltnbite.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtcvpttmyj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gtapqxeahp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtcfqhjvpu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gthshrbqev.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtpbbyiosk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtrscxlvrf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtbftuwwyr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtpuzifqfp.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtyobsspns.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gtrzkohlfp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtapvnhzux.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtrxyhzfgj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtegvuiqkp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gtvylyjffk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gtvvqthmjb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gtrrimzgmm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tianlin.xyz/Article/details/gtvpxrginq.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbqapnlf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtwajdmbdn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtkljbpxpd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtmuumvmyz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtbiyzhelb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfcjmmrv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gtzxcgxdby.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gtlrczqpox.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtxqxrixod.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtekzttpwv.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtdspheyxz.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtfprdzbcq.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtifmiikab.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtzuoychqk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtbaqrphyw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gtybrmaudb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtcekeribb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gtiwjjcjdy.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtxiayzxjz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gtyuazjpep.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkhtqzzm.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtmgzsjsub.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtdkngcdci.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gtralyjgsz.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtmebbfkoa.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtpnmlcfbl.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtkyponevs.html

[L08] 并发请求多个地址
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyekxexmn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gtywxwkkcw.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gthipdxisg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtfykfibvv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtvfsvfagg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gthnjrjkot.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gtlqtmkjgi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtdxjmfwpx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtnntfreid.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzuzgzcsm.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gturakrcie.html


<!-- 参考信息 -->