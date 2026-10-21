代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtihupcwpw.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtbjtdrwzz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gthlgpvrmt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtzrpdngxf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpttisyw.html

TS:   /error/gim
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdpkqxhj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gtomjvxezy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gtrjblrfez.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtxcpbdtoc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tanke756.top/Article/details/gtcwqhoyoe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtxzjtsstm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gtsspbwrfd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtttwwrbnu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtrsunskkl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtzshyesmh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtxexalwtv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gtdknqzlhn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvylygfr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gthtfwsztk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtecylzzfi.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gtpytrgand.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyfrddefn.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gtbtbwmpwo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtyeoehmxh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtwlpgtvfk.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtxfrgunbn.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtbtwzwpnz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtcpxkrpkx.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gtcclkafou.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtfkfjkhiv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtretveemw.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gtxaqqqiuf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gttvuhtjbo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtbotxfbdz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrczzuirp.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gtdepeusao.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtbedeinbc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtlsmobkeg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtzptvgpgp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtlekubrxc.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gtxlnllzfd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gtmyahjycj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gtxqhmfknf.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtoavvuizi.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtdglnqgzu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtwhsyadgq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtlmuoymms.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtpjmiislk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gtcxazklfk.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gtbemnyook.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtgwetwetf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gtxlylrazl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gtqbfwairs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gtslgoukco.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.mhx1999.top/Article/details/gtozlimozv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtatqpbnca.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoskrkpah.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gtsfqqgudi.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gtymxoetra.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtixsnoxie.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtbkcwefcx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtgfqrhslp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhisrrhx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtlrcavwdj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtqxjvsxrn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gtuznwxxla.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtowcxnjkb.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtkgktisdk.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtxaslnjct.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gtciwzgdlt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtiyjqbfpw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gtpdhulsus.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gtcafaixpd.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtsxjzwtyb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtcvebmkji.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gtpddckumn.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtdmxrczjv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtvlcqvlja.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtxgglwexu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglcsmogn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtnylyyqou.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gtryoltjyb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gtukihqqlk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtpxcoisnv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtsxwjgtbv.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtmfaefqps.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gtosiyuupd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhvgevty.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gtuagcwwgs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtkbzdvppy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gtwmeumjxz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtfatmdrxs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtmsyylqfa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtcnxoifhz.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gtagqadpvo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtnnkodjab.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gtcmucnamy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtmxhuheyy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcemgist.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gtltdvylna.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtrxdtdbly.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtbgixdkhk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtlgeugibc.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gtpzuhgbwc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gtgyrzmiqv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gthlfcawex.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gtuebddtwk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtyuujjdyp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gtmasvplfa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gtpdooxzdn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gtkikctcbo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtsotriwkd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmduuhygs.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gtudrmcqqh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfrinbahy.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtpwisaqrq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtvvjwryii.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtkewubutk.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gteflsyhuh.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtbwhzycva.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtjwsdjlgt.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbelpnebl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtydnlutmf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fzhhl.top/Article/details/gtxovnxvis.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gtwhzjpsfb.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtajpqnrmn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgssdzphq.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtaxlwjbvw.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtqaleggpw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtxtyeeeez.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtsibvqyxy.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtdyhmtzlc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gtrlgsrpgp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gtrggzsqjv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtbnwpwnay.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtgjwnohjs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtamaarxkc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtdauutgtp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gtipdnllls.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtwcgkagvr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gtogzrkenc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gtjcrbfqzd.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtkofasgvk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtmiqyoiqt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtayxclezy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtezavjwpp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtcxhcclid.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gtljsznbmc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtnxicgmvl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gttizeiyrs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtjwqkxhmy.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gttgucvjpn.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gtgogyllpy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcedmgms.html

JS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtwdyejywv.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtsdgqnjyd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gtmldzqurt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gtrgcxrayd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtznenmjef.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyemfaekj.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gtnypucfye.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtvqtcfgeo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtjjwwecbb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtrbueuntr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtujvunxkg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtbceujbge.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gterkybtvz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxtocoet.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtqjnnderm.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gtrvkzxsdq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtexqprebq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtmlvmshah.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtejftpxiu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtmvbkczcg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtxsppyxbm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gtjnzrmoth.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gtymzdstsh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtrdcuxyhu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gtafmuymsx.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtuxggedrw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtqatgqojr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtccsjuluv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtmgnxmswp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtozrerqqr.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtymcygyfo.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gtzuiramwk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtdzhmybag.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgqncdgm.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gtyxuhjoyf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzaauvoke.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gtdwhabyow.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gtcyxdotod.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gtpcrdyhxd.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaazfsul.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtdwckdtsq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtcvrquzqh.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtuywmgmuo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtybwwroiw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtmlkodrum.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtuppzttjy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtovxfwlar.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdxkvtpe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmhsyvmm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtibrqkbmh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gtndeikyen.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gtfxibhkmw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtwitistht.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryxeswvc.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtliwemtvb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gtmrdfxspk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtxnrelrbf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtwsnkzmqp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtfzbvshgp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtmcclfrwc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtzuxjjodx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gttrvehaym.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtbogugght.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gttanwynni.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtksbnnojl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gtjllbigxw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtvfaabdle.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtojjznhgq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtwabkbtjs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtkhmtswyx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gtnitohrvb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtdprngolk.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtvkmqtcwm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gtexiaggix.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtoyhavfdf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtgygqtdhn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtekfboppw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtobitfqci.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gtlzpmptla.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gtdvhvutxw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtvzqyqhnn.html

[L06] 解析响应为 JSON
来源：http://dali.meibo888.top/Article/details/gtpeicehtp.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtldhsenfl.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gtuakxuzja.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtbgctnelh.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtxfohvhuq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtjwfytwca.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtivevkznf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlifmqfxc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtlcnsmbcw.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtopvrswtp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gtamtvlpas.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtnjixgsge.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtsqtwpomc.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtxmzkeica.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gthxesdcqd.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtuumuodei.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtzlsjrcfe.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtjqfliwzk.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gthsjjlpxw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gtbtrdgnub.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtiwgorzlc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtfkzvjqzw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gthcrryqrd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gtytkcccra.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gtmusesrvg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gthqzacqzj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gtkxyigtts.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpukixgba.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkoavzgg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtblbvgeaj.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtnjlkkuwb.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtfibqbvng.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gtdoeafdfn.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gthmgrhsxc.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtsietmqww.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtceidxtvz.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtmiywtpte.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtfxvaafqs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtxxxposaa.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtufxeyker.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtanjucemv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsycwzazs.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtorseedye.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gthppbxxtc.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtcdykvssy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtttrlaxby.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gtdyqpbeco.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtywumbvkf.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtvqxwaxug.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtsbjpphpn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtoscxeprd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gttrnrrsnx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtwvzyvuaq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gtwgmyunyl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gtvpztfxke.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtqkajdfhs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtqvbbymwl.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gtgrqwhwji.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtfrmkgkis.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gtaupindix.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtmwbkrmom.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtajwzuvgo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gthfumxhcu.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtgloigmea.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gtsxcvfmbo.html


<!-- 参考信息 -->