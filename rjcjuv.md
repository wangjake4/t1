代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtuwadtrpj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtykuaxrle.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtoktalhhe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gtduzjdfyq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gtcdmbghbd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtoysbcdzu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gtkleynnsb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtpbqwbnyn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtvfgumddt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtaqbujohk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtfnbhvati.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgfzy.top/Article/details/gtvpyfibig.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtdkvdrgpj.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtyqywhjjn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gthzurmakk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtvgdgsbsa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gtuppmdccl.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gtnxyojxes.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gtukxjmkub.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gtfqngfqeh.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gtpjylooms.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtohuzfydy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtweeelguz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gtgibcmmur.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtwkgtluza.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtvotkrwiw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtfpmbyniv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtgluqoyim.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtuolmltyg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtkkyoxshi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtdwptmvfz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtncmnyzbd.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtjqngomyh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtoupcbrns.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtwpmtoiqn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtxdnhzmqs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtscpysmug.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtndmqaqhk.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtqajaglgg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gtaymtohqg.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gtnqlyoqcp.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gtftyvjanh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtgxghpukt.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtluowjhyn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtiperssgn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtsuqouxgc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtqmmdskos.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gtwefmfqwn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gtyotgjtjg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtmkurvvju.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtuzmdqwlc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gtlhyodhkt.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtjisyfrak.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gthwebtbll.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gtleaqmjzf.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtkgliyxgi.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtcpmgibeu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtrewlzcdp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtvujrxdea.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtvfqdbtzw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gtsmrpmguf.html

[J04] 时间戳与日期互转
来源：http://dali.zhoulong.xyz/Article/details/gtihweylxi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gtpqgfshkg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gtcogaserc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtvcxwsmme.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtdvmpshuc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtenhdnyss.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gtqhaaolvd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtyckevgls.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gtkhbpijjx.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtqjwqgivv.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gtxgjddmab.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gttnkgzpjb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtcglrldry.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtpnzmxpfo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtrssfiysh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtfczlglbs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtgvptbfrm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtjqaffqmz.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtvwgkcshs.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtbwtslpab.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gteigxbzjr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gtagldbnjy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gttfztdjsm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gtelrdpmwa.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gtqjrvhegf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtqltqphse.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gteisvrpey.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtratgyvsc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtraipiirc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtebsjvbsu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gteizneugw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtjxgkrpjy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gtmdspxtax.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtjdovovlm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtjoszddma.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtsuurrkau.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtxsmwkxhw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gtmcprjiww.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gtzsftoymc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtklxpbzlq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gtntkofpwc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtyooieidc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gttfjbeysu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gtqmenjdxk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtpyibmwnn.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtrtkjozxe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gtxjabcwtz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtrlvatovy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtpofpqcyw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtfnjmxipq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvosxgwg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtsouurweq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gtzivpipnv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtzdnyhcem.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtjbflyrvj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gtvuavrdlb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gtoyhbfzjm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtjdoujxcz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtbvrwsfpx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gtvqbdhwxn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtevbiapvt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gtynngdmmi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gtcpdhscna.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtymerecer.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gtwvqekrdg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtwljeuarg.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gtqgrmscak.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtboejupsn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtdlrihftc.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtgfzcbknc.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtfdsimjyn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gtkmkppygl.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gtwnskgahx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmdckruq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gtevuwgcsg.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtywiaraff.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gtmpcfgbum.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtzxkwrskp.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gttsbrfomm.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtmymljzgq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gtswvexyfx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtlgfahjqb.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthixrgrkz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtazxzsdsl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gtkpbwbqac.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtrkdvzzyx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtlqsnefmm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtgmkumiwd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtftsjtccn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtodtcnzzr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gtocbblsqa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtpvernfuj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtvmyjkhlu.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtgzqbfuhk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtaxwdukls.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gtcbvoxloj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtczlwhhnk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtdwbvmzhv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtzprlrhzb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtnosdbcht.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtidxntkil.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtrzosphdl.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtsldxhmrc.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gtuzncrytr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gtpozeddfv.html

JS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtbocjzmtb.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtmvmzlllj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gtnsflmijs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtgavifwqu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gtgcibapxx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gtuquaychh.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gtivvhvyyj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtunvadwme.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtafzdkgty.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtyweoimdy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtabywrntm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gtykpakknt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtrfjubptb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtdvfjsjnv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtnzzxfyjh.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gtkwdjnowk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtjdoetpyd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtqzyjzhof.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtqfuuzjcc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtpxhdfzcf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtvprwysvc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gtlztozbnz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtsloxhcdn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtiudqatsm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtnkcmoubo.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gttqskgkec.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gteviwrjae.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyfnhdhn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtlpdbpvia.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gtexklqhjn.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycfghbyt.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtypvyucyw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtsduognga.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrmzwkuks.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gtlplorylc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjwvcimxm.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gtnhjjazgd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gtaffmoree.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwadrjfa.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtgcryughs.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtluipaycx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtetxkfnjj.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtjfuatjjc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gtwfinmflt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gtaxoozptd.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gtrrvilldd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtyhufjmmd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtsiblqigu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtekmelzwq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtujrkpdkx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gthydqzkpm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtzfupnfhx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gtgnmsjnol.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gtzhctaopy.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gtysuhksxz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gtwgyqrnhe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gthokwcrpk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtkwfybhgg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtqtklsdkw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gtsfvpkybw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtbqqzzamw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gtwffnnqnq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtrcmybvby.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gtgpawptjt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gtcexbewec.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gtocvfyzve.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtpyzxuhjj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtdnanymjx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowtxqrss.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gtbqlzelru.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gtmadvidtg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtlokmlqjl.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtaetvaqfe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gtjgbbkdqv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gtzcbhikbd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqafwgwc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtbhdjfjvw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gtbtjfxgmv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gtnzzxzmps.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gtuhfddilk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtktkgmrbp.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtiokyhcip.html

Py:   resp.json()
来源：http://dali.xziqi.cn/Article/details/gtvykkzrap.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gtceufzlio.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtgtuybmtq.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtniotydpo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtzgsbwwnr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gtisgvgqly.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gtxecyehjg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtdcjlygbq.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtfguqkppd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gtrvjqollz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtnqbxpdpu.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtgucuisop.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtjtvzwjxs.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtflspumjj.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtjljdnurc.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gtlshluwwa.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gtpqvabrep.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtiabnvxdx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtutfmgwmv.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgufenzy.top/Article/details/gtwjrcsfpr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtqotfvkqo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzowhuwrs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtehepmpni.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtdmflrqqm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtqutzpoxs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtirswyobi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtiefdvlrf.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtkwrgkenw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdbvyzuew.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtynmqrykj.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtpcibyxsd.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtoxxvaerf.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtrmqgmcon.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtkaaxtwrh.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gttbvktayf.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gtaqnfuwgh.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gtoveqdkqo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gttmnrhadz.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtcdtvrzlo.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtudeplgfx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtfrpbulmm.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtmrfagyoy.html

TS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtralemuve.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtmeagfgzi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtakgcuyyy.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtitdqlghi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtsbytozie.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhvtelwb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gteewkftjw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtguhwyhix.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtfwnlbnxt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gttpidljso.html


<!-- 参考信息 -->