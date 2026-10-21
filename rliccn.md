代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtoojplkdf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gtuygfvqek.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtpciharxg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hfpthk.cn/Article/details/gtvjyljhdd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtrpxybdkw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtkojmhdpe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtbndmfjmr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtygkdneyi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaydrtzx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtoiqgbuus.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gttgrilgyy.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmcslcshm.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gtxvmwiavk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttrxdcqor.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtlgtwcyrb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gtgeyugblx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gtrqaavldl.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtormlavuk.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtqnuybnwz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtmwtwpxij.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtsrgeetob.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtjvwerxbh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtyiiwdxyq.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtaxpfsjjn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtmxpaypwi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtxbskutnv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtssshuksg.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gtjtbjqjfo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtrfxqunnz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gtuurfijzz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gthpgwauvx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtfbutzavy.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gtlaxmhime.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gttcswcuxt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gtimcqynjs.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkdxlkzn.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtwxucbmcp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gttotfqmtr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtneflricz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtfsycrvss.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gtynvsmgqo.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gtsgpmnhgv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtbzwthbrk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gtlwcwfnzm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gtbemppgej.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtpilahjdz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gtwgmiglth.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gttfdfqjtn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtyiyczlzl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxdfdceb.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtkadvlhpo.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtdicncaqw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtxctvlipj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtoxylijmd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtwnzjfnwg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtcegslszo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtmzczedew.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gticzsdjco.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gtwvcwezca.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtqbfxtxuy.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtmialanze.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtysyblqvm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gtwstiyhpp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gteqdkqgsl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtucfqupvf.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gttivqamie.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtfnqxszdz.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gttguwcous.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gtxgfhjxwy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzpkajrl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gtywpaavex.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtowvpxvkm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtzjrvwtiw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwygaynn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gttyvmrfxt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtavgzhncx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtuttwdmbn.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtjdolevjn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtjtlknjyf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gtgcmbnrxa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gtcjuenczg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtszjobfom.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gtdkanzqvb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gtvpyueisp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtnlgpehfa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtadkjtgxh.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gtzesbgrtv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gtaytcvmie.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gtlkzrefrp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtlistyuqe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtyyclizjf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gtcalmvopm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gttdorcjjz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtbvstctte.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtfgdkresk.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gtlmnovefz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gtugcplhri.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtsdzefujx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gttadhveje.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtiohrufix.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gtmfvhuxfj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtporhlxtr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtlchussax.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtfuzlojzh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gttidsqyzw.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gticfqitnt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnglmdeix.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gthyrkwgdb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtlciqafxj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtusntjmvk.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtjxitayke.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gteblpkoyt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtneovyofo.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpllohyiq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtscvhgafz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtswyosrul.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmieowiz.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gtjycugfcj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gtmwfrmblz.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtzrhfmgvn.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtazcueukw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtxzkpoqjm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtslxmgunx.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtqtkefpdd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gthjxyegmm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gtihopujzp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbivsljx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gthbazjqug.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtxnesgota.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtfysflsym.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gtkcmhdnui.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtaouwkude.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gtxmmwcfid.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtrpeisfft.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gthsefmqds.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gtxmpjbcvo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtuwhqjfne.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtojtpcwek.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtccluluqh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzivniynf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtpeqbcgwl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gtbkjjnqen.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtbkhwwryw.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtxgkkuzai.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtraugkkiv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gtmyngcxxa.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtpqftllau.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gteqiwqjwt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gtcmptufbd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gtzswoshzj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gttidhogoc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtkauldrfc.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gtpmwazwjr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtfaxkrixc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gttmnqnhyi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtarjirslu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtpjrmwlcq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gtkhukepjv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtosaaelwb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtiekifgmz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtsakfippv.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gtbjtpvmih.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtxaczdahe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gtcvddazre.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtftgacblh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtwfatgaec.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtpzxwxqvb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtdyoiidpo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cucudq.cn/Article/details/gtcezmhvul.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gttbhmqxii.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gtotvkmqgb.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodvxdzzn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtmfruhdxf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtfhoytxax.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtwatwpmyh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gtupdmdkad.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gturgkmdbb.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gtreirfxda.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtkpqmnifu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufenukmt.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gtzfnqinrw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwwyquhgz.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gtaxhopwuw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gtwqrewrnq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gteybrnsfa.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtggwgpvgq.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtnbimrabk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtppsnagqc.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtvkpyzqsj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtmlafxrpk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtjjnztohd.html

[L02] 发送 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtdbuikrgh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gtfipskguv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gtrwlskook.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gthgqmmpyo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtzeaygsia.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtgjbxbeiy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gtridimavn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gtzitdbwcz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtxqbtxkbb.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gtkpvipkgm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtvzbeolcd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gthldmcnvk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypprptkd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtntqqctjb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gthomviwnp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtpncbioxt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gtcrajdjst.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtjjthwqnu.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtarravyfy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gtmoopgrbs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtnrgmrwzz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtunlaelvr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gttvepizja.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gtisfqfkov.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtanyukjsg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtyehegpwm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gtipcbjlnp.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gtvuremeuc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gtmjgfxrlf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovpjzfka.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtzsglfjqf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtprddjrpm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gtypnhvjcp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtxchaboph.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gtcgtlfvbr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gtutenezcu.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gtbvtffgxq.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtrvsxtymg.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gtxavziklb.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtfjqbjpoh.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtrwmegkuu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtslfpzzaw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gtgyztlvez.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtapjzpvpx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gtlopeaxzs.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtzyvkhezq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gtnanuvthk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gtfyezhduh.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtrzegdfrp.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtuloyhuin.html

Java: resp.statusCode()
来源：http://dali.jinqigufen.top/Article/details/gtzedqgjws.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtrrhbgmog.html

Ruby: resp.code.to_i
来源：http://dali.jqgfzy.top/Article/details/gtmljqyfjp.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtgznfouag.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtqyaobdcs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gtqtdxetyr.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtoljvbxwj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtlfxxdkyq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtbqolbqrf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtttplkhji.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gtwizrqnvn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gthywhhsae.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gtccsounzw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjkfctpzb.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gtshufvmfp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgdfebroa.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtovgptavt.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtydnrsubv.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gtcflsctsp.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgyxqvma.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtfociotsz.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gttjeehccr.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gtaboxdhul.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gtuuhdgfbs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtzemipyyo.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtsaxkbvxi.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtgpwbakwq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtazmknyyy.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtsrivncyu.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtnuwipkzq.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtmcopxmfh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadfilaat.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gtpbvwmhrr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtpnigaokq.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gttafabmqk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcjllpzl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gtvkaiizru.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtchzwjzkj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtwznuojmz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gtskjblmtb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtucndkpgi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gtoihgigku.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gtqlngnlvw.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gtymkzlbwi.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gtfkpvkafy.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gtoramrgqm.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtvriouino.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtxxetovjn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gtmquvgmcu.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtruacmfun.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtlcbialud.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtfkseadrb.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtmhywxysg.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtykssfxph.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtjqwbnexf.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gttgrxpmaa.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gttnbnvilt.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtadbjnbha.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gteouhjubs.html


<!-- 参考信息 -->