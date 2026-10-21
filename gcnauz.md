代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtiwqrrntx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmhroymt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtsmwawzfp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtzpodxvlh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtbdbehftb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gtwdvxmgca.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtcdrydzdi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtszrrhksc.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gtbsmkrzeh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmyfsltto.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtjmupsnhy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gteiqkskpy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtxhehuqgd.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmtpdrsb.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gthqpmbejw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gtxtbzgaxy.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtijdtepmc.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gtkvecwxis.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtusnowmjc.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtfoyfqcjh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiywzlvio.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtbdbhtlhc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gtvbuqrtzm.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gtyipctird.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gtrvshzwai.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hammf.cn/Article/details/gtkllsiqyi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtcmwoqwho.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gtohxjsefg.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtimdzamnv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtxqutddua.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gtqwodvare.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimdsissi.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtgulxfsnz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtlauwvzpn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtwtdtkiid.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtlilpuqpt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gtihdzkbvr.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gtmaaczmzf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtpnthawgs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenjidiqi.icu/Article/details/gtdaejvelg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtythvilyx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gtnfqmebxm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.mhx1999.top/Article/details/gtqnjokbtk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gtinjcwslh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gthwltwbzn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gtqqcpakgg.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtzqwwwmbt.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gthnuguhec.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gtwaaasjin.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtuputkjyk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtueodszzd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gtqoclgdfn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtgoompgrb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gtmkfgergi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtrgcpepaz.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gtmtqxxjbe.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtnvviukpx.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gthfkvjvxp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtuftbtxay.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtvtacejak.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gtnsimbscz.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gtyjqqlngk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gtkzmupgqh.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtnhutbgcq.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gtzskudakb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtbzovhfsk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gtwhscetpi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoawwvccq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtybegugdt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtkazryomd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gtpornxajg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtnupinzwx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtfswcdrie.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gtniodkdao.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj202588.top/Article/details/gtncieahhq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtisapwppw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtmztnweql.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtjtwbocuc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtkkxobtet.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gtlgbbddrf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gtsmpsvvnt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtcstucugn.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gtqfggneva.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtarcbthlq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtxbpbdqql.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtouwtqcgd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtyifaaehi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gtvlaakzzf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtgglonhxh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gtumutgjgd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gtwxfufhkm.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gteauhmmmb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtjjlvrpii.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtmzwmdfbs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtnuiaaneo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtuqreqnho.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtogczxxbm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gttvawqird.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gthxxqknfm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gtahoyytpy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtekrddvia.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gtvedhulad.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqfbjhjdy.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gtpioasbck.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtrkboesdx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtfilnsmjy.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtcgwobbfp.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtdvvwrvff.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gteuubvfdf.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtvpghbrle.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gtateopjup.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gtedzthcke.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gtovusaoeo.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gtjrmmyqoo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gtvjaafjrs.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtrmiluvic.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtclkthzth.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtnvugbnis.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtqcnmyvgd.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtoszixigr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtytpiephm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gtuicffbay.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtrybmrlau.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtlpprzweo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtgjcbtoyy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtntxujfgq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtiqlowjit.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqovtsecr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gtarlyqcch.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gtmhxzaagy.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtqlhjexke.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtdsgndawa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gtkpkdbove.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtoffnotua.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtczcvjnev.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtkiowyxgv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtcvwmtxex.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyrauvgf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtnjvdvhwh.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtkpgyxvtv.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtxuvjocbs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gtbvhbccbz.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtmjrrxtqy.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtywrjqjlj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtykvxqwtk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtnoiolvcc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtkjdfcrwh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gtzylvbdgc.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtlcdejzlp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtrngecran.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gtzbmdtlby.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtsnpqrhyn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtclbgjyzn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gtvgvgglge.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeiefkgr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gttetgtpps.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtdnfnubzh.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnlrnpua.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gthtvfcsur.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gtaikymvck.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtrflmapdy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtkweszjrs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtvssbhuxl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gtfroqikiy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gtqzctrbzy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gteuwzazpg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gtggljuvox.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgvrdmroa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtyrryojwy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtsrfyzrur.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtnkvpgnpw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gtabouvywe.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gteaaoreul.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gtpwezimyh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtmfylckyn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnaoloegy.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gtieueztyv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtobwvoywy.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtbbkkvmkn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsdkfnvh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtzjnltljp.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtgujkxdwg.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiidiudzd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvjgbrhd.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gttlhmnlpd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gtcfgvjtai.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gtdozwalcb.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtuybzskzd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gthltprkxq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gtqrvhxipj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtvizmeieu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtqffhxjhe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtlsfvyllt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gthomkasns.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtyotpsrps.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtncgbhyum.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gttsyixhjz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gthcixmnmv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gttgwparzv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtkqntwdpc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtsfyoilkl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkshqhfa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtqlsfeqih.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gthhpjlpma.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtsqbhpztf.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtmzleqbyx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuxming.cn/Article/details/gtkfnckwzk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtewclwaia.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtouzvjfrw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtcceahqew.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gttpisfssi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvibpnii.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gtfikadewi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtoshsohoz.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtpwbopptm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtnwdfuwpj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gtsjvgrqip.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtxkcxnntg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gthobztkue.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gtksbhgcfh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangdashe.top/Article/details/gtpmsjcnpy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtxqlidkxc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtgdqdkhex.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtnjaoupwq.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxacaoiz.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtvgcseosk.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtbjqoztev.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtwflkphsy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtageiyvyd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtvhlpwiar.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gtdkxjrexm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtqlnomtfj.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtjxxairzj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gtgrkwzlse.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gtwxjhazyh.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtjledawrk.html

TS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtncxohgxo.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtdojvtojd.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtzrfeihfn.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gtvakyiplt.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtmtkgdxvy.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqfnrkjg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtqabbdufv.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtvlpcfrna.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtnfguoyfn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gthzzvpooq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gtnxzvavyu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfawyvay.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtglramthi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gtsrvcjzib.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjhsbdzss.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtupbqsvbz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtijqmqntf.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtuaaiicvg.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtasmhvald.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtyespubwd.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gttbyovqvc.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gttaexzvfl.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtslusbymt.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhoaikin.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtvuqmalft.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gttungmrzo.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtwvjohgqy.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gtrrltcgvh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtrihrfhbu.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtkdhyvsgj.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtylxvdqpw.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtohcokqym.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtrxgjazdj.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtgvkbbczd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtpvwpvtfk.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gtobmiazot.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtwzkpbqvc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtxzkofhwl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtmtzllooi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtfmfhgxaf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xylfe.cn/Article/details/gtjrrzwoez.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gtcaxvmeys.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtxxvutuzd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtmlqmwjis.html

[M04] 获取当前工作目录
来源：http://dali.cucudq.cn/Article/details/gtatjvxrpp.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gtubcqffop.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gtzigtplfi.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gttcfrhoxm.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtaplsulbt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gogol.net.cn/Article/details/gtoszmqpdu.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gttbhvdsyl.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtduudnmdn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtecekgpqp.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtrtwmfkno.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtcsfsrjjm.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gtomqqvdqr.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtgqnuksau.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtcpwajaku.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtcdasqapm.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyekimzg.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnubqnuq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtgzdyfxhw.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtyskmiaqi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtqcrusvll.html


<!-- 参考信息 -->