代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2urrsvsrx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2csysiwft.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gt2rrztcuoy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gt2boseqrkl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2awfyjxyz.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gt2zixqpksj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gt2pmdjvlyb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2satsvjjh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gt2czwnudro.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gt2xvrishzu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gt2ubjvxocy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gt2qhcjzcpb.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gt2sbjlegug.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gt2pygirfsb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gt2cwojngbl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gt2dgcinypf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2ilwlhmwe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2nszpebsb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2leqepyag.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gt2nipwwjuk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohompffz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gt2nlwatgfv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2agjgvmzb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2szbeupfb.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gt2ifulqcrj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2plprgdux.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gt2bkmrrcqj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gt2wtqpdmkf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hifsorja.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2uqepuxjr.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gt2ietejyde.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gt2tcsgayyg.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gt2tocmdddo.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gt2ujbvalba.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gt2myhdxmck.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2uvcawfiq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2nnyzehbx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2duqtwaet.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2rztpppho.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gt2xuiamive.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gt2gdrtbrpo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gt2krruezzv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2pkbxahug.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gt2qcmlttab.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gt2eyuryofs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gt2ypdlpynk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gt2cjagosay.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2jowkgota.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2vhulnays.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2odpvrxve.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2dibkhevu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2fwmytdne.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gt2aozlaepm.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gt2joljuoma.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gt2otswhbrq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gt2qezcogqf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gt2nnnsfkho.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gt2mychpulo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2rzgtafxa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gt2xpcdjwxc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gt2ykshjlbb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gt2qcsygifk.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gt2itdlrgnu.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gt2rndqzigz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gt2fethanzi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2vbqhwejp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2vzlhzdsp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2ngvgiblc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsicromu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gt2wkixhnkg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gt2aharisij.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gt2ijdizoko.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gt2wsymkhim.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gt2ybdmpttr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gt2xccbalfn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwxgrkob.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ayiirkji.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gt2hjeedvvy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gt2iwgfdqbo.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gt2fhurcqcn.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gt2ybinlubs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2tespbtzd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gt2qryeuagp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gt2hbiatbto.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2omqbochp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2qguulsqg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2vmiqgfkz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2tmozrocd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2yosgapkz.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gt2qdintdwb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlmsbljy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gt2kehgwvpg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gt2dfcdujxx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gt2esybglqi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gt2lmjhxqis.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gt2bvaenwej.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gt2xhidksti.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gt2punyaiiw.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gt2qgkpskwj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gt2bveffgov.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gt2cisdwvaj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2wujiuxkm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2fjsykkmn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gt2uzgxgxtl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gt2pgikwzjk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkqnkeqh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gt2btrmuyeo.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gt2zdpkpjag.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvncisc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2gfnbwtws.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gt2iuraklmt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2tsbqnlsm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gt2rqjbrifv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gt2aefuvbra.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gt2vumjrhrz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmtawuvk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2kjsuzhyk.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gt2gnartrjl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2wrxdqvdz.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gt2wkqcxuyg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gt2kbhpadpp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhnnqpin.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2fpuaczss.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2dgopwdzq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftvpkpxs.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2kpdudhna.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gt2jwusjzio.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gt2qzruzcpx.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2lxalnhuo.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gt2wxooovto.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gt2hhpjgkzw.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2qhgkgxrt.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2lmgfajom.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2wamljghf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2noznyvzr.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gt2mtkomfhp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gt2ifsgkatv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gt2lgbysvhw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2fszgegfv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2kywyiwxa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gt2znfknayg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2pxedghes.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2tctewuet.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gt2tjdwrtif.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gt2gkjksyxb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrvcibvq.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gt2deirnzav.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gt2pakvmlgc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gt2tggtbusn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gt2dtbkhivr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2oafgshms.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2swltxfzd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2jbxwzoni.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2kiplpnid.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrunwquv.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gt2iwiusugk.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqkrykfh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gt2koxigmiw.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gt2oehzfkll.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2qdobhvbj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gt2fptqmseu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gt2wxvlbiga.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fytndskw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gt2dmoeosmd.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2pudtsxpg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2szkooigv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffysbizj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2nfgxhztx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2llyvsypr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gt2opcoctuz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2jcdntccs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2owwwahbh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2eqlauoiq.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gt2komfopsp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2osgbgkbx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2ydhlrkvx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2ssfqsioi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2sejnknyt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtggpits.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gt2qtjgdztp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gt2fjfgpmdp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyqawxnj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gt2zbsusgzo.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2leyryeuj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urvlysnh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2idnvvukj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncmmujoz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gt2ncmnvsbg.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gt2ipojxcwp.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2etalkwoo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gt2ugrrhppc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2dtqmmaor.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gt2tmpjnvzu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2lchcvema.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gt2qpanrzhg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gt2tdopdtrf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gt2gdxqfxwj.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2bbywpjvy.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gt2izgxwdro.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.iojbl.cn/Article/details/gt2hrvoguua.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efdtlpay.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqwjigor.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2pphqnogh.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gt2jjyugffj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhpuecii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gt2mdmqvyrh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2dxsoquxy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gt2nklokaqo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2acdqrwrk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gt2cycabqcl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gzhubu.top/Article/details/gt2ijicjsgn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gt2ldfecwfh.html

[L03] 设置自定义请求头
来源：http://dali.daxiang520.top/Article/details/gt2fmradgan.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gt2iluqorwx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gt2sexixkxn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gt2gzbcmgux.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2gnxwsihe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gt2rxdnnxof.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2hxxxkkki.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gt2abzblzdd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2rxrvqwsy.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gt2vcrvlhql.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gt2vpmtsteu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gt2zieuqmij.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2xtqeyzfv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2afncvkpv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2mjfrtoum.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gt2japurcbg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gt2fuymqbsp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2yqlyifkc.html

[L05] 上传文件（multipart）
来源：http://dali.yonumen.top/Article/details/gt2jkueendz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gt2kjyfwoju.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jlsjyb.cn/Article/details/gt2rgjrujxj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzpoulwr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2inivykss.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gt2ptbtskdi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gt2moliyjqj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gt2dbfxfxdp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gt2ktxbimsx.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gt2pttjgaym.html

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2fahztuvi.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gt2bomrorzj.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqhfkqca.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2uydrohlw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqptrmse.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhotzmyc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzlvjuor.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zguxtsfu.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2wkqimjvn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gt2gawyvqag.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfofzxag.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyvgaoyy.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2eugbscsr.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2nlvcgtkd.html

Go:   resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gt2ffxdyifc.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gt2mgyeycth.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2ttzjtfmv.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gt2bjehehvo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gt2prsayahm.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2ejdaafnt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2lgpkmjcf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2soeixdwu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.birdmap.top/Article/details/gt2hitqblpx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gzhubu.top/Article/details/gt2xbynsecu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2dsfleqfd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2ardyzdqz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2nvqsshyc.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gt2injblqom.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2fhjacztc.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqgpxlsr.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gt2erxjbgjk.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gt2evzjqrog.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zsvekxhq.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gt2jxvqbbhh.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2grnsffwd.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gt2fatchhhw.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gt2ksahihkf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gt2zracmhks.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2olrewobx.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2otfqqwsn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gt2sbewungc.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gt2wbnzzcty.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2hlfvuupb.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2ppofvejh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2kkzafdwc.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gt2jrpfjzkl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gt2nbmcuwtj.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gt2vognegad.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gt2xrmvlsil.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gt2jwiouadr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2eyaofyuo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2fgqcjqur.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gt2tyyyxwxd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gt2eryftsuu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnhzkckx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gt2sdzvntve.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2avmkxzfk.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gt2qaafnbgl.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gt2oldribwd.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gt2imuwaefx.html


<!-- 参考信息 -->