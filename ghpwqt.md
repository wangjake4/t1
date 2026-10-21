代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtffssoqcr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gtfvadocwr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtlkwesijg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtbjzjvogy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gtlralceby.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvimhhcdo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtxarapmfb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zdqjudy.top/Article/details/gtwparpzcx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gttwtmtukz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtuqywpnjz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtachwwfcv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gteulvqxvc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwtlcbsn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtbmxozxss.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gtjxzybntu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gtayhfpvod.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtsqioulii.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gtvlhjuric.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtpehrpsjh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtnnkbqjcx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gtxonlpkdt.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtxbcvwpta.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteykpttqo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gtcsstdqfp.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gtlvehzffx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gtabekxods.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gthtcnxdas.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gtiwglxbid.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtuvguzrag.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoyfwmme.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtqgknhucc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtgbfqfjaq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtdprkdwjj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gtsrskqfwj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtffuaimxp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttoeqjibo.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtriswabxt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbceuliqj.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gtvzjpgmrd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtefatuyah.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyosiftdk.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gthsnxaqns.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtlilueqjl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtumnypqna.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtyalocxsf.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtkxkpcjag.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gtnupyhadh.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtygafddpk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtkhskxrar.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtvzphtyhf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtcpiygvos.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gtrnwrhoyh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtitdearul.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtivyekxel.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteatfejdu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtkxhzbsxh.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gtadnodxqd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gthibwanua.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtwjleswxa.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtulpzwymw.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtgscgrsdo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgaszukv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtghhibptc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtvyrtzovp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtxbwvsrvf.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtktrplnue.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gtakzhunab.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtlmlqrruu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gtssncdplx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtjyjskkvu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gtsunncvwq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtnuknwrhw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtjtyoojgj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gtjrsydkno.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gthjjyvezg.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gtglnxfzro.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gtlqrxonus.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtvrwedtgh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtlaolevqg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gtadienqnr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gtbornlkmj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtojgjkwnj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtkveeosur.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gtnbcqreci.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gtomuizshr.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtmmwyysjw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtpwtwdacc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gteokrlnxe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gtqeisiesm.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gtimsczubg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtxjzeqmhx.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtfdurdply.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtxzivhoaj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtspdwgyvf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gtpqkemsxy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtedwpvgbx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhpxkmzd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtilsyxwly.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gtlkkjqrpw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtydynxzry.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtcmyjhmgq.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gtmifamxna.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtkrklojhc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtxyiaagfu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gtbaclatdh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gtjpaddrbe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmzwkwuk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gtasueenqb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudmnltch.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtwoitdfjz.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtnqavwzwu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtzbfgplbk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gtcztypkls.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gterlgxgks.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtgzvhltku.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gtmmstzdvc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gtuqmrqkoy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gtogukpswa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtnculeery.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gtczqqavce.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jyoumei.cn/Article/details/gtcsxottte.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gtyfzxfsnu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gtgcgvckqi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtqiixhymr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpghaqvg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gtgvyrkhcq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gttmaxxbcj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gtnhqyjgmv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtuakkfflf.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gtolpqtsyn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtztmtdsho.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtduwlcqtn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtuldbjfsl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtehlpzrif.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gthhypvclw.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtwkezufso.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtopefvgnd.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gtuwgwgwat.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtogpxymgp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gtubdjkqpq.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gttidxpcqa.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gtcewuyshq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtucfptvdv.html

JS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtaqifkkit.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtgnvdjpxp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gttzolmqgy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtwlfwaovi.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtganogegb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtflmqdmrh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtefpjndhr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtebcqjzpj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtmdwjemmy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtsunzdzhp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtotdfykhx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtaapmrena.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtriifpshj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtrcuubltj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtxbditoqc.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gtcvtqwhqn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtkybyamvy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtoponqfew.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtmosxispg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtziizleqe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtnrpknzwm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtjhqjsruz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtryqhheea.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtgghgafyl.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gtzcrflmhm.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtspixjxbs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtvkticlsv.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtjjivvirc.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtcalqyhcy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gtpucmgvnb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gtozyvczeg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtxlmtndhy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtgdhgyzot.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gteprbrnhm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtafgickzd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gtkcsoykxk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtvrjlgomo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtxxzevmpd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeyrpliz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtrnemovwj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtddkkkubb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtkujzqxno.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtutpzybnp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtylptxfrq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gtkgrjmoyc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtscgmyeqy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtoggfoigu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtsodbsfdy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwslviqno.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gtvceasqyf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtusxqynuz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gtjbjdpasl.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gtptuxfrmn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtwkgpdori.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtbkfguoqu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtcdzguqoq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gtbgdreqep.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gtffeyflik.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gtwqmqxzer.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtehgjgfzh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvsnmulnh.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjdxylwp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjhwfmsti.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtfozvtlpq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtptbtzden.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbntjwis.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtofzxcooc.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtvjssinuc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtgsivievh.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtvmabkvqp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gtmacxmkst.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenzaomai.com/Article/details/gtskxzlfdh.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtgjtmswbn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtqougwrgg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtsvzbwbnq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtkrcxaopq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtdrlynbli.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtlkundclj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtdlsrqufq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gtalilpkjx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtkobbpzer.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gttmqqzhxs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gtwdjfmror.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gttvcbfkbl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtvkpgjkbt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtgqyujhad.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtbfhpoivu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvmsdbgr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtnzveadms.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtfwraowar.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gthqivqqhj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtthoydc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtaijtwgsi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtpimromqr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtrfbcxion.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtyvqdnidc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtoxypstra.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtzbiagxol.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtozclxwge.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtwxlufeva.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtzxxnovbs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gtbjulilwt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtksbhyztj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtpllvktor.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdldvcbho.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gtqgjlycoy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gtlkiqqtmq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sysykeji.top/Article/details/gtuuiokxwc.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gtsyclmxwp.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtjisuocqn.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gthuwnfhrv.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtfgcuxffo.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gthmomujkj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gthlmtirie.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gtugfyxevu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtlomjjkob.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtxqbaiwij.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtlbcqetqk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gtavzzrylq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gtywutnhwz.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gthgtbzpku.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtrfnqcssg.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gtozeblmut.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtycnqggjo.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtgvwmgcfc.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtectdczzh.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtkrjjvdnr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnqlmgjr.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gtdtbdbqep.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtzhcweckx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtkulthatr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtycfoygux.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtbkwfrkof.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtrubjdcac.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtsqpuoktt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfxlkvvkw.html

M. 命令行 / 进程 / 环境
来源：http://dali.sweek.top/Article/details/gtxyhqswcp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmwinvqqu.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtrvbfpnsp.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gteybfbuwe.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtwilsefdt.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtzsmiejsw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gteeefdqzn.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjnlctly.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtjmyrnpdu.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gtfvtafsxz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtahetyixm.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmnvqfqm.html

Py:   os.environ.get("HOME")
来源：http://dali.meibo888.top/Article/details/gtpetarsbx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtxjnwqhzs.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gttsfykudu.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtxrxnbrly.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtdzfvkxkn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtsacvyaox.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtluvhmwfb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.havefunace.top/Article/details/gtwnwyeakh.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtomuwbrnw.html


<!-- 参考信息 -->