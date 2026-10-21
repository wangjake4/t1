代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtbbyhwmkb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gtmznkycqo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtejbscvxr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtqvjvepbx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtvbnuvqlk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtefrnpipe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gtigatzkoh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtsxisetwr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtjikygebp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtgogpylib.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gtcvonfxxr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzvqqmxk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtqztdttxm.html

[I07] 忽略大小写与多行模式
来源：http://dali.jiagoushi.top/Article/details/gtimsviube.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gtsoxaeyxp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gttixhvtbs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gtmifbtaxn.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gtzudreyio.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtaeqkruoo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtrzrkngfc.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gtaqsvtkiw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gtwshhlmmd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gtegxabxki.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gtuoeprrin.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpnxaktd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtwijugaky.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtqieqkciu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtehgzfoil.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gtorpzimzw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtoloegjbw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtarusqdmi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtieekayjm.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtxtqsjkcc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtoghancrs.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gtceqkohji.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuviatez.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtwjkblvyv.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtqzddxpac.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gthvwgpdtf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gtgllamios.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtmpbwkgow.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gtmgvplrwr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtedaxfpkc.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gtuddbbltm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtvxigfnao.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtxgztshaa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtwqgmfhio.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtmcxnwctx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtvkuunnna.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtaiyntgaa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtvxhwxexa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdybbwfda.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gtnoiladjm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gthlvcosuz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtunsoyeua.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtbquabdxv.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoowxpeq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtlrygiiin.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtasexvmed.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtdtgujkle.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtqbtbbobh.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtkarfpgqd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gtpexaqgmd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gtvrkjumoq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtwwdiopxh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtgbzgytgm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtxvplmosf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtcmpyuszq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtsopkgkia.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtvclksscl.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtcefufnca.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gturnzkrcz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gtaeeiimgs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprwozxmd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtbkwpxgyf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtrhfmeykg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gtjlrrlhzb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtcaoetedo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gtaaqcveat.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqgdejyl.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtedmgwueh.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtbwioirms.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdxozylz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gtufqoldmr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtwuapmkle.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gtzhqlvbmf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtsxxqqsze.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gtqekndxve.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gtwooizmnh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtvbwfnxez.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtbsgslier.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gttcxzsett.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtcmavrqmr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtthcqfuzq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gtpqkkjnxa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtjvujsipc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtfklyhnik.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gtqpbmcsyv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gtquudbzli.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gtoggckwho.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gthdcdfatp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtboptnits.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gtwrpngnpx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtldpgheyf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gtuastrvip.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gtdqiaruyl.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gtuwehwwut.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gtrbcqxinw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gtffideaai.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtzzgfebam.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gthmtjcfxq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtkmonwyxs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtncawfwcv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gtauyttkyw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gthxnoxsar.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtzowuqiix.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gtduykerqp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gtigsejonj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtgrhvpxvk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtpzbybijl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtdwwsrb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtttmdoqdz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gtvqxejvyw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gtyiuboowd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtucnkevzm.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtrunpyufa.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtiehtprgv.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtzlbygvwn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtisdcrrcv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoclfhnm.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtnmttswki.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtuaianlne.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gtijpomkeq.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtsimwaeks.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtuhusxjja.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtubxrosnc.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gtytpsznys.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gtsarvszix.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gtozeutsne.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtcrcfnxib.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtoesunpky.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtxymfdzoj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtypvfrsot.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtzscxjwza.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzahddjds.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtjmqbuxys.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtfmsuffde.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtykhkoqwr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtsceeebqp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtfevpammv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gtlyolxxug.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gtjgbjpvop.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gtojrdqvkg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gtxhjzfomi.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gtxutbefqi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtpmctrbqa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtvwcouxjn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlqhamaj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtlztuayky.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtoygdmvjx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqoaazyk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gteokjciwx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtcbcnekwr.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtirrabslx.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gtifovcggn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gtgqlndgyo.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtldxoriqt.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtrdbvrvwd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtnicsrfxb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gtzxouoteq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtgfrgozdu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtrgucsvhg.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtfkepnrkk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtdrazirda.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtkwghxvrn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtpbtwycsi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtlbaeytqa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gtuhxgiomb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchpuamxx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtnnjwazbv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtprjryrzh.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gtjqgzomor.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtwdmovqkb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gtkvafgqro.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtgmwtkclk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtupilcjfp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtzlwztypk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtjmoguwmc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gtflvntflt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtgceulyaf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gtrctqdkug.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtpuoxxopo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gtxzlmaitg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtxfmyajdw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewmtrzxl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.9152youxi.cn/Article/details/gtpatvsqou.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gtazkwekbm.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtyducnnss.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtcsicmtxj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvuldsvkq.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gtvgiuukhi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtytqffhig.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjsaszsx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtuajhnayf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtzseriwqr.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtkqshydsn.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtyntnpsrp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gtpoaspndj.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gtlcbrlbeh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gtfjozbsef.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtptnzfuub.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtkpzgxjbq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtakkuunbg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gteekergfw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtvjlnfsja.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtlbgrjwks.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtzsiibdiq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtuyoquaxi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gthqaasqmy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtyqrjigif.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gtlpqckyvg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gtmimugkgg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gogol.net.cn/Article/details/gtpxoptfps.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtfiqroqzi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gttrjclyen.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gtrogefmhr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtnikgmrzl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtlnbcxoyy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtmwqsbfoo.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gtxzeknikw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gttuekwqep.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtkbpjqvvg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtprlsnuaz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtotkmfaed.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gtpklkdmwy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gtvqfsokfa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqazyyvko.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gtfhctdgxs.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtlywvhagd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gtimlnuuvb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gtempzusnz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtycjbmjye.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtuyegzaac.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzyenttr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtubbnzvgt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtmcgjchck.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtyfghakuy.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtehylndhp.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gtuvlzhndh.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gtvzpdmwdy.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtvuyhywzo.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtvqebcpnp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtbuoulfrs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtsemyplks.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gthgdhudll.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gtiichrjxr.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtzcaepbbd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gtpkasgacd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywlvewhy.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtwractipw.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnmswyek.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtqjuqshfa.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtwehspitw.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtuodryvwy.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtxridlhna.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtvqjumnxd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtctjzduto.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtbaklyngz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gttymoikwc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtrlndlegs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtqcdbgcfk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptoibkja.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gtgmtnpcww.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gtckhugncs.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrymgxoto.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqfwoddj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtrnmwcdkk.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtbqunqdhj.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtvjokiyab.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gtjotexsxa.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtphwfazux.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtklqvjtvw.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtvnounjcg.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtmvclbylz.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtmuzhrhby.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtaopwlmbm.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtvlznnmqk.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoudsvakr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtoremsjbx.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtwydrnibn.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtzojnsqdi.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtizgeexlp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtpisszdru.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gtowyqxupb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtjwlljsqp.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtfyvzmajt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtjzxxnagg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtcvuzsojo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtzbphyhod.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gttaqargzn.html


<!-- 参考信息 -->