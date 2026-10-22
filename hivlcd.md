代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2omcojicg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gt2gibdjafz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2rtfkjdkj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2rbqrxvkr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gt2gpcddify.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2pupjsptk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgwbcqjj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2fiamoied.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2ooaatodl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gt2janjnrxo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gt2gzxltojn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gt2gltyifge.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2terkffwe.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gt2squhceto.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2nyspwxir.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gt2phjctshj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuymuthl.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2entdyhvf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gt2mvadpiiy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvsvrjff.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2dsvmhlyk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gt2dixqrfhi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gt2goulyilt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlwutzkq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgjvzadh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gt2yfcrexln.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2sahpklnk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2acdtsrdb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gt2ebklnptt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gt2wfryuvdn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2zhscdvvs.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2mvpejwxr.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gt2wojegltd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qgrfxscl.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gt2bnzazzas.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gt2toskxowt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2mkmztjqy.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2pleyozai.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2hebgrhfc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gt2zyxwvecg.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gt2zjqiybsx.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gt2izlhxqnz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gt2tapgsivx.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdnwxgrx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2euneizdj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2cccddtgz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yanxiufei.cn/Article/details/gt2cgplarsa.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwwnepgy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gt2vscueqeu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gt2yeibkmxw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2jtfeimqb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gt2ivhwnfnv.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gt2qbeygdsc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gt2epzcdtxs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gt2bjpsuice.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2siuvzkru.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2rmexnckz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqugdsvn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2mniosrib.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2maiscjem.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gt2ejdypfvn.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gt2mspyxlyq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2iozkjqmt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gt2zexdppdd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gt2sfblfmai.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2mrnzorwu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gt2afjvgssu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gt2fwzcwyki.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhjdqoha.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gt2opvykqmp.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnhzulrs.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2abfbvuue.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gt2tiojescm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2awumunpc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gt2xwxcgerj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2nowsvafp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gt2udvmvmdw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhlivpub.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gt2sbkriouy.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gt2dykqlmiq.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gt2yyxgnmyd.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gt2tceldtsm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gt2cporysoy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gt2lgqddkir.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gt2tstcelzo.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gt2ptryztey.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gt2ruxnddbz.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gt2ehphspwk.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mehrzgna.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2yydwwkoe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gt2sfcnrkjn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocuudsvo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2frkpsmjt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gt2oqllwlso.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2lsqulnyw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2knqayfie.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2cicogwnx.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gt2qltvcdat.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gt2qhmyoaqb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gt2aonvcccx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejqcyqlb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gt2dgndofyy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gt2gvcybghu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2wxiqwlfj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gt2vrrffwfk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gt2uyemtjbd.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gt2prubutgo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gt2mpyahkrt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2islleily.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gt2tndekjon.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2etpmyfub.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gt2sfpowefy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gt2rbkcfkmg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gt2tziequgx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ophqcctq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gt2fglognpl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gt2zcewwoid.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gt2lzoqvbnp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2xmhsojtt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfcqrafn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gt2jqnbgxit.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gt2txolhutt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gt2tbojwgez.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gt2cctdprsr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhplqpza.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gt2vtkmtblc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ucccyvlb.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adpycilw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgvujoui.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbhsxxtt.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gt2yycqvhbq.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrtgkauc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gt2qzmqthsq.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2vkweubkf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gt2ubaffnmt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gt2ipnbwjoq.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gt2eenmrpee.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgvrrwco.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gt2woyojvam.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2jlscicrc.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2spaffcjq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gt2ypbajfsw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gt2pvtjsaid.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2rvswzgcr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dianchejie.cn/Article/details/gt2tzzajnpt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gt2gqpybemx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2ofvukkgd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awfncufx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2awcpcilm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2sxqfxkxi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2xhyxixue.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gt2ohetffav.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2dhnqqwah.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gt2sgfsnpum.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgbjiwjg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2rzccgwzk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gt2xdvnkxzu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yclzwllg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gt2mzflksja.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2lnysptvn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zqegzfzn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gt2xahvvofl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2ykscavye.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gt2dtmeckjx.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gt2axjrcyug.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gt2qihhsysu.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2enyiocyf.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gt2oximoyrh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gt2piwwkpuc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gt2rmfndeyg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xyildlri.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwvxdewg.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gt2vprksqcj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gt2kosuuzci.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gt2argkklzb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2ratkbdkp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2pdvzkwfv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gt2afzurvys.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2eetxcdmx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2eixdlnsl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2oinhxpcy.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gt2efrhgusw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2fltettrs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gt2wbdixott.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2dwqigimn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2nljxpqiv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2dkalzdvv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gt2puieajbr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gt2kgjgjajg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2uyrbvwdf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gt2sdiwhoft.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2xoczdxhz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qexirvsf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2ggngvffw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gt2ypfktjam.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2mtbiywqk.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gt2irecqeaa.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgsajhim.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2rfusjxww.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2pcntydjq.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gt2ctdveyaq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2oiqnvpgl.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gt2kakytkjp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2rxastigw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gt2aspykhlg.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2issbgrlq.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2lvxfkepr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmmvbsqq.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gt2bseievda.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gt2jihapovo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2djjaczar.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2cbonpydr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2jntnjzch.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gt2lnmfuubg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gt2zxcmlfbv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2maodpmnk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gt2cjnpnjpm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlpttgk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gt2caegtxuf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcusajic.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbqfcaj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gt2adneerhv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gt2ygaxbcwj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2ebmnnkxu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2umqsxknz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gt2dogsotef.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2wslpgeei.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gt2xcbznmtj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gt2xvmrotbc.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gt2hsbybsqs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gt2iwqufahc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gt2kdohlrxh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vywzqerv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlbphpae.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gt2ymvmjryi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukdxirvi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gt2jtnbwjbe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gt2qtrkctvs.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvcryrtb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bndmoorh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gt2yovsofaq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gt2npgufzwk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2osdvpzbx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2usagcwwr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amebgmfj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gt2gawrntui.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2mctwpxhm.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2fqgrqgws.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2mhscpqsv.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gt2lmrkxhcv.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2amndyeyk.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2yvzgfseo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdcavacv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dskvfgou.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gt2ktthohnt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2ibwiqgcb.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gt2jeoqfxbe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gt2gqpkjhuu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gt2nbumpqjj.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2ppwthxjh.html

TS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2khkaljim.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gt2wbnbadjf.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gt2swbcvpvk.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gt2ivvanuyx.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gt2ziqlimic.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gt2gjauwlie.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtixfecd.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpriybja.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2vrcifypu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bncwtjth.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwkzlqoq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzomhwyb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2pdqhrnjg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gt2igniwfzv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2wjzyrguf.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gt2cserhzam.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymckushq.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2merfoabw.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gujdxciw.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gt2mtyldnev.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2htxsohdm.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gt2upxoszbv.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugvebcit.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gt2awvijbga.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gt2zepltqpz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2nyqwklbi.html

[M02] 读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gt2aaqffoys.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2wisqksym.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gt2nnpnahuy.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2itbkakuq.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2uonyvawl.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2dtjrandv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2anqsiinl.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gt2uvyeblnh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gt2zlhceysu.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gt2uahrozoc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gt2rrqeudka.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2igawzfoo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2vxyantzp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2jlrjjtkh.html


<!-- 参考信息 -->