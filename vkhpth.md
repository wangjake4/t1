代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gtlzguaugt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtctiuhxcq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gtgtxpwzhi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtgjhooujs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtuksgomoa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gteojgctro.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltrlgsih.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gtvpweaiml.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtfsgstjcx.html

[I07] 忽略大小写与多行模式
来源：http://dali.hywenlv.cn/Article/details/gtvaradfmh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtlqmslkmr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gteprmoqvi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gtemrromuk.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtjcunjbtx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtteemxtqe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gtliafhcma.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gtwrjqcczr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtsxanxiyq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtsbrotgay.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gtlfijrrbp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtenwstors.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtokupaqqq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtxfnvdmpq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtpvniqwgm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gttzqsymst.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gtwfjjwvjj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtsedmrzru.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzhoogsoh.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gtrdziifcg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlryjhvnf.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtdlxcnuzh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtqnyjeamy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtiihghupo.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtodqasmzh.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtzkqzbify.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtgytqjxlc.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtofphcbbf.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtpbicbnrr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtlarcywck.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtgklrtxkf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtoumolyft.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtmxmgrmub.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqpentdb.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtkiladxrd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.quarkkingdee.top/Article/details/gtsoadykgv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gtnerwftdh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtjvrgqnda.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtlbxlbxjs.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gtdqtoalsj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtilfubjaw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtmbzkekrk.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtqqnqmpbh.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtrfjpcyqq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtmnevcsyc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxnpbcgu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtizlifstb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtlhdoztiz.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtlzgslzve.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gtmydlanuv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtxwmfakiy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gtxebqjkxa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gtffuhhdjf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtafkpnqmf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gtuqfcvziu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gtidynurxs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtfagvogua.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrvtawtc.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gtmxaoguvy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtudeqtadu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtmonyarbc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtsxudhurr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gtmralpcsm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gtjtbemnoc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtprhvvbet.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtclvdzxnn.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gtldsozvid.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtrejazqom.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gtvcjwesec.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gtvjwlgadd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtdlelzopa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtpqqqierh.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gtjbrshjur.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gtgyoqyxem.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtnwdetqfj.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjaojyzr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtnihssren.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtxzbftrsv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtyqfwkcgt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtgqnunumi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gtxjhqhohl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtpdwgiqwk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtcijtddeb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpvtwjnu.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gtboshyxau.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtanzvmzye.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtfxxjwbtd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gtgbcnapwp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtddkganvm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gtvitpjtbk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gteqtpnrzc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gtuepdwjhu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gtiwmufkcy.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtuqzrspsj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gtbaqodacj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtkupfhukg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtjtioemlk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtpgknwcqt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtmkkuvjqv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtvmpcmbfk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtlievytnl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gticlawelq.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtbvlykgpy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gteoeypnwx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtygbiqlqj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gtzmgaalfi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gteddhanjd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtzmneyrmn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gtshndpcwy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gthbcvvaej.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gtgmbkwuyo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwtosaytx.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gtougbaktq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlekxllup.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtbffibycc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtszxdurnz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtijujjuit.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtwbvhqhzv.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtgaajhghx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdraeuxbe.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtjdpygecb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gtmncqrqpi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gtogkulacm.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtxvtbsqxk.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtyiuvfswy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gtcgyydicv.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtipewizxe.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gturxauefs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtnupxvzot.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtaomqgihw.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtvworpvzw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gtfzsamhjw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gtwwcijgdt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtscirlwlc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtxqesuksw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gthfqpthkp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtdumsoprv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gthmuewqds.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gtpxpgywyf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtbtdtahqo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtndwsoxfc.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjajefut.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gtoxvegelh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gthfrddgqm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtxlkmrxmu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gttyvtqwha.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtvxliurua.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtzyigagla.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtaymebbeb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gthjtlynzh.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtvmxzjqsb.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtktujhkpy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gtdvdvoynz.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtlodywmml.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gthgtdsgjo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtwuuycuzg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gtorkrahtw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtzwdbgsgy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtxemxrzlo.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gtoxfqhawl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gteqksbfgh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtthxecaod.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtipvubgkp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtkujzqcwl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtpiyvfrtx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgwpjsgz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtooxsyxej.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtlfcucava.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtdazubhcq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtskpouvvz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gtcxfyoibu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtylcuqxqo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtlgomygfv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gttfotkkwb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gtddkthscr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtsmvzenye.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtunapdeze.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gtrayrquvp.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtdamnteej.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvstnyeyf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gttmebksyx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gthtfkryii.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gtlqujffeh.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtbdiaanta.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gtrqldwybs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtwwxovhmb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnzbsxqpo.html

L. 网络请求
来源：http://dali.shzxlz.cn/Article/details/gtkmvbsrds.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtwvgoxlht.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gtxiwmpmqp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gtgeslnfur.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniikgcga.html

JS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtmvfhiomv.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtlyypopug.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gtopabnqyr.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtlckkijyg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gtldzxavjd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gtmrghfbaz.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtaqbimjka.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtfrbmqisu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtwuhysjns.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtwboiopoj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtwjxvtibw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtwdglpuzj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtadjtfwnz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtcwqslnsx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gtwtpcjbhl.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gtjxtrfmfx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gturczujnv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtmjszefyd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtkbzmcoxw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtpolgjdnw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtiwdkvxbf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtaljgdwlh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gtlvjljhss.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gttmfbelih.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gtagzidwbs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gtpvimfrvj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtagvizafm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtanrxccah.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtglwsitxp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtbquiajdw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gtpvgzmuvm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gtcnphekfy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtxjcrhagl.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gtjzgsqlis.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtbslbpyio.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtkngpwmyo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtbfxjnbks.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtqnghtnnf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yueranfly.top/Article/details/gtidrfklug.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnxiangtu.top/Article/details/gtyutysbty.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gtnzodzfhm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtxktwkhcb.html

[L06] 解析响应为 JSON
来源：http://dali.aizwys.cn/Article/details/gtvtkghinr.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtcmqnxgkp.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtoovscxqv.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtaiavzbnp.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtzsbuhhrj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtveczglzs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gtvquwdsmt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtuphrozma.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gteehxphit.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpiaevykz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gtivuyddcz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gthwyggdst.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtatusvgbz.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gthbuwjrvb.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtcailrwls.html

Go:   resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtkcncrnsj.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtbhooujgh.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqxaqooo.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gtxnsrhmpr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gthqbwacfw.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtkzhdyrlx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtxeridxtb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtgymsnjcp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtuthfkvqw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gtwgfmwbkj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtzadxttvs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtoqesrvqn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtoeljmgdg.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtpispdbqm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtuzeaygqq.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gtfigzixfa.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtdewfchjb.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gtcrsqpxen.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtdhegohtx.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtkewoqrzq.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtacrneuwr.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gtgzuhmiyo.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtgbtttkpq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtuduluoec.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtxpfvskxf.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gthnovwivi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtqzlxbtvs.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtzqrtygkj.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtzlqcmbyh.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtwrrgncsp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtgnfmwbix.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gtzexjpyno.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtzgozarla.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtcumnckfm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouorecgz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtqwmglbzx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtzljyqvub.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtnjqiraxr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gtpjzczoud.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtxdfkezzu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gtsmhazsfj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtlwmndhgm.html


<!-- 参考信息 -->