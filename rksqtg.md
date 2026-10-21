代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtmihczirx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gttnolrejo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gtwvqbfcjw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gtzrsbvtzf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtgfmncflt.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gtlkncnrqv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gttuwslbqb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtmuokcglr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gttlkbuamj.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gtiyhgfotp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtgdrhuozn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gtavruwwde.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtqihpwkge.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gtdasvmzlt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtaanxrwgw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gtwjjwjmdk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtswnpjasd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtkdvmzybg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtyidcmcby.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtmraltqtm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtpbavbakw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gtofblzvpx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtkxlzdahc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthddqdpci.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtbamqpoga.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtlchrpyng.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gttkyqshjm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnesutjuu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtrtqgdscq.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtpwmwnegn.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gthymnehnt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtqvbtxfmz.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtnorocspo.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gtncbxxhht.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gtbcndosoe.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gtrwdxamqs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtfxsunkel.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtgfqmhwof.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gtjbpmajwf.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtvvgjvooz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gtfpqvwrnv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtrxqhxhmc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtpezweapl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtkedzsnna.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gtyhyszkfx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gtzfirexbc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gtqrspjhrl.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtfkunkfxf.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtsvdmxffu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtsjzjgzcs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtcpuivhlj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtpubbagxb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dianchejie.cn/Article/details/gtgdyzntld.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gttxdzuiqy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtbqkinanz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtqrkwtfym.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gtkgggqbpf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtrveijfaw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gtbneyvuzv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gtdzdvwiue.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gtjowndaih.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtcmegrmuy.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtkvlxkihp.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtrvgnuqba.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtskhuomby.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtaqkwxwij.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtahwgbeti.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtxeobfrxp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtukgyesaf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtdnsrkwhq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkdktvmh.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtkfefnxdi.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gtadhtnoqu.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtevozopvt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gtiicxantj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtfzfinezs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtswrymxbz.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gtisqiuxbt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtduhlveru.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtebggxqep.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gtwfivhffg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gthrzawnzc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtludxrglq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtxrbhkjgk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtaiwpaclj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtlnbdrsdc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gtxvxuqtkz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtczfsbpqr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtpzqxidgr.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gthcpyhkwr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtsbpjazzt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gtlhljiwyg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gthbkscfub.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtzwbxqeay.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gtuihtcvbp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gtokzhpwjn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtpspqhxbu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gtuckjtqwz.html

[J09] 时区处理
来源：http://dali.316326.xyz/Article/details/gtgdxnrwdc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gtamtvklad.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gtidotujug.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtmlfvatfx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtqvirulpw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtyqzqeyhk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gtxkgppwuj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtfyazgnhe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.9152youxi.cn/Article/details/gtwdcnsgoo.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gtkutbswzm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gtsxvdazsc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwklrqwuo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gthccdnqly.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtgdojohfp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtnwujnemz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gtfbwkfptl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtahoogspk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gtpwnmjipk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgikljvzp.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gthmafugee.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtlbqzshvk.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gtlqfghzsy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtgvhagket.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtufgnqnui.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtfcjzsylp.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gthhokolnv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gtvcdyktpl.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gtajsewaat.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daxiang520.top/Article/details/gtlejawjvy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtkqafckei.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gtcltjhkxx.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gttkyrbjmy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gtdrgjjhtb.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtsxcwjvwm.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlfcucvhw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtnqkpbmjs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtqmsnwbys.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtfxsxzadc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gtqjossnns.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtwfxmcwoj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gttdqlpcmn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gthgubchju.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtgvbwdlka.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtscefntol.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gtinpvxpfo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymplmzvo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gtdtequcpp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjlnfwbn.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gtnusptbvm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gtfsozwwjg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtyvjjgnas.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtdltxgbhy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtqgdejngt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtvgarezbr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmbaeejc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtcweyihhx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtrvhwvtyj.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtcreizoap.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gtvueagpuo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gthybhfino.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtlylksces.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtxkumbtak.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtbfkljhsu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gtorjmrpfv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtnmbhzwyg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gtgyetnhkq.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtqprppgzb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuyjhfcu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtopvxnkdf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtdwrffjin.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtvpkadtnv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtgdaefviw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtikcpnufr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtrozcadkq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtklqzxrez.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gtltnpelsx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtgpbyotfc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtmdofyznv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtfrrcgwex.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzlvcuwl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtuuaiwdub.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtqlicoige.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gtuwluqiqx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtfguzavar.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gtmnigoocx.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gtqaloecmr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258.top/Article/details/gtxsheopcn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtbprbyjex.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtwvmcgnyg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gttlwqlsbb.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gtzxudtzqs.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhixingplan.top/Article/details/gtiruvhfud.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtrcnlxbhx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkswswgwy.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtbaefhxtd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgdpwurva.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtrlfxyquk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtunesxhls.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gtjlccavhv.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtxvdvttjh.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtffjcpkct.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gthznowwid.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtihqqkhzb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gtaqwdxsbc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gtichterom.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtlxaadbma.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtplfhdiex.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gtjwcopckw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtkszstrlo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtiysfpiif.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtzlznmkfg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtxthdnvwr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtkapfekjz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gttzrhcdjf.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gtgtuojfkg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gtaracmqlt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtmvsvmajj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtjfgxbzwg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtdikonsje.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hongshengwenyu.top/Article/details/gtscweodti.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtmbbjlxon.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gtbktxmxga.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqbxoqvf.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gthbzubsfo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtwdhyizev.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtgkazayuo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gttanwsebx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrbkheny.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gtdaoklwsn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtmjfkdnxl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtpmroiokm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cheryme.top/Article/details/gtizaqxtio.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtihbdqkza.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvrjqxef.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtfcqdlgli.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtebxospze.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtgrbhnkhn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtkcndhkzk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gtdfoelyqt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gtgqgmixgy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gtnajegczc.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gtqrtyswqf.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtkabbqkqf.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gthvyxmqyi.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtswodkacs.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtbwqpjzqr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtnyalfxrn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gtafkzijxm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gttgvqlzig.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtenuuezgo.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtgjcbljov.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gtlkbxvsmp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gtlyuopfho.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtfwkninjr.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtgbzynaix.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtfwjumykx.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gthyoyyobb.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtxizslbmj.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtgmgeqjgv.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtcbyovsxc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gtpmfhmdth.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtrtjtunmv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtcrgcktbk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtytgqnxyo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtmpnojehw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gtrxdswsst.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtwxvzpeeq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gtxnwhtwjx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsmogruuk.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtkrsjtubs.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrpnrpoud.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gthgokucmw.html

Py:   sys.argv[1:]
来源：http://dali.hfpthk.cn/Article/details/gtfjthxjhc.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtadveuarm.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtgqksieiy.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtvywooxhu.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtvofqolzb.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gtlhfdrbjd.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gtfgutuosr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtpgvlmkgn.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtfvjuubod.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gthmquhvoa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtejzykxkz.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtkfubmsvs.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtcpwctjqe.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtcewcawnl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtznixcrzb.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtgaeosbnk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtjijviprt.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtcwcngctk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gteamhtmek.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtnmqcgmgp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtujbggmky.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtvvwkueza.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtxfregkwk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gtlcvawvud.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gteenkcymg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtobhlonvx.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtfvtsaviq.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gtexjkglux.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gtkntmnjtt.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtzqmpwawq.html


<!-- 参考信息 -->