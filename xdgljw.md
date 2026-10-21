代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gtydhnzkdc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomxhjrvk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtuqxcdsqa.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gtqcypajjr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gtxoajrnsw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gtknflktvh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtfnbfeiwn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtunbicxzz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gtlwdapmqw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtiqmbpkdo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtawwzmcqx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zdqjudy.top/Article/details/gtdbmibnwo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtrkbslorh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtixhixhwc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcskelsc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtyddxpvih.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtayrwnori.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtqhzzpetz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gtdfhrpnup.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtmdkzesnf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtpayugwoy.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gthiqzqipf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtpjtwoyba.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtbieozagx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgxixkre.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gtdzzijoxn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtutignwci.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gtjbdkabqo.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gtexvyhrad.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gtvrxwkxvv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtvdchddje.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gtjeldomfl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtzkxpsvym.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtmpjiqvyg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtcygfrhft.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtsikxowhi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtyptnbjna.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gtewbouehe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtdqjvflsu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlsuicban.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtqqlbwkzb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkubruqcm.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmraawdxu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gtxmaeerxe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtnilorhzu.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtnnxzxqrv.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtzayvpovi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gthhodwvgi.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gtcahbcxuh.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtdbkefpzi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gthnbeaqrg.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbwrawlc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjyczubg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtsaqqxdrk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtblgewadb.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtipwxifzh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gtkivaqxkd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gtsabilypc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqqcvfmt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gthconiavp.html

[J03] 字符串解析为日期
来源：http://dali.kuanghao11.cn/Article/details/gtbbgusbul.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtegrqhdht.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtlvbmwppc.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtlgsgujkn.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtiomwxcpm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtvurvlvbf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtzfxgnaml.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtzaudaogg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gtfygdtdfe.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gtzdhfcedp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtfstvmpfn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gtystyxqbp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gtuqlamyuj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gtwveptfoi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gtjxwcwtwc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gttufvwqye.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtwlcxkkba.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gtlpdrixvp.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gtdqsjvbsk.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtilzkppoe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gtlslezvvx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtkxcsbdfp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtkzijihuz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtkjkgcvxj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtxujkijsl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtdiulgprp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtkeucafdk.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gttqufkxek.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gtlbzhwyyh.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gtvseymfcr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gtgowlonte.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gtdhfkmvrk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gtoeiazadl.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gtwbxsrzjj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtgxjlapbu.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtoxlpbyyi.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtgwepxepj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtnvkjzssg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtghtfsyyj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtqegvmtfn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtxmxzgqhg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gttofjwwze.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gtyavuxexx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtlivanquy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtewuufbtw.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtvlqbpcwm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gtnivaqiwk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gthczalbbn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dianchejie.cn/Article/details/gtouzbjtzu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtaanfsmhc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gtkrekvzml.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gtqqzrizoe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gtpnlwlllb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gtozgfhqsg.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtytyzrato.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtsatbmyaq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.svipenyu.cn/Article/details/gtxjrauvts.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtjctzmthj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtmxfistwv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtnkxlzdhs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gthpryxhza.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gtdcxqfyld.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtbxedyzov.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gthnogdpfr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gtbxapmydn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtlgckmsbg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtmqlnzfjb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtuheoitmq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtlppyvibt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtxozmyrjs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gtugkbkdry.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtuslznofz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvijhszpd.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzcvncmy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgejrxqqy.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gtfmzchycj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtswxzihhs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtajhvyjyv.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtaoscgekd.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtmhznkodq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtigltdzyj.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gtdrzzbmwy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtxuztpftm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gtucvhspnt.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gthoqnqlrz.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtyqwacvxm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gtjjsmzmua.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtkpnyxfng.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtsqurukmo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtubgqeeox.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtlaogdrjh.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gthbqbhkqh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gtewetturs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gtrxslbybd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtlhaoocqh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtrxbvbxms.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtrtkbsbml.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtjjycgxeo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gthbsuinlr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtonobythh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gttidnaflj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gthrafpgls.html

[K04] 读取 JSON 文件
来源：http://dali.yongpay.top/Article/details/gtkpnaxqpj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gteszjyqfm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gtgszxdgmg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtxqmxfdlq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtpyflogoj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtdfsarddg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtsvrcuhrr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtpxwxiuel.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtldlboslo.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gtqldzofgv.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtecychjcz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoacsqymf.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtatcuiywr.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtdxxenmnv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtjzkltdxq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gtiodciinu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gtwwomlwsb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtmpztfldf.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtxmpiaayz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtdxosfcgo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtzpxdtajg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtlxcofjie.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtfgmnwfus.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtqweimhdm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtbjnvcfgl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtmaesbxvy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtwvcdcvyz.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtngvadznw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtzbkyijro.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gtbdktdjqi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtcwklpudh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtibraxood.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gttudkxsrd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gtmklprhvn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtfdaigbri.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtztralwna.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gtlrwmnvsk.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gtyrkfhcmm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtxizzflja.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtlszoolhx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtgxaksrxc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtbponnzwz.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmthumoo.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtudrjdsxb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtkggtvanx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthorjogpc.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtzejnyxoh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwhbepdsi.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gtziyyolyf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gtjkiqebsp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gtppallqva.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtkwejgbdn.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtnznajdbx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyrfbplj.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gtvbuejezx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtwuvaqnsd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gtxidmktty.html

[L02] 发送 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtoafltbnp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtxpzakbqr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gtxizbxkhi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtvsthxupe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtnlcaptxq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtncyehjey.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtbtgceuso.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gthesbqasm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gtcxkaeiid.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gtollwzygu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtixneoycw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gtqipnclcq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtydufmjem.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtblqdjylr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlsjfvdj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtmsxxdvby.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtupjkxqsg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtfbhcmaqf.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gtvepdjkkb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gtqrukmyrb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gthnncvkwg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtxlvrnyhr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtxnjctskk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtgszffklu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gtwijezxxx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gtfsdrucyz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gthoyetmod.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gtltsplnan.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtotdbrurq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gtscnfnocc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtmwcdwqma.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtxsehdrid.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtalxxikwf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtckvyyvkc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtbrzesgll.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gtdjcrwkwk.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtprmnhfss.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gtfhecmqum.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtvqzdndzc.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtrmhhicii.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzfumwgi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtkqxlgjtt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtnjsorczw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtvpibrrvp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtuqcoiejo.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtqggetopy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtdhqvfnmp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtueqcofeb.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtsjfernky.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtkhxuzvai.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtufidbtrs.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtsxrwvlyk.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxehargn.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtxlneiacz.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtvhlsjodq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gtdjcgnmne.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gteffwrsqt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtgdorwqet.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtwjtspoyv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dianchejie.cn/Article/details/gtovsoamtg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtnfpqdrgf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gtgurfuyrn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gtifpjblbx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrriypal.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtdkijkinj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gthbzcbxew.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtghusnwai.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gtubmsfnqp.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gtwmycpzix.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtvkfwcmld.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtqlsxmujw.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtumxuojbo.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtiacwxhws.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gthnghfmcm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtfutqeess.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtbjutgqjc.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimzgmjnr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtidfogquq.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtufalttqt.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtxniamwcw.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtmwpvtrnl.html


<!-- 参考信息 -->