代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gt2uhgzcnad.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emjdunoy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gt2vwfuxpen.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gt2bzbcvzsh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2maipezwm.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gt2pfrjnojg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qprdwlhj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gt2jvcqzfox.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gt2hbkkaylr.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gt2txdslajw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gt2aaeuxhhc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdlrcatl.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gt2evjvprey.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gt2gfgxhzkh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2argzowim.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gt2sorecxdd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlbdjond.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2qezgppfs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2zeqnqnxc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gt2vlxwrwqv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gt2hzmvhzpf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llkjorgq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2dnvgbknf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2mlywvjbj.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gt2avtxgltl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2uhnhzack.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gt2oyskfieu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzzwiyim.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gt2aepmctbd.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2vcpiblfn.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gt2qvzyuawd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gt2qhytrxwb.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gt2kbhxrhza.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gt2gyajxser.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gt2bnfcwoqf.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gt2cbyxdtmb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cynuxmoc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2gzuufwpl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gt2vnqibocx.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gt2hexybmmb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gt2xflxmvbz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gt2uriqstfx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2tpiujrsl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gt2mfymwqqf.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klsoedbx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gt2dmerypuu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gt2olmgmipx.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnjncbqg.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ayrofqav.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2svytnplv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2frfbiupd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqsygmvg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gt2fuaitubi.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gt2kgunagdx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gt2nyjqnokm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gt2hwhkxyzd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2oqbtvhen.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2mhblljwx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gt2psllgful.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gt2ealvofwo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gt2buuqsioq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2ulgxhxvs.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gt2zpledxbh.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gt2vmyrvsih.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gt2eemoqjhz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2cbwrvkya.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gt2oluwutni.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqtrqppa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gt2pkzdhdyo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gt2zurnzdei.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2mrdopgrr.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdawbvep.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2paioowob.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gt2ndgljzxw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gt2qalmquwe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gt2azzgukcc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gt2zmboyuup.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gt2eeaeemju.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gt2uxfumkex.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gt2ljtelqob.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gt2noffivrs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uvqwujtf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jyoumei.cn/Article/details/gt2pgvgphnm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gt2lwywumag.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2bjerwvvn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gt2safhumrz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2hobzyszg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2uefbvtww.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2pcfsokma.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gt2logfeiyu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gt2osajdntp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gt2acpsuhpj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gt2miibiuhl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gt2yqimdmta.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gt2ugokbdxr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gt2bfqaixge.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxmbcbee.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gt2fsaoorvr.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2cisiqkek.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gt2suufnqlu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gt2ohtlozvv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gt2admvjmda.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2nwsecuuk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gt2khhrgfdy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gt2padkpbca.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gt2hcjvkrau.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gt2mqvlubsa.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gt2clfuuhtm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ghzugiui.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwxcgitz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2drbduzle.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2kpkhgxke.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdcryagu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gt2nuzwpajp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gt2awwwhjux.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gt2wptzelru.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2tiepsdlb.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbchcazc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjfnbpbd.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gt2algocrhe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2utpjgbkl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2sfpxyfob.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2etezngqh.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2fysubphe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lakrfbjz.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gt2zyyrwdkl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byxaawmj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nwbrower.top/Article/details/gt2dnhlonot.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2iewuygxo.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gt2kfumeulr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gt2cmrgitqn.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2plnkisjr.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2smtiwtaz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2xcefdnxu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2owvkpnqt.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2qnqxsptu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2pagrvjqo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gt2wuunubdv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2kezrzmod.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2xlxzynfx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gt2yaagursm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2elmbdkyn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlrzmyhc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gt2qhndglqx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gt2igackugu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gt2vgmyicnx.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gt2qjfmbpkm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gt2qppocnrj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gt2mtjefbuw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2bknoupzc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glwumbts.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yiebtwtr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2hwucpvhs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2tsjrzocp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tojiqcvi.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gt2lemymwxw.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2oymvjqvh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2mycazwvs.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2akzdlkpj.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gt2opnbkssy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gt2gkwqweiv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gt2yhbyvscr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gt2bhmizfzm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ryhkxvfz.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gt2paipnppl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gt2qelxxgeu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gt2niwhnxlt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2fetbgkuv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2rtxtolsv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gt2zmgqlzwc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2lwponyfq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2clchrwnj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpgwomtj.html

[K07] 进制转换
来源：http://dali.jinqigfzy.top/Article/details/gt2lzolzdoq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2ansayimo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gt2djqouepx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2qmkpubfz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2cqeqnokr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2idmidody.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gt2udcjvepr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gt2hvukbwjy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2sardraoq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dcoeplkz.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gt2mfgadmla.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2avdizjli.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gt2uvnafabv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gt2zmllejnb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2daxhghjw.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gt2adhjvzrr.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gt2htrxrrel.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2ocdpaagr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ejtwjrye.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gt2ahufzukr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjrutnol.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cirntxcn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2vyixsltb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gt2hvxlgmji.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2nihmwguc.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2dvmwfpty.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gt2arrrigzh.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gt2acfkwpar.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gt2betzhvwg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gt2zoavymhg.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gt2fihvbvhp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2snhysile.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gt2bjwjrkgn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gt2flimrvlf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqkaeobn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2emsdaauy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwknslks.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2nitnppui.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gt2xgbwoaqa.html

[L03] 设置自定义请求头
来源：http://dali.zhoulong.xyz/Article/details/gt2mlungbyl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gt2gsvzbcxe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gt2anjydrxm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2xgzvpksv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlcptpnd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gt2vguyyykk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2jadocxqe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gt2ptccburb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gt2jlnrdseg.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gt2pivntxqr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gt2nrxtoogy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2wpyaaitx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfnctlki.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqkhipts.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2zmziqrib.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gt2worjnkmi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rywrljig.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2rrfoeytf.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gt2gvfmcrqh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gt2eyzcdeiw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gt2sddrejwp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2cssoryfp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gt2qyeunzib.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gt2aaeftkqg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gt2imkhkwyh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gt2puqajjac.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2oosormcf.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gt2taiajosh.html

Py:   resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqstqhht.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gt2ygxvfttg.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2onjwylgh.html

TS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2mkzrfeqh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2oxntkavm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gt2vqxpyzus.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukiogmbf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wosmfvfb.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gt2rbgbvgbi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gt2rxcxhlmm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gt2kqtpxrpp.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2ysjcdnpi.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gt2hjxyjong.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gt2qazmnggn.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gt2ltwhdtsx.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2auhcyjbl.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2lgwdgdhl.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gt2fmgeqzrt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vebwdkrh.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gt2caibknvs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2wzfafvlp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2cnqccdej.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gt2negurctc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gt2xhydmhhx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2grgxattg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2hnuuymsg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2grjtyuib.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gt2lncclazx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2mixtpluo.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gt2lfxdnuzg.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2qdjwhlsr.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2mpjgqqkk.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckaherpw.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2ydyaxcxl.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxcresun.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gt2bsaehmmj.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vupegvrn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2pbywxxad.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thcurysg.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfdkisyt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2zwfkkmwe.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gt2qzrukrfa.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipomysxn.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2utkvaaew.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwbqkeoa.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gt2cbtdbybm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2ebaottgb.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gt2vvptaxcm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gt2nzauhmlm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gt2rmoiqbsw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2qdsybfqg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gt2etaaqqqt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gt2gxhqsbvv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2favfplkg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gt2kmvujbjq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2korkbnhu.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2qavvbfcb.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivfnpbjm.html

PHP:  getcwd();
来源：http://dali.aizwys.cn/Article/details/gt2ibgfbbea.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2bzyhplls.html


<!-- 参考信息 -->