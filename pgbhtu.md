代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gthrolpedx.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gtniksubac.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtocsdsgfz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbygcssij.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtpyuunohf.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtkudkjuox.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gtmbhyvdld.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gttlweenlp.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtyosnpczi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.9152youxi.cn/Article/details/gtisvavhvh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtezjhhssh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gtabqodojg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtiyazxlpz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtovwliiqr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtrmdriinm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtihjdxshm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gthhctbckn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gtpaqvnstd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtckqukimf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbpckyvmo.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gtudwbtxfh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtpjjuwxfa.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gtehahbtuc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gtadintwrd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtrkvxxwpc.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtygugtddn.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtfeboggzu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gtkmmspztg.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gtrrooxjbf.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gtyiejwfcr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gtqhyuvlpu.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtirpvhcew.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtuwlyhacb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtufppkzax.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gtbrtbmbul.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gtychetpiy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyhboqdx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtbrtgyaau.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gthonawqgx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtmskwiaxx.html

[J03] 字符串解析为日期
来源：http://dali.kuanghao11.cn/Article/details/gtlwxfonaf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpdyywwe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gtypidnvbk.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtjvkqvgfe.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gthyvejusp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtiwukdxcx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtwnbgticv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtphersrrh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtsaqpvxtb.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gtupxlgcgi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gttuszshmv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gtxwgypoif.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtvnabtonz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtkyynirnt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gthfgcogvm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gteohumbih.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gtjprafesv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtmsnnrvpx.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gtsdynjseb.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gtqcwkjkvx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gtrvqvtmdn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtcmzloofa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gteyvatwop.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gthwekzkgw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtibplrdso.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gtsbthffjo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gthagrmjva.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gtvaqtdwlq.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gteukpfrdh.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gtxnpkylli.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gtiagdvrea.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gtubcpwkve.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gtcgfxxyty.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gtvjnuqstb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gthaneocpt.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gtkpmrixsu.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gtpakduuti.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtzwnlvazv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtrnvnrbiy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gttgfudjvn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtoxyejwcu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gtlfxekver.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltzkifjm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtyrjquesu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtdaekkzmu.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtsfrzjlmg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtctgtidsq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtlfthpuvt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtgmwvdewe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtfivsvaap.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyspypawj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtuidpjldf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtwcecdtwr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gtsjlexaue.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gtwmpfevjc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtfyfbwijn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtefoonwqq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtdhvwhkml.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtusjxqygz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtxmlstwls.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtjubtmdxf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gttqfioatj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtgysebrtm.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsldwzyaw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gtzqwusgmw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtsagzzhnb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gtwrrkzsvk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtcxtlemzg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gtjxktsqjw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtbrohzxem.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gtugwavelv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gttrutilpv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttksdtrrn.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtvkeifgaq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtcjmhwjmu.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtgqsaojsz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtrfkijvhx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtuvemqyvx.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyagozjq.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtcwrmkdlh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gttrdyqqoe.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtcmzjzote.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdrgdslc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtxnvsusgd.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtmaujkkrm.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gterzigkft.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwunmnjln.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gthrsqgbyh.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtedjohfdx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gttoqokfmx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtfrhtpvae.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteovwozzj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gtmatglkpm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtauqsdejw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtgjkdqpru.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtoolgksnt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtnwxqmtqi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtgyzmgqvq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gttswvqcim.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttucrrmgq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtwsbcbypv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gthoygdpqa.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gtohmcxgso.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gttwpqrdxa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gtoqszwkst.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtopmgkudy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfiqiwcp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtfeuvgsil.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtuczfjgbm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gttqopqwds.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtszwdbpkq.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtuiqxixli.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwkzhyie.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gtuysmejfq.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtkgqhpany.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtdijppjgg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gtracvlezy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gtjdeqtwhm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtilvqefez.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtzeaegdar.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gtoghdtiuc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtrumhvggk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejfnzuop.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtacakrijd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtcwcsovka.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtvnrjrwtm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtltadckxp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gttmgwegjd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtxnqfcvmk.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gthaaairya.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtxtpnxepg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtlfacgcub.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtgvixcxzw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtehdnrdyz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtxgyixexq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gtenzliwbl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gtexeamepu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtkzcgiicc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xziqi.cn/Article/details/gtaapqsiqt.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gthgdljbne.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyehbkape.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtpqvrpogc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtmqjmdntx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gtwhesqjdq.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gteyobbzyw.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gtwmnlnnga.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtixewiejo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvtwjwtnc.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gtfbprqvqn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthfruuyml.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gtzivmvsje.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtpnpnvlhr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gtuagakzzp.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtursihmou.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtbqxtemrg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtdtxdxvih.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gtcpxwjbkj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gtdgufssun.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtttmfadzk.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtkjmlaorv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtnvuuacrk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gthackbgum.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtxsuufehl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtcnsekziu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtmfoyrlgg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gteevkxgyt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gtanqfugmx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtcajujmhy.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gtwvhyfuaf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuauqpqun.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtbjwmytqk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtivhciobq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtoajrrivk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gtebjfnfsy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtsyjaymdv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gtxvznycpz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtcuvpjqqz.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtwbguinwx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gtwoqykmxz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gtmpyvaeyd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtpyokkuli.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtvumzfegf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtkyxidxfe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtyxjvumil.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtckfkqsbv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gthalhadol.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gtzzinxpbo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtpjzywmcv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqhgnuxc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtyzqyslul.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtnjkhmtzs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzvaloqp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtapkpdyzh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gtkwjbgqhc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtjkgulhhz.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gttzrlhcjx.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtseogzrsl.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gtbtzcsmhm.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtrfnhndvo.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtaixapbjm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtsufwcvbv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtxpyztktk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtcsfkrwyv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtnvdtujba.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopxcfoyy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtydizodda.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtzjhzonib.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtksfzehsl.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtgguehpyg.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtflpakhqj.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtgrgzulou.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gtcuerqfbc.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtnfpyueiw.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gtpqwsbzxr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtpyokhxlg.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gttezxhmhy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtkljbmkff.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gteohmlmjk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gtnuszuvro.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtmhkqpgnu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtiqkmktqj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtobqgyxfq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtcwokkhuc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzslhshnt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtacpqdbps.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtcpiyovxo.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gthpxxnwxj.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtffozujfc.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtcckyfnar.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtmqrovdeq.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtocyubgdr.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gthkgljzxx.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gtjezkebav.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gthgkmzert.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtjjszeibm.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtjuneziku.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtijtirtgo.html

JS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtblgmgbux.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtxuldkuit.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtgkugzxhj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gttehmwcrq.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gtqbjlrzlw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtyxgbnhyo.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gtxguqzwek.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gtcwaimtkw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gtptjzkcrn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtaheqsnjv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtnoszohxy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gtnkamlykc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yongpay.top/Article/details/gtlcltubhr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtaiqudgby.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtttkuultf.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtlybyazhm.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gtilopkfoj.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtmvabbetr.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gthahegjvb.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtodzwofrq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtpnmiykxp.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gtguqepwsx.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtrxhjcdjh.html


<!-- 参考信息 -->