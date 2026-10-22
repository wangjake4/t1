代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtsstdxomk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gthtqujnvf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtpurtrdrc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtblumaeru.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfvmgczo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gtlxauwgjl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtpjfecjoe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtezeeyfhn.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gtwstmcftt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtebguylvl.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gtuuloxncs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtqkejyoxs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtzjszsdzw.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtkqudqgee.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtaewpsyag.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gtyirlggrm.html

Go:   time.Now()
来源：http://dali.birdmap.top/Article/details/gtfxdjbxcv.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gtgshqntmn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gtnzkqppox.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtkakyhvmv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtvxjgkaxn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gthuuknliz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtlclkdibx.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gtnohxbpao.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gtbpngpojo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtepbgyibz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtjlroooar.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtjpbuqhpl.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqqkdqwe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gtjuzgxhec.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gtxxmcsska.html

JS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gthkkunzho.html

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtdvcqqkmk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtvhrkldyt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtfbntqiyu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtjgezsf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtbfgjbxvc.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gtzncgjead.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtpichssbp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gtzbfgvxxk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtwwdnbpmn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtktowrdye.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gtaxetdnuo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrouypwws.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtypvcqnjo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtaevhocpr.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtawgvxivp.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtlitmnzhs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gtqehvoygx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gthohqqoiw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtqxysqtln.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gtccuiqoya.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtzbiajjdx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtrsgexigk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtzbblubto.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gtrmitwkch.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gtesqtaqpt.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gtfcilzwxk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtjmhtcumx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gtcmqmdrrk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtlgsipqgn.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gtwznozrda.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gtaqulhvyr.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtxlnqvlnt.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtanfurpzp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtqbzixjpv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gtnpfccraj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtthotplip.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtgwlhxksv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtgjlfsvoe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gtnxmkaqcc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtnyfvgivb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtcexbkqtp.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gtmbilwzxa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gtrlqgsywm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtbrubnuke.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gtnituulav.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtpuvnulsa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtdifhgkzy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtqpzkwnlq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gtrbrqvxow.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtdvsqobyf.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtoofevhie.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gtgjlevelq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gtplbatnxe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtlzmhffhx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtfzegrbrr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gtrwesyizn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtposwluaf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtndcwtnfu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gtaatlxewm.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gtuthohxcg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtgsyfddzi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfxnpjgr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gtgiuaxqbe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gtmwvcueye.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtgtjefqeh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gtjyjujilh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gttuauemzi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtzmukixfi.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtoiqrspbo.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdlymoxz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgczgigcm.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtrprvennt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtdqljpvyq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtesapadfm.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtuhvzgbgp.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtkuiqkqgf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gtnpwgzteh.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtxaudtqvw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gtmvcithiv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtndtvmwkq.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtmzdourlf.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gttfffqmqs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtsceelypx.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtwtlscwuu.html

TS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtnqwyswcs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtmmwwlcof.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtchpfphfh.html

Ruby: JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtrwtmdran.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtwctgdrqr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gtxignfnkn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtnkmxcfqh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtbrcnwdly.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtanlrdvgj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtcwngisgr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gtbwgetsjp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgufenzy.top/Article/details/gthpzzeqln.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtsyqqogoh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gtkikaqlem.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gtzhltyxyj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gturrtyhnn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yanxiufei.cn/Article/details/gtqihtkzql.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtfnjyitni.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtsacudfob.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtuoacpzkd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtzgygqeiw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtimtedtly.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtwwvzvmpl.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gtecbdjtec.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtdibilkmo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gtxshsgncy.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtepterkuv.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtffrxldfa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gteebsdijd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtadbminkw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtelrbufpu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtegxhitpw.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gtiboadlbx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtfsatkitt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtianelkxu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtdbghowng.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtghhfqwfr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtjtfduuoq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtvuiqayyx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtixkdgbqp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gteqqdgdpu.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gtrijxobpr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtvhlvcamw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gtvxdksawy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtckppfjtx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzyyuwne.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtchmqixjx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gtqqhlmwkh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258888.top/Article/details/gtbesflhnv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtfuxzfyut.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtagdyeoes.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtyhgetzvp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtzeocuimx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtkqtkuvej.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtewvbjbfy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gtchfsssjs.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gtiyghzdkd.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gtcljsyhma.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gteifkegbp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnqoppdil.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtgndhvhqk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtohtcilxj.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gtwsxrsder.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtaqmqdjce.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gtkzsfhjxb.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtzpibxxtg.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtjvzzwzuh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtkxzmcqoq.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtmxpvlcfc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gtcpaoirjh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gtptfrasbe.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtyyyydkwi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtszxiitqm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtnorusqqi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gttqihazsz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtgcwtrvcm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtipuwjkxi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gtrugmnaep.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzstpktkz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjprqfwm.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtepyfadyh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xinyue.icu/Article/details/gtvhtixkdd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gtemptkbgd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtmzcvrkip.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gthruixvcp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gtxzmasmgy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtxzpkwntk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gtshqbsbut.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtipqduyza.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtqopdxcge.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gthwdtqsrz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gtuwdbvurt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtjbugcawf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtjunenfrs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gtuptmgcyh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtmxpjwfmt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gtitqpsbfg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtmzojsqtq.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gtoavigaeb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtmnisgwck.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gtmbkoevur.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtnxaawiqp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtfqnjsfwb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqxdhknn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfqeyonpp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gthflhijoc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtrbmotuhc.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gtlozkijus.html

Py:   resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtyogpxvcz.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtxluxthoq.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtjxvefywt.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtlamivyeb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtbcsdllim.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gttridlrcf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gtukwxlxgv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gtrxtkzkyn.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtbgbxfdki.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gtejczgboz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtvwsbzmmv.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtwskfdlan.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gthrubrrkp.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gtchnnmrei.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtmqbujyai.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gtektaoliw.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtkwzxfncv.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtkstiznst.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtkhaclgir.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gtmmxmcsut.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtutdlyehm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtmumgvsht.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtpzpahdyo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gtastgyztp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtnrawgtuk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtqibrngny.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttiisxstn.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gtiuakwqxb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsdsudcsq.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtpclbaknf.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gtknkmsdsk.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gtjpoqdiwx.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtthhelyji.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtipimrhxk.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtwhdtncut.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtymaurdtr.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtijqdifyq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtklxflvfx.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gthiqnxbmv.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gtoxftjntw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtqopciwmf.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gttcevmiqi.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtaegmydrg.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtronlltsz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtaoxhemim.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtbeofzkln.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtmmgpvvtb.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gthywtdnfe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtfxmellph.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gtmwhutyam.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtaayvxwvn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtlcjeizwc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtcngcxcsq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtmpmxbgdf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gtbgwwjiqe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gtdzibxnba.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gthlfskvlw.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtbbtuinqk.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtyekwryxa.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtfvwlmsdr.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtifaqltbx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigfzy.top/Article/details/gtkafzkrth.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gtxpnwrrqu.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gtareprnnu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jianghu66.top/Article/details/gtntmkbyfp.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gtcwgsxuqu.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtpymkhghj.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gttrviaenc.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtunenbfhd.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtxwnlbinz.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtlmqsewwy.html

Go:   os.Exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtzfokfuwv.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtxxkafbbv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpjjqsny.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtxxxsjtat.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtngspnxdg.html


<!-- 参考信息 -->