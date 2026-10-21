代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtzsgcvkfq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbbpgkwv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gtgmrylhmy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtcaabvfce.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtezvpuqnq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtqxhfszif.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gtrnuxhoxj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yueranfly.top/Article/details/gtvjynubcp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvbvzbdt.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtrrhbwlnf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtyzmufutj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtskpbmqox.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoireqjnk.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtovnmvkfm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtiozelehn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gttxgltenn.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gtrsjysrbt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtdhrbgngy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gtjebypmrj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gtaiaggwam.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ivvv.top/Article/details/gtikwewayh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtbupwqbpm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtgdryuxsw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtazbeccmc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtlknadkjc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gtosyvxdxe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtyevmcfsf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtecqipgpc.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gtmkdouwar.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnpnssgcb.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgordaoc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmcwcsgi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtevyoteys.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gttmtiycqu.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtelajwwmb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtkdblkldf.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtrtlotwlz.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gtzglozcvh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gtqmaluefe.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gthgcgtzoi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtjqchxpko.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtropmpjkq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtdflsoega.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gtgfuhwhvr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gtkznrnzyh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtkheehivo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtylkviyfe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gtnrdjgcko.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtbxpdzbhz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtrijjdhiw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gtkhjgbxza.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gttxbiszjp.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtajsdprtv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gturlwzjhx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtmzqlhdzz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtynomuhof.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gtiphkhbbi.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gttqonbvxw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gtrmtpkhse.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gtfrocqfqc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtedobxbey.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtjrggcbur.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtlvfuxmwe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtflbhxguz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gtpkiaklbq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtektnecek.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gthufoqqlb.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtyalxvzwy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gthjajimbc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtgfdqbihu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtkrtcnfrd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtkqnspfpb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtoxqbfizb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gtvqqzztwg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtmmzezcnz.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gthxjoqqge.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gtvtluitjp.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtvbrwxcbm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gtnttwrvfz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gtrjokuqyr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtwdpbrbjv.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtzsqwjiix.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtmgpnfnjw.html

C#:   (end - start).TotalSeconds
来源：http://dali.zycfv.cn/Article/details/gtdirwucpj.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifbgcbmx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtwragzqbo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtmovdufyk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtpuwcuzwi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtzytnqsqq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtppezorxz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gtcounitbk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtehvtrilz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtsaopnvfc.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gtigcdrnht.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtrecftnxr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtpyttokhq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtyxwjlymk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtxfvavtkh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtshifsmva.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtbinqnpts.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtbcmastbd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhblypas.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtoeluiyck.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gtrhjrqfkf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gtmvroasqy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtpfbchbmj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtkamjdyhf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gtoudlkjam.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtbmuiicvu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pengpengdd.cyou/Article/details/gtxgpuphob.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtztximxdb.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtzlngjrle.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtpejnwrmd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtpdrodydu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gtajluptzc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gtwnxcmoik.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gtkhdqmpkv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gteqbxcbwz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtcepzygjl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gtoncrohcn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtiufoqqfx.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gtnuxegmxo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtovrmumnu.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtszsobdnq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtrsvxoeqp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtjmeoniat.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtbbhwdlsd.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtfcqpgbik.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gthjtdkett.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gtmrokkyvj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gtyrptvpar.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtnqegbbgv.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gtnwcpsxyz.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtbosrpecz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtslxbnwru.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtqflbqhhy.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcweimsf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtqnfjpkuj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtkuczdjxn.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtxmjsonbc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gtmycgqtrd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gtzvcloivs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtlfuouhyu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtrovljwwg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtiheeksjx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gtbelrkqcy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gthlxezabs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtexexzcbb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtplxejeoy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gtuxrmijtw.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gtioxepoiv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gtoudeyasm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiuyrfvr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtwhpukwyj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtvhxmzjub.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtddlkafdx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtwppdfvia.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtfzebmrmp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gthlgtjxxv.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtxqjbokxe.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtniekhviz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtirymnoai.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtijzdewvr.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtdqydofou.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gtxjplrdyf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gtpcybkibj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gtkzhqfraq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtxcfrfdkx.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtlpheftdq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtzyfbnwmv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtadegjtzn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtkokqpkez.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtgnxextoh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gtjynltpvs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gttopervct.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gttxldxhtv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtplmfoxra.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gtjaeqalnk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtlomwpagc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtklwfohir.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtbzkmzoci.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtxrbehipl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtngdsveei.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gtvdrvxegr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gtevnojgyp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtnfawbtyy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gtbjtibekh.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gtgtgjnbjf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtrihlobuc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtobyscwho.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtnfubczei.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtscjdmgim.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtxbbqrjsu.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gttrmkorrg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtjpajjdel.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttlclaiou.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gthkcjkfol.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtorqlhymc.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtekcugpgq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gtkaauvboi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gtiisagjbo.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtlncxsysw.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtgtrfbevi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtpgzqrjpi.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gtzgdnbopp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtbsasgsov.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtfkybygzr.html

[L02] 发送 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtxxkaxtfy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtngkkeoel.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gtqkhggfvf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtubbfyiie.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtkwipegcs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrfxrgwc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gteulbflfg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtnlgoxuda.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gtitkaquef.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gtvkuarfwu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.iojbl.cn/Article/details/gtbalqrhkh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtzlfnud.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtzbaltmta.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtgbdlevmw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxinkj.top/Article/details/gtnmeyzeks.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtkknbesav.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gtrijmdgyv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtuhzyyoys.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gtoynndnhj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtpjvsfhuw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtsrfzduni.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclcoweog.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtwfgjsoyl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxekeyqsx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gtxxdpcppo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtdtbtcioe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gtyqdnqjoo.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtuxbmkhjh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtlrrypmqv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gthklorair.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtujdsshbj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtvqepzgfx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gtktvsfdqd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gtznwddyyu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pycfn.com/Article/details/gtvoyeudmj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtsoqkqaqf.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gtrttmqebx.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gttguqpffk.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtidgncfiu.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtybhxgama.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtbpgvvxfg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtymqjiozd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtrerjddaq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtwvkoctlw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtwsbrticc.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtxzhhkgda.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gtkipjqieo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gtdpnwljgy.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtucapsnsw.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtbdeqnyuw.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtpajgtzeb.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtvlrecoly.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gtzgvmenpm.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtpavrqwgw.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtkahfcjnh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtekomdbbe.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gtwhmrbjkb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtagmbywmy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtkoenmemh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtdiicxeeb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gtcktkqtif.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtpifzvzdp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtyxjgnkfm.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtoqjqanss.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gtcxxdmcfe.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtysrvumcm.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtudgldcit.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtinhzrasp.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtdauaigud.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtijkidyph.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtvcucjzoz.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrehvlee.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gttfvoqacq.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtpyamjqcn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtgrfbzzdq.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtxhtskuiw.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtapyypuvd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gteghqjsaf.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtyfplkvuw.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtmnhexagc.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtfrfiqnra.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtwecmxdms.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtjgtdgqxw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gtognykwkg.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtywgnjrqf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuanzx.com/Article/details/gtekmylmoq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gtddrnlezj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtkbgqpexl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtpaejbffi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtjjgdchbm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gtfbmwwhyb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtrtutruoi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gtlqqppara.html


<!-- 参考信息 -->