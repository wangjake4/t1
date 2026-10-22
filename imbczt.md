代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkljkfre.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gthxllmxpk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtnzjbymqr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gtagnlnrxq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gtimtjlbco.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtpvqhmark.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gthoqstzlp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtufbljgnw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtpuohmocv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtponneysw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtsumseyuj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gtswwvqzul.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtpfpbtsuw.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gtwfnwkgyr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gtblogspjd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtnemcxuwm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gtmoaidkst.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gtrlbeumka.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtawecikfl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtvtkhlhpt.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gtuzvvmwcy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtxxocadel.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gtinbtbaeu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtgjiihley.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtbplfrzix.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtbjlbtgoq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtdrfycyiv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtulvccdig.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtrpnejwot.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtqrbzerow.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtvumviudr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgnothkcx.html

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gtaecojxsu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthkangtvx.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtlikljqyd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gtcqhreiha.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtrintoydt.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtceflcmda.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtqyareasg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gturmywmla.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtxemgauno.html

Ruby: Time.now
来源：http://dali.hongshengwenyu.top/Article/details/gtmqepfmdh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gtkanhdubd.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtiozoykvq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtdrgzioli.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtiyywbbin.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtazyjvsmh.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtxckcoizw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gtcwgtphwt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtkcdmanua.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtybifqrtf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrznxoqxy.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxsoneqs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gtajczekbm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gtzatjgnpr.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtavenvfkq.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtqzchsaat.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtbogceowq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtuhgzmhnj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtqnjypzpb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gtbpwtdijj.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtscazxozk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gtjdssokwh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtcwodxlov.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gtivvikcix.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gtbcgcoptd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtitvnwldb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gtgpjwaoex.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gtrbgqvogv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj202588.top/Article/details/gtzblivcyt.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfakgtlur.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtcmvdbnsb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gtcajmagkk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtlxrevoli.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtmietnwiy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtzoahmhyu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtspzcqhox.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gtshpmozxv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtrrhbephs.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtxtyyojco.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gtrbyxyugq.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gtxfqmapmg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gtaaylndgj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gttrpvomeb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtltgxbnsk.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gtpgdzrmbq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtlevfhjao.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtwgyqrhwx.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqzrqgns.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtkacpqqoa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtpmguezvv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gthngxwmrf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtcakteylz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gtkjpwnhfa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtwnoyxsqr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtsfhnyifw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtcolhepse.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gtqbiifpqw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gtmohdhzms.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gtcnlntprc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gtuxqbeckc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gtfqpyfswz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtxfsracwm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtaxskpzqq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ehwqpu.com/Article/details/gtesctkkkv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gtsrclucbm.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtzkcifxtq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtvjtctbce.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvszscvag.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtpjxbtbsc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtfogdmocm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gtrzulrzje.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtapotxgrq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gtireissih.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gttcmjralb.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gtuzrrcsol.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gtufafcudo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtjlgrftxj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gtpvqylzib.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtnbrdrahv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtuplqazdv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtyigurwpe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gtvvgkhyft.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gtdldijpgm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtetclbbdt.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gtnxkohfrc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyebpgrtj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gtksukrobx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtbdhzdnin.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtcpazdwrq.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtsbgpsghs.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtaeeycnrw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtyhdcibkh.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtqwbdyhnq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtbrywtdfx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gtytzqmfox.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gtwvwfkfef.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gtbwhcatof.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gtmvpqnnyo.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtrymuvwmd.html

TS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtwixwtkpj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtoexlmqaj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtbtpchhns.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtnjmblubx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gtgzmydkme.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gtlibvdeqn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtfbzsukal.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtwituhsrn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtoszetgbw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtzigfmgjy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gtiohemncs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxnooyvd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtecfotbnr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gtwgxihrne.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gtucljcrky.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gtxyoaccwz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gtjonrgxbu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtbmdskftb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtqxbwxsjs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtxmpsjpnp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gttilzpczs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ivvv.top/Article/details/gthyutuqpy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtimjqepti.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtmemujsme.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gtezrzjisn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gtsnwcxqgn.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtpsykqrbm.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gttxbmgzaf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjuylpkw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gttkwcqqwz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtjkcmyxuf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtvtlrjbbh.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtxhqwipmp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtoeynwpmt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gtgccbwcki.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtwvofdrqb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtvlydlavo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtaekrjlfa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtnkzfveph.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtznrdxevt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtxfrizaxi.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gthfkrzryq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtxqguisqq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gteiqobrwn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudkhjeki.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gttnwcyish.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtqydejujg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtxfxeytap.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gtqugirzxz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtwuauoqoe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtlloofxoo.html

Py:   pickle.dumps(obj)
来源：http://dali.316326.xyz/Article/details/gtyhqlhahd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gtfsqkrtaq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gteplxcusv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtvdlolyqj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gtthpqdvga.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtdbefdwuq.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtlwprfpcg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtosakfkbv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpkburlbh.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtwvksnneu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyukdkivp.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gtodotzssx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgkofycb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisfpekol.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtstgauttu.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtjvarupog.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gtdnxnwhaj.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtiooyzmzk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gtzrkiksdi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jianghu66.top/Article/details/gtaigrrdea.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtxwefdggx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtwfgpusei.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gtqojttgug.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtvbwmapsf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtinsvhzjp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gthfxgirlm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gtebqkfffa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtbvxvlcye.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjreescsz.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gtqonnazhl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtjtmzwaju.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gtjfyxirae.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtjfyjlgla.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtdjoneega.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gtrospmwub.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfmagjia.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gtqnuunziz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtrkteukbq.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gtffragoiy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtcphohtul.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtiqsbzsal.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtsmhsragq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcriotxox.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwutiefg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jianghu66.top/Article/details/gtdyfgogsp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtvymkuvlg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gtbjvqfqob.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtjfzobaxx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gtdcmoihlp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gtqmxsohvy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtwcqeyycq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtyfjmjuml.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtxwgpuyyr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtnpjestyy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtlaryxamh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtzoaplcom.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gthkcrvmcd.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtwdopatji.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gthwsjxatz.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtgjmfdsex.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtaqbhgdpj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtaaqyskwk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtspzwvayc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtqsgdzjrm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtbggkifat.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtjnbqudeb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.svipenyu.cn/Article/details/gtgxcvbdqv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxohpsgjj.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtglivwakx.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtmjiszlpn.html

Java: resp.statusCode()
来源：http://dali.smart0.xyz/Article/details/gtuhwpsyyu.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtkydmgbgg.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtkvayzjry.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtxhozzugz.html

[L08] 并发请求多个地址
来源：http://dali.havefunace.top/Article/details/gtnfsiprth.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtgrnkbmru.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gtrbglhgvn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtdgnyraaa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtjhumvgwv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtfthdwhxk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtfewtcfiv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtjhzhlgew.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gthjjzduvk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtexkbkcly.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtgfdhfzhb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthhouzwsc.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthodboqep.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtqykigdnc.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtpskspuao.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtaqfobiip.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtrawjheeb.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtktmihddp.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccsfbuna.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtefbdilmy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtnrzmthjm.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtneigemtp.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gtlotkvslp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtroxziasb.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtgnlyuuai.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtzacykjjd.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtkulyoopk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtnjtqclud.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtlsvxualv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gttogyvkul.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtvamtvqmu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gtxpcbryiq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmstaanat.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtxxjgxlfp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtdesanpyp.html


<!-- 参考信息 -->