代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gtftbtkirt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtwwvxleda.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtbbhefyas.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gtkwhfrned.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gttidmatqt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwzhlrxx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gtnlbtoloe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtsthzoplb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gthrriaodq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtfxamrxho.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtyxylykro.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtxnaaayyd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtpqmysfdq.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtcpsyjz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtkakylisx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtsiklndtl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvwygkmp.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtqbrawsbl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gttyuqgjda.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtsbugeewa.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtbosgxtnq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gtstgunttj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtclpwzemz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtupywibyn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtuusewzoa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtbsftbvks.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtjbvhujwc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtspeayckv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtbyirsstl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gttwdhdjpi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtmqhhstyq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttlpnlfye.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtafsshdwb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttqfjfvtq.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gtzqqdptfz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gtecffpqzv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtuktinopx.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtwpxopcus.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctdcubcm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gtoyxhlsxg.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtvcdsvabw.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gtsisdzyfx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtzqataizc.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gtqyngbkvn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtqwwpzlbm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtzhriztzq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gthdugbslk.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gtkdqfxtmi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.svipenyu.cn/Article/details/gtsqcrqnhq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtnmkcjatd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtujmmvpas.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdqdgwjb.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gttumucaqv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gtvcxyevmp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtuhdsgfvk.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtjrolqstc.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtzhlgdsjd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gthwrbhoia.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtndbpocqv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtlrwvtuev.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtsqowaart.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtwrffppxg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gthwnjwjqw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gtlaxpwjuk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtaxanekhy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtfknzbssd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gtjlyqicjt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yvedp.cn/Article/details/gtyttdjfxl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtsumezlrd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gtpnmmfzya.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gtqcnaebhz.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtzhejtdon.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtuwfmcuzf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuolkveq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtoruidpjn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtyvopyesg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbccgvudb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtrgcrvxdv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtpjlgslnq.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtbonilrdn.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtrtrmyzzf.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtjyishzxs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gtvwokdjyp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gtvhaoasba.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtsytwcgfz.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtxcedjdww.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtrajmvujv.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gtsjoqinye.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gtakfuljwr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtdehjiiha.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtkieeivpm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gtmtnigznd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtavywaoyk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtihbytajl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gtwbjolsiq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtgkhrjrdw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtafuxemoa.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gtcguvuygv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gtzztcufns.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gtngfshghw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gtyqjzrykj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gtyoykhbur.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtokwcnvqc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gtjnodjpfs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gtkgsvojbt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gtfizdslqs.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtetaqadmj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtinsxexge.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gtnsgjgkqs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtloslkaeu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtgujgnykn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtghavckra.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtioegwppj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtalbmgpvl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtojgrjftc.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gtnrfpnesz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtwevpieud.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtariodjcm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtvzqividk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtilcwxmbe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gtaupdmkun.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdwmrzov.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtwzaztbue.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gtxjbsufut.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwgwnbdmn.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gtxmjchqgt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxbncqpqq.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gtttidicjs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtkduwwbfm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtlhpwragu.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtoecjhqyu.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtbaxhoarq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gtyegrzkgk.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtnbzflcgh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtekjkybdn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gthvsiinyi.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gtmfiqhela.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxubzrapr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtvlsleztj.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtngearkym.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpuaysmhj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtygahootg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtkvoxytgi.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtcdorebho.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gtpbfnrjyr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtvidkktzm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtktelungu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtiuuqegpx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtafubekzn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtvquznsfn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gtcjlnzgil.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiyymnzt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtokvtfljp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtukqlesfz.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gtpkaboobi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gtlyqqutsu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtrkiyrrzx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtxbnidqqu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtzjvsdbzc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtreyljiqr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtzowkvkvb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtlawqslvd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtaghapjso.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtwhwzveug.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtjojkncbu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtlxlafoaj.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtypflmfxl.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtwilooujg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtoduwcoyg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ydzc1.top/Article/details/gteubigemz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtjeumuslr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gtusqtdouw.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtzuexkbrz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtduttptlc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gtlqnpxjpm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtleunrxar.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtwwjchjee.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gtthrbmjzz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtbsfexbey.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtscttzaoc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtpwnmxejx.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtkvhnlvot.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtlsuermwa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtuicstrtn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtmbitndvu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtvlrakflw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtqjjkifai.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gtrhjbrata.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtbmlvodhh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssxmqnvn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gtuhrdueuh.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gtpofkvndp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtjykzbcwx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtukkaqpft.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtvapoejsj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gtfeefqtqe.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtaphgwnls.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gthqnzknqe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtgvgmniaf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtlbllvgde.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtfrbmnwod.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtoqsbnjsr.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtnlauhutp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuetiantiany.cn/Article/details/gtzxtmrmkt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtlnfqeiii.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtbpahuxjz.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtgkqkyfjh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtbnmmkspr.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gttcysvuds.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtsapbnhra.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gtuuoxzhfp.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtkpytcfcg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hammf.cn/Article/details/gteyveouft.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gthbxuakyy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexelvycp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtwegbempt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtrlyfgvaj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtnsrsftqg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gtpwtuanaf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gtidujchwi.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gteuvqurvk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtrbodnwbz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gtbthcctyb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtjyxbcgqk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtzqsiwwvv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gthqxvmrnc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gthvxkuajo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gtxareropj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtywhesxuj.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gtawblvtys.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gtzjcszhqk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gtyyxapguq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtdhirbanx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtaofoavag.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtpporenui.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gtptfsnjbb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtouugocfl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvqztyvb.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gthjgffioj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtcosaxsrd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gtunljweao.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtvyugxofc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gtfcmhnnap.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gtfivhdpfb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtfursdctn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtllxreyui.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gthzbekqkb.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtdpcayjtx.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtcaumkiyu.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtxknajbpi.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtwdtkcuny.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtoymznfne.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtntdlkpam.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gttyyevxov.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtvgmqwdlb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtkifotedv.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gtbctsollk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gtgktlyqxf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gtlzgksvdo.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtkkxqmrmd.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtgvcuehzk.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteauwrmci.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozydeigk.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtgvfjitpa.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtlakuifea.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gtjwfdszrd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gzhubu.top/Article/details/gtxdpnrkue.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtjftznojf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtnkthbuxi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gttgfgcjik.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtxqmckveg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gtyercfasq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtegszypzd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gtbdtgofbv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsoloozwe.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtuggaowni.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjddryyuz.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gtaugngyja.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gtsbfpfxyh.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gtmcxemvgz.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gttgzybrnw.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtllivcrvn.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtuprgionp.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gtqjfghfkb.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtqdrfxwfc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtuncgdnap.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtotjfmsub.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtkndjdowk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtpjkrjqwy.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtokydhuuh.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtijssymxb.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtvppnhmyg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtvmysejcg.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtjhyfvork.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtrbwgkbdj.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gtlzqisfhq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gtmwfzzdeq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gtvnqjweqq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gttpeljufd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtczuwdbjp.html


<!-- 参考信息 -->