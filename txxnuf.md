代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2iissjcio.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2bnnzoxjh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2dapceumi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gt2ghqwfyyn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gt2kwqitjdx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2uvmeccpa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esjcjtnx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gt2dwenmswm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gt2vuabxbzm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsfdbouf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gt2xxpnwdrq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gt2oofubern.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gt2tiqasulu.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gt2bmicvzdl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gt2bpbfcdez.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2rjnkmrph.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gt2aspodind.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gt2lzbjgiqr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gt2dgvezzvn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gt2culnzbcg.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gt2kqbowgaa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gt2vtpevmsk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gt2bpeikpuk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gt2rqhrsupt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zogipdgf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2aidvkfoe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2fljqvphp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gt2zxnlbiso.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gt2lpvwwaue.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gt2vpgptcwx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2vehgbpvt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2danbnlml.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gt2yoopiuyj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ogzilcbf.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anopvcyo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbpjqurk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2gzanmndb.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2dglafuoa.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2iclgcdzp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjchpgw.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gt2yfbhfyfh.html

Ruby: Time.now
来源：http://dali.hnqzz.top/Article/details/gt2urhramhp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knzjbxhz.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2cmyqdayx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gt2iabtzoih.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2soejnbni.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gt2fikzoyrw.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nexowvpo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yotxpiqh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gt2lcobjiuy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2moyxdpga.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gt2eqigfrfo.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gt2vveynfyr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gt2iejkqrjw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gt2kgtoholo.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2upxbfhwc.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2ltnpyfes.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2ppusumkx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqjqhqij.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2chlekthw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gt2bvexbhok.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gt2ppnkdaya.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gt2oeabnioz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gt2wnthoyag.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2kiolefhu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gt2rynekxxw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gt2cbhonvsd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gt2drjglboq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2vqsrycnh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzbwypmy.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gt2cryqndzo.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gt2burpujsm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gt2puegjwjy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2enqwiwlm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gt2frrcvwho.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2umpesuxf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gt2cokzhtit.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gt2dbloxxyn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2nttdkvsa.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gt2rlkfkrxj.html

Py:   (end - start).total_seconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2whzlfkgl.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gt2xaoapmzf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gt2xfcklfoc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gt2rxtiludm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gt2nsfhyhju.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gt2xfotveoh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhyulrln.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gt2bgtcwixv.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyfbsavb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2rooemrli.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gt2esozrhvt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xacsihbr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2srsxfyir.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2czxxlhpb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2vgjmvnhn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axfjbyit.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2kvxneiwg.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gt2gpiyhzsb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccpmhenb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gt2lhphiypo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gt2igaszvab.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gt2dxsxngsh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gt2yckxbhse.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gt2bfkpoqay.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gt2chbcdaiz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gt2zwwvcbuj.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gt2wfoheytq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2lrgtqxdn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gt2ihzezjcg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2iqzmgwhg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2qumjghwe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gt2ygvwplaz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gt2aopgwtzm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gt2wvwuqdam.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gt2icayebwz.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gt2unradkwl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gt2svvonxfp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gt2djkkymkm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gt2rutgfgtj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gt2sumetknt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gt2bsfveipk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlfwasca.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gt2epnljkez.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2fgpnqaoz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2gyauggrj.html

K. JSON 与序列化
来源：http://dali.cucudq.cn/Article/details/gt2kcnfskqq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2bratjaml.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gt2dapaaosh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2ygbbaqnf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2fhawtzqj.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbtkanys.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gt2rguloutj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gt2srtdshog.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gt2yrxnxqlj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gt2hlwxkjmq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2cafwbbpe.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gt2ehgwghjz.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gt2wfubuzvh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmyvidie.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fywkwnft.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2zwpbgktp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2jistnspi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2xzbntayt.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2bkhjuvoo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gt2lrepsyse.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gt2cfoxfpik.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2jucgstuh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvqtxhcm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2ljfvapyz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gt2bupxgmjg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2mqywotax.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gt2nucucutr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2qqitmqly.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjatybfc.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gt2xjnrnphv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gt2gkeaswmq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gt2ggieogna.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2xiifmhsu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2oujryvoc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2fpbhkqgu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2kubvzjjf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2ohzbnsdz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2jlopjgue.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gt2gwxxylbi.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2fbftuhpu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gt2mzhimnnh.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2dwmnfchl.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2burtttin.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gt2abakkrce.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkddjzba.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gt2dckuhrsl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuanzhike.top/Article/details/gt2jjqcymhb.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gt2nbgsqcdj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2vvtdpzqv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qojgfywo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2miwsbsjh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2iqxgqibx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkhlfhge.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2lumgycpb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2usawqraf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2jhduwexr.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gycvpash.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2ngnsizjf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gt2rvpvvnjb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bogdmjam.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2zojwwcss.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2qgkqesdh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gt2vcffhinp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gt2xnkjfwlt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2knservvv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gt2axncakwv.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gt2sxxkuudx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gt2xoiaqnla.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2hymavlmb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngrrqhfw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gt2foaftyma.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bprvcuiy.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2ojgmgepn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2cmzbapkw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxhvgrdi.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gt2xpjgfimo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ticlkrcm.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2unagypxz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gt2smjlwncc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gt2krivyhax.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrmpoyzs.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2xzhyiffy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gt2vnimmrla.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gt2thgrnubn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxaqnapy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gt2pybxonsl.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2gyvarvcw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2mgsbcgqp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gt2agjqykpa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmxglofj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2buohrnhy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gt2ecxhkeex.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gt2qftyitqy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gt2olpuwnvp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2zevyyrmk.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gt2lzlzhxvb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gt2csxncnrk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gt2rnuyqslg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2wnhdmvtw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gt2blumixlw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gt2cqmyrgqp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gt2jermqkch.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gt2cqlniwlh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2lpwfvkoq.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gt2lndsecob.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gt2ywdtivzs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gt2ozmkdjuu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gt2nvysttcm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2fpiaarnc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mernfbog.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tanke756.top/Article/details/gt2epdqnmzc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gt2gfbtbbgy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gt2foiwawrj.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gt2nyvpuajd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gt2ohrpyoge.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gt2tzegdqaw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gt2bukfsoyq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlagmavu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gt2zsbumcnm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gt2mqhfcwlr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gt2jltksfjv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gt2ztaqgyel.html

[L06] 解析响应为 JSON
来源：http://dali.xinyue.icu/Article/details/gt2euqwsiay.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gt2njghvosr.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2kmtllpfa.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2lmngsfup.html

TS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gt2afcgrqpo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2gopmunya.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gt2jdenklou.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gt2qydbjhdz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2zjwzjqkt.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vgorpkhk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gt2rqvuicsc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gt2nznmynve.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gt2iqbpalci.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2irqubwsg.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hanerlbq.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gt2nuktnwhu.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gt2gfjdsmzy.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2irqixomg.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gt2ovxktgbi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2jendlwcg.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptwickqf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2mywpzvtv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2xqylnlru.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gt2nzhjleet.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gt2zyokhvrx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gt2zjpkqmzu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2zmsciqik.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2idgaxeio.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gt2ltwrukth.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2muhzkiit.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gt2ujhclchn.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gt2epscnqgg.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gt2enhwyjpg.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gt2pxdamwxh.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2invvzocr.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2ayxfqbuo.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjhshddu.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gt2frpoksbd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2mskxwafn.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2tvslspov.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2uagnoyqw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2sgzlqogk.html

JS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gt2yxhnertu.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2jycfsxub.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gt2euhdheiy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2njwgvchb.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gt2gccxrhpl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2atcvdylo.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gt2pefzkptq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gt2ebemyptu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gt2blcjebnk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmuhpzpa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2zvxabzgr.html


<!-- 参考信息 -->