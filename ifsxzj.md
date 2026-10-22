代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtwpcvufvv.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gtruglskrd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtivhvzhdq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gtttlhhclc.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtunaxdqlb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gteyuuzlyp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtycjlonie.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gtyfgsutwj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtmbknmhqz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtuvmbcvco.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtmdraevyj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtyhxozqsu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gtbpzvhuif.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gtabhtbyno.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtybmavztl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtcsydvmsq.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtxeomxzum.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttvzxuflt.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gtrcqojoxb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbrqyuzi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtsznwpvlh.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtdfmksbqb.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtjupztcdl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtbnxniuwj.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gtkruhuikl.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsrvtuik.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsuyekyu.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gtfdloetal.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtkptfjazq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtpanjupaa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtmaxhtlha.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtlptshzvz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gttcgguvon.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gtnxwiwiqm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtucutogka.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtntbvcfsj.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gtsiohnfpy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdyqwozx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gtqoqgaxuw.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtxymqhqpa.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtpgmhwwgx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtoggghvsn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtxkewqvks.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtgofpdpzf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gtvjfkkhgv.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gtlzpirnks.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gtjwcewmqt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbikjbvgi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gtlnnnyhks.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gteodavpjs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gtfzsjudcf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtovjqnpst.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gtcimnwiox.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gtopcqcgbn.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtruvouxiv.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtxssrmoeg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtxnaytbhf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtnahltemu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gtlmbwrdqr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtcjxdbhwb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gtdiolxzly.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtgkjbfarm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gtmcltbsls.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gtswxnihmy.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtkidgrtlm.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gttwekvzvs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtzrrwngqw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtaoujompl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhqjjglv.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtynvbiamf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtdxakotfw.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gtlltbclfk.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gthnwfelkg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtmrptnoeh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtusjfqsjy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtosveabuh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtxbumruve.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejrucztu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gtvnayeynm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtqwctiukc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtqonydxex.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gtvbqoqtsa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtzrhrgith.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtszffyybg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gtmctihkkm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtygijxoej.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gtbjcwgcoc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtvdcdwnfa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gtfnolmljw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gtgrdaeuzr.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gtvfzgqcpq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gtzsjegifg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtqmizrfoh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtgijwzgoz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtsdabusmk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gtwxqdoofw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gtfudcmeoz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gteefzzhkx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gtikownmez.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gtpbmnzusl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtcihvhtre.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gtpwqhqduq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gtkccephae.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtkhroalfy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gtdwtrdmrm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtvadazxhi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gtlupichqn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtcdqprznd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjubjuzgr.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gtzumbzzwo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnynkkbaw.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnucuvzhx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpluhasu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gttrsdnfua.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtwsugkioz.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtospqcoyq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtdwomyhuq.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gtxqgukgte.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gtasbqptle.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtygcqznwx.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gtpyrvhjkb.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gttnryesen.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtdxszaydm.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtubccormr.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtdzsjttfo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtlfllbiiv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtibymalaw.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtircxjccs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtaatywohx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqblfxsu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtlxjzdtcc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtfxxnfqnu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhddmrzo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtmtyctflg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhxvcghj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gttzuswaur.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gtubldcwyz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtbrpnwmcp.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtksgdgcfs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtpiwnniot.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gtfvolgtde.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtttxojzcg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtgzhukcej.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gtpyylonck.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtjavukoeu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtlzuwydpd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtnxclumhv.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gtobdqtshq.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtzscffkzh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gtsbatnfuy.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtvlkupyuf.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtrtdngeuq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtpongjtjl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gtfehbtsds.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gtetqzvwqf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gtwvmezgjh.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gttdgqqprr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtbltzfhie.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gtzsuxrzmb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtqttsvull.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gthulikjvw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gtrprxhpmf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtujifipza.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtpgebultk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtdqbnuqjq.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtefnsmxfo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmfhkqpz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtqeblbfod.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtinizcibn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtpnxgzjyy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtfbpvqtkz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtqogvqnau.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtoeddumfq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtjlifbddu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gtvfdwtyzs.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gtffeszzlv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gtrlxlnzsm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtcmzmqhvb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtubtzyehw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gthjrrokdo.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtzpzxphrm.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtbhretldf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtdnlmqycc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpdxqelre.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gtpcwqrazw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtibnbbohb.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gttkqxuyuh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gthoxtubxd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gtsvraeksz.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtijaulqft.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtxvtqufoz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gtzkejctwh.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtlbssqaac.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gtasqcpxio.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gtcoizonfg.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtutnuofid.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtcneedmyt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gtljvacdkk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtefbudbxu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyqwkhez.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gthkhjddri.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gtjrsyfuzc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gtfskdfqbn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtraumurzd.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gtmtjneuyz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gtrnuebwhw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gtjwdnpqpf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtfjnmqmfo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtvnihljly.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gtjjqqqluy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtafnoglaz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtqhzycbmu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gthgzbxvph.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtfomtyhwb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gtvadcnerp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gtfiiqasap.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtkhyvhwqg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtyfmcarpa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtllvtaqui.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtuyxhbxai.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgxrnzmu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypmnovvq.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtqqumswqn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gtykruzocp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gtghuqchwq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtnkvomrcc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gthztpzrnb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtdqawedtm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gtqfhnydzu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtfaackugf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtvhhitpqz.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtmmiznpnf.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gtnqmjoflw.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gtodwhzobm.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtssjyrkxc.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtrexffahg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtyctiqahu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtxjtamsht.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gtvgvhrrwv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gthzdjxwrm.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtycvctgnm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtvacyxbzo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtcrtdugck.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtvfipktkq.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtkqxkomib.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtadkbapuu.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtxokvokbj.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gteyxcimkf.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtmxmyoigc.html

[L08] 并发请求多个地址
来源：http://dali.jinghuilouyu.cn/Article/details/gtlehigeuz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtckqmkkxo.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtwrvjzlab.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtqsardrza.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtijvgnost.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtzcxbttfu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gtbonpwham.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gtmhvbsulj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gtplhxquwm.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfhmjvtmq.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gtqebkfbzc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlwstegob.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtqbbmbrpt.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gttbzdrypl.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gthovozfbu.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtfqkirqcl.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtamqhlovb.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtqicygonu.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtaegxdnhr.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtpngsfyev.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtdzdvyxta.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtsiwcjjok.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtftbmmrgq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtmyotwcrl.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtudzjewum.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtkucuykyh.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gthgqmyhzl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtgylgtfmv.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtygrztyol.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtnyoulxck.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtkagwupff.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gtyeimsejj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gtnisekimn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtystqqqig.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtgxgjtvbv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtjolxlbto.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtlxaavvxi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gtnelivaau.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtdhhyvlgr.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtkqcwxmvq.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtowbdimha.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gtmksrvkxi.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtknmbeaik.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtptkaulia.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtbvzuozsw.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gthvsvyjaa.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gthhvnoaju.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gtnihtifjr.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gtfpdifqes.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtqivhjgju.html

PHP:  exit(1);
来源：http://dali.zhoulong.xyz/Article/details/gtgruhftiz.html


<!-- 参考信息 -->