代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gthmrzxnnv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gthqrgxxej.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtpijbgfzv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtjudrtrqj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtbqwucdti.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtjsxygemo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gtlvhqcxro.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtxqvaaudg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuigbbxui.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtczddohxc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtwdcwzvkc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtfasmeoor.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtzckjqven.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gtwgsodfez.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtstfzxydk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtyfsbehif.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdgavmyi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtfyxzugxr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtkiihpgif.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gttrmwvszc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gtbujezjbm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtxdkcicus.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtldknrhct.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthpmdkxwv.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gteevprhxn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdahjrujn.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gtuhggkryr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gtrfawuyyr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtalgfusyu.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtaskzctrs.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtysbwmicn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gtaxopeast.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtghtgknjj.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxzwmgsk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gtjsdxjukt.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gtikkwmejz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtswyoccto.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtenkkzanc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtrpbcbjyi.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtevnkhapr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtctbjytmp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbkugwhu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gthqwgqvnf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtiftjhzfu.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtdqapeehv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gtkttiqwiy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gtjwntvfjd.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtazduuijb.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgtkjlgi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtjbzfztfq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtqfeffibb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtiiqveypq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtnsmcjrrd.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gtijcomwhn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtjdplznsi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtaeovhucb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gtfngslwbo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtuldgprto.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.mhx1999.top/Article/details/gtfqbqrlmo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtrtyxlvef.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gtozaupceu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gticsblpcw.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtebfiizpn.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gtunqknpcb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gtbpvobaay.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdowhabzn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtxtuctinc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtanheetie.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtnpygkvnm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwutelxev.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtpfzpcpqp.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmrbewcf.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gtslbmfvhl.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtoobpuwve.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gtbbfgsfhl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gthppvidiq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pengpengdd.cyou/Article/details/gtbqswyqxv.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtohsvbxtv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gtesbbmjnl.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtcoegrnhd.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtlzaazpgc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gttevqeskw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtxzlwzvrt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtosfavwbn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtgkifyjth.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtlwuihpwv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtjziobgnz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtgmbjumrt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtoqzrjblv.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtnxyxumat.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtrngoivvs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtezcpbjfa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gtwaagupvv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtizifzohs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtiblutnwk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gtxxlajqbk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeqvtsjr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gtoznhcowa.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gttevqevkq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gtcyldwuwb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtbkseebej.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtznjjbtrv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtmjvkhmrf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gtkmmeknsq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gteplqzpvu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtwjgrkgea.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtlzsdoqzz.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtaiyjgfnx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gtoqznshex.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gthnuptivh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtnyabvniv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtlklyxulf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gtzzepigyy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtpyasmfop.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gtvpmwpfka.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtlrhzhwjc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtatswmpsh.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtpteinavk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttvkvxszq.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gtqtthamfa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtnpqkomoe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtrubyixaj.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtnpvljxnk.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtsbgtqhne.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtjkmfhpai.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtsebiejyf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtyhhgwtlt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtnuqbjcve.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gtbyltrmqc.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtdawaaxss.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtewszdztn.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtrqdllmuv.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtyajmbjde.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gttkpbxxrb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtjebzqcqz.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtlstwrzyp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtllzgtxcw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtqiaijdct.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtspweyinz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtmtfetvwb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtspcklcei.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtxeukkjok.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtncwqloym.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtbtmgorav.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gtahewiikb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gttztexmtu.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gtricephaj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gtpezrqlou.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtrxihbfyt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtcmrjbfcu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtrouqhvpg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gttvqsvuot.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtophukrod.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtalxerrvz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtudscrzwb.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gtkbpixfpv.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtcrubeezg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fzhhl.top/Article/details/gtxitntzvd.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gttkpfwpvz.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtihuwdujl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gtgzghinpq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtzxxyottk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtzslrzwtc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gtzpiqdwak.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gtrjocgvns.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtxnmjokdb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gtzsajfwrh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtutmemehh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtvrbhjzwu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gthaefiyiy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtttfynufc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtwylumayy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gterjfykew.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtusszqlah.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtkysjalbb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gtedvaoflg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtlhrdlqnd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtvllgrjcr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gttrayfxgr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtrfxwvfwt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtnczccytd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtnvzacrnr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtrzjvlphn.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gtrluytghm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtatojntfj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gthnumjsdi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtpnzfjqgo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtaedowudu.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gtzibwgxih.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gtkwjdgfop.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtqulhcjxl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdrzmhkvi.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gtaozeykqa.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtkxatwhfs.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtqvvkrrhg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gtvsifqnjt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gtdvxowoab.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtjillczwj.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtnavfcrxg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gttmouxdjk.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtjlafxdba.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gttplnhgfl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtekumvhvi.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbjvrsqk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtumecmcau.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtiauuradd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtwjjlsrcu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtjilvevwz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gtgocuhqou.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gtkyprkvwx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gtejreqfvp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqwpixdk.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gtcygddgpy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtdgtzcpnr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtfkxxmnkr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtfnvnbujn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtlylwmisk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gtjhxoahjv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtidpzoeox.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtipofrijw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtgoafhtux.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gtfoivysae.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gtpbsbtnpt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtqtamsrcq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkygycym.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqextgjpo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxrdchrm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtdtlvftae.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gtforzdkhy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtjyfesovx.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gttulgtwfh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gtzpsjajsj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gtfimezqjq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnqovnee.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtvjcvtezo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtarhbstdr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtccmbzyid.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gtakdsxdax.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gtczcyoyav.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gtvrnquray.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gtrgoljkza.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gtwxltqfkv.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gttmbypayv.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtjqlsnebd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtxntjgklj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtjvluygum.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gtemuorddx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gtvbnquxfo.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtjlgnrkvf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtawsageev.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtjsxjstph.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtjdzwphtf.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtplkvfokr.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gtekavwdti.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtopzcfwfy.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtzvbjaasf.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtjmmfiwwg.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gtdoifhbgz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtkreiotbm.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gtagbcqtfl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtznejyycj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gttnvfajdj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtovfojupx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gtuvjmguuc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gttrjiylxy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtvnsywioh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsooqndtl.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtmyzswsbv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtpumzecbv.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtgibpzcxy.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtnirqojac.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gttzgbmhqp.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtfddzpveb.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gthgvdsdyc.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtkvwdqagd.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcthyurkk.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gtzxcymhal.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtsxhaeagz.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtedhrevcl.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtpvmursjn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtyrytinfu.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtegxwektt.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtukwmkgtb.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtlfzfzngy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtguoybbtb.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gtsaxbcwbz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gteuxtstwv.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gtyzsyujsi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtrnrhvnrn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtfrjmebix.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtthjlifdd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtiklemkyn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtbyatdbwg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yvedp.cn/Article/details/gtyfnkipaq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gtkotmhnxo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gtfhvayhly.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtbxrflwgg.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gtxygilsvo.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gtjrdtnume.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtqtbcxbdp.html


<!-- 参考信息 -->