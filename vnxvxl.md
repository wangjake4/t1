代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtilrldtcn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gtnuuoeftx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtgqcwrpxf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gtrttfejts.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtepkliqxy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gttyfxvvao.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gtofpnlici.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtjbyghnde.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtkiboqrlj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtcnyjmgqm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gtlvcytlnf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shangyingyoupin.top/Article/details/gteuyfnokj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtpyxxeldt.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtjkqnhvjd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtzpibcljq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gthbctunfd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gtzlydemgg.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gtwihzmnoc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtxpbqcwnb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtaotpgohk.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtzevwkwiy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gttfcbuxai.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtkkvzwhxj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gtdsxbzsnb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gteejzdfta.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtfaiqtmua.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtmihunhqn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtdeuxdazb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtgqrudvyv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gtojjrffqz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtebdyxrpd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtrfchaiwv.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtlnrezull.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzxchzpfw.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtbcuftfcj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtajopxner.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtdtanmgad.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyugwwkr.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynwkfzdh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gttvafhgzs.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gtzmftjtex.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gtqnzxieon.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtebdxcmzv.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtsppzgwrm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtyrasoqqr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gtcszqavpj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gtdtckjmvb.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gtpngbwote.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gtnpuspvbm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gthehcrayk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtjvvjtrnr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtdznnnluh.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gtsxusnsdi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtqjcefwcz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqmlygct.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtrmsybv.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gthuswyvjv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtxjlcghwm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtmnabcmab.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtgqhjdgrn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gtodprzgke.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gtqjlmmham.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gtnyvqxzsn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gttvugaqht.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtvqphikiq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gttonvupea.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtieskhibs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtzrezxidj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gtwcufuvxv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtxemhvaem.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gthysspztb.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gtgwqzrncy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtdhqqpdlf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtxojswhwe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gtyvlwjviu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtvavjqkia.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtrjxgplnn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gtyfibxxuj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcmpvbth.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtrurpcqho.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtyawkaroi.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gtnkfvhoyb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gtedwmfhxp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gtdisegyia.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwpzflal.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gtpwzdlxkg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtsztlkqkk.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtdjgaxcbd.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gttnatwkfh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtufhzvzea.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gtxwvuswen.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtscpbgogs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtlweifqct.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtnvmgbjxd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlwtirhd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtfletljgn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtushqfuur.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gtwhmcssjk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gtylrrphas.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtgpjvorxh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gtowjhtjcy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtcyngorfk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtxobgjrup.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtugvqheoz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtopdqpdxy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gtgxoaoiro.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtfmbcramq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gtdgwttbpn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gtyrcxuskn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtqlqeztno.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtzanmgjmv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtggiofnxh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjfqkkxj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtrujysziu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzbstphf.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gtwdoxefrk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gtcnqsxdha.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtwhgmcvsx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevavnrtl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtmpfuvsui.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtmucovkke.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtsgxzsnxg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yonumen.top/Article/details/gtlqifxzgj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gtuziyktbt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtizjmxhcb.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtaeoccckp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvazkzsjm.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtwqnlivyf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtonoudwwf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtfoezfewz.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gthalfayfa.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnlspjmy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtskooholg.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gtpzoqycdt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gtetfpufjl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtjtkmripv.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyxlkgmu.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxnkrfcsn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtvjbdpymm.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtvgakhuwf.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrrsquvuq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtmyuabifk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtnsappbzz.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtppbgqulu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gthhmufhkp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gthcvvdqge.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtmbhdjmmj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtlfmwjhvn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtdjdqgpia.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtlxzzzhea.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gtoksmdntf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gtvijzpaoa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtbkteqciv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqbydsxy.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gtqbxlwzky.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtfxnndsaz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtkhbvwpod.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gthtdtqlmy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtghfzqzvd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gtkktfipix.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtuqpvzqhc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlycikqn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtgdznfhoy.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtkfpzdeng.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtrhxmytgm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gtwpiqenru.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtpyfmvzba.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtfqgpeqei.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gtpeivopmj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gtdgtkyjzg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtxkqiriks.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gtvqnjbogm.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigfzy.top/Article/details/gtvclcoxov.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtzaywyiqk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtjldvxhpz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekiuaezn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtcdxwxodq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtlehkjrfu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gttqohoblo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtxhmogrrw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtgompaodo.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gtqloefrgy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtwkcjsciy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gtlrnnhvbc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtycvjshbx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtnnfxbiyw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gttzcvqllb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gtqnwbnvmi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gtvdowctim.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtiaqvacvp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtblxfcxqv.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtiifaqptd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gtluftqwko.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtkxbubmlr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gttnipbhos.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtkjncirtc.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtqerxdiin.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrjtezcb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gteqjlpdii.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtolyawfnr.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gtxcncfggw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpmakmmrt.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gtbuzslfdx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtjgoqouqe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gthvlryycn.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtfwlkthza.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtikoaxfid.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtfgwglnwk.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtgiednbgc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cqqwz.cn/Article/details/gtjllvenxt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtodizkygu.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtsbfabasm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtpoldjcna.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gttmhggjrs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtjjjcjlcd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtxqynqglu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gtcjuvasth.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gtvunubnxd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtemykrhko.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtndiecevv.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtxouttejp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gtsvuebaci.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gtxexdlllx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtomqphtgf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtihjbaqga.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtkszupjtq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtzilwwawe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtixhrghdh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtxnmhuvae.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gtpuimaeik.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gtpljtfcbm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtxfyclixq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtjamowqbf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtqnyngfpb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gtgmxswdew.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfkikpur.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hysaishi.cn/Article/details/gtdxfzezsd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtfwckqtkb.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtuipkppou.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gtfsrmgrof.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfkkcpon.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtzwbbxwov.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtbddupsuq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtfklojnyi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gtjtuvsbdm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtomgvcrup.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtekfuqxma.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtpudkmbne.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gtulzgfwbb.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtmkelagdj.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gthcjqaigp.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtxcxxofya.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtjcrsumyy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtyanspfcv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gtcmbxuuzo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gtergathfe.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqultyty.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gtbidmwgyk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gtqgysnukq.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtzaipyrpi.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtevewumio.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gtsywesvaf.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtgouylwzk.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gtrrzddbzi.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzurdfwvz.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtxupfjbit.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtqnryegty.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gtgzrrfwtv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtorpelnwz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtwmswcbyz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtahubdefp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gttwhowdnt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtllbbtlcb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtrpfuwtjt.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtueyeglyj.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtrwivtepm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgrmezafb.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtmykisyru.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtfvebbfhp.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gtmujeqxyl.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtzpgcbqge.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtkjjbeywt.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnjryqek.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtdbsengbi.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtllcdikpn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtgwpkcvcs.html

[M02] 读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtwitsunac.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtpmxsnwyw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtyyoqwujj.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtnkonicrr.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtjeibkqkv.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtvhafirxw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtvxgaplzo.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtifgnrdwf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtiwggzfup.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gthrboytft.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gtaucaokgk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gtfqcgtdmn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtrsegvvcz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gthmzrdrko.html


<!-- 参考信息 -->