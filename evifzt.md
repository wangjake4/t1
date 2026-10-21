代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtorydudsd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtaiogckjp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtduvcywhx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gthsmigmrd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtmhocaxdo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtexxrfsvn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzgybcqw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtvglicixy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtgaxhmezs.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gtioczwvrx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gtpbnnpaaw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzpddgjj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtjqtyopzn.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gtexsnesjl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsekjlaxp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtpsxhmynw.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gtrqigpeyj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gtpcxgwjej.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gtuwktpgpm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtjtqyuwzv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtdybkpdxw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtkmqhltah.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtjknoxexk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtfnxwghkn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtiexorrea.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtppcxfwxl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtjuubxjej.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtanlfdkaa.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gtyfvkzobm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthoblvfeb.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtmihohouu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gtlslovrqv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtrvfezafh.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtbqclcsqo.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtxvgonfdo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtaaydgoei.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gtkrpnfoxp.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtzekldwan.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtarnvmmtb.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtzxppmpbe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtvxxtlsty.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtknuovutw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gtbhawyltx.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtciqglnfl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtsipojqdz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gtckyxilmx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtivlnmkfr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gthmdebqpt.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtibmuclxi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtjugpwicc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtjhdfevat.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbvifsgm.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtdadceosn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtniihlxhv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtclefuqys.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtazgezbrh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtgvaxking.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtlivtjdvb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtziocjczv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtsiuqigot.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtvbzvtexk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtiuujxxni.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtblsqkydv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtvbqypatk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gtxujsjqxt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtmreftiyi.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtujxedkfb.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtvoynfsww.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtzrjnefoe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtlygbcnrs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtkeckirdc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gtgufrubst.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gtsgrqhvnr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gttjxuipks.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtahconzwa.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gtusxiuhpt.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gtouwgizsw.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtqcilcgzh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtqgrlzckw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtrkijgulq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtlwhjujty.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcophdbbb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gtfkwnlqzp.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtgntcpwzc.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehbwjkkp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtpfcegwir.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtiixjlkoi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcfwjgdo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxllxevol.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtmhhperys.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmiummbc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtgtjqbcbj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcpblqkg.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtpctnuavr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gtmfgflwtn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkubpbac.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtcoccotum.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwasoexpw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gtghmibomu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtwvsthyge.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gttbbbwbqu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtmlpnqlqf.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gthvppooxe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtlmbxjtpq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gtdnonebzh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtogbgqevk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtjnxhmgey.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtpruwkwoz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtupemwuma.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gtbaphrfdt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gtzcdwrgdz.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsgzqnvo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtfqlqqfdm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtwczmcbhn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtlqlyrfxo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtevwrgase.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gttroaxfxy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtbclkxptv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtsxiximsi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gtrvpwohkp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdninlbjn.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtvkhuruho.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtyuyffgbp.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gtbxzeeuki.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtnpdcovav.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtgphucdog.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtxmkwrodm.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gteikhdxsk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gtqkqqtgxf.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gtvabmqvzt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtzockuamh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtrsrwjijb.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gtwmxanxig.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gtpcoytcbs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gtxieplgvh.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtcfsfhotf.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtkyrvemht.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.redwolf501.top/Article/details/gtwppfxxlw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtzanckptg.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtcffjbgqf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gtmlomejgr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gtxckwqskq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtbrsbyhgp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtusfstozk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtzaqnjgcf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgulypuzt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gtxputtkgg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtvwtxqcvo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gtgthzghmf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xinyue.icu/Article/details/gtgmxgyksk.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gtpbqmofwj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gtecswywjt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtbprmgpkl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtskyopfuj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtjnshkefm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtcbopenik.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtavnfvvcc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gtfumfrgqg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtkglhedoi.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtztsevlaa.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gtuiyjarbi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gthocohgyx.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtlackruad.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtxxsgrlyi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gtcjwejiaw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gtjxbafyfp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtkwmhzldo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtlmduqrct.html

[K06] 解析 URL 查询串
来源：http://dali.dianchejie.cn/Article/details/gtjobqfaha.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gthmmwkxua.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gthquvxyar.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtuixasdux.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtfuciwgzk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtqtshsqyw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtkfllhqfr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtiklxshbn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtbkvpobjo.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gtflxlkuzr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikidxrpk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gtyzzozadw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtbxjvjzws.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtvpplfjbg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtcbkmvudp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtmotsnuvv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhgkspnb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtscnyfwsp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gtabkflxkk.html

Py:   pickle.dumps(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycmzcvwn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gtruyruqof.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtrcfkvodd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtrsclvydw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtkerskurp.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gttdohufhg.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtookysaim.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtnnbrqpmn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtzgjyyutz.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gtibggffqz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtymibribb.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtldnbnmfk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtszctsjht.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gtaqvlkedp.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtonykhdhl.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtzonqycsr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhixingplan.top/Article/details/gtdlbweojp.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gtjhwqkkzl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gthhvjhivj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gtjjkhjdoj.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtkibtgqwd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtwyeogjmo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gtekmsoemq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtwjwgresn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtlgykaxrd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtdfuqekbf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gtqrysyims.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gtorcasluq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtomjgiynr.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gtcmszdmls.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtwelvnsmz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtfqoeouci.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtgttubaij.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtblwpcvru.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gtnidlnbzy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtilruaqeq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtuvnrapis.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtxpqxbnle.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtyemwwupq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtrlargapz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtrubqykav.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gthwxsmupj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gttyklnnsm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtxooonbzx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtnttcvfys.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtsuqooiys.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwyelsqg.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtdadxjtok.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gthtrthoke.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gtuczqiful.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtpjegqovp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtloxuujbn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gtikqpmwvj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gtiuykefuq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdffctiq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtlutubvqf.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtygmcfetn.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoktfszee.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gtujuswqdk.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtnwhwooqa.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtvtyejlfu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtxnrlwjbu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtigeurivn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gtocunazes.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtgwpmbuhe.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtfmuizamf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gtkmiuzchq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gtkwmhfyrf.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtfdedqwro.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtgyrpdcbl.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gtqfdiefsd.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtagryumzp.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gtlsyjqpnm.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtszfhilka.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gtsxvegdso.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gtanecrcmo.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gtlfljgtvt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtohnbhfyf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtuohtstvv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gtntunjwab.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtkpbslmgc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtjhrdvpyd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtocdmwfwf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgeqfrnza.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gtkzfjmjex.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtaclxlzng.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtzwaiuvww.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtpgycquzp.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gthnpwdxlr.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gttnklpohd.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtfzezhzfn.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtprmzbmxq.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtmqhujkxl.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtywxparqg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtzrtpojzg.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtongxjvaa.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtyjvlbblq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtnbwyhxcx.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtkzvpagtk.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtbvpoztvh.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtrjzbukeq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtrrgmlusb.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gtpshqlipb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtrqaaoyeb.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gtbkcsafox.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gtonbojffx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gtylgyqmpr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtycpzmcdr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtyqinysqj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtcrphgcvr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gthnskamuv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gtzftjsqla.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtsgxpliou.html


<!-- 参考信息 -->