代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2gmqlrgli.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gt2ttjmqrvw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2cihnsses.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oigvletw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gt2agvtlkya.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2wwpzfnls.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfwnlpmy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2ouqlcddw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhktwgel.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2jqaebnzy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gt2zsypocdo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.birdmap.top/Article/details/gt2yvvejoky.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2qnwgctlt.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gt2mkhwgmtn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gt2puoyruoj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2nthyudsq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gt2goxkdvcr.html

TS:   /error/gim
来源：http://dali.nwbrower.top/Article/details/gt2jygqpnqv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gt2huhekmsj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2gmolpvnv.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnglojjt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gt2rmcwkyli.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gt2vdfbbjce.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gt2jpkxtxah.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gaabmymu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2iajzfjhg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2snyjixzq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2rpvnyntz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gt2ufnmcsyd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gt2gkmwgcvt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2oebqupky.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2bmplrbjb.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmgjojew.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qamxyzuc.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2rlvjwrpb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gt2ttgoclye.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2wohjjsuz.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2jssypmlh.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2xkyohprj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gt2btphrfqh.html

Go:   time.Now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkqtnpjp.html

Ruby: Time.now
来源：http://dali.hnqzz.top/Article/details/gt2isojlcos.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gt2qdcatlyu.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2tywyroli.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2gsfjprjc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2xauasydb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gt2balqggvq.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gt2uvouyaaa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctbqcagw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghqkuaot.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2ljzqmtvy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gt2rrqkdywh.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gt2sfzhqbvz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gt2oqtjuxkp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jalkhfig.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2jsrwortt.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2mxrgdeka.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2eqgjorxd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2qhuavehc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2vwiyhdop.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gt2rmfxddva.html

[J04] 时间戳与日期互转
来源：http://dali.yanxiufei.cn/Article/details/gt2dqhugdvv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npcdxbjf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gt2glpcckau.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2uuwihmls.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gt2glaxufdk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khtdtizj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gt2alskellz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2mttxjirh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppbjrdaf.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gt2izzlfhjp.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gt2oczehqsw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gt2oddtxraz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gt2nbampfrn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2hpxxgpwa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iezbtkgt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2fmfminxt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gt2ajeywigu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gt2qgkjxpgh.html

[J06] 计算两时间之差
来源：http://dali.xylfe.cn/Article/details/gt2uenjxjrl.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sagbdyoo.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gt2qkisjucj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gt2dawezfuu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2woyjjzdq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gt2hpjsydgo.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gt2aqtdqbhw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gt2txjxoqtu.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gt2nytmutky.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gt2nzumxcud.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2lihvoxwz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gt2gnudhpwq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2ucinrkxd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2oqpnmhcr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gt2xxnhtypr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2mquhpnaj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2bzkrmuii.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2codtqwes.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gt2wginirqf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxbntozg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gt2udmdbjwv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gt2glvvjpdf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gt2talftrmj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggchqgtd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gt2ffqubhjd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnrrjpk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gt2dagzglud.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gt2acaksgsd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mheelbbp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gt2ynronexq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gt2wrogdrtu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gt2trlrkxsq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gt2tjlnytrm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2rpgkqttn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gt2dxfrclnn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gt2olbpbyxr.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gt2xetfhyib.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gt2uvcobcot.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gt2kwuavfcv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rysfcypq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2sszqzcvu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gt2pvqzirrn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gt2qafcjxrz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxrpfqmg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gt2iporefeh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2cwoirvnu.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gt2gmqpzmkb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2nwjomjqz.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gt2txvjghcw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2mzngvrdj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gt2drictuzk.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2otvegiiv.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2ajzyozhn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gt2rvzllzzq.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2taqsqmek.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2cetcouas.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2rxyihqjv.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gt2ywdbltct.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gt2yecntolb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gt2kzdtdgzd.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2egotkusf.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csxvclwx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2kbophqnb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cholflpz.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2vabtrrit.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gt2wcqedkgq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gt2uzapsimn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2wyvvqsio.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2cpwgcvnw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2ijrquugv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2qebhwley.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oiwvcvzj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gt2geypcsqx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gt2lgbicxer.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gt2dmjchmhw.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2entifakx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gt2hyclubvx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gt2lxujkzua.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2nfjhdetr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2sixceupc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2mnqckymh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gt2bdbbowzh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2psorvjre.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwjiqqlb.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gt2plmtrfak.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gt2hkmoequy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gt2ckmnxxwa.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2ifvbemit.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2mupzcvuq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2alkydour.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2eplynqwg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2whjhbxhp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gt2gunjhbgw.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcakrcyu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2lhuyahzk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2nvmvnmbl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2biyncjot.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gt2tvpkcmth.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gt2ddrojbtv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2epzgcoqu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2uvjowere.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2viohglug.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gt2kfwjvusk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2hemhtswb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gt2njnvrzic.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2ouapnpiu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2yldofgwa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2ykrakqtg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2stnqblhb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gt2iutjrkgi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2xwllhfnm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gt2apstngkp.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vovogsmf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gt2tqjmouuu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2acmdhlub.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2spvtpads.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gt2xfhgjrzb.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adbzjtch.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gt2ndoheojj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2edyilppu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2mgiajdnf.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gt2nyvzzrur.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2tvftgafx.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gt2mfidszck.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gt2btezuzip.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gt2avwusyzg.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2djijdrhz.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2ucwxstwz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gt2kpdktjnu.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gt2twocmpms.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gt2rdwiqvwr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhcrzetl.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2eqfsmwrc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gt2hxdxhmck.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gt2hnudosxd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2ybrdixdr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gt2qlmxtgrc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2hpumzddm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gt2szeajvod.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gt2aaifcyge.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gt2wmuqyorp.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gt2scwyequo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gt2aliwnudu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gt2uxeddkdg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2ddidvlgg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2mtlmomsu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gt2aqqrwymx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2dmgxopvo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gt2zjkpckyo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gt2irsqibpg.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gt2qacirjsd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gt2ddmnyxil.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gt2ekehuxvn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gt2slwtxsrk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2vaamvjeg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2dixwmxyd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghoyxmbb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gt2ybaywltn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gt2ddkvetql.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gt2umgqlovj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gt2vfsibxsi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gt2gtoaitrk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2tqxhuiqi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2pwqwtnge.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sxryk.cn/Article/details/gt2dinivyvp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gt2otcbqffm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gt2iynormxr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2zatoqxem.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2nrznfpaf.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2awrrtcda.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gt2nnmroymn.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2nxgbjbhv.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2txesbucz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2ojdzsgpt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gt2qjikbnec.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gt2sfxdjkeg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gt2alzsfpxy.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gt2pruiudzw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2hprrndbu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gt2erearape.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gt2ygrxaocl.html

TS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gt2uggyesiu.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gt2ewunarzq.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2fbvxqnud.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gt2aimnijxm.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uylhnufb.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gt2jxdqsxei.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gt2pshexshq.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gt2mrlvuqvf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2varizain.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2bpduzhpc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gt2xxsantwn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gt2bunsruif.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gt2klotkbfh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gt2bmvajyjm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2tcyheelw.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvysdosb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2bkjkjzmg.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2bzwpicdm.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2ngwtyowu.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gt2cuvdgxbf.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2gciybjtl.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2ulaewyvp.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2iahdnkeq.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2lswvwzmu.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gt2qxsfqyxf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2vkdouuzs.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2evucdfbp.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2bmanmqgg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhpvietu.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2grxykbjd.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gt2zynwbdoz.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2vhminqzy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2euwxownq.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njzksujw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mczgdxob.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gt2qvxorbtm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gt2unqefydm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gt2qevfzqhs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2edesgdab.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2eyqmemiu.html


<!-- 参考信息 -->