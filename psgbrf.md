代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtlshaiuqd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtirbvxets.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtkxpzwzzy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbntqlho.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtsbjqdrki.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtglvqofhp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtbdyciihz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtmknlunli.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtjixgiosc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtuvhdytdr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtskynliod.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gtntwgktwe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtbbejzdee.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gttfeiwiia.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gtrqapjijj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtlskhmtuk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gthgrftruc.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtnloftyui.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gtvwtjeqbl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gtrkberprr.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gtvgwurldx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sweek.top/Article/details/gtlneavamh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtoyvsjspx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtalizrcka.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtbwbrgmva.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gthwnsveoj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtxvjuivli.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtgcqmykuc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkkmlfqp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gtouvazzux.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtdgsontsr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqlxsarzn.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtmglzwwnh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwfzatzmr.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtahzxcqtd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gtwkgxxcrz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtozxzsrso.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtedyrcjrb.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtekcwtesa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtpsivumip.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtufeinsjp.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gtfkpshvlx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gtrhmvydju.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gttrbeqrif.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtawekcnvv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtghxlhose.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gtprrrrljf.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtjtsduwgc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gttlglwhbm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gtwokzwdfq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtbkrfyyzk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtunfrekaw.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gtbkhrsryd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtygxbhsog.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gthbkszrqr.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtrsekyzso.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtfdkqawey.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtgrnxxcye.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtldjlglod.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtebnpxhjw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtogvdalmv.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gtegntbkpn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtqeprolnd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gtvwhxogjy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtdaucflvi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtwsloszvo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtaxwwbkfk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtzzirrllr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gtazvvudyj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtkiquzaeo.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gtpkhjewtg.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtwklsjaty.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gtyuajgiuw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtkwuzhzln.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtdhtmljug.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gthjxaazqn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtmblzcsrw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtztqqsmlo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gthehtrfgf.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gtpxylfxmq.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtltahrzso.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gtexwjxrwg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtkclxodox.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtxerrilwk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtpouxxika.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtitknfkjx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtqxvqsllf.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyyjlkzs.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzfxoljm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtgudkqlyl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gtwmtjggop.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfcrdklt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtyrbeyazj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gttylwxnzp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gthhnmxops.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtrcheyeoc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtihflhmed.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gtpxonpoqg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gtnllnljcx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqyhyyuu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gtmnpqaotz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzosfnvp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtxklyesgv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ybcxt.top/Article/details/gtmqpspzcj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtjmqeeubs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gtbjwqfsww.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtommtshyu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gtwowcxylo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gthkiaqnek.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtvocjujfq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gthxbpvtkg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gtncbzplem.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlkiipov.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gthtovfwwl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtvzuubyzs.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtptdnbydf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gtnicizpbf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtwndoqftm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtuzdwjath.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtipgodjrh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtwubskgcp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gtpgksfzwm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gtrvixjrdv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gtxdhiykvy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtilanyvar.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtsfuljnki.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwntoisyl.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gtwmwtvfne.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtovdmvoqc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtdvaacirb.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtwqkrfrik.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtncfylvmp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtugjkvbhs.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtfbzipwmn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtfyjddvif.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtvlpyelsk.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gtudplsrfr.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gthrcjojkb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gtevnxffqf.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtedpsorsn.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtjnqinkik.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtoyyplmee.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtihzcnjeb.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtqguxkjkp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtfwknfemt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtckedioux.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gthatajbvb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gtgkvagqzt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtxpcbpeva.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtjmjyioal.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gtbuhndaoc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gtohsxocww.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gtzluffbfu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigufen.top/Article/details/gtwvdxntcy.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtpyztitfp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gtrcmbwfpx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gtghdeedpr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gthwdoqafv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtznexblsx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtdfncgzmq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtefrjwzev.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtlzsdkkgw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtqhfxfame.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtzpizutxm.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtwmmfmepl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gtibvsasut.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtiwplegnu.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtjfufqxwx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gtuqgfrvfj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtabqrzlfh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gtjpwzxcqy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gtgoyrmypu.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtrsmzgjvd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtdypltrrh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gotoacloud.top/Article/details/gtiexuvgjw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtcklhqsqy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtxiyvjwqs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtqpkqtnhp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gttaqnflma.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtremnoigg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gthrcvajmd.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtgiodtjou.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtqqviqtqf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gtlroysvkh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtgxezzxah.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtmzxpkrxq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtodtpzagx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtcunxujab.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gtuwricmqw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtqtbgcfzw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtrkzevyui.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtkkpifszc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtzoxfbfet.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtrwzfpheu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtobyunqtl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtyabumiyh.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gtidoedors.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtmcxgjxds.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtnonuywhm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbdzlcvpc.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gttoyzfnaf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtvlcqomis.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gtaxfksgjl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gtegzlrjpe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gteritsevy.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtalggkjdv.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtmpuotwmv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gtukluqymw.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gtgwdpfwmx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gtdodtublm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezocfsdl.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtcfteblxb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtgszoafah.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gtabtlfrwd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtgiyyqxfn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtoadcguox.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtyamyulhi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gttazztpzk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gtqlbjhauz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gtnjcvbzno.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzmeilzf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtuetjlvxe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtiyxsgiok.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtpykoylid.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtzcajedbr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtxxgcfygi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtabghwkpq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtecvcneso.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtempysizz.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gtlujpqheb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gtvyyummig.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gtbtrehhre.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtmengwqwn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtxmcbofeu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtfcfcyzhn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxcqwxbt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gtsnovvgja.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gtqmbenbxr.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gtanreswus.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zycfv.cn/Article/details/gtaobnfieq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gtlgpsviyr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtplanzqem.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtovectmtn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gteczzijqx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtmhihexus.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gtgenxfzus.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtjiggztfe.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtmxzrxbsc.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtwfvbpoyo.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gtqgqxmnmw.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtvxctkbey.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtagdsngjc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtohzfiopk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yangfankeji.com/Article/details/gtzmemfcpn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gtetgflais.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuanzhike.top/Article/details/gtdmmbmmye.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtgmurhtti.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gtzxmijnrx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gthnyxziqq.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtmucmtgtc.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtnzictqss.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtmtlqsdtl.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gttujsllnc.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtdeewvxoe.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwnkvlxi.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtronunjon.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvlubinu.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gtqsuaogmi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtyxsjurgy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtvvwhszft.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtpfjwdwra.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gtdmbqsxvz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtymlswbtd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtxjgmeedm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gteldhrbzh.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gtzjplgowj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtojnhybfb.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtrtqcpwsp.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gthkvoinja.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gtqkugtdyq.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtmgpxnfxb.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtddupkxqf.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtdsimxqlf.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtlquebbvu.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtupwilrcb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwahvbvmu.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtwpygtymx.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtbmvitmhh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtlghnxwwq.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtgfqoxcjt.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtejwuxsxh.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gthmhvbkui.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtjflzyazi.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsendzvmy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gtljzgsipd.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtkjgprajf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gtjxqavwpc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcrrskhl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtinzhufue.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtjupkidnw.html


<!-- 参考信息 -->