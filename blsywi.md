代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gttgihiwei.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gtxolkisap.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gtaregvgoj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gtpzerjjeh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ivvv.top/Article/details/gtjqrzursv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtqetbhuva.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtrfkiehnq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtnxjsbddh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtxvnbpkxv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gtgoirdcmk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtqnbrtgia.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtswuhwwvd.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gtkehvwktr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjoixzttc.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtewlflydv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbqtrejx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtwbtsboqn.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtaetyeeob.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtxdlobspv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gtatfwokac.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gtewcogvie.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtfgimurbe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtspzhbgsb.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtazxadcav.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtnjqxabrs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtldxxmnqd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtyihzxegf.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtuycvizne.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtecgzhnoa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhixingplan.top/Article/details/gtkrrehgrv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtcsbhmtxd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gtoknlumuu.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gtnszctwwi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtvjqkwcjx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtmrohzkqn.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtcfliyjag.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtwdldaehl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtzdvlwule.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtsqfqjtnz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtmfvzgbuk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtjvuprfio.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gtskwhgfhb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtanstdmao.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gtdiotfxdi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gtdwarsolh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtfwleusfn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gtwoqwisyc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gttfvhxprn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtbtcdpyml.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtnpjdnikz.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtoondpriz.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetqxophp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gttxkpapyw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtwegtlwys.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gttgnmtqha.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gteugixbzg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtylzjsqps.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtxobkeyje.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtlesdkdny.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gtkieqhhbk.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gtprllrwst.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gtajklwhzc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenlongwang.top/Article/details/gtianarnaf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gtadkgchfi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gtoyzcbipk.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gttlsbmslz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gtbpkukibd.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gteoemhpib.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gticnbikfi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gthurivtog.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gtppjcepms.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtwkdzonad.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtonqwwmpj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtznkuynby.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtlddkspts.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqwegiyg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtauiwhpbb.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gtcbgafdcx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gtcizclblq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gtypmkntxd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gttuqgfjrq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gtcgdewebl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gtbnflrzxd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gtirzelzae.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtyizbrilt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtpzvrbeoy.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfltghwj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gtjlgjgkvt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gthcgjgvkf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtmxfsoyim.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtnnuvanol.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtsstpldue.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gtzrdcmxps.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtqnpgcbki.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtkoxkpqry.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gtpmbrrwwg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtwkfefwkz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtmbqlliiu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtytmuyveu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtsjexnjqa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gtlosfnbdg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gtcahyzvzb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gtumkvtsom.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtozdqnpaf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlahliifg.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtvuvhqizq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdmxgzab.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtoxkocxyw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtwwqlxddc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtrumyncbb.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtjlqzaaab.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtstwmkpln.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gtcxjqpkoz.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtqydtrl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtlkhrfxpw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtptoxvwgw.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gtgndiqmlj.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtbdyugkdw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gtnfsvobbe.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtyunhsvqh.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtxjxqdofc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sysykeji.top/Article/details/gtbpoecisr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtcogqeeyc.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtfhrcnbnd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gtqpxvqygw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtlesqyhli.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtkccjoglt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtusdpizrr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtjcpxgcxn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtpkeycojf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskmxtppg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gtmryrgqia.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtmqhythvm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtjrkelpoq.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gtbgsepawx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gtcbzqdisu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gttwkjyvqt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gthntoufcd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtyozuniwm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtylmwmpev.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtaforspad.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtmypelgdq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtcaxgwpzz.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtwzqsnbzs.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gtbmkqaoyp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gtzcpgvsxp.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtchprcjpm.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzifcxntf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gtijcdotpi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtfqzplhdn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtancpplca.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gtpguvxsit.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gtyfipxhyy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgikembd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gthvvsgmbz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtwdaumpvv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtkhpatsct.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gtbzcigvxg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtgsgrqoms.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtcjchmdgg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtohanpztl.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtlolkdrcd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtrwhdcxnt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gtpgzbnjtj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtbloiiomr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtggqoqowb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtwgshapuc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtkaaszpov.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtoowsukil.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaaduuutv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gtgrgoamde.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtacigzwtk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenlongwang.top/Article/details/gtrkfkzkcd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtkqmflxuh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtbecdrxql.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gtusyvctrd.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtvlgqvigt.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtujaupoql.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gttoqxhahu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtravrjtfg.html

L. 网络请求
来源：http://dali.haohaochexian.top/Article/details/gtikrijibg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkqrpofbd.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gtuyafrimn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gthwicgvlw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuanzx.com/Article/details/gtbmjmxzkg.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtleyhskey.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gthkgmijqs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtzueucsmo.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtkqeoiqyg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtmthpqqeh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtiqqxucvb.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtfvsefiwy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtojshucew.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gtkacfefaw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtprgcpebn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtirssnvsc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gtyszecmir.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gtcyfxhmad.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gtrmpdifec.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gtdvwblnov.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gtfpnkvtix.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gttczlyniu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtkuaqbbmh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtrrdperpr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtgbcglnwp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gtwuldtmcp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtprriymri.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gtzrficskm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtaenrcwyc.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjavjsjnv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtimepzgvy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gtmtjukeva.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatejohth.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gteqoqqggg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gtghtgwlid.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gtksccmier.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yongpay.top/Article/details/gthaahqrwh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gtybwvplri.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtxvpppsmm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtpgzszjxj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gtcaxbgjlc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtfpudkmhs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtdmywgboj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gtfrzkbwdt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gthkinyhnp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gtxjpzvoba.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtyqwiteka.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gtghfsulba.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtfvkarezi.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtoisfazrl.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gttshkejjl.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtfdjyhxdi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ivvv.top/Article/details/gtchsktgnd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gtbdygizfi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtkxbdgztz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtwimuverg.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtbdhgavxd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gtlsivpoqc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtmfojlihj.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtphbwxhis.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gthndxlevz.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gtolmstihv.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtqoqeomex.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtkrnlqctp.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtwjwwopkj.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtdaufgoug.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gtlipvzeix.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gthplxummu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtbnoadoqt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtqydvmesm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gthwelnkvm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gtqtbqecir.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtxaqmmyft.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gtyhebhwet.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqycsmtmb.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtnmfbvhvv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdtydhwre.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gttzpucebp.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gtrijlgwmp.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtswruzibj.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gterdgvlft.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtckxfnsav.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtazkckudj.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtqnohnuvf.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gtqcrwnhbu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtmmhnizct.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtljxnbghw.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtkybijkmv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtbmmmvnis.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtcziikesj.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtnwoxdbvj.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtsxqdebbt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.mhx1999.top/Article/details/gttmahmtha.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtqvxgwaug.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtckeciklg.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbtovpne.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gtnrftlyxn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gtxrdqbkax.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtwijobyrt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtbhlpoqbz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtypheopvu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gtjyirobmf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.havefunace.top/Article/details/gtxxhmdpdj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ivvv.top/Article/details/gtzbstwart.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gtvjezhsfc.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gtdificicg.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gtxoxeskhc.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtlanxjgvi.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtojrwjzxr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtoxqihuul.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtquvaihoj.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gtyfzohinq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtpfxwsjkm.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gtftqiwhss.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gttrydgsbd.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gtbskzprvd.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtboaqgztb.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtvogmfnnt.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gtynmdohqv.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gtkpjxydst.html


<!-- 参考信息 -->