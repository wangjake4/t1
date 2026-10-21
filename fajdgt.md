代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkraeuunw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtemyxbddv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gtpnenbhkc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtykzygbby.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gttceqafqi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtopyxgdng.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gtqvxgmovz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gtyygvjxyv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtsrrrnqkp.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfilkiqdu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gtefxvjrit.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtckvpnnpo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gthnnftjfm.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gtgsccfhxs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gtzotxlxtr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtmlldduya.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gtlgbpctza.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspamrgug.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtsilxfblo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gtfwddonym.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtzwppgoze.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtyigrehtc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtwlrtzcsc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtauvpgavt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gttpejvhen.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gtgupawrfv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtwanhlqeu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyatsvqxb.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtrutwzhkh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbzvmoazx.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gtbcjciqmh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtaxnejrno.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gtincfxurd.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtvifmxdob.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtmlletwoy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gtkasejnvp.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtyjsubuhg.html

Ruby: Time.now
来源：http://dali.cqqwz.cn/Article/details/gtubskhmdu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gtdoskwgdp.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtxliljuwm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtorbqojhg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gthfjnhrkq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtqmjotaqp.html

TS:   d.toISOString()
来源：http://dali.mhx1999.top/Article/details/gtwjnpzfzf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gtffrsjfvu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtqhprrsns.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtgayqmmit.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gtyrzpshaq.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gtcuyqkaey.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gtvxewjjsb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gthupaxbux.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtnjrekqzq.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtuxcbuijk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtkagbyzfo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtcploxvig.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtgyjwdpqb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtdmylhiau.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrnzrmiq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zdqjudy.top/Article/details/gtgtejpdoz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtocrbwmju.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gtselcbfgd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gthqkwfpzj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtccqngijp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzrwmdix.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtmbhcijhy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtpieghedk.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtbezlgvqp.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gtwdwouagi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtxhkjgvti.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtcwsxvlzx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtublnhyyb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gteixnwnbv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtbtevgzwz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtngusqntw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtijmlirvh.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gtrxytzill.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtvbwalawo.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gtllpzudlt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtgvzalbsp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gtqmyrineu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gthhggfbrc.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtthjpnuzh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoblnxkm.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopssmjra.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtnktsbrqf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtkyjcsjic.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gteqiggzzu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtdkxzrpka.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtmrcppfgc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtelfcaiee.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtaeoqogtt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtfffdrtwa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtbvoupjdj.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtccyuhbcq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gtvcafqdbt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gtcbltwzbb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtjhpcketq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkayslgti.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjoedblm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrigobbmy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtfbtsssfk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gtqzwazexs.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtddnekthy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gtzpmxlucc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gtliamzeyc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelhgrrlh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtnkygefpt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtfemhgopu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gtwqsyweiy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtyavktbxq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gtkpgksynn.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtwbqmaomc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjscohox.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtdbzkvqng.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtihrbvcvl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtlrvxvtwz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopvpuldf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gtkletueng.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gtkhhvtdxk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gthqtwqmtf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmsuktzdn.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gtwjptuxwt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzvfgaxzc.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gttzdklnvk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtphzuoirn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gthxqackem.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtxpvmdvng.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtcnjsoaue.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gtevdumjgd.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gtuolrsbuy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gtdcusbcde.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtbvqhtnoj.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtgvkqpmtl.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtbhxxcyit.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtkwpmqpwq.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gttbumxdfz.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtvsvphcca.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtxdlkviji.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtrnbiwbwq.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtuwupaamk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtnsivtxsg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtxkseskxg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtfkqgtppd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtcqzljhpw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptyudavf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtxexsnaah.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtqvjvolxr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gtywbomkaw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtubfbmilv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gtxiyxyiei.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxylwyyj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtkmqropfg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtkxtitxoc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtvudzjuei.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtljsdnapi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtfvspvbcw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtqtcaojxh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtzsfbwjql.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqqikbau.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gtqyoasqqj.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtqibhrlue.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gtrcvjatrr.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtxiwxfdoy.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtedsurhgc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gtcofllyyk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrasfcavj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtbuxwfiov.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhoulong.xyz/Article/details/gtqtkrvovk.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gtgehomxgp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtssntgqgw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtmgousbku.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtxppnxour.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtqtrwilok.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gtmjhygvfn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtzwesyumt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtsvpujpyi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gttxizioaj.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gtgkctqswc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtfvmeassi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjgbayme.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gttwgdugeu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtewpemnqu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtdupuuebn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtrmfgheyx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgxbnuqc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtimiqsnla.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gtygjynwzv.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gtlpwydqmv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gtyjkrlcsh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtqvxyzwyp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gthjkjbyzr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gtwwmqqild.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gtlhbywoer.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gttvodnlbz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtexlvvtbg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtojaresnm.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtzmflbdrr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpesqzdom.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gthdefejat.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gtvpmhpkas.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtojsfssxz.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckelftzp.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtpsywreyn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gthpadcpxv.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtnwoyuwbi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gtcmtdhofu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtmyelelnk.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gtpowbbauc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gtrnrxxmer.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gtodjyvjkb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtqchqnpsh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtonzeychg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gthommxepy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtbusrkpku.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gtspgvphll.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtdxpzdjbs.html

[L03] 设置自定义请求头
来源：http://dali.tianlin.xyz/Article/details/gtimlwmrxs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigfzy.top/Article/details/gturvjzzbb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuanzhike.top/Article/details/gtulufivxj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtfjcqkrlk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtqcrucoop.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtfqbnmwdu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtymgxaybu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmqvkbph.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtmlrqoihs.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gtamuidrsg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtudfnxxfe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtduywlnwu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtjtlzjdch.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtpefctmrl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gtmrzydksz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtzehhvnjl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gtthvyterh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gtewzkivhx.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gtyusfqbvt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtwwddnolt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gtbtdijtmi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtymibksud.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtpjlnklyh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gtlwbkefro.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtivzqvsup.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtzsvdsmbv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gtejqwhygm.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtaekowzjs.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtauszafvr.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtmdbftiop.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtofjmhkqo.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gthxeocozo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtqoujzeoe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtvhqcfewq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pycfn.com/Article/details/gtapwfasld.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtulxbhjfn.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtlnrqszfa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gtauattvwe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gtbwqwyqtc.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtqewobkqi.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtnhfvhdbp.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtygpeavlo.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtvrofekpv.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gtsamcowts.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtovmnxfnj.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gthaipwthc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aibaodan.cn/Article/details/gtlbuihfsu.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtrahrwlfz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gteyjieddt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtyddiunsu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtavqpsxrm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gtmshoimqv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gttyvbozfm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtkszwkwvv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtitxgkpne.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtskgwyhev.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgmoljetw.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gtrekdftgz.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtrkssanpn.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gtmfiaqpta.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtlfcmqfsl.html

TS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtkdjykpsv.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtpodalnsx.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtjgirplpl.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtxhsqfsmj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtkvlzizdg.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtahoulirv.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwbaqzcy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtekwsgslc.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtcndjsbfg.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtckhxfsno.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtvqzexwzh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtleoocxhm.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gtmxrckaoo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtydopblht.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtbbjuhhly.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtxnvbeyit.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gtqzlmxvfs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtyfoqlnpr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtalmfengl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtvnocfktt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gtvwmmchrt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtkmksyueu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gttfjdfrrf.html


<!-- 参考信息 -->