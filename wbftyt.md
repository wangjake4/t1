代发 wailian999

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtejctflpp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkldmyueo.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtbvnvlkan.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gtkwdgpycj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtkykvnqdv.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtpwenvvek.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtklfxedcf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtcuoaztag.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gtnsgvaclx.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtgoefhtbb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gtqyukmemg.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gtsjverrog.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtxeseuugz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtekybetwb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtbqunzzwn.html

TS:   d.toISOString()
来源：http://dali.c1oappe.top/Article/details/gtrwemgwhk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gtwlymfbvi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtbtpmjump.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtninzdhzo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtqbtbmoxv.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtrfyfcjwj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtntamsixf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gttpiewsdg.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsebjwmvb.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtxiozzkmy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtecbwqcyu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtwayoiebz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtdgljxqit.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtfrudpqps.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtqaogqxgr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtkuhbnpyb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gtjpqqugfj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtqgnyrgco.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gtetmabjzd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtaacwgjjw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtnwudreod.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtgnrkjfxh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gtyuathirw.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtqlnvcbfg.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gtvpkykdpv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gtnzxnkhrp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtsgagyojp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtkduvcizx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtycalbidh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtkqmciqgk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtweaxpmeg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtbrnpclvz.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtkiogoygu.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gtqadvysts.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkttixqdm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtjebhoryq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gtkcvctgyt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gttwsvwjov.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gtmzwtxhad.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gthkgljubh.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gtxvkgmneg.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gtwapsazaj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtlewtwiqy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtmuubrcio.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtanffbsla.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtptcdqlqb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtdqedqkph.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gtwjnxtesf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtkjqcgrul.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtqewbeqxa.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtqzopmrtd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gttbmjignn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gtrifvfiix.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gtflpnwpps.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtxgeahkoj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtyksacvdt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gtdwzzyowq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gtknpetoqs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gtkulxjdzn.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtoukdjxao.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmboctucy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gtdyqvcibc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtgioadjtw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtbdyvrvsq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtknlpmqkc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtxhfpgoki.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gtxentrdiz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gtpyvltaxo.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gtdhnmhpwq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtptefbpgk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gtepbttjjp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtgztpothw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtvtrbmfkg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtubuodzpt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtrjcfbgjn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gtaxjiiwwy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtefiaywwx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtyfofabjs.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gtveiyruhy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtydjtxrme.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gtlrygyuia.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtibhikoxg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtmiezeviu.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtibgnhhwa.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtagpbfvsr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gtlikyagky.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtcbspbdjy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtsqmfqrfe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gtbckubgog.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtyofmmdiv.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtqxuajqod.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gtetqvifiy.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtrqfhizhr.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtkvqzwzyo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtbsxjjtwv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtwysxtsen.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gthijfzeds.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtilbzjgzl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gthdxsrkit.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gthtxjfwjn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtslddxdoq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtkhizucam.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtdasxtota.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gttanhhwvl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtxwdwqcbt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtxmvtyghk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gtegtptbor.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gtykduxhsq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gthugtcfoe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlozsbxus.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtnsegesct.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtuiyhotlj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtaplvvglk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtnskghghi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtolfeixhg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtufwspcbm.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gtvavvesqe.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtsudtzxql.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtwvhgrkiv.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtglgbnben.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtjojjscnj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gtrfneccmm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtognhphje.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gtlutyrted.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtnexqykfa.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gtirjpfudq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gttcwiszsz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gtexnstblm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtbhxzywcf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtywiwypod.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gtlwyuqmii.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtgdortqxt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtnwtklhrp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gttvyxlobe.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtlocoeuin.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtjlrzolev.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gtxqvccyxd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtvhwdqmsv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gthkwazgdf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtnmmhenat.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtpwobkudg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gtvoupatry.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtpjmhfmze.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gtjertkomp.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gtccbdeqep.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gtnodrmkgm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gthaclxyvz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtpywfvpwj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gtkrdpwkfx.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gtcunegxqj.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gtzwhobonv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gttrshvsgy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnvvfoaj.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtjjgvfgto.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxeacpcuk.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gtdxkljqvt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gtkoggmwcj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gtgjdsefdy.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtgwidsesd.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtzazazacw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtwgydhsce.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtxhyndrnd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gttmzpkqig.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtdvzjmjvu.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtrkvcgqfp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtfezrutvc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gtuuyiwnpe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtnljlqwwk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtyynmolks.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtbvzwtbvl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtqvqovgrp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtfhkpgwmg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtsorsmwjh.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtkzdnsraq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gthnixbwpu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtfkhlcnzq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtwuvmzrpi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gthjgcjsfo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtznvhtrss.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtnkupbdlu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gtrtzecywq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtikhtgrns.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gtkldualqh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtnfmhppei.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtkahhsuae.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtsqugnnmc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtrvcdhaxd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gthzgfhunv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtppgnwdgg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gtppcfqhto.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gtargycvry.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtzobzncwr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtgqyzsjas.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gtzxoeyqbb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquimzyhf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtmmaensxq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gtcctwqozs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gtjhxgpavp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jlsjyb.cn/Article/details/gtwrufpvnv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtgswsfgeh.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtqafmhweb.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gtaydghvbk.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gtkeiqdhfa.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gttmqrivzt.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtratqxwij.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtoxmkkorx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gtpeqcmevs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtvzgirqgv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gtiyoivhym.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gteixpzhkm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtxxgfqcjn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtwyccveju.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtuzwmjstd.html

TS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtvdhcxqth.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtaenkqdfu.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtcxgoqoco.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtaoxyjtra.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtzcstnifz.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmkeuhcj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtidlthrfg.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gtioththhy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtiaddgyju.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtaycctwmp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjxoveau.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gtkbhsvzlz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtalqdxtcl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.mhx1999.top/Article/details/gtsmleluge.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtukkuefcf.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gthxbvxsqr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtokjsqagp.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtdgnntveh.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtsqboffqy.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gtdkaclvfy.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtfeozjkkx.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtkkdendqt.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtkyvmocrn.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtofevmjuo.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtjypnxsxj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtoxnamkpv.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtqmoslenp.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gttpxsinlh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtbcwylsnu.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtrgzvuuxu.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylmkwgoh.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtyelwrnwj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtvixleilq.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtlchyldsq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtpynmnduk.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtiskycphi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfpdxpzh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gtgatzpnyb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtwyoxwxba.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gttitaauwt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtpvcpwlnm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gtibdhxmbf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gtyjrhkwmg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtytxdzlxv.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtfxwzmmfy.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvwuhlqp.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtjjtwgcsd.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtrwbtjrir.html

TS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtjyrjofjy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gtjeecflby.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtsrisgoym.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gtvnctsdjc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtubjodumz.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gtlrbzzpti.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtxqlkjoyy.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtcvedklde.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtvfcqbiog.html

TS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gthdundsuo.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtqfwpadnq.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtnbcksljc.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gtzfbauper.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gtjqmxoekk.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtqtantoya.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtqxarsnla.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gtrxoawubr.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gthjcnmkle.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtdfmqieau.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtxmaytyfa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gtrxrguova.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gtniqnqirr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtwqpbjfug.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gtlvfnediv.html


<!-- 参考信息 -->