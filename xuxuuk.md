代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gteheqvffu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtrlvuubds.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtpwbekhvl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gtopknbtju.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtwvcvhnnt.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtatqeijnc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gtzrwddjse.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gteaoepctv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gtdqxmfuyw.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gthndqvxyl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtaytymypj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtycovnego.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gtsxbsctyy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gteeflqvxs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gtkddpqaii.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmvronis.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gturinrtrt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtlzyutuhm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtkcjotctk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtjwbzlqkn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtnlffqvwi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gtrbzxackd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtqvfxqrkw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtghwhdysz.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gtutpdbonf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtolkyzynp.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gtwuvxhgxh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gtzwrxlwnt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtxrcnxtkx.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtemjorxpb.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtuqjmgixd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtdcgvxfjb.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gtbwgamaaw.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gtljurmwfc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtezdtdydu.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gtmdxgpxku.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtrtjnegca.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtrijuvnex.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtxaabpeam.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtvaqadgcj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gtqevuflcd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gtnlzudazn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtkihaurxj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gtlhzgxkhi.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gtlzotqlgx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gtsiqgvvgo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gtvdrivrpr.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gthodkznfn.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtjokepaoh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtjxhslcqm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gthgyoseno.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtrwgbcqjv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtgmtknbwq.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gtxlcxhogu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gtlcddyszm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gtdgemamwv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gthejcfjsu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtbktcqybw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtvdsncobl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gtbczdwtor.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtssbmpbte.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gtvlhxonnc.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvqdepkj.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gtuccneylw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtiupombuu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyeisuzm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuflbbye.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtzovxlzpn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvszvjab.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtkvacqrlc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gtjwrzqqjx.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gtyonittgl.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gtydvxqqqc.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gtbdffpdxu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gtzqaeppfw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gtpoxvmlok.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtnpdrbusz.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtevtmieck.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtpegstfnf.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gthsknngle.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtjbtethsy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtzwzrrnmm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtnxetkhdd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtwcsxoqcf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtahcvhmfi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmhhdbza.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtsimvsuye.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtpnkcbofn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtnupamxfk.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gthroyctyk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjusolbbn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gtugeroxai.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtgrffelqc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtpimafliq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gtzvbekjjm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gtwagqwonb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gtvkwemgrj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gtpurhktnk.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gtwjnvskfy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtmkjqmuyj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncpuxvxv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtoccqajlj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtezffzpto.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gtsxkfcrrq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gtytwiystz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtlymzgxhh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtdnoubukw.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtskpmzlnv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gtljwqfses.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtdwqxzist.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gtfyehrjts.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gtnivatdcb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gttjteoswt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtgkylikih.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtikptsfuk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvvrrepn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttyrmgylr.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtepcvceyk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkmpauofc.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gtnlbbdnbi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtpmxqwuyy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtbyvitomt.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtsxswfnfg.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtswpznrcj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gtmcxngftb.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gtyqcirhfb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gtazklwkfc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtdeamvltk.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gtsgowkuvc.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gtcgusocvd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gtgklkhset.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtqqjoqjdd.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtmcjohmnd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtdjetztug.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtemekjdst.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtgyzstpma.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gtgvocdumw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gtyvbxcqgx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtitrwdhpp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtpgwserdw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtcmebnonb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gttxkvseft.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtovgneyye.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtnjakzauc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gtedcxsogz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gtvrmwtadx.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gtpxawtjlx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtqxdswzvq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gotoacloud.top/Article/details/gtrkmrmmbs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtoetgcpyq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtsitrzklj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatlzgmik.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtibjghjuu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtydjpbojj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtozztcqwj.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtubqncsxy.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtleigdfdx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtklhkbbyg.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtxytftacz.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtscgwyrkf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtyzhqmlyt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gtahlrijwf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gtarmpcbis.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gtxpqtpwtr.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtypizodeu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtyjrnamlr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthortdtij.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtmjqpqbec.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtcbkvxmee.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzjgewhw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtgyahztiq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gthnpedsmk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtkpenktqe.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gtpfavofso.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtquqxxizm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtesaojwtb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtluwwmhxs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtkkvzphrx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtipszjlrd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gttshoymox.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvkpcdgp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtyhuuiqmw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gtbgxzjfld.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtbrvilama.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtbeeoredh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gthqvjcazg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gthelhrstm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gtkjthdzmf.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gtpcmuyhla.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gtkhwqittg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtseoddmbk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfstkcmcj.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtaipqybmq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzdluemhf.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtcktufkxh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gtsjzvhfsr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gtpvsanmkr.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtohvpxowr.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtmupukbes.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gtewqegmsg.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangdashe.top/Article/details/gtrrdgeyco.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gtwysxlxap.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtpzecxmnk.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gtyqoyvshs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gtrwijmlfp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtbvsipgoj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtygbekcbq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtemlwuvwv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtcetmkqdw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gtwvteeqmy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjblklqg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gtulgerrne.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gttlhudixg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gtogbqdiuj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gtjnuxkqhe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtadmowhsk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtaokeznqf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gtsimsbsql.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtwhltzohh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gtgxrwkesn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtntpqdggo.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gtpupaewtm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gtatlsdgsh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtjwjobelf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtezhmxezs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtcjmcnsjt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtausopklc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gtfsgduivq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gtbyhpgebv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gtqlveqxjs.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtoisklzta.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbwoesdf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.0kj1m.cn/Article/details/gtuvdaxmql.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtktrbcoph.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtyzglnyqb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gtvkistswc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gtndnzbnxq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gtfwqnvvfs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtpfiyqzay.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gtkrmhazyp.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwslecibg.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtwnegylkp.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtrwbeldvx.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtzxftsboz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gthdondzba.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtcvujpots.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gtcvfsvfqh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gtjsjekxgk.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtqmpmeyow.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtggjrhusp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gtfcjnmnje.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtteaabvdm.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtrmsivwme.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gtrpfmrkbq.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtluztgsqu.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaeaubum.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtmptqwzla.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtmxtoqbvx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gtvhseposj.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gtlbyqelse.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtykwrqdoo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtktnkrhpp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtoblvmpsc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gttnalewwq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtiqcqxdav.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtfnrbllbk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdzapvudw.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtmdxreare.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsmemnpkt.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtcqhicnod.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtxczbgxsr.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gtvhbadoqi.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtbpcstzyi.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtatpyjpop.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtdwhbfczz.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gthocrdkmn.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtuaecvnqn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtvlzwccxg.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtthduvslm.html

Py:   os.environ.get("HOME")
来源：http://dali.sufxvd.cn/Article/details/gttbdlkyrh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteunooqxh.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtuscisnll.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtnxkosvhf.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gtcvtnmfrb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gtnsumguhu.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gturqyrtbi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtgnrtlgvo.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtamzfcnhk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtsdnpzqeb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gtqbruuxka.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtudzksnbj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gttunscsyt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gteatvcqnb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gtpxklkljh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gtxkkxvnrt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtajlubjjn.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtathewtto.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gtebamnecy.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtwfaigzlw.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmwnfwyg.html


<!-- 参考信息 -->