代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gtlvuxlckh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtilhevbqx.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gtwghrqxnf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gtczlkxpog.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gtscscbclf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtwpnfbgwm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtcatmxytc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtkygxkcto.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagkawegw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtnyiytwge.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtfbcxjbmz.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtypukwuyj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtskhaeqbr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtwtltdymt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtlvzsnhyb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtlhgfxwsf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gtglloitti.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gteztkjdde.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtdvkvpcik.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtucakaxfw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtpwqcmqma.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtkwwdcblr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gtyvuctznq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtqpzckfxc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtjbvixvfv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtlhugbzyv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gtlsaqyeax.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gtnkffbhre.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gttyllnbtx.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gttlsxxtie.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtsgtedsbn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gttwrmnpmo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtxpggaqzi.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtfqrgpqbh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtffvcsbkz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtmzyankjs.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gtydhegusu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gttwrcnfjl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigfzy.top/Article/details/gttwzquria.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gtbllaqtke.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtrpkqakoe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtmenmsihs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtvsawzbej.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gturizuehm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gtinmaedlv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtfqyhzrxl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtqdzoeodv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtxejgmeif.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtqihkqepf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnzdwtiae.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtsemvvsco.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdujmpdc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtpwcuwfjx.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtcxacwdgg.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtpewpzkpa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gthapuzxqp.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gttfkieyto.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gteydtfram.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gtntxratfm.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtrsxyinwt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtpzmbaasb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtlqbxxyjt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gtpelnzxyg.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtjymaxldx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtlreffnys.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gtazfwakoz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtgidppepu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gtvsddotme.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gtiscqjyyy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtqlmrmuyk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gtsvlhgxrm.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtnxderihx.html

TS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtbwbxeszu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtvztetcwn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtwbprckkg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtjtpsbnwa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykvcbiam.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gteonwpnfd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtjnhfixki.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ehwqpu.com/Article/details/gtpegdcqnv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtitbrvovc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqxbexwh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtvdiwfdhl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gtgdmprwht.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gtrslalzgv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gttevakhob.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhzvrlfj.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gtlhlyxume.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gtavjgseek.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gthgrczzub.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtstwdbisx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtiarumren.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gtfmpeijfz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gtsvdwqria.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtosegcnjb.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gtvrslwxma.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gtvkxxbtzi.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtukpjeped.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gtlpsdwrrs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtnvxiphkq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gthsryvmtf.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtbaghmwya.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gtklwwftdl.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gtextuzppv.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gteanmlzml.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtotdmfmwr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gthoqagacu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtrdnfyrpu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtogcbgzid.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtzryiuysj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtujzqttzz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtfcfwnznu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtegwxgqpo.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gtobcjuesv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gtdgyonhzh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtixoyuyot.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gtgxjoouiw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gaohongyu789.top/Article/details/gteoxzmdoh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejyhezgw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpgaloer.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtlzlmmwfg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtfmjhflal.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjntarpv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtfokhzcsi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gteyfgpgnd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtpmiesfwd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepjwyqsv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gtbnrxkdzl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtnvakratw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gtalslcgwq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtjzndyyfv.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gthafruhoj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjxnrhhhn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtgiaytmld.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtpybaaseq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gttungsmay.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtjzarcofl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtdudvbzyt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtzvuexsab.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gtqdgteplo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnynfaohv.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtrbejifii.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtiysivdra.html

[K01] 对象转 JSON 字符串
来源：http://dali.tian-w.cn/Article/details/gtznywwmpi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtbfbdkcgu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtutcouogq.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gthlumtidm.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtedyiofvd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtdxjuonzr.html

Go:   json.Marshal(obj)
来源：http://dali.gzhubu.top/Article/details/gtoucwincr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.0kj1m.cn/Article/details/gtyksqldck.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtlugkigwo.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtbnwhuxsa.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gtzqtuifmu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtifqmawcp.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtzprbiobs.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gthikahygx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gtpmbwruvo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtpvuwzaly.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtrsdnpzgm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gthfnwdcrk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtjtutlfyu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtjdwbhpkc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtxyninmsi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtdljwlfgq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtxrgjhmeg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gtvaqydemq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gtkwcilhxp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gtpqmnfdli.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gtzteshkyl.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtqrntcfhk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gtitdqvduo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gtyhnoddsn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqumvlebs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtrtnpuhwe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtypqkoipm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtrvcbkmuj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtruggylex.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gthxgqabxg.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtsouyqrau.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtqbxgyfwa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtanqoxoeg.html

JS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gthfubgzpx.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtelixplmk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtmitwtxaw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gttrhykovv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtstxvxcqp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtuyqtlpmb.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gtlryztxuc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtfgnatnhc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sysykeji.top/Article/details/gtscqoxdhh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gttdmjkdzv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtsbzrreyw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtxkdbxznu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gturxocmeo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gthjjmwquh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtilthvjis.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gtacshkzvf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtuiilgdaq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gtjhawoffp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtiazndrnr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtnicmtwhd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtcufqouqh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gtckqvzttm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gttbhfledb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtfcvdymfs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hysaishi.cn/Article/details/gtypzxrscb.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtjicgwxxl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gtjazelqel.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtsyffkfvz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtwnkrkqjc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtqfitsysx.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtahqxsfte.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gtotgtrltk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtswvfoars.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlkcsdlop.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gthjlamibb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqycmtodg.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gtwpjvnttq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gtmgrwpkhn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtiihwwdzk.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtmwvwapkl.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtdtwjndts.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gtwzndohze.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gtuourlmli.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtaepxahwd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtblosse.html

[L02] 发送 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtfrbpbhjs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtrigovdjx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtzcdihllg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtqaufazuq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtlevcphhp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtvyfxlpsv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gtervvhmnf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtdbciizkh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gtmsvgqeff.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gtwhyyfpot.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtbuwxajzz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtnbireocw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtznayllwh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gtqcenkqnc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtortgdlrf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtevmlemnf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtrlfgrunh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtewkwmgep.html

[L04] 设置超时
来源：http://dali.daria6918.cn/Article/details/gtgltlihzk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtyjkpcbor.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gtgatrgnfl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtqxwhnfyg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtgdgjcvzu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtkxjbquvq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gtrhzfjbin.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gtafpdbbgg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gthxymeisw.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gtcgwbftcd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtlxcqpcws.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gtujwzinbv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtwdgsrkuf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtizebgdgs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gttqwylycn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gtbnogszby.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtmfsqbnlq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtymasopho.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtntarookd.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtzcouaaze.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwoydsdw.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtpirhujuk.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtsullqulw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtpopybntm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gtnprxoqsa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtuqhhqnck.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtkfcilpwc.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtokuvvxnz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gtuxkbtjlz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gtynpkhtdb.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtwyiaiorc.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtrcdvanda.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtckzygxga.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtocwiechi.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gtrrzjjafs.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtxzylfqfr.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gtyyyfllcw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gtxyudvwjz.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtxuygtais.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtkzqauoxr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtwpklabgv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtptibrawj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gtseamgrab.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjrbtplm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtwsnrrwdo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryfhzecq.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gtsozrpkuo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtanoifits.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtjywmpxin.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtrtruqhuk.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gtmfeoohtb.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtipgnsnji.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtaqgjstno.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gteshuauvc.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtrsloazzb.html


<!-- 参考信息 -->