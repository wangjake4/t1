代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtseihmdoa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcntfppe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjsfuhew.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gttzrdgjod.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtjuvbeevi.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gtlkhosvpe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gtbsoyqfbm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtuwdzknge.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcitjfmea.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gtwixjxkja.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gtqvzqykel.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gtvftfugwf.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gtwcgtbqgv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtvybtrssi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdwrckwh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gtyqakmrjq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtoutubuiw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtaemsgesx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gthwodufin.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gthgfmxsnl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gtxtuzzduu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gtwaamtabb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtdfykhudo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtorussdaz.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gteuglegmc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttivfwqoe.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtqwziyifs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gtndsuhhps.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtswnafjpl.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtzyfyfvtg.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtxeynvxae.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtjjjerwgy.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtxhajlolc.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gtklpsudng.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtnimhlnyd.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtfrqfsxdv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtdeabwuss.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtegealsig.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtrgzmasbp.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gtsxfgjbrj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gtyuydbjlh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gtabsdzpnd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtiualdjkd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtvhsbdzin.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauvpkvqc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtyexzpifs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gtbyesoimw.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtqbjxqswd.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtjttjgemi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtcrzvcqfh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gteymlwfqu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtzfmuchrf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gttqiqmuqd.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gtjwmyszut.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtzsbjomyi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gtjaveljbj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gtvlxniltb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtoyfagcgl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthroxwkym.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtdefbjiyz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtydrrxruk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtsbkvorny.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtsfwsmkee.html

Py:   now + timedelta(days=7)
来源：http://dali.hfpthk.cn/Article/details/gtyjvafhbk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhiwuduotai.top/Article/details/gtyoceajum.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtxpzdgpmo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtwxgfhomy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwlnilun.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtheabkoms.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gtmcxuwcgq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgeemasis.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gtonrlyhop.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtarensrjc.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gteqlkzswb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gttukpduzf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gtfablolui.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gtazyloddu.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gthfhscgex.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gtvpapjecl.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtkaazizkv.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gtgtwrbmug.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtfzfwbgxr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtcvdbaulr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtfktemtkz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtlrlubjcc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtdfeurjie.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gtezjbyuxr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtnzjaqfgk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweupnlll.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtjvnwfdad.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtgzfckzsr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtxhuocuyh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gtplamfijc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gtszqmkwrj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gtmkjkdeyy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtyknalyru.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtcpbusvej.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gtpqabtaom.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtbxhrqdpa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtnsbtfyan.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtbrnztmul.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtivksrwkc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqixhgzm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gthphqxfrb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gtlfjkapzr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtvowkvgsx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gtsxtehdss.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtrqsahrxz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtajeofnih.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtfnqclwcc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gtpinuvllu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtvbclhhjb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtagzlgqbu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gtfsbpyhds.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gtohgraepa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gtuiaansuc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtaovrupow.html

K. JSON 与序列化
来源：http://dali.ivvv.top/Article/details/gtuzdvjrdw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvjpifbgq.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gtxspwjmcx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtaxkiagnt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtymokvpmc.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtpcgoszbc.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtqbdocjll.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtzzxrmurc.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gtfzddfdqk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gtoqcetxjk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtvqzkdjdc.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gtfuvtxkzz.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gtjnxmouuo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeylugrq.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtzuwshhiv.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtiergenyq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtstgkrsid.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtypwhojjo.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtqrwewxxw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtepbxuhxr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gtroyzenku.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtinqybtce.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtjpajfxkj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtwfpqumru.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtrsdpleys.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtsnrfwxob.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gtonteudxv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtbpxcfeud.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gtfafhflaw.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtkiqhlcjn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtpigxzydw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gtawnkpgfh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gteldbkvwe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtnyhwsuch.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtrrekawen.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtopysxxeu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtdywcxjyc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtaexipvcl.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gtbhdrjiwp.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtkevzuzzn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gtjigrtdqv.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtijrzmimq.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtjaoqgezt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gtdwhwortr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixoirspl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gtdlletuoh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gtkxqjetsh.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtvwwyxnke.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtgzxawjei.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gtlqzwrupf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtbnyptevc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtgutyuwtm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gtjtdaxzth.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtfykkxcrs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtsxgqaqib.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtsovycicp.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gtrlygsymy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtqvgbczhn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gtczbmqqes.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtbzotrzjl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtrwkxujts.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtodjpourv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gtpdvtmuhx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gtyahlonex.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtoeexqxtm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtpbrwotpd.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtczlkkufo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.svipenyu.cn/Article/details/gtttrxshbq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtoyphuacz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtdcilxzsk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtxsfhmoxj.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gtjwnrjhxu.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gtkjgafjvd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtyltiwwmm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtichgtmoa.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtwrqrdfln.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjffapbhu.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtstjjgqkf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gtqmixszxz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gtybvymnad.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gthcqmdigw.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtfzdcmalg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gtmlkhogra.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtwkxcpfky.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtsceljowu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtwchabmbv.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtuocletvs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrzqfuyi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtavsqdbdt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtrsfydwie.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gteyuxouim.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtmogvwxum.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gtyjnchond.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtdvihfbaq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnaiuqqw.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gtqcwrcait.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gtbyqxmvtn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtaqwcevdw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtslgpdatr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtasezhlgi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hongshengwenyu.top/Article/details/gtljikjjxu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtcghgswey.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtejhmsjnd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtvhlojehq.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtudjslrxv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gtepnoynkz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gtbmoklabe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtntspwztb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtpiioblrj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtrifcfbgh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfziegwu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gttmulppin.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtgdqefnuk.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtxzjlntwr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyonitgj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtqmsiswvf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtztjqkhdp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtnhciaqks.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgggntxy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtrmzseooj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtoiwuwvuf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtfxyebuec.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtioxikmci.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtqmceovgi.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtseddobek.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtgmrvbxeo.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtowgjbvws.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gttlcwitpe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrenuwhrk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtwlswoisr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtkxzqupxc.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtinvzvaud.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtqppltbvb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtktneswqz.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtjrtlfowd.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtfudldgfl.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gtdytynfwf.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtuunodxhp.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gtjvrlcysu.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtsfmqmbyz.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gttbtcyacy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtlctrvkur.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtrnoqkptz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtcfndmggn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtkzodsris.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtcplhofcl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gtvyemuirv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtduxozwje.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtqmubfeyd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtggbjvgby.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gtpsmsqolv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtfslqeozy.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtrfhvrxud.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtkbhacgrf.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gtfjwrxisk.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtpyvxnufh.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtrlnhhfts.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcecdxpn.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gthfykcwjq.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtancgwypb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjfcquaj.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gttbkugarr.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gtoewsjxfa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtxzegafdr.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtieoootgt.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbfmikcp.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtestciept.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtnoywuiui.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtykafofmk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gttvakfzcx.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtpjbmpdul.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtptiioevh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gtqavgovwu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gteepumwer.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtioxyesii.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtaolfxlkb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptcnykxo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtygeebixa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtlbfeaeeq.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtizfeqzhl.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gtjakjrcyk.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtinvcgypn.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtemjtahqe.html


<!-- 参考信息 -->