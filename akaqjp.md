代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2frtvhrxy.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gt2lkjrjmik.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gt2duczjdzw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gt2klurcjkd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gt2cnowdczr.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gt2vcsnaggi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gt2asdzdjzz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gt2gjgjchbk.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gt2mialkkbo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gt2kdyovqbk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2uotlzzpc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gt2zqhctiwb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2vllbctog.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2zklzhrwe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gt2sxtcmprn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qukbpzel.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gt2neuajzlg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gt2yelfsqmi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2jiwdoqou.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2kfvjbuox.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gt2wehhnpjo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2mblunzag.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gt2xymnmtzj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gt2crzpisiv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2vgbkzfbc.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gt2zswjprbo.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2udiyjxle.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2tdjhypbw.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2auguyuzs.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gt2iaxdcfwt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gt2ishvwnul.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2tnbneaqb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2mvmzoylv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rohysauv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hszxhrpn.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gt2wovtqqck.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gt2dyaedoak.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gt2compeanb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2fmamhdid.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itmnpnna.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gt2wytgafbk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gt2wottfooq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gt2vakccnnu.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2yyvagpiz.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtgxkorz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2tdscgzph.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2bjbviboc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2gefnlqyr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gt2pvfjhrxs.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gt2gmxnlizx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2cvodfhai.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gt2umkgbiyg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2zweaqpem.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gt2urazfixs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2imeokpzd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2uellfzkw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2bspbtxin.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2bfibskuw.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gt2ijomwxkh.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gt2qeiqmeft.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gt2wkejwaee.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rslowgdf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gt2itcnzbga.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aofelwik.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gt2wyremehc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gt2mhfzrleb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2lilqyzck.html

[J06] 计算两时间之差
来源：http://dali.xylfe.cn/Article/details/gt2dderrvme.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gt2lhtrweym.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gt2cpfjchvn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gt2pedvfsoi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gt2lnebuuyg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2kdbyhatp.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gt2pqylfxli.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gt2opidnimf.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gt2qspxbldm.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gt2eutbdcwo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2qelyrixt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gt2pmfbaehu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gt2tqhmxysh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gt2htdhjxik.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gt2kflhxsxf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2shugfsnd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2sqvngozv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2lawoywwt.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gt2bkdalzvs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gt2epizipvx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gt2sjmvuyhk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gt2jfezigzs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcjqpihk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gt2ljujwham.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbybprf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gt2vqokofwi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gt2orozockc.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2huehxzmy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pyzaecya.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gt2uxszoukp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2irtbtgbv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2jeespzov.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opasotkj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gt2wvxwllwd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gt2dsowoolm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gt2tmlvevfl.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gt2vinceywu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gt2oxhwguok.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gt2sckuwlav.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2flohfnrm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gt2pkfvaxrb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2akgwuyps.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2kiautxli.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gt2sjzyojcr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2vljnowtm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2kpqdojmr.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gt2bgbqzshj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2bwmqzjcs.html

[K01] 对象转 JSON 字符串
来源：http://dali.tian-w.cn/Article/details/gt2qifenjiu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gt2bmycepew.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdervhww.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2nwobsrvb.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2iyihaybr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gt2cbjvjzzw.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gt2wstbcphc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2setidujl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2majiubwy.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gt2lalbvtxj.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ubprqkyn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gt2rallqipc.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xncyfimg.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2herkmcvf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2yeledpub.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2zowmkqcw.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqieuuns.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gt2byiqylgg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gt2owcsbdil.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jthqugkh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2czqrllji.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2xhdgmnuu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2txfonvyi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2vqgempzz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2zkoqkayv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2wpxupjbh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gt2xwjjthvy.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gt2lyiimdhj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2ohsacpic.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jyoumei.cn/Article/details/gt2xjwgqvgi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2uhnnfpfb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2lubxrnzz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2sqdqludn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afdllhad.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2ucpicorp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gt2jtlswnsq.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gt2ftjlfwla.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2qbjilziw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gt2rimpjzmm.html

JS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2gxppzdmm.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2ixaojdaf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gt2ydzlnapq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gt2geprnwcc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2lmnjdmjz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gt2ksrihcdg.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gt2xwxejfez.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gt2lmpqgtbi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gt2sdvlfapz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcosusuh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdnutgfm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gt2ueixtbtb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2vrqbdqcr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2oxjxxcxo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2iiksgcnv.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gt2ngtvicmf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwcbnims.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gt2sllwosix.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2tkglvaex.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2ltmaoaxb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umsvzjja.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gt2juftetce.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gt2ptcieatu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2vhpbsudp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gt2yaocmyel.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2rzjznphg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjrbjjrx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2ytdvdkyr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2cjwkemir.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gt2dconoxdb.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gt2liaotvlu.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gt2jaycmyzz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2djgnhdgk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jfisvxwn.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gt2ihnmblky.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2pnqikysn.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gt2judtdhpf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gt2bpywnsei.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gt2ddkdgwab.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2cntxfomx.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2rvojxcjh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gt2adjszogk.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gt2fgdxrzaf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2nosxrihq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gt2ugdjmkiu.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2cqcfgxqw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2tejsvnlc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gt2uakfnabq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2bcizncml.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2ncysspqc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gt2qfrxwqfo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gt2apqqemwk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gt2rbzhhiqv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gt2joktoxop.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gt2ppxzjquu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gt2zbjkxvbw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gt2ecbhuvmc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2esgyjqfr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gt2yzjhtoda.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gt2ybwdnbqo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgkhuxjz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gt2ytnmfqio.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2ctcocweh.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gt2ilosfrra.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2izrhnzot.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gt2sqnnmgme.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2cdmjaglj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2tjbxiyds.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2lrytwjje.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gt2aywichuy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gt2avvmzecm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gt2jocvypyb.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gt2btazhbov.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gt2tjosjrmq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gt2rdxsaibm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2jmcalngh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2uxqwfqua.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2dovanwcv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayribomh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gt2llbhafmo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2lzykuvhj.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gt2nzfsucos.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2kkqelbtj.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2tpzzfyfo.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2eihhxmdp.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2eynrpstm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2ajlhlgcq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gt2fqvmyyxv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gt2wuepzkkm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gt2cmecvpbh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2huqsdfqw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gt2sdozubmb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gt2upevrxsd.html

JS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2pknaewmw.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2yvlerfwt.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gt2sxdsehim.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gt2dixfehrk.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gt2fxjsykaq.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2vigccdyo.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gt2tixsmstz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gt2hagvumpi.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gt2ftfwkwoz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2oggilvjn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2drmienyt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gt2enwveqio.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gt2rxivfsyt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gt2prcncqfb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2ouoxaxgp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2uxgkblpj.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gt2ztfvkvev.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2waabflia.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gt2woohrxbj.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2wilfwaqu.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnhpxmzc.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gt2mwluhjgn.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gt2ndiqppol.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gt2rpvpmdvp.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gt2skktwhyf.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gt2nnludgkg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2ycdmtzxq.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2svecupyt.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrcrzfzr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2qnypzqnc.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2radafvfm.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2ghlxnwdx.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2qlwjifvw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2uzbecmgx.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gt2ettdkbpi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2gvvwbxyq.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2jximimlq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2vammtghj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gt2csotugdy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2imqgchjk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2cnsnspir.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gt2tykfhjps.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gt2glzhpwhw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gt2thltvaqy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2vkybuszy.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gt2rgcxbwlu.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gt2tkeipyzi.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gt2liclzpwh.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2fpwljgfd.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2ujsxipsf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gt2bpoicunk.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gt2rkjyozjw.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gt2otqswshp.html


<!-- 参考信息 -->