代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gttarnzwba.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkirsflbx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtpriyphkc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtnnolhrtd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gtvpiadqmv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtnklpgyjq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gtniujvalg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtvlytlfsb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtxkuqmwmc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gttlwpodbb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gtolckqzct.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gttslhcxto.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtvnwfjygj.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtvuztbhyi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtrqoqwkpc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtekyksmtb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gtvuhrxjbi.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gtsuoobkpk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gtzxvkgbtt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gthletpxvk.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaswkplvk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwteoftz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gtkyeshuca.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtseyfvqbb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtrwkyqhnk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtfznubpgv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtkdqceeia.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtqhdzextc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gttryaozuk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gtjgcdnndm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtytxydalo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkmpywnxx.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmagkivd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtinacpzei.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gtsmdubdtc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtzsdlhmvh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtjroamobj.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtvjgpvfhr.html

TS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrqzbfoy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtcrkwfsej.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtigjyvnit.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gtwtldeotx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtlylhxhlq.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtwmsakmsk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gtybqjrwqd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtoerovfwy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtyhsrozbo.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtxkontype.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbuqsmoy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtipjqbiqe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtrmcxulzt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtghqjcfxl.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gtiwutxexv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gtzutfnqvx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtkusmgrxv.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtimqgkrun.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtqwglxicw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtgkxihanq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtyrvcuqfw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtqvtszrae.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtfjhfqoet.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gtvkhjjnne.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtjrdrcarj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtooyavliz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gteubamqvc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtpgbzkrxw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gtjacnnwvq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtsubzscpt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgeauiyki.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gtqsjvbcep.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttptblokp.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtblmxfmub.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gthxoxulbk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtifmlwczb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtxqzpcarw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gteaoblzpz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtypalglja.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtwcrjbarp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtwczbisgh.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtpderpzoq.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtskjuuhrb.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gtzzdmgxwr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gtpdtnpeks.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtryebjafy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gtnvnnhuxp.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtmilxxnec.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gteqhuytpn.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtbzkvzpdd.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtrwevyukr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtkotjkdmv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtuysdihll.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtprklddpe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtjlfbpdjq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gtaogqgsah.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtolfnrtdg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtiwfgpvxj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtmbtxackr.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtrhsmgllg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gtdmiontam.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtvyyvbzws.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gticfftkez.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gttrjvvacu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gturqwhcwa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtbsqaswkg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gtuvaihpce.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsreyhtx.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstpjgcuf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gtiwugjqje.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gtynbvholc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtsrwxvifp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtaljpvcwl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtsvfrdndj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gtocqmplvk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtujhctetx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ehwqpu.com/Article/details/gtzboayonl.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtspqfforq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtoepbyfdt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gtxsfwidcm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtublwgwyr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtfignlwkn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gtdzjmtcer.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtxoafxdcz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gttmoyhxzd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtnwiyxfgz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiixecre.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtppaufklo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtiyxbxpef.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gtjiknxwjx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtrxpfuqvl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtoyfxmeyd.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtfiutpzbo.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtesghlxpm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gtmvclsmnx.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gtnivcdaby.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gtyxsjojft.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtzvaagbqu.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gteibhomdp.html

Py:   json.loads(s)
来源：http://dali.svipenyu.cn/Article/details/gtlopxxiny.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gtwinizuml.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtqklbioxh.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtlszcfacz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooxirbcb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtxbndtxzh.html

Ruby: JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtqiuapdbr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gtbaxwynpz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtfrqtykxk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtvbxjdogm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwccsvsec.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtojwnwzby.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gtmqrpjbhi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtjvezfeqa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gteabgewca.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtfvxhbjrl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtkunqgdpo.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtlngwgmlc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gtqbyvtltb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gthaycldbc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtoinbknkv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtobxpmzdv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtwhrplfno.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtyabxpquw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtfnotpmgz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtmrlgmulm.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gtdkoexasv.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gtivvqxxct.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtzxklfusz.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtdixlwkoy.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtkxlnbvea.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwkvyjuz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gtamrbflyw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtaikwekmw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gtbrtweaxg.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gtlxmengkr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjhdduhg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gtukbopiin.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtzxjnhgsz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtxtkxegkf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtbamkxpqs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtfxribsxa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtvovzaxap.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtibwyoiub.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gtexhzusea.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtvzmxiqjs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gtxmwflpjc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtpswufjpq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtxjcoznaw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtqwlbrhag.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtiqbjzjwu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtfdfkpwxm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtrfvxccfe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gteyqwppen.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtxgwqdgly.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gteicsnzcy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtzmyuqzhg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtnyzkyqqi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtpkhpgqvw.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtrqjqnqve.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtccuoupgo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtfqtxchbz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdybukzlm.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gtslrcthoi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthkninrwi.html

[L01] 发送 GET 请求
来源：http://dali.ybcxt.top/Article/details/gtrxjgsjje.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtoxngizcn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gtnniqahjh.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtmlegsrxm.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtizbfhuoe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gtiehewdbe.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gtshgulwak.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtdclsblxn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gtorzgibsm.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtanverrqi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtflnsaefu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtchyowfqs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtcmeiiakv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtzwnbnppd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gtxrqpopxo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gtidprppjn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gtavjisuaf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gtjyizorsi.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gtrpqsymcc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gtevmfoejl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtfmbwxzjl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtpwwamekt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtpqndhykv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gtehkayniy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtimmbunuf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgfzy.top/Article/details/gtbrnxnato.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtdrkskqem.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtqakajlco.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gturficqsk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.havefunace.top/Article/details/gtjvxkpkam.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtmnvdfuxw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gthuyueuci.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gthdspsywa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtmuwndjrr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gtvnrqzyjq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtnmhzgkbe.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtgizdwncp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtsnggniwm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gtspyzhugm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtqamioruy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdyjpyfb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gtctcegndi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtganfxvwt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtkurxyhwj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtidbbfksr.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gtbupwaufu.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtvtufyzio.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gtuqnonpxp.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtjijsijkt.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtgbwakqyo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtmvlqjzvz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtzsksovsf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtlmiouqtd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gtlxsiange.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtkdtnxdjf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtbcyojtgo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gttpjzeajw.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtppcuansa.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtjpbtudzh.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtjwupfwpx.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtiqpiynrr.html

Ruby: resp.code.to_i
来源：http://dali.gaohongyu789.top/Article/details/gthawfjyqc.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtbmmkwzeo.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtxptghfuf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gttclpplov.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtoahzazjm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtslahqtat.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtpmvsawdq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gthqmlblyn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtikvtmskn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtlmosizpx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtqpsiadgq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbrrgsxxp.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gtfgmkkxum.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtyzgxxpdg.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtjwwelwth.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtagkeubsb.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gtrtwpoasi.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtbzgjdpky.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtwstdnwxb.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtwafdjisv.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gtqdsphyvp.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtnpjqftod.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtokpvfbfn.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtscmpawpn.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtoxrebnbn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtuxhiqrjv.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtrleyobkx.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtuefnbgal.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtwcxfhzxm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtdtxdorea.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtjmttvkca.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtzelsuxlk.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gtgsvkiynl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gtkcaegynm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtnnkshkby.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtrqlatxzg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtzjdnujwn.html


<!-- 参考信息 -->