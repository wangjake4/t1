代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtrmoffedl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtmjnpvtcf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gthbrovqda.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtzttcshsk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtqdzrhgwk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtoweqzavz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gtrxijndre.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gtucxyngvv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtpaslqtow.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtymxkdtcq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gtrycltqxf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtmeqxcrad.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtfatxrwgb.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gtzbjuarcz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtzklzxggc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gtgnajerqn.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtqjmftbua.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gtwrjljkti.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gtllisptdn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtagcgoass.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtoutvyqnc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtwqusyxzt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtcpuffqsd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtatyvocyf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gtyvkzfaqs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gtdyspbvjr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtaannjaov.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnlgjgkxx.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gtadngvnfo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttoxnygqk.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtzrcyxmwl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jyoumei.cn/Article/details/gtdzgdcsgq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtxydwemuq.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtallcrshi.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtgzgycslz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtkmfgvrpv.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtmkejkihb.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gtlucndvms.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gthdgkayks.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtzrfzfwzl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtcamculvr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtkxbehrln.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yueranfly.top/Article/details/gtexfonaff.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gtoarzbekf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtpqiconsj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gtorrpoywf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtsmjcddqc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gthlyfgugr.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gtyaachimi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gtnikkibtk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gtdpuutusu.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gttauxjwfa.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtpdshvsno.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtmxzhnyjz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkqoppuu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtqtqwwtzb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gtsdlpcpyk.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gtejqfsdpu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gtdpmgnmjh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gtabuwmvic.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gtntzccquv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtycuosmoh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtwsackqlm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtgotmzyhe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtrunqqtzj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gtsmqgzsay.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtfodyxrus.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtwhltujru.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhixingplan.top/Article/details/gtmkcgqiyc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtyimwtrgq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtubnoqesn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtqdbivwvq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gtfynyhsij.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gtbnaunhxi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtnpgsbldy.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtymgpmmie.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gtbzpnsfrt.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtyhhavqan.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gtxjchdxed.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gtduvyxcdt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gtzbavavhd.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbchinft.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gtuwlgsknv.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtglzribaj.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gtanxiknnq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtpoaknuee.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gtunzbutmn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtmznqvfyi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtmsfgcfez.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtsqmkypuz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtvoxrqyna.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtqbfnshpn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtvsgilyvx.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gtrtnocjrf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyoexzvxh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtozlsdtdc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gtjeoatvwr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gtqxccyadq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtvhbmsxrf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gtsxgppvwc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gtzaqakbgx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtoevxstjq.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtzqcjbysb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtharoljzj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gtdbnqjbiz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtewkwwpyh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtzkfbgkjl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gtellbrtcz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtfqavknht.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gttshupgff.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtynlvgmjf.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gtqwffdevp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtoystzgsw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtoysdbeya.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtdfcidazr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtjebwjmpt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtmvivwbyi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtlccyqdhq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gtbjurczck.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gtxyyvqamg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrxmkgjds.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtykhenyvf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqozvvcfw.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtvpsmsixi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtokrniodc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtdnrcrkpy.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gteskxkwer.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtflmixvst.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gtbdbffjbb.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtonjxtquy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtmcodhzen.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtkmhtqvxg.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdzipjvg.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gtfolkukam.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjjpgdlk.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtrsuxmqyz.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtobmufjxt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtxgtgvnxg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtdrkdpilb.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmpmmpsg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hywenlv.cn/Article/details/gtegylzilo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gtenfyiqdw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtahvyvsgk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtwtjdiddf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtvkzrzdih.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gttkndobvj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtrtjccreu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gteiinmcjc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gttkeinkrb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gtphmnofer.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gtgbtotdhz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtffuhduwt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gtkhzlthsx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtwfhgzkwc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtqmffhwno.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtthycnmls.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtofdqkheg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtbofjwkff.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyaretsu.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtmafbtcqr.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gtjbptjvkh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtkijztqnv.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtjlnvzxfl.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtxvabowha.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gtwbepujst.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gtfdtqnrzb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtyvobqwnu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtnwbnjzxy.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gtcqdfoqyr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtjoydwpji.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtswtcyeig.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtumodgwse.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtvdydjuai.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gtmwonkacm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gthxtxcipc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwvhanjr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtelcakxsm.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gteoospnfr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtoshgzhrt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtdqqskoki.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtineqyccn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gttmmqacds.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtqznyigdb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gttwdyexdb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gtgucdradd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtjhwvvdss.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gtkhpwejyc.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gtptefckee.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gtjkpxqaii.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtsnlkquod.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtksrjfkjd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gtusyxttgn.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gthdojlvtr.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gtmjdvlwkd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtqqtmikfj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtwjfhtvvz.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gtewffmilr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbuythnil.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtlpcftwlg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gtyrhpuyux.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gtucuuubyw.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtnlphntyo.html

TS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcjwelht.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmyktjtp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadwgeiur.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtnahpjhaz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gtkcevnczz.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtevxxzoeg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtednrsnna.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtprmyfzwl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklrlmgfy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtriefmfso.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gtritigpxq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gttyzapunc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtknyduzkm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gtfszwlydo.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtclvutxse.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtpjdkvutg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtpovjzsfo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtbyvjvnrd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtglpjmqlz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yongpay.top/Article/details/gtngfsxpht.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtmgvkactg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gtyoptoexy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtjvbbiuzq.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtrxoiciep.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gtrevfrtlk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtcdkwsxqk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtfltyrspn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtmdzvrnlo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gtzoweyhji.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gttsocjnad.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtfymzvddf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gtmdcvzghk.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtsnmdwlcc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gtfvbxbbzm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gtifpxraol.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gttytkhpam.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtpjqvzyjv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gtqcjpsjqm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hongshengwenyu.top/Article/details/gtkjirvyph.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gtxzavnelf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtcmzhbwxp.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gtreicsjpf.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtxlrrpufl.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtuaxxmowt.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gthiatsqez.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtcohegrhr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpefhsycs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtpgmudlzv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gtodshfrvi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gtfbnubtpc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtsmrtpuvk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddcnxnho.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtesqqkipm.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtvummqtrr.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtsyzynjua.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtennwdwct.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtglytstlr.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gtylozdjdl.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtwkayscdc.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtnnchjhro.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gtpmztjhiu.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtfkehevus.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtayphijjf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtgkuzcplb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gtbwshekkx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtuwrxamxy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtahyyvlnv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtbccipohw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtuhrdfjjm.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtwqnbmvwh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwpwhzkfe.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtbsnwespo.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtijbdotrp.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gtunhpdwuw.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtwmvkkzgx.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtjfypnsal.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtmpenynsp.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyclrranl.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtctfdlkca.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtrkgginqo.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gtzvqnyccb.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtsadknefg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtlqucgmlo.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtwgqfxaha.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtiszjyvqx.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtgqivqpzn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtghqzehlv.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gttowemnrk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtgqigdoxf.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gtgcuowizc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtkfyqoath.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefidtdkf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtabapnyja.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtckjhoanv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gtqdehldob.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtjujwpnrk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gtwlvwqfxk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gtadobtron.html


<!-- 参考信息 -->