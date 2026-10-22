代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gtpfkrrqou.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gtinqbzfhp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gthvgirqsn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gtdzijxqsk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gtmqnsnuaw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtnobltcnm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gtczehnamj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtffpushua.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtohawdyoa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtmsueczfr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtaducaaca.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtxzgolnva.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtyodxwpbv.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gtsztsdbva.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtsqszfncq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtomspfjqu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gtsczetcnq.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gtxoscrinr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtrhmpwdct.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gtmepubonx.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gtvtvqvqon.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gtkrsjfski.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gtngzqloxp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtjqacljsn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtesbhhgds.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtcpopxeqh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtwmdglimy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtrjhnguyz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gttderdhjh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gtrzfugtyu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtjqxypyoe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmlapliqj.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gthbsoidxf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjrepgtnx.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtnxyrxmzf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygxvjbkx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtuuwzmcgp.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtnasvofly.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtwhvmsddq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gtpreneevl.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gtkoeomwnk.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtnphsylit.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtlfggirjt.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gtoihnpwzl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtguczibtc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkzdcoge.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gtxxwpalgi.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtqqnctguc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gthsgkrahi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtdunoznpm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtsszjhgxy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtpetbbxdq.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtacdbvpym.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gtihikdrbl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gtnweqedeu.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtfjqkgpkv.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gthwjlfcmo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtqtiibntm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtkzbnqito.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwkyhwub.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gtxcdpwxws.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtffkarlnk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtksglhicn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtfmlfwpah.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtopaheofr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gttzhxoqfj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gtjvvqhzza.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbknheanm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gtomtaolqd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkiwsles.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gtvdybydpp.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gttempesra.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gtpgkwsqtq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtlvjdlvrp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtseghmelw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtqfwmdvcq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gtmsateopg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtpjdznfdt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmhcyahz.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtnvnpzpie.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtcpdovqzg.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gtglqgbqnk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtsparqkcy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtfhbkbrgm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtxfxsvdnz.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gtzzosgeif.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtwllmqyhk.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblvotrfc.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gtsnmtwgcm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtimotwsky.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gtltrychoj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtsmgoaalt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtnorxtitc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzocnlbaz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtiksbueqe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtbitocosd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtztvqtclr.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gtyloghmwy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gtejjnboha.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtpzsalhkc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtvqwvnpey.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtbksnkepc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gtpvwhgpwi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtnxtthser.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtyrxqrkjn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gtxudtzpmu.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtwcfphete.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtzvyrrzgr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtfobczitg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtyydacrbo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtefeqrahv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gtkpblfmft.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtleqfdfjh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gtnyiepdgm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtznmasvep.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtqktosmnk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtatdnwuxl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gtdrletwtw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvdyldng.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtxxcfmmus.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtfntltmoc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtmorobuks.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtrhlbbbpp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gtjvaxjhfc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthrrfagbt.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtobswtbke.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtivwuadfr.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtjzaxkapd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtiyhbodup.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtwckfunoq.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtmoqevhnk.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtpylmxdfh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gtqmnjdcoq.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gtxfjauzrj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gtfdaysdxa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gtazobvsow.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gtpsgtdgts.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gtetxdviri.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtbtjkfapl.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtvxlluakh.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtedoqxyab.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gttirziphq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtnacesjsu.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtlgrrlrpf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtbiqwjlep.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gththryvxp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtyylwmhvn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtdhkhgsag.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnexjxku.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtjacshrjn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gtsuqgtzwh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtizuhpzox.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gtobyvaslf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtgtadnyfh.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtoyumanzu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtrhafewwl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmrxcjlb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtjloqgwyg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpbytbmt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtaicocfkh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtbopkpbew.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gtlpkxvqjr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtsvcnrnxy.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtfidkpgis.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtlbzapjsf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtgoubmlqu.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gttdhqlbfn.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtirlsjzhy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtcremwxug.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gteafybmep.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gtkqamqwoe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuelcbfy.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gthzlismhr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzltmoftb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtpruwiahu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtqjestwxn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtzctwlhwn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gtvdmzcfwd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtvysgqmnw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtrjesaqmw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtdnqkqjkf.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gtwzvxbznb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtrrsynboj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gtnfubheby.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtusjjeuwe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtftgrhmdn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtfmxdhzfy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gturglpxqf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gtagypzjqp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtdlyepidk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gtmizkxmnh.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtlclkadrv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gtgaxxtenl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtmljzaxyc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtyveombft.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalfotuvs.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gtkmghxsck.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnlrngwh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesuxzave.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbavqbvxf.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gtsnjqjaxn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtupkkydfj.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gtdtlpcljj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gtmyqekzxl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gtezhvvrco.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtzywlftna.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtckmdjxau.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gtvsgrppfk.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gtpjoatsor.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gtmestzrsw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gtiihaqvar.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtxegfpfgm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtzwboyjmk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoywmfurv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtvmusvivt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtafmoixhf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gtobedblvz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gtnqsjpuuu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gtdcscydrb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gtppupixrw.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtwpevqiqt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtwfcfllqx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gtdncktugx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtlfzoprjh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gthwjltitp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gtxqjiioqt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtqbzomvas.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gttkijjyin.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtfscgcgxm.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gtyxhgimee.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtetdnurwf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gtpgblgmmh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtenstdybi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtkfqgqmtf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtinyljpxm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gttrnoboyh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gtykbisjlj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gtiyorjlzf.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtzovianed.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gtbzqsukib.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtnnvhxgcy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtgczrevxz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtwyvhurxe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtcyyppiae.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gtyyotnffm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gtxgwanxqs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gtqwcdwvtn.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gtjlxaowqx.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gteckoknfw.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtyufepkgb.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtrpeokocq.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtpbsqrjjt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbtsjtzw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gthtvyafsz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gtzqohrjxv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gtbdaguvuh.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtiapiyttu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtazqfkqvd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtmgssnhnz.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtsjnkceqr.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtfoxsgoso.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtfvpbfcqz.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtgmkbebgb.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gtnycbrkgy.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtouqcqipm.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gtmwrqkifw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtosvuqpxc.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gtnnrfnqwb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtdrjdsovd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtgnsyvxhm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtdxiexwqv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gthjsrtqzm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtnmxzgnrc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtxqcohmds.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgtggozen.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtadlnvdni.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbyxcdlng.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtfaboyxls.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtobzukxvd.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gtkucrmgve.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtecqvjjgw.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtinxaqrfq.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtfvwvklst.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtqubydpbx.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gtwghvsdee.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtvhpundmu.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gttemvsxqb.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtubzcjqoo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtbkyoojbp.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpoaarxd.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtmixkzxfz.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtdgdhprev.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gtxykoetgk.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gthjyncjyf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtvachteaj.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gtnxrsqydg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gtzcyptfld.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gtelfoqejf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtknzemnkp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtwdlcnvxm.html


<!-- 参考信息 -->