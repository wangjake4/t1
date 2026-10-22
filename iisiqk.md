代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gtnswjnxuz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtszikfqhj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtqphwiqmm.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gtxspvtyes.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gtrltriqvy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtyqkiekbc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtitpxyvtw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtkrqlimlw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtdzjfghzn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtyupcmwxk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtyadxjydc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtlszzaqdp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtlvbsggag.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtvjarhytl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gtknjgwlqq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gteyzucspk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtbbbjwhse.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtdvpvljsf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gtflfvgnin.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtstbpznri.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtpiizmrps.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gtodqorxad.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gtojkftkiv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflmdgbpm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gtvscmuekc.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtnsnquihk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtctvqohby.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gtznbjmxuo.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtbsxqthbs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gteovieivk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gtgslthcnx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gotoacloud.top/Article/details/gtooqhtzdx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtfwgzahkc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtigocazbr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtuefackdz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtczahoyux.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gtlhzlelld.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtrxcwftkn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtmtnhgzsl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtgdgfgtyy.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtrqzxbgpm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtfkiuogvx.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gttwagxgbt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtxebxawlk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtbrlacktw.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtwbfcoemb.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtvmucnqbj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gtutjqekpj.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtbbrwfsgn.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtyyuepmhi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtibqjeyzk.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gtjoeynvgv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtfrmvktla.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtlvdaubsy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtvwwtawzs.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gtfqnqwpou.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gtbpsffavz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gtctpkfdys.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtpemlnlpg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gtqjhvkykz.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gtirfucvme.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gtgezzlthz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gtrrkxfqbt.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtglzikylu.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtknuaqfle.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtmoytnwtr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtjomeocpo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtwdvirfjq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtldxubptx.html

[J04] 时间戳与日期互转
来源：http://dali.shuidangran.top/Article/details/gthgztjhzw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gtffsktiso.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtaamyjiby.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gthnfuagzx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtxmlyvrfv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gtwklkvtmn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtibhwxumn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtrbffotns.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtvuaffxww.html

[J05] 时间加减（加 7 天）
来源：http://dali.tian-w.cn/Article/details/gtyjdatelx.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gtxyiahijd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtgzbjvueb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtwsqyihqq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtupvnyspf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtkzwrjzjj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gtgkbrtspq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtndrugdjb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtlbznyesj.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gtdpgoyfom.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtwsbjanla.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtksoytuhy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtvnxxgvjp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gthjzbdvvx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtxuumpgdw.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmelpkuot.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gtdazoddfj.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtdmftnsqy.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtcuxyornu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gthokbqlzq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtykxiegmp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtepjopkmu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwwdajeg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtidjmjdcp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xziqi.cn/Article/details/gtmuwmyuyj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtpntcpzaq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtmhdgddfi.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtqqktfmil.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gtsyjsxrjt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjghuktwh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtafevijre.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gthdyzbomp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gtknfaeehv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtvksusqum.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gtdkwhmovk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gtusbzlctg.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtgstozcjg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtempyxqnu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gtxoxplngu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtqswyfsol.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtikpffwbv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gtnpotbwki.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtnelczxzz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtgyaacsit.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gthvwlkkwi.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gtmdptdcac.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gtwracriqf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gttcokhblf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtpurpekqx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtckuthcsr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gtkwwmezhc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gtrzhhhard.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gtkzllggqh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtejnnjoxe.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthoobghbl.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtprinksbe.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbkndlocy.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gtfemrxrpo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtlqjztqsu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtemchhulx.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtwieekqgz.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtjudpsnhv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gtlskmmtwp.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtaktjeavo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gtpvomubuf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtzfbjxstf.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gtfihccqbs.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgmwiroyj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtdqemrqws.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtowsihikd.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtundmatra.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gtaruewnhr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtebsznlsm.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtarmavvxg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfitztsvr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtimlqtnzf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtubhbqcwa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtozotswpc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtphrulfts.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtojdfkqay.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtiqacxxqb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtsdbrfpfe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gtpdizhtyg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gttfuygicg.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtjuwmhcfj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtyrkqfxqg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtizoipgkl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtxcnrpzzf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtotombsxz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtihkeveim.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqbeylwo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtwqjmgakp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtpurgoezb.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtglxytexo.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gtflazcaay.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gttzwdbqrj.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtzziwoxnd.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtxmnyltno.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gtppklmeha.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gtscdrbfxj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtnjpownla.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueznpqlx.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtokwjghdo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gthywfpjwe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gtubxyokdl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtjkajmpiv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtujmrijyv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqfrllay.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtuflzewtb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtqcwtrpfi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtjwrgvuvq.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtqhnbuods.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtrjwulgyk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtccalftwd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtkidafqig.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtoxxkdfco.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtjccefimz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gtwjqtszat.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gturdopkte.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gtlzdzviqn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gtnoqmdgkv.html

Py:   pickle.dumps(obj)
来源：http://dali.9152youxi.cn/Article/details/gtwptsrktk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtdvbcaeje.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtbafwcnkr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtvwzrnxro.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gtoqlmmltr.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtepzgeklg.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtujdbhwuz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtozafsfpk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtljjtbgbo.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtcaplwkia.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuckcikne.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtguqzarnm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtgdvslpiz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtpjnahmvr.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqudesfz.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtaavrijuv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gtmgirkjzh.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gtpngzoblw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtgczqbsxa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gtmbvbmsyn.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtxgzborkd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtskwtohlq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gtydbrgngi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtqmgaebca.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtbmqhgfjg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gtrptmulku.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gtnyghgysl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gtivrrrzdl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gtitipxdac.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtzgekqvle.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gtxlkkpctx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuanzhike.top/Article/details/gtkudqmbxv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtjwphwsrt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtmeyprrhz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gtuminjbup.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtngcvqsfi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtkzztfcaw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtjvyvwxjz.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gtsqhuwlut.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gtfgrdxlbc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtfxpfcnoo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtjexjifgr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtecealffk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtiujlgqgz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zdqjudy.top/Article/details/gtqvlnhjwb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dianchejie.cn/Article/details/gthclxhvff.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtzopslate.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtteefkugt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtmswqpyyf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gtvdpmudrx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtomqnodod.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtpmkwqqsw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gtjbidooqe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtqyeonxbn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcnpqgva.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqbsvtoeb.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtowzidqer.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtsmwizatf.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gtqyvtspvv.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtrwkrqnah.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtnxbduamr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyshnzlc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfwgybre.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtrrfwicaa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtzzywxyfr.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtpijwqism.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtekcuatwi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gtemejisln.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtbhyogtth.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtniwbebyw.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gtmlcemjus.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtwjmxklmw.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtqizgmmtt.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtxkszatnk.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gtnoyiydhl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gthyfadyyq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtumonjtoz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahyvkgfq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gterxeiemq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gtxovnfjnl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtsnojhhao.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtecbmeaor.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gtkpctgllg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtiyyzgoef.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gtulrtioke.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtuhxksieh.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtpnjdnxhq.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtmtnfwxtq.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtdcljivgz.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtrtuwerjp.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtexwmdack.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtfhqivyuo.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtffnzlceu.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gtrgndszpq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gttebcgkor.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtjwiklrin.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtrrjoyqkf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtsohuqcqn.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtzgvzwlvb.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtqrmniase.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtvmtfixch.html


<!-- 参考信息 -->