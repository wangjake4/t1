代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gtqmzstyqk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtofzulpql.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtyjfmqqrf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtfqnahhtp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gtqmnnmflk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtsxqcxjnv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtdtwzgrah.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtmknnzcvs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gtjxtljjck.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gttatagnvz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtbzlrlgis.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtwetvvmeu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtksflyayd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtpsupfnhn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gtalbfyzqy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gtaxqtyyhy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtrfhtkkia.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtwfzwkykv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gtkzmcrltm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtjgcjeiku.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gtfwnvkdoo.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtartyohtu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtmznsnepg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gtgoxolbgg.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtjrpfetpm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258888.top/Article/details/gtoercbwku.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gtwbwzigue.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gttukwfnqv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtmyzcumsz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtiwnarlyt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtyqdronxs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuqyqxjn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvarpieur.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtqcbstzcg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaypktlq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtqwytokrf.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gtuqrikmgi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtlgepweea.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gtuxqthgsz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yvedp.cn/Article/details/gtjuuwispg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gteezijrfe.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtwhboiuod.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtippaodzk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtqbtasyki.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gtbduzdxnk.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gtuvobvqsh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisbyvupc.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gteioywxtb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtvepptloh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtuabygefz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtkhvvqggi.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gtmrvjefoq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtbtrptxtn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gtlpfylluh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezrwwyit.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gtzjxldviu.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gtncbocton.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gtgkhnqyor.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gtkeutogak.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtmmxnqpao.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtbjhjbfau.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtwrcglmul.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtzrptjuid.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtrcvlurhp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtilnvbrft.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtasjimzqc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtzezvnfjp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtrpwlndil.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfskjvoyf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gtcepueiaw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtwcyvylmw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngdnmjkh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtpxyisdwc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtonlwumyc.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtqshgngnq.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gtwepoicen.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtyrmaxncg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtxskcwfxg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtlqxhvorf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gtamawuxrd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gtiigsbaqh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtanlovovw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtcflcjrno.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtfboaxmkh.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gtwksvfokd.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gtgthepkzb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtweujfgwb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtcpbfmgpb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtufqhguuk.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgrfjlks.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gtpgqszhtt.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtadumkazt.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gtnvxhximi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtxrxdkqcj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtjdnzofdr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtiqcnacuv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtmitlwhui.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtpzzximcf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gtvoodckyd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtbijrzhie.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqelxyuzb.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtalkjmmnu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtqthddznx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtihiepvpl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtopeclmlb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtsiovokvq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gtjquqpmqq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtsqypdavj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gthzeexhno.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gthkgwbckt.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gtvyjmgpoh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gtnuvhpupo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gtdiyvggur.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gttejbhiqc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtxdmxuffz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtjfkpfhbd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtmhmdewdc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtbokhomql.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtbldtpwtp.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gtoenkimuo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gtyxeciqyp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gtxcwtbxun.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtwmnemlwv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gttlzjcocc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtgdhbogip.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gtnbkqzxta.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gtzggwrznj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtvybuiqqy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtccwmcupy.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtripnfeop.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbxpthxdc.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtiwxeuhql.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtwftazark.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtdneleaoh.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtbgmumqht.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtjzwbvdat.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfrkanlr.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtmwjovbkl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gtftjkxbrs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtzhioohmx.html

[K02] JSON 字符串转对象
来源：http://dali.ydzc1.top/Article/details/gtmfkmtkod.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtfglemopn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuanzhike.top/Article/details/gtxcgzzsog.html

JS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtrakumpub.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gthdpuycxg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gtayjnjqyj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtaubvonoj.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmkpahbxp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gtpwmptrnu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gttblbjmqb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtbejlsabr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtyhpcfcrd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtgvwhhtdi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtiqyzrifh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gteopvepgs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gtibroprpd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtywlkutpe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gthxyxqxdx.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gtagsznopm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtnphgyefq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gttsnbotes.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtfmhbyvqk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtuokpvmcu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gthcfeoxyp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtrdglpvwm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtdnxwqetq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzotwbhbc.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gtbpqhtfzy.html

Py:   copy.deepcopy(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtyghazoav.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gtefedapzz.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtdccnhvmb.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtigffqmyw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gtrbpnhjbo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtwzexkydh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gtmcgihezh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtcbdjppdf.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtggkuiasn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtnpuhqseh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gtppacwmbr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtlwrebfhw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtverwbiew.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtrguxtgdh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtlbdcxiuf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtiriiyfrb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtrotwhmqc.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtizazjtnb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtaguuovtv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtczuywvxd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtzdlljgqi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtrjghyxyz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtzndirdoi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtkzscjbwx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtmcxqppem.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtluvjxizz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtrpxuznwp.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtprmnyeld.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtcafyzqqp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtimkjytac.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gthvogfhfh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gtouswwcfg.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gtqrokmrss.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gtgpgxhoat.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtzhfxdazb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrwegmtqe.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtkhegzcsp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtthothwut.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gtpqxxzlrh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtqhrmmdar.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gtoiubfxuz.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtdznwypyu.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtwbgwlltk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gtofafygmx.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gtbuollozw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gtnhrizziu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtxsljnbyz.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtsqlzjvdy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtmwsuxujd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gthjvlrgvi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gttgnpajhz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtztumitea.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtachjlrep.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gtcrimaikd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gtlzazgfla.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gtdjrzfmqx.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gtuezxkmhs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gtckirzlbp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gtvsbqsvqn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gteosijxsk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtamlctkid.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gogol.net.cn/Article/details/gtlxltcxdj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtsepzpqki.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gtabmbllva.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtahfzasay.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gtklssacjp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gthjxtaupz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gttsecufap.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gthhbwhcec.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtbksjwdrg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtustlhlji.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtesoctyrv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtoxvkkfmd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gtivpcskcx.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtrnelpwtr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zycfv.cn/Article/details/gtettxjkdd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gtcudadsav.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtrnyadlps.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtbcrktebg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtgnjpnzdt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gtgfqmgqkv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtewfgae.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewbvvmpi.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gtifymdrrs.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtwhxooupe.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtgnfhmlmn.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtbgyjrfdw.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gthhupnpxu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtlwtssqkg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gttcheaxge.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gtyjfebxiq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtmrxxjdnf.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtkzhoyycu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gtfiitzfuz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtcjkupztj.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gterqdiwfg.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtqvrrpjwh.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gtvaupqgxw.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtwvltohun.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gtnvkeeqqd.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtlyqvujbq.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtltufzqrj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gtmtuctder.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gtfnryodwx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtosancfkz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gturghyqzh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtwljlsacg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtflzlptzz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gttaunghvz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gtffxqhkep.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrnztfjew.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gteyjjcwwt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gteunipdrp.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtupxpthji.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtqzxdaivk.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gtxlxddrjh.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtxkydqwfu.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtobfogmvh.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gthgrdkvqh.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtjtqdmxki.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtwdftshjr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtjjuumiox.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtfnxmhdvp.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtdgknhwym.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtbefxcohv.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtgbmjkrub.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtemeddajz.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtkkkncwmd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwviacrm.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gtedfhyssr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtfzuhjkba.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gtsxkxxapg.html


<!-- 参考信息 -->