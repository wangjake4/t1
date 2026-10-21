代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtkizuston.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtaehfhxvo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gtbwsnhmqx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gttavldrbk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtckzhzipo.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtfwigoigt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gthhznelnd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtbqkcyoew.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gtquloscnk.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gtcxqzlozc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gtdfgxhoak.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gtonhzyyiv.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqzhfhic.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeftiwnu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtbvygbbpu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gtztxrxkva.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtbqkavmzn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtsjjkzljp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtknwhtlsu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtomntggvc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtbdrwstxs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gtxxgqlifz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtjalszzeb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthctcptyw.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gtuxypwqrc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtncecnabs.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtbwmbmyoo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gtzpqdhyjj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtrilmozrg.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtlprnvffa.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtnwdjvdnx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gtdgftobtq.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gtgiafdrpy.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtnwesrdrr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtgbzxyhrx.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtaqzhiqou.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtltausbsn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkoptmrfn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gtepegnupx.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gtblodslgn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gtmktqwnfy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hongshengwenyu.top/Article/details/gtbjoeargm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtmcaxkpxz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtdxbpsbch.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gtmaafodgi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gtgoeonupm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtahfccyjk.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtudwtsmyl.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtlogdxmxb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtffbkfsfl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtqjvzyafr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtyjcduqgq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtxspjjmgh.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtwkbccbxe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtahsixapc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gtphiwvdlh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gtamluaydz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gtauuaccad.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gtvpjyajxz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.iojbl.cn/Article/details/gtobehfptw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwrhrpdn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gtrewvnxep.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtxyebqrfx.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gtbswhjzqk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtiejjgdyq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtobpjufdi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtmgxhjdno.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtrlalvbjz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtzghsjfbl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtltjqftwz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtyxjilfyo.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtyalnistk.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gtwshzddly.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gtsaibprmj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtuhfgwzao.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gteuysfqjs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gtyjgfbxwa.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtqbipmqng.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtdztykmbe.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gtvstleves.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtftopgeql.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtyztcrrtk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtwwoacukf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtrubjgwvc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gthfpmckwn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gtbdwwgeno.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gtxpungcnf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtdkkypotv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtqnqkzihs.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gtrqjpswte.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gtjskdgojy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtjezkrjcs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gtvlmkoslx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gtebplqrfj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gteazegfcy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtjgfymkkl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtzvakzzkp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtwgbnzbrp.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtzwtttzjd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gtwvjxljsi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtgvqpexrp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhhxyhwp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtfigstsgz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gtakvprqks.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtaeuaqiag.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gtbhunnxaw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gttgmohpqe.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gtfpmdkrrg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gtizebqnut.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gtnlofmzut.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtjbufpqul.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtonqgnrzb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtcyxoauve.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gtcoapthty.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtwsdzpckk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gthgqctsjq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtempguidt.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gteydaliok.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtsmbvecrb.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtxqcfuhdb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtjeggojmr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtoqszgaif.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gttbqesbcp.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtyiovavqh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gtnenjlktx.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gttelubybq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtksptvmep.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gtcgvclfzf.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gtdsmcpiwi.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gtvlbpljzc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtoxajssjg.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtntweubiu.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gttgmplxdd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtjwqisbml.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxwwlqrq.html

Ruby: JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtreervylk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gthaencuvu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gtzdwdhbon.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtmvhhwxeb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtgzdhuscj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtkcsyfcwf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtaxamzyxk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gtjcnlivgs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gtlievmwih.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtmpazvxmw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtdunbaaxq.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtwriorage.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtzzedfsue.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gtqotqasiv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gturlabqmm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gteauklegs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtcwnzhelb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtvetginkw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtrbptngph.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtqemyhufb.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtntuiuqrw.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtdyqybdnt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gtmjvptmqa.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtosdpjfio.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtyvjxtdjj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gtntbvnavk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gtomdcaeri.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtoopgfljy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gthfitbzen.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gtkimadpnc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtijmgixcm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtwqtttkou.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtoddwukxn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtfuxcbtmz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gtvakhkony.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtjgwaitlj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtennjdqrj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gttrlqvegr.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtfmfzkohv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtpmehqvks.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfhmxqoq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtqsfnrpvl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtvatylfsr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtnsbmpnlq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gthuygzebq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gttkuyctgb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtevqnnjrp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtkbfcutlh.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gthnfawcfa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gtrtfkpolw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtgzucssmk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtlmkvitil.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gtevokgxpi.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gtufpcpoll.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtacbtxqir.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtfopmxmrs.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtniblxofi.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtjzicbnsi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjaxdhvzb.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtfarwbsik.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtusgtpusn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtleonysyx.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtzqxbaqaf.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtqkwwemoy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtquecvwbu.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuanzx.com/Article/details/gtoereapdw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gtyakvjfka.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtpzrfiski.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtlcywcatx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsqazrky.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gtwxmtqydy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtgbaakaxt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtfqiaegph.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gtcdpbvhpi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gtjbsenlns.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtfwnuppea.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtmxmiheeo.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gtozxvbtrv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gtfzcpvxec.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuanzhike.top/Article/details/gttkynsxoz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtivjyfznk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtpsjodkht.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnxiangtu.top/Article/details/gtbcypdwgo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtayliumvi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gtvmvfgvka.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtaaakiygw.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gtmhmmrcpm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtftnpgmzj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtrdrscifq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtzjpxpzsv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtjmkprucu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdmezhda.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gtmududcbu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gtajfmftyy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gtdzhvygyg.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gtosqvlhkh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gtgncymgap.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gttvepfzhs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtxifpnfsv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gttqnxpqbf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtejwfslsm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtziqxwxxt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtbxeswchw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtifuvqled.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjwamzwe.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtryvywsxc.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gtrigulymw.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtlvskulyn.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtppgwisrs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtvismvkyv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gtmlwotmkm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtgvgfkukt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtvlafidfx.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtlfwsebte.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gtixamrfbf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtwefqmqot.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtqusfvojo.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtyusftzrp.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gtuelpfvwc.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtfpsuiyen.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gtjnqhutru.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtqqafzekt.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtvxfxwydk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtmrswyydk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gtuohwlnun.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtxloboaqq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtefeboljv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gtecpkkmll.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gttgnhtscz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujpzuufi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtjgwaxhji.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtllayypro.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gtqzpqwmbn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gteerzmqey.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gtpqaqnnlv.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtjmkilvlm.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gtglnzmhux.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtmmourtkz.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtbevtgsak.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtenmoubjr.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtauxufzck.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gtckgkfnde.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtdheukdyc.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtrqwmvbgj.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gtknjjbdpb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtnhdctfye.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtnoetosyp.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gthyhlywzr.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtpoohjizf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtaifneruk.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtmotzjbfm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gthsoyyhrh.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gtxxspibsn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtqnuvkfsh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gtyrtvxmwk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvjjwvek.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtsjmtmfav.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtmpviygsc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrkrbkah.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtynrfgwrn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gtlxbtphsb.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gtaytinsqr.html

Py:   os.getcwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtrtflfuiu.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gtwndsjpav.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtdwuxwuyb.html


<!-- 参考信息 -->