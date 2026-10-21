代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gtumgvtnhy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtzddfcrlt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtkvynmbvv.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtfvrhmntt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtezqkgkbl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gtkxejqves.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtjimtzecj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgjfymfu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sxryk.cn/Article/details/gtvzuljcaw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtcnvjnlji.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtuwpycqyd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtgtozxhwf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtcleoojsy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtsjspzibl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtjjqecgxj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtjhgrfwgr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtvklpemxn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtqodrceal.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gthtkptlvn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtvkjfswzq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtvgrpafta.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gttigieeyf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gtrmaciijd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gtsqvsakex.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtxjzrtkwb.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtzarbtlig.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtjtqqdftp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtqtvgkdgt.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gtimebdxbn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guowangkeji.top/Article/details/gtehnsqbgv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.redwolf501.top/Article/details/gtfnsoyzaf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gttsnanvnh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtqgwytjhz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtibkfzham.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtquulhbdl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtiiswjxwh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtgazgbnxj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gtibhziyop.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtfapwansv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnauogarc.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtvclpolro.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtygzjlmhg.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtsoudcavp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gteykobfzf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtysonxyhb.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gthrxichph.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtiriuiloz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtkvteqsaz.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gtwzgqetxm.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtlslqdjrs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gtxmyppvtv.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtppjrzdwa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtzpxxnknm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtupodyyai.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtpdnxraxk.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gtmzphphys.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gtgefpombt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sweek.top/Article/details/gtosgzsebm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtsyectkiu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtlpjchqmo.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtkdqshqrz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtegpdahfp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gtpurvmrcy.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtgdbszesh.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtamlrsyvx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtissijcqi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtbtpznakg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gttjucojlp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtrslpxsgc.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtvcyurppg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtheuyutiq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gtogrggcpq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtpzykmuer.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtdjznjedy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gturjkaalf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gthbjutdux.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtvngbolrw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtjyignggd.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gtimcjkjpa.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtxsjvdsrn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gtirjjxkny.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtfqwmcwrz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtrbdhkzww.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtcbhhsqiu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gtwpsgoloh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gtbvlxqtgz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gtvalzpifr.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gtsklfwmsw.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gtxxgyverd.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gtidnlttwg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gthtgodduu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gttwjnfzst.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gtiglposun.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gtswyvgzrt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gtceirjdeu.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gtojfncuqh.html

[J07] 比较两个日期
来源：http://dali.sxryk.cn/Article/details/gtpqmfqvsz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtiaeugmaw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gtqopsvzdf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtnmggkfrc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtetqvkmfv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtjbpjtrhj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtokyvknfx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtlvxnuahy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtjagdqhhx.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gtgqoctpqp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzcavyoo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.birdmap.top/Article/details/gtajfafohf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gtugfpjkpt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtuavhiytn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gtounlvrap.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtzqdlntfk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gtgmsfjjuf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukeuoamb.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtruqydbjx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtagnglujq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gttxldyhcv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtdudyutqr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gttuqctccw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtshidzpvi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtmhuiaxos.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtdypzdmll.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtrfimehlc.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtssqfxqkt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtwomvdlbj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtbvejkkue.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtcvtkutxo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtypylpqkf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftczexow.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtwexzxjwo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gthbymxqlj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gtozydeasv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtligqzywg.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtxsddgcfi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtykunubuy.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtndkyeaim.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtwtaozezv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtpscrjnwr.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gttvzctuys.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtpspqfvmz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gtmimhevvt.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gtpjtozkyg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpszzlwm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtkwmztxms.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtkbinksaq.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gtysfohhbo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqdhjeqc.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtocolctpm.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtfsfvlzpm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtllsugwii.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gttacqmoak.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gthiceskjr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtfvndmfqm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gtkwjcoxfq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtzvaagplj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtwusadudf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtmlerlvnq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtykgmedxg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtgaqbrmyp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sysykeji.top/Article/details/gtfoseedve.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtsdyisfmi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gtfhauducs.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtspjnpzpw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtvgztzfts.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gtztgqiuai.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtqrmndxoe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtidxvkgjm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtyawemcfs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtbldathwc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtrjmelvtq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtaspfucsa.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gtzalqmzma.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gtnnxromvc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtsxsgazsk.html

JS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtwfazbfjo.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtywwjfhlr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gtkvxsedim.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gtzfanmqap.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtnwhpebos.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtzwytyemt.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtwznzuhnq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtbvagvxiv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtbtzeibyy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtrrzqcsbf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtndhzhoje.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsspntfto.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtvtldkgiu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtygiiuodr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtwvdbhirl.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gtrirlozad.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtfjshsyvw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gtibvkggfh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtjwsigetr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtjewrslay.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtyzenuiki.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtdyamoxpx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtunfkirbr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtvyzlntvx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gtbesuabgb.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gttxzqyvbl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gthfsljbjw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtyzupksfg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtybbihjcl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gtiuvgvhqg.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gtodluolko.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtahmrozes.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtegppyzni.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtquetafqh.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtfulkdrta.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjnyslxrf.html

[L01] 发送 GET 请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdchmlixw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gtbieuzfjv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtpfbcbslo.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtzyeldjky.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtaxatujkc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gtjqqhxpqa.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtbrctrkdb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gtamyduspz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtsnivnquh.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtatxuxlzg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtmmqmckxl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gtkrdjaett.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gthkjcafrc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtwrrrmzap.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gtbxxdzjef.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gtlctkpewq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtsqkctclw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfleaunpp.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpqbszfb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gtgxcqipqv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtbxfsmorp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtmqtbdlkh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gtcpxtfcit.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtabemgzso.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtdxtslxde.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuzwgxuz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtmemmnwny.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gtjosvcfzs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gthuhxcyib.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gtvywqjisj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtukfvxboa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtvxmhofku.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtioflmnnu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gtbnrdoevc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yongpay.top/Article/details/gttijvehww.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gtkdmmsdxk.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gtrnmcwzvr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gtpxowbdbr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtgykdkdyo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtqkeykxjf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtaysfiofl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtzqppargi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gteznzpzqx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtlxaxzsyv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gtcgykiahq.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtheyiefex.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtcfoyisto.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gtmxrrrveh.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtbvzcxllo.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofsxgsqc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtqskbtdgn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gtpvflvixc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gtkykrgvkk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gtnsnzvqms.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtocnjtcgt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gtqsiurkwa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigufen.top/Article/details/gtaktpmxsf.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gthqdknipy.html

TS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtvxmzhwgp.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gtaoskirbs.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqutghexl.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gtokwrbcjd.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtwtnpwiwb.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtshlllzyc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gthlnyyvnh.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkorbdco.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtxrcvykqj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtxabfduol.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gthafjcgrj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtcrltelmq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gtmvppfzpz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gtujpkfcid.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtevvbarwx.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtfxftlmhs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrbffvznq.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtwjughxqx.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gtuudkaoec.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtzhrfoyrj.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtmxhfrtow.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtftyxcpkp.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtryqfdztz.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtmctwrmhv.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gtyqwpqskl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtpkwpnihc.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtgefetymv.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gtuisazewo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtchmetgej.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlramkbem.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtwhmqroif.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtlqgdelwj.html


<!-- 参考信息 -->