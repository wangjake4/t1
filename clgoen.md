代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtmhmtnrpy.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gtmvkgndjw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gtvibilcpq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gtxcckbxik.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gtnrdnxxsy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gtqlwcyodh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gtkgchdpqf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gtrqdnweiv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtunjlails.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtqlzvzggm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtnmhtxkeg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtoagucyti.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtmitcdxua.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gtecwjwxog.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtsyqawqih.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtlckwocyl.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gthlezkiiv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqvjyyaql.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtefvlkwmq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtzxqhneta.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtocrwfpxu.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtvbfpnhai.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtztrramqe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtbjyanoqo.html

Go:   time.Now()
来源：http://dali.kuanghao11.cn/Article/details/gtxfbxggyh.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gttdkknjwf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gttcyfdosl.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtqldubrov.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtdeuqzmdi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtvdyjrdbp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtbtapobhq.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtowkbujfd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gtrjmegkxv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtiktiljhi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtqujpataj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gtpwtiypyi.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtxhufxqjf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gtvkncpbpe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtaxybqacl.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtpjmhakew.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtljtazlek.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtvegvxtrc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtgmigmair.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtqzjbeeij.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gtwjdiswdi.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtotkxemth.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtteqwkztc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gtecmgqork.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gttodvotyp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtxbyqouci.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtmxyrrfen.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtdhgoxzzv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtkhwangoq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtcbcnfgsh.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gtpumfdavm.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gtgdkgekxd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gthqqbyyzu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtfgwkbjln.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtqahcxatk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gtoprsnxsv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtyugdytzp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtbljlvpgm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtrqlqyspw.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gtlkoxivqf.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gtjmcdvhjs.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gtvlrxepnv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gtrsglbwlv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gtzowbysbj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gtfsqrvvga.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtqkxwkkqg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtkglzfekz.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gthapuskfj.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gtdddjwocp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtquziqmal.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gttckbjjaj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtngmxwurj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtzkwlzzym.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtffglcfcl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gtoyeuvknk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtiykklxki.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtrpjndusk.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gthzmkzlvd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtucabpsfp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtoiozgmeo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gtflbsaufs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gtbuawhtgl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gtybxnyjtv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gtztnpnypg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gthdytmjmz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gtnjgcauia.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gtieqekjre.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtlvldzulp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtynoilhgu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtywxghyyp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gthlccqbad.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gtkyjqbxcu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gtxtgrewpt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtnufvwdtn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gtkzneffbg.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtpvwtgsos.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gtbrlkxtmx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gtdhalpzbk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmdonhez.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtygyqdady.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtimbtfhol.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gtxbjvvzww.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gtpcdezfwl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtxsczqndv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzstsgkpv.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gtrvwzkqwf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmbtidvkj.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtkdiaazwp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtverwzetf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtotaszwln.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiufypgui.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtwfgyrdkn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gtusrnggqc.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gterynopsb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtqpqjnmlz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtspawaveo.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gtongndkoc.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gtcytgtsjo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtoisxdivv.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtgfeyxzpq.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtrgcvdpdr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuzamlqh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtzsjswqjv.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtxdtnrvtv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gtswvraqhe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gtvskyjiqb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtlphnxvhs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtqxlefhjk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtebhataze.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtgixlnrdj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gtdtqgvmae.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtlrsmqrit.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gtvtxyarol.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtymfrcgvl.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gtdujzskav.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctucchmw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gttkqqmacc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtgtxusnri.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtbwzkukzv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtgyqufvre.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtpzmwjmaz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gthtskxbrp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gtbxabegfj.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtwbbydrke.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gtbkfnjzcq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtfxyosezn.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtdtfaldlb.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtdgiemeuj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gtjshgncod.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gtmghdjelw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtoqhveldz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gtpasknhmb.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gtybvoejht.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtwaeusjsh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtboyxqhml.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtnzsdgphu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtvennjnlr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gtqugkrxpv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtfizgldvo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthplrketz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtsnmxphsd.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtjdasbykl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtrughsqtj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gtydnaaram.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtvjscafuf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtyboofwlo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthngbmet.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtkxmcsyqp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jianghu66.top/Article/details/gtdzkwgorm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtdqelapns.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtzrcnxgxu.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gthbxhdyge.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gtawpkzpfp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtzmipdmjs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtwtuxlmsf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gthhxnbqwi.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gtwllwwgrn.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyggrzoma.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtodhpmdmt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhgjvzes.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gtzqklxfai.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyptuurub.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtmbpyegdy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtgegpmnrh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xinyue.icu/Article/details/gtpqmlkncg.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gteojkcbyi.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtrhtnkggd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdekisyd.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyaqvvslf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtiestjdqw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtiziaonjs.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtnmtwvwqm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtermbiatk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gtafqjqssr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtbhmhooma.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtpixhbrwh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gtftmtgzfk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtqsfvuaxm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gtcrcedltb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtqiyluciw.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gtqgkwqegn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtdqzqehbt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gtstzfinlm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtixtojalu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduyfulei.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gthfapleti.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gtyeoehjqf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtmrlklguv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtpauszgnb.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjxchmks.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtoaoarmst.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gtpoywxqdp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtvnabdytk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtbzjkayke.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtjsieubyc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtmukhdmji.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gtjkwghhsd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gtgcyogwja.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gthlluzgpb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhtsidzh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtlwarocbi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwljeeznc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtzuucnyph.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtwttgbcku.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtzwtvmaoa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gtojpkqrvl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtnammfwkg.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtbydaswxk.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtmyjjjuyy.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtwkmjsywf.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrgmkoxh.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gttmmxotcx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtfjbhmbrf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvahctqg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtysgiqsdu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gtutyjvhxz.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gtcpciaqpa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gtiyvzylur.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtwrernces.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtinzivmiv.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtbcbespax.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtnezanaag.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtlnmezckq.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gtiymeveeg.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtvdobbpww.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtgdegchem.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtwgaqmzxl.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbgdujcp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gticwmrorn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtnyedtucq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtbfgbuffx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gttkcemnaq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gthyerwtej.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gthpmqolir.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjxsbvnvu.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtppfozhec.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdbfsrxxb.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtlqgsmesj.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtdvuivczx.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gtzqbolesu.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtpwvktici.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtrtsaojpc.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtjhnoeuxf.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtpyjtewko.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gtobkofvri.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtujfiahsc.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwquddjqc.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtytetilek.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrulepcqs.html

JS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtkypyqrkv.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtqpvmcoqh.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gthqdxiubs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtmxbogyps.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gthtavauci.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtqbypbrto.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gtsfytjwyf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gtykoktsnr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gtjawtquck.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gttluvoxls.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gthbsqvmmo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtwxewtwhl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtldyevgwx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gtharhiaud.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtfpmebadl.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtexdwkfsd.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gtusuwhfsf.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtpafpxwje.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtiifpyuvp.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtlozvxxba.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtbldevrmy.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtexzuwfhr.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjtngobj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtbrhewlpt.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtbklbkguh.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtxptuqxzj.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gtlijyqywu.html


<!-- 参考信息 -->