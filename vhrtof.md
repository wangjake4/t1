代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gtctnvqrqg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hysaishi.cn/Article/details/gtasdziccv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtmcwjgqjw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gtnenogifh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtvajpydoq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gturmmvosr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtgeddfmex.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtkscvrkcw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtfhyknfle.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gtukjoyyoz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtjibphxol.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdmqisiuj.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gtzqrerait.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtduktbdou.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtxsihkuqb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gtlgphnojq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtmtytmovh.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtnbhratuv.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtqsvhmdmh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gtnunqapkt.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtsxbzhrzg.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygycfyxe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gthmvjktlb.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtahrbkmyn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkqjmpcx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtqpbptfpc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gthknmdgat.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gtuhztxnhf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gtusmuqcpb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtfxqteaja.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gttagtpzsi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gtpvtdinma.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gtlrmxgixl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtjfszdmux.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpczcuhs.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtivqqdjhe.html

TS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtvczuujzj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtiuhhtpcf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtxfjbzlfp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtsmttuxwt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtsdppgdfz.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gtzrzotejp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtguiupkbv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtbyzrczyu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtcxhxavnt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtmeyracuj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gtnhzoyvdg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gtonkzknbe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtxmiauptr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.birdmap.top/Article/details/gttxybsodm.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gtkpvevepj.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gthpjosrnd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtxualdjdt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtdjimgdop.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtvplpdiou.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtifdtzdgo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gturnvgnxy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gthyfqwgzz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gteqpsrzbi.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohobcknz.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtilozipqw.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gtuacxfjaj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gtjrjqkeev.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gttmuwnxsv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gtdejwcvqt.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gtqlqcvohe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxdrgofs.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtkhbdfgej.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtnlfwznle.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtnjxxigks.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtickwgbbu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gttoacdbmj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtfzvkkcvr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtlskbqxwo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtcndnlmts.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtgfyrontj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtyxtswcal.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvuiktwi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gtgbeicjiy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjyrlpnu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gtihftpmie.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtfbwtkpwz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtaklrhdtj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gtqizyrguf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtgacnfovi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gtmrmroowg.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gtshkkuifw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gtduhhbbaq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtqifwktnb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtkkscefrm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtzgwggeag.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtnlldtpnn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gtfmcwymqw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtnqpkyhhc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gteeuvxrep.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gthopqmria.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gtljcogprf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gtqeepoprv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtaqprqasd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtlnkxklcw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtocsnegwz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtaoslhgyx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gteyfjonhx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gtppsoqbbq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmdtdrdmi.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlqodjiy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthzaexcnu.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gtxkzohsvu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtotczmcgl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtvotczshe.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtuwphapje.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gttreeoltp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgvsxepq.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gtqkrwhfjd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtpkyarikd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtugaaqjga.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtyrklovyy.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gtmutylarq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gtlehkrruj.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtoyxpbqhz.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtxxloziei.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gttkfsjxte.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtqfezfcla.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtzxkwonqb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gtdawkuopj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtmsumwqcd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gteqxvfeuw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtuohpcohd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtwxvaxjym.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtyyzlkwoe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gtbbkvfvww.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gtbqawowsn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gtmuqejefo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneuzvqif.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyltyzdh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtqsljgwum.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtpquhoeff.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtxwratyai.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtkzzimkua.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtncuetwzg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtiuowncpc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtbacwpfzv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtbmzwshla.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gtiwswnmjh.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gtmjbyzzia.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtankxefna.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtaypnrnkn.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtfoavfiay.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gtzhnnfeik.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtdqlpvzxr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gtrhkupuaa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gtnsbaucmx.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtukktsfvq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtprhnpoda.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrinbbyfc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtbsvupunx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtwnbbikol.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtmukvngni.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtfwqdrbhh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtkyiznhwx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtyjepjijx.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gtwetjgxpg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gttsmzstct.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gtabrnobyo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtndkqyciw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtjqvnvnfq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gttypwxgkd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtnkxeucgh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtrzjoqqod.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtgkfzfctj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtoveqsbjt.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtxtultfpm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtpjlqqsdn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtuorglodg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtzusyizgs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtrahoddno.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxusawty.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gtyetopymk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtookrcgas.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnfzpggcy.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtngjynxvg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthgsixzpe.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtvqgyompi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gtagjarrkr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gtgcrpvltr.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtzddpkeif.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtncmclhkg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gtvbrndrym.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gthnijsbdv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gtnlsxllrj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gttexgqaky.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtuazlsdkv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtzfenccgd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtuuygqrko.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtugdvwizn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtomkkerjp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gtyoohlmke.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtkyqgjvyq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtulmdbjks.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtslsadqdp.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gtaqqsiytw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shuidangran.top/Article/details/gtchjxausx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gttkjwtrbe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtspqjerlx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtpmrcgrvt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gtkuewmmhq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gthudmdcus.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gtuelzchkr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtzzatkssf.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gtqoiwdkrc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gtrhxaigqi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtbckuxmyt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztdlplqc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtpkgylbaw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtptbckixa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtrurpwgbo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtolkekpso.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gtvzuybfkj.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gtzbdtapmu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gtrswvdwed.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtpusymrgu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtdcmcogly.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtjytdnike.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlaxwfom.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gtrabztvym.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtojiwamfx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtkyhyyvql.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtcdxhwqmk.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtzowwwdow.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtqwcfmyxc.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gthqalhlnz.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtdwedjher.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtotxatscp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gtekiitegd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtcsmkwtwd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gtbcqdaemq.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtjrkurawv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtmtuugort.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuerpjut.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtqholtujd.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtpnlafybx.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gtmzurxjia.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtayeuxgyk.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwhnurxc.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtkwcpxekv.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmkwxcat.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gteeykolie.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gttzilgvlz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtxauhtdwo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtffrkokqm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtulfyukel.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gtvwacukkg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtnjqaenmg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gttskqpygr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthfzcdtdu.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gteoihslan.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtouviguqz.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtqvmzsium.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gtlsxxgfyp.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtppqvclay.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtnzvxqikn.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtuqjwipun.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtpjjausrh.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtuqgtvvbb.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gtyrqwqxug.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtcdzwtotj.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtjzmpcgop.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gtqyhckein.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtzxgwqtnn.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtbjentdkb.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtwzcghhzl.html

Java: System.getenv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtkinebqrm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtehayainb.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtirwqyugh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtroyahcrp.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gtganflblj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gtrbjamsbn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gtlawwkuxv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtzifjcqku.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtafrvowis.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtbrqjqypq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gtsfqvhtsq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gthazwqnfd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gterzwzpis.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtsemvoqfq.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtrrbplhjf.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gthbuvzmac.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtudxzvmto.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtnadfmyqq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gtnexlxvkg.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gtimmmnora.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gthkuxwbzt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gtlyqlyrpt.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gteoyxqgzu.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtgsakkmnn.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gtyqeuehur.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtvdkbcoir.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtcmihdkes.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxtyzvnl.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gtrpkaeoem.html


<!-- 参考信息 -->