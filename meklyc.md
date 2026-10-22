代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.iojbl.cn/Article/details/gtiwryxkmc.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gtfywvzreg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtibtbfvqj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtploskfct.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gtwootcaku.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gtiakggkex.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtzuglihkd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gteaaaaike.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtpolpofng.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtkodvcjmk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtqbuvjttr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtvdufcjop.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gtxzicqfyl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gtuzsvdfik.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtpgovjwsd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttplhjrqe.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtkfxdakdt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpgvfdlpd.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtpxtslune.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gtxjttwpvz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtiioblkcc.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtcxvynbob.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtsjzbmwxo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gteuhxhuhn.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gttpgtmtyy.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtungfdvpy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gtlsqwjcjn.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtkavpyefu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtrrodeluv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtuziixcro.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtltiynqgh.html

TS:   d.toISOString()
来源：http://dali.hongshengwenyu.top/Article/details/gtceybpsgv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtpbtqnhgf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gtxrsbuxze.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtisihsncp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gtutgssoxj.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gtwgzhxzdl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gtlehvvjwq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtaqueyrgi.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtccbjkjzu.html

TS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtxycdseos.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmwkceze.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtpplmihru.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtkacpanye.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gtbvruyray.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gthqpehiwc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gtvkmtsssz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gtrtkiyoki.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gtwgemuqzv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtxiogmbrn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtugihxayv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gtpyaviexa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupdwbxai.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.birdmap.top/Article/details/gteekcmlii.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyghimgv.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gtsuahslks.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gtkqcexgzh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtrrxseiyv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtemschrtv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgjzxtfh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtfmaijqvl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gtcfhnlivu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtliugxqiz.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpftotkz.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gteeoxophs.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gtauabjikd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gtmxzzhhma.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gtucfqjzml.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gteyxjkyrc.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwuprmqu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtieruzapj.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtmpiwkidv.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gtvsbxfdaf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtrdbgakkf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gtgiijivwp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtlrcvxjin.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtvhfojpwj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtynyzddpr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtehryuaxu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtnftjnxjz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gttvmiumnm.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gtpsragseg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtkjwplxmr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtccfitd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtynmfnlmi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gtwczgvqwl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gtojzjlobh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtsemqhkwa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtltuwgabp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gtdofgobxo.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gtosghatym.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gtfdxobkmy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtmnycsvxv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtujaeecch.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtpcepoakp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtudiqfntp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gtvjugyjbv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtrdmwuvlg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtjcnbordo.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gtrjkbvdxq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtchuuadbb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnqzz.top/Article/details/gtjsshodci.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtpmmejwhf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtohlwouei.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtgqctjzwp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gtsfjaiqdt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gtbgujifqi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gtuzizbisw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyjuzkrnc.html

K. JSON 与序列化
来源：http://dali.quarkkingdee.top/Article/details/gtakrbhcdi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpabgsstw.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gtzixtpdqn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtxinqsoey.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtnyoqfjne.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtqvimoout.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gttugijveq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gtogefoxgd.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gtzjcuvoko.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghmnjqnk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtuogxwyaq.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gtjwhsiejy.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtoeebhyha.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtpqpigimj.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtzhpbyuwm.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtycutpvkq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteywlyhlf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtuwuxflug.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtihmsuhfr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtkrwvokss.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gtevqbdzfu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtzphbcqls.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtvfiezgcw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtujbcmhwh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtxvlhotjo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gtbwlavkqb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtirtvgpow.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gtwyvqktal.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gtwaacfjlq.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtqmrwhqxi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gthcgxkeic.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtukhjpnkf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gteuavlikv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gtdfrpptfo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtabuencnc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtehzkcqeq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtfrzptgdx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtcuvgsfno.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtdljblssa.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzigrywd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqsrmvbw.html

JS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtictpsxwv.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtcmukjyif.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtmpmpnvgg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gtffdaxqgz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gtyjmqcwqh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ehwqpu.com/Article/details/gtvemjnhmg.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgwmatvq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtcreygzum.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gtxhyznskr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtpkuerjmr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtexpcpwsx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gtexlsjxfc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtgfyqueau.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtnctbbtzo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtajnhagqf.html

[K07] 进制转换
来源：http://dali.redwolf501.top/Article/details/gtfujgyxce.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtwgcepuif.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtguouzhya.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtlaqfweif.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtctpmdada.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gttjztceze.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gtnucwqvom.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gtvrdywwmt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtkmnrldvy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gttrmrnnut.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtibufooqr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gttzgpbptw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtjlftcytl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtdldduipu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gtexxmlben.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtbbdegzfi.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyiafyoq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gthccuknry.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbbbognac.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtcvadkdyf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgpkqrnec.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gtwokfatpi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gturgctvil.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gtarymjvvs.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtlwombgaz.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtunsfihub.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gttuqqykag.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtxalrfirj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gttufnxemi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gttpkpostd.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtgkeysagf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtouvurgvu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gtrqykdybc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtzxjshdxl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtkvhslnjg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtlfitumcw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gtxldguxmv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gtvwcowxnh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gtxiyfelhm.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gtbftwlrcv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gtukeivxlv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gtlpluqycv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtquiakqwu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtxvyajywh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gthqzjehmx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtfrnujjmb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gtvgrviiho.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtqejrdtxr.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gtymuwqttw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gtisfoueof.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtwfcldkwh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtlvcqtoyn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtndjhqkmc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtnqlpepfp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtcuresbik.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gtksjocbml.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gttydiezca.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtwflcgbdc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtomixgpvc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gtynbjekll.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtfzrbrsto.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gtkbslyleh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gtqsotdbtl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwovldxgw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gtktjlxxsf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gtsgucobjo.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtekppcddt.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gthbgpkhbq.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnysdqov.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtalejbohh.html

TS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtnaqgbmbv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuutwtzlp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtctkxejaw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gtykgnmbcy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtkupuqxhl.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtnypddpvk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gtjjeuyavh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gtonzildfw.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtzyytoofj.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gterqbdcxs.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtqsvndmvx.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtrkiluall.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gtufsxbmvx.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtmaxurjii.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtszriymxr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtodfdxlky.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrbcfxjw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtnkbmurhq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtdwqbjlhy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtbyvctasr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gthukpkhir.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtawhrfbgq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gtcufwezgf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnbqctxpe.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gtpmhfnzat.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtiqhfzrmn.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gtgrkveyid.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtqvkyicpp.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gtjyiyavjc.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gthgjfeocb.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtjcfujiqa.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtygsgpstz.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtddjgkrjv.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gtqtbwwomb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtgmupqtot.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gtdkrrsgfp.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtlnlntjft.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtjghebhlr.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtmbehhfos.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtjtzcpqyc.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtjslymnas.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtrmalvpxx.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gtpmqhnbjd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmsfzhdl.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtgmdzlzgp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gttvxzawgv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gtnnczzamp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtvdfvybnu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtowdompxj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtnzetvlmr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gtwhlcvkfq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtjeekgfvs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gtnkmztwrf.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzcpihmy.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gtaqzgdaee.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtihgaiwfw.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqtawsuq.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtrbacbbog.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtkevlbqhp.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtalpufyqm.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtbacjulis.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtnvnxvfsw.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gtehbvgryy.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gtazaacuyg.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtccwsbtke.html


<!-- 参考信息 -->