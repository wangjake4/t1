代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtazuqktbz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtwcyfwlnf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gtzpvlmjds.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gtkzghdkis.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtsyvwdnwf.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gtvtkzxirs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtseagbbov.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqvvbtrt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gttfhrnabc.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gtkbnzpnuh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gtctxdbvwe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkruolnd.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtctzrwlse.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtytseutpy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtjwocilkh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gtaixbbjdl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtluphdnly.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtzqqwegzm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtgebtenjs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtxhxneton.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtoaqkbfzx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewnpuciy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtabdnsuvz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwqmdcuur.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtutxqxdvp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkrccfjar.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtjcanajlr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gttwdxwnxr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtgtovllxz.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtvpptbjrd.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtlvrtrtsj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gtjqfooyvc.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtwxeanzrh.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtatzmpszx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtaycincqe.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gtkfpdraeo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpywzslnp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtgkeaphwt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gtrwxciuim.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtebdbhyid.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gtjrikgsgu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gttozjegbd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtkldoxlyj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtbggmopub.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvwonnmm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtapbolron.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtmiiyamec.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtbwpfowtm.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtftsplyvh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonuuswng.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtamdjohnw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtrkryjffp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gtkdtiatto.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtnjwewwkr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtiobjqthz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtjzbzguqt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cucudq.cn/Article/details/gtrrpkvxyo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtsxqcqmuj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtvcatagar.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gtwwuzjrwe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gtcavfdvkl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hywenlv.cn/Article/details/gtufqrknvi.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gtmjugpjzw.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gtqlimbriz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gtspiqepuk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtcovxafkb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtwtuzlvsl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gtqmulyrto.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtuhzhkoif.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gtuqyxlumi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtffjfqcbw.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtfnzxpija.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtadbqmorx.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtuxcahuzu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtleqhwrsk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gtbbzcpvfp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtxjmrnrwe.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtumxqwgbe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtqqlrhxoi.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gtjqzzhwvm.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gtncyjwsib.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtsopfjrdz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtmfqcavjo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtgizckwpt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gthlgyjcij.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtdyyjsszj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtioitnxxj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtlxjhscdu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtacmvadfs.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gthbjchhna.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gtpimprlyq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtslcdompp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gttzkotnoj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtxdoldkar.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gtbjouaqcx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gtmefmqgsn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gtjelebpsc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtxrvbyuyk.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqzcwoig.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtxlmxnysx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gtlaufhwdo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstitdihy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaobdbsa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopybuawm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gtzszopdyz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzqtgwnr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ehwqpu.com/Article/details/gttirxelew.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtgaaxikce.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtlxhrejhq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtzzvfsdfp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmujmwyt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtaxkzxbug.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtoolupmgb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtlyabosfs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gtmbobsfyh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtqljtvpeg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtizqhzoyj.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gtteffcnld.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqlxjdcdq.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtmuzxwldh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtbqlgiavy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtebidfmxk.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtzartqhmu.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtjttoqpfj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtttvhhrpe.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtmbimunbv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gtwilhimzc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtoazqalqx.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaydwivoq.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtcwnrhhms.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtknnbbifh.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtfuozxjcl.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtrpfyybjk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtylbgxojn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gthvvbpdaw.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtomykagre.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtlhzbzcqm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gtylnhgmgy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtceeamofz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtakqbexbg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtboypommv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtjstpuacj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtzagygemg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtffxvfklk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtmpbiexef.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtpzgwjapm.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiypqjgd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtdylrmjxa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gtrocfdsvq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxtrjpge.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtwttvaqyb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gtcloyjgns.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtsejqcylv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtutkhewsf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gttwvpjrov.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gtublyjivu.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gtqmvetocw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtjujjotum.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtyjzorpfd.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtselcpndi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtzzabreha.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gtgytfekrk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtmkmhwjju.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gtrlbfbivn.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxnivvzh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtrohpvywd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtqaewgibx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtwixdofiv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlhupjzp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtkkbaovir.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtkuprcknb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhnzqzce.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtshihtjwo.html

[K07] 进制转换
来源：http://dali.dianchejie.cn/Article/details/gtfcjaezpu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtblclqwtq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gtzpccwwkj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtlaixnsek.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtbtfyuait.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtikhalbkw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gtbrueqsdq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gtzplqkmtx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gthyvkbbxu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gtctbzyvil.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtsagbjsdv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hysaishi.cn/Article/details/gtlejphobx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtpmkxwkcq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtyovsdvnf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gtstmbtqxg.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gtpifplugp.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtvtkrolei.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gthmpzlcfl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthrvnfjhb.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gtgajystkn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgilcleel.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtjldvptmn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gtedbiwljf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gthtbclvzy.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtzucvzylz.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gttfwxffnf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gthxjjtuoo.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gtlsgjvowc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtxwyzabcj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gtbtselpuq.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtgxixhimt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtnncfhbyq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtawikecvx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtyjysofsz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtcscipaio.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gtnhquqnse.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gtktssjrwt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtpptrrsrt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtholxlcuu.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gthaqxmgpr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gtktwfellw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtifatajow.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtrvsjjeul.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtulvybvct.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gtiimuiioy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtjexefasf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gtubeynnyu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtapdnjotl.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtltbhrcps.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtctyiotrt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gtbjxlyown.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghapxlbp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtcsqwoldk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gtzloxlaxg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gtxbxbufla.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtbzuypdrt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cashguo.top/Article/details/gtitozdxws.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtgjhhqydo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gtcnxrtozm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtekjwyiaf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtmbvwjicy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtesosqkhk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gtijufnwkz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnxiangtu.top/Article/details/gtvigxgrgd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gtyvexansj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtgrljbpnr.html

[L06] 解析响应为 JSON
来源：http://dali.chenlongwang.top/Article/details/gtqrlqrlmg.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtgrajuqaf.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttshofcxo.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcopcfwwo.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtkxghjgbl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pycfn.com/Article/details/gtrnccakam.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtoxlhkidd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtauxigwyz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtiustxvmr.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtxahigzjo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gtgyclacjc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gthgelcbwa.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtqfaxukdm.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtcedkebzs.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gthiszybfc.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtxnnvfnsk.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtqrvpmmzl.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtpohhsmis.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtkbqobqdg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gtceuvsxzo.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gtkrjpbtvl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtycfrtssv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gttkkrqokz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtdcebszya.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gtsajfdlmz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtfnsrisgp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtfffvpulx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtsldrjdzf.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtnoyqdftj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkzijwkky.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gttebaccvv.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtgpvnvtae.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gthlnvchzz.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtehotoeic.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtsvyvevmp.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkeedqouv.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtouqzideu.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtqppibghh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtbpwhdoos.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtbtsuxplq.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtejdusgbj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtahlyxzcp.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtrivsgfid.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gttyjixrzc.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtlhoyklco.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtcimhguiz.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxswuehng.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtygcilson.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gtorngxwti.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtrqcqyjkq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gtnvjxtrsb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtpkrzbohc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gthtswdpyf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadtdiwzd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gttionmlcz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtfmrmtxtf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtxiddpqun.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyscorln.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtiqqnxifp.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtyijasord.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtprjugpel.html


<!-- 参考信息 -->