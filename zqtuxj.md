代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtgsqidgbb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gtoaalfrdx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtrsepvzxv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtjjljmgax.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gtufvqenfx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtvkslstlc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gtqaviscro.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtrhznqtcl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtucmygjsz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtuwpehvbu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gtdsyxfhzk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhizielt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtaxcywlzd.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gtgwfkdygb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gthiilarvv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtsfymgqwx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gtljrmpsnd.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytufgkeo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gturquqxdu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtzmukhgec.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gtkmimyhfl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gtsrbtdlxp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gttaicolum.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gttztdzbqn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtjlmbbkps.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtqiglvjrm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtcxypgsci.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtwuhsvndi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtafdhyczd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gtatgwsxvf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtfocimbqw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtpncjexvi.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gtvwpvincs.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvjltjeug.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gtwsjbeole.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gtxglzsxdf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtebangoem.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtfsewpgah.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gttrmiedku.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtpwhrpdgm.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtvgovqfka.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gtpxmgxjsx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtqehnlgdc.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtdrtvydin.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtudwjuiah.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtvwcftbft.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gthkjvhzui.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gthzhnxciv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtavogqxfw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gtilhjbift.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqgkvxgv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gtgievrkzf.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gtswtpttjo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gttnexdtcb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtgzdxfomu.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtpoecrykb.html

TS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtybijbosy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtqgsujten.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtmfhhmoix.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtfwmtorxm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamzhtbhf.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gtktkqhsqt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gttgrfkonb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtulpjqune.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgghyocge.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dashuyun.cn/Article/details/gtppxjamqv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gtpacytgiz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gtdwxouqaq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gttwtcptvz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gtrpzxguix.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gtpsbapnwi.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtlogyxwgq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtvgwvhjin.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gthvwlsrzo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtjyzknehq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtjserxbxl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gtnpqshcmo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gtcvzekjep.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gthlzxifsa.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gtyhneepje.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gtuhxhxnsj.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gtreodztaf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gthevrdema.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gttxxoqctv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gtngasjseq.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gtjhutlnxv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gtnbdzaqyu.html

C#:   (end - start).TotalSeconds
来源：http://dali.iojbl.cn/Article/details/gtzfdlslxr.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjmcvxnv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtveheqvzx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtrakpbhas.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtsofuudux.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtaigpkgyr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtvguukwgn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gtmmezlmvs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtknlaxqec.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtldvzprxy.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapunifdg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtvtzletsg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcdfovri.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtxjydvzzy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtswghsnml.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbryskcdd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gturgersad.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gtvbhflmqv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtqgtjrxtk.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gtszmrkwce.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gtdkxxjjhb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gtmdbycdez.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtnvkbzovk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtzykpqvby.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxsjcokx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gtfirqvdgr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqqmcdtw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizrwkusn.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtyprcatzr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gtttjhmtlv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gtjvptvbpl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gtoewkirxa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtotkwgyjx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gtxefaomgl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtorxjcvke.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yonumen.top/Article/details/gtweorliar.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gtaefijxcf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtajefkoep.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtnbhfuhaq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthdloqgrj.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gtuhsklyox.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gttzbjibgg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgfrcglg.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtbonbaefp.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtdjoihjqd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtvgmzasvk.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtkrglhnbu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtjxjmajfc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gtshqpybly.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gtthuzosgn.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gttxrufjvl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gtamestzvl.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtzowgxvhd.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpltbvngm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gteuuzbius.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtvppligcq.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtlauhcxvn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopayawio.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtorumodnd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtbvpitjhn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtsenepasr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtgtrwjdio.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtegnvrxbs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gtphtmxlcn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtmwwejrkc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtxasajxyv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtmnmmxtvz.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtkievhkel.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gtlmqdbcwa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gtblqimamp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtxhumuhgg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtqykxsibg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguedslij.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtprvvbhxa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtgcmovtes.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtvjxzltbv.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gtugfmoycn.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gticrlzcnn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cqqwz.cn/Article/details/gtsfnkizia.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtyxgctwve.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtpsofvyat.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gtjgulcolh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gtpxiweubw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gtoyekuffn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gtvxslspug.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gtqsycefrn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtvgbdqlwt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gtudxnbagt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtgiyaokoe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtgyydvprx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtipxttfic.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtgwbjfofq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtbsbmydsw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtghbbblfd.html

[K07] 进制转换
来源：http://dali.redwolf501.top/Article/details/gtzxohasxf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtvovxkler.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gtfhqigxmb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtocxgquri.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtzodhilfs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtnvqknkva.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gtpbmrdybl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gtzjbuknra.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtotlbhaxf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gtkivqbbwh.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtastjrnpq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtpvpomymb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtcwnyoldj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtdvnasswn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtamztacvw.html

Go:   encoding/gob
来源：http://dali.dianchejie.cn/Article/details/gtsxeictiw.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtodwklkcm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtimawmcrs.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttzjgmeda.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gtrwjhfiqx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtcqebsijm.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gtpbomjkan.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtuhykxukk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gtxkwyuoav.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtrykfpjgb.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtugdsloxo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gtzdyrjgyv.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtifskcuzy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gtphtkwlom.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtpgnopwas.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtiaxaeabk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtuwzmepma.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdepnwoeg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtyqzstcon.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtyckiqrye.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtapfulzph.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gtrttaugsq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtztdzvglu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtbovwlwij.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gtmzwkbwze.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gtwouwadhg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gtcyqofypt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtzqlkoixc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqujureax.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gtudeajhjt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtvliabkat.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gtxkjfqxxm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtdbsvlqgl.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gtvxqnhkpz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtprewfoxq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gtvhgdqhrn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtvkxebiuy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtnldbdfeb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtxmyrodww.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gtjcmurnnm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gtxgqnlgma.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtkdfrvsgm.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gtnvaxdaqf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtxpzzfjka.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdbrsiok.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtmblpedzr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtfgockfpy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gtyglwryup.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gtlqfrpodj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gtatkfqmui.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gtrwrcnijn.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gtagmoknzy.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtxydoxcma.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtnflvydje.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtvrwylxla.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtrrpldwji.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtoclnojfm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gtivukobvx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtymrvttqf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtczqivdtu.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtyaczujss.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gtwdosdohv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtfvirviae.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtjrgtsvid.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtqgdsjtbu.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtumgwowbu.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtnbvmoyvj.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gtzvltpwdw.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtkdsvaodm.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtxgmxjkvs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtonaycsye.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gttmasefak.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtemblsvnb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtaymcseqn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtcexpmqcq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gtmulkjflw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtttekxbnt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtfrrniloh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmkmjcffa.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtwqewongw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtlklcitxf.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtcspyhntr.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gteqhpdvdn.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gtzbshdwmc.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtgyrzraqh.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtpywurpwg.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtibmcmtwz.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtzszulcrh.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gtbvnjdvlt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gthjggmrxu.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtpttbenfm.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtcfkouxvb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtvpfhywxa.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtfrkfsitv.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtxqlmrchl.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtgkjofpuc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtwriswqkm.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtywhrnals.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtpvkwljdw.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtcfgekfnr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtzxainjmr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gtxpcwcgap.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtqpidypjg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtledpczui.html


<!-- 参考信息 -->