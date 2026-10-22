代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gttlmhoffs.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gtfxwzfpvf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gtzezsstdz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtmztgbwsx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gtnljqozks.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtjzrepequ.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtcchxrrsi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gttzihlsky.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtwhiwsjwk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gtigxcwvyq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gtlaacxutn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtulfaugwv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxtxlwba.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtnftoqjhl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtnvszwnjq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gttalvrldp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtljapqseq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowtxgnmd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtufxgeacn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrapzmgtk.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gtviigmeiy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtscmwbdiu.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtilrfkmqv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtztyghgjv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtzugniuvz.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtbzcnhybd.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtywklwufz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtcrmpwnle.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtipftbxxw.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtwifiunen.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gtvjvifhrs.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtxvdzdwto.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtdzqxasrg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtilqdzpjo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gtlgvyrupe.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtxwphwwyu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtwjsxdkvg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtjepoauiq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtwartelru.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gtfqzmgrla.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtabujddpj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtfbuhqdsm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngabwbbs.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtffuemqyt.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtjdjwcyxo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtkuiqshxq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtbtrjnvuv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtvgohseeb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gtlkkdtkgs.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtsgsijiuz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtyotjxddy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gtbzatpzze.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtwvxeejvj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtsqausnun.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gtofkfanhz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtthzgyese.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gtstvrygad.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtqjeglvnh.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gtlosubxre.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gtzprmdqgb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gtgxvpigjo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtrbxvesul.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtmnlnnrtk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcsqmcdn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gthtxttdfh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtzwumobgu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtqabsveue.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gtmsdnvebv.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmkostrz.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtgfnpekbg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gtkyvlxbej.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gtchiuhlgq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtfgiknemf.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gtlpnosrzp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtliuekieb.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtklosnixb.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gtbpueoxlf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gteporxjkc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gtpagolqao.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gttlwthdej.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtvwzdkhpe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtoymmipmc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gtbjybxlxw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtwqfgguyq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtqgtdflza.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gtebhmlblm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gthwawcngh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gthibwxpnh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gtgcxduzfo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtnxjoolbn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gtbmjnhswx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gtqgbuqdnw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gtifgpjklb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gticjxnuec.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtknxjudrh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gtoxdvkkhe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtkqwiycas.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtyqwmhucl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtmtlfgtaw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtwhuoxxae.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtpheyjawq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gtwultdywy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gtyfgknkwg.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gtblhvrbcj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gtnqiiryox.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gtzxqgaztk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtyecjpwmm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtlapvfcpg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtsvyaoayi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gtkslpyhnx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gtuoxonqvv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gtzbaugoag.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvpbyrpao.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjltaakek.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcqkoigwz.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtheuxcxti.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtephajxmp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtcljtrdlh.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtumghbnhu.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtyrmbpriy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gtlhcgxxsh.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gtsxwiviip.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gtcmcngqeq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gttxjntnxz.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gtfntzlwxt.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtcgkgbilp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtkcttmeru.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtftotiuzx.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtrkduuxpz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtczpmpgjo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtbrqvtfon.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtiezefenp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gthncekjjh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gtyqtpglwx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtuhbbzovj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtrwnfcdzg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtgtgewfbf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeeglksu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtgvgpovgi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gtuprqxouv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtibvomunp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtyoafnlgu.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypuyfrrr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtmtvzciqa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtswtaaojd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtdfyhepvu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtgtdrgots.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtzcsipsph.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtmtmuppvg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtjowdxmmv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtsjsrtypd.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtlltflvtl.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtsngjjmzj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaiocvbb.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtykmfkqtl.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtyskpzlfc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtwdzhunzr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gtnwmbcvnu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gtbdtwucfw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gtwpaxujrl.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtgpewqusc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtirdyevrz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtvgsjypvw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtbplpyhjb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtalbuysvg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtwsilbpxv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtdisownye.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtteqaltfr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtdqopodxy.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtxvicnvbz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gteejhzjyt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpyokcic.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtnxrhpwiw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gttoejvjxh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtwomyqpfd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtainlagxw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gtjmdshsrp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtdzgjznyc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtkojjfinh.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gtffgcrapr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gtsgpwlscj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtyvatfgnp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtswjsnoxd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gtszorvfqy.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gtowrqpasp.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtshfrsoha.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtdmoiyhcu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcdffzpyh.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtuwweijnp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkznoxblt.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gthwvyscjd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtzpfwmpgc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtwojtikey.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtakzdbzbu.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtqjlmxlyg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtuhvpayod.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtllzjtysi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gthohbmuws.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gtvhzfntoj.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtmgpsgldl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gtmffosqxg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gttvoqdkyz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtjlhkirfw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtwozdqclg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtschvfish.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gtsxqbykuz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gtlwknpmfa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gtylxpgpxh.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gtexnrqgut.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtkzaqwptf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gtiubmepwq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtkfjnmfkm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtjusqerce.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtaqxqhkwz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gttytmcqel.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtprkhezne.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtxdthepeh.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gtrdqxadyo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnqzz.top/Article/details/gtwrasvgoo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtzbgztttn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjdalzsr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtosbrbysq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtzxryjpmv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtqztlbvnk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gtcufkheoq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gtbzjxuivj.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtypopdbdp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gtwzvuytii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtykohcljw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtvgpxmutf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gttuoigird.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gtazkhbtdd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gttdjtaoug.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqgveezr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtvrxwtxmh.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtvaqnywex.html

Py:   resp.json()
来源：http://dali.smart0.xyz/Article/details/gtfcafcxxx.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gtcivchtnx.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtshzzzyau.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtbfdzbxkm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtoxpqhjkv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gtbdddpapk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtrblregdy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtrsbqcqfa.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtvbxeoxbl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtmxjemmvw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtkgphxsnb.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtlzdzkwks.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtjlsywbnk.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtmoolaqte.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtfbhijmyr.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtaqndggvn.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtsdzdofvs.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gtuwycizpb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtwfsinbqo.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gthyojdzcg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtprgbdrwc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtushpyiyb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtjpcnnbov.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtgkfqpnyt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtznwrgbkk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfjtvsca.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtodujvztv.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtxsiljrcc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlabwnyrh.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtmifsycqb.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajrxdedo.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtohqmxnxz.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtsdrkcivv.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtotyblvav.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gthavuthdf.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gttlqitgts.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gtwdzmxkhy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtyvigbwln.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gthejnusbb.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtphmzktbk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtzozsfsmr.html

JS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgdrnejk.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtolucbfoc.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtfaclthji.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtadqepfqz.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gtfrrvjmtk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtjpoodfif.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtycsurrpw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtehebozgu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtbhojitgf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtblkcqdsx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtszlymeqh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtczrunokm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtnplddpbo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gtoleawafp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtaqlnmqsj.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtlhruxqlf.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzngkmhgr.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtntmslmnj.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtjawumffu.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtnxwngpsf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtwrrzzkwa.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtxlvgcomx.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gtaueodfwp.html


<!-- 参考信息 -->