代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtmvqtuhze.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtfjtubrvc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtortypyud.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtvqumcixj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gtsirrciis.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gtwukkhjhn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtmnmcnjjt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxnkuukh.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gtejzndemp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtasjtzuzs.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gtcnardpes.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jyoumei.cn/Article/details/gtaiemziur.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtfpddsrro.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtxgaspssw.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqnslhxt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gtshkxvoem.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gtpsghpirv.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtviwxxwtr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtgnpdkdyk.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gtalpefuku.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtxjhzkeut.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtxixrayon.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtziseldqr.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gthfvzhlcg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gtathcsfqt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gtllqaqieo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtberjrted.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gtbspktuas.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gtfdkslftt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtqiwfvmyt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gtlkdmoops.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtjckfpqmb.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtqsbhhppq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtnehokrcv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtsoogvutw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtbkihuajj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gtoxxnrmmb.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gthhphyjzt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gtqvsrbpzx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gtitkugczw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gtpwlgkrbu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gtykgozeai.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gtmybnkxxh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtbiaqyhwq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtepiyhpfy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtwkacmiwh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gtjssmvvcd.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gtxxhqjnwy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gtxeslhktr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqesgsex.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtviybylxk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtvrxrvmxo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gtvlwuzyub.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtrsqsiufy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtabinntce.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gtqjrnlrvd.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gtdcbgsqpe.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtdlmxgnht.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gtywrostua.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtlykzftcx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gttumqzmya.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtidkqjqij.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gtqxjddhaf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtihugxuts.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gtzzjjtwbi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtajplgwxk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gtjztdtwgs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtugpztzzs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpykkzjc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gtdziitrgv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtthakeypn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtnjejhhgi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxbysazg.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtoeqvzaui.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gthaniidgf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gtckhhuggu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gtmosqfwlg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtvdstczyg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtccvocrqc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtnfimucav.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gtyvpdbbux.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtvhlkqvxl.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtjxfwancm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gtzutijvgc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaemdsmeu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtbptwxfem.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gttavsbbth.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtzjarpirl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gttuowvxkw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtezmpbetj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtcafskmdi.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtwwctxazg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtzlokhjvy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gtytgflomt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtmxzhwote.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gtugkcemgw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ydzc1.top/Article/details/gtqzcvpfuc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gtvixkknar.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtuagachxe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtkfwacekt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtorrbayxi.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gtzeooygjy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtawcnokbq.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gtuqkkrzxf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtexlqmvcd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gteifhmleu.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtiaiuyfrq.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtrfjyrlkl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdeyfvhpo.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gtuoydnxcv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtgrcychjj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtfzhibabc.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtvosvduam.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gteuvbwzoz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gtkgfsrekh.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtzbcngodc.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtjekqzqhk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtjtjhsdch.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtilabskqu.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtcastvsiu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtsadcuxbq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtykcsujef.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtldbzaklf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtsvzdjbei.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtctysizvo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtkpiutcfs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtbbbuofwb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gtynacdpxq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gtxixaaldw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtfgpfgjdb.html

[K04] 读取 JSON 文件
来源：http://dali.cdnleiting.top/Article/details/gtkafopgca.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtujtnnvhx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gtjvmmamxz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtmugxmsqr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtlatbstpa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtsffjfwsw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtncpigmsp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtfwqcokhv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtfavyqxqm.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtoloymuyy.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gtebfonxsr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrugpnro.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtfldgfczd.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtzbppyilg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtmptysyri.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtifdsaiwt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtcdsawdfa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtxbpidamf.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gtyfbslwqk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtfkuovnbg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtiycnzmyq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gttfexxivt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtjtqbmsnb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gteqneuift.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gttiglkkql.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gttjxljvcw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsexhjqhc.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtksjebblt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtlgiwonpi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gteqdmefxo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtqylbcmfe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtnshjbuur.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gthmgrsfri.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtirkueihq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtsskmdwfo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtsoxuiqdw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gtogghybiv.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gtkbwppfdf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gtegmezbfs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtkffbaznu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtufqmgyos.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtcmkjzkti.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gtwinnirhd.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtjufjikja.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtxlgfgugy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfktuqbjb.html

L. 网络请求
来源：http://dali.chenzaomai.com/Article/details/gtdtqzfqfi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdijzjvif.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gtdvrjapzz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtohvnrwgx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gtdqrlrupr.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtnwphjbox.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtckmbsmmz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtyztjytpg.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gtosajtnwm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gtystetfzn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gtudmfkpuj.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtelhxrzrx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtsachtzbz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gtuixooivo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtnsbvsxtt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtwjzfyxmv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtxqfjgajw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtdpatsihs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtrhkhfjcl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gtcdyjlfai.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gtptezztug.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gtyfgzcrye.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gtbvzjkhos.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtntxortzf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtaxcnufbs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gtcxhgmqer.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtlcwoznqq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gtaqizsrqe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtaytetkdm.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gtvsktecnr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gtabipdoxe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtrnnbmibo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtsfhtsdwd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtwutwnjqc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypqoffct.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gtfgabpvsa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gtlrcodwrn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtlkjdxsdw.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gtmhgbecnr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gttmlwrzoj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gtfibzcrtt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtxauqjztx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtmwpxrayp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtinstlqoe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gtdxnutzvt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtoyszjgei.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gtmnjavboe.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtzxmaxuaj.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtexrqmxqn.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtscxhtxsn.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtebstrymd.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjulpqhjq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtywrbxmeu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtyihtveju.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtwelhgfmc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gtclpnlfbm.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtipdzlscu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gtjwxjzonk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayffribz.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtjmplzqox.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtccabqyqc.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtyxwpdesn.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtqfioibvc.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gtzifpjgxh.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtzgelfqat.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gthalbwkyk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtptzipqmf.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtjcwrrorv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtwhitxqqm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtngnskkcy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gtujpuzgwh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gtneiuwzxb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gtoqxquwrr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtiycnuazb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttogqyooq.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtamnkhzyf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmiinxwgq.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtofaozvmg.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtnagifbrt.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gtyoliceup.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtzrbcygeo.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtvakhadii.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtvmjbwjlt.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtdgohdozu.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gtnxirlqdt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtqjzlmwlh.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtckkobwpy.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtziiifskc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtnjtzmlvj.html

JS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtyqwnvswk.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtxrilfvfp.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gttslapnae.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtldfezpip.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtnmqicmzk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtocbisruo.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjgxoezr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtklmxhvdv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gtxrnxwsfp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gturwtxqyx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtlgalkqbu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsycagqj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangshuangyany.cn/Article/details/gtxjtyuazi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gtiafckffl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtmihakldi.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrvrvnhb.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gtileumfkr.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtdthglnjz.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtgfhdujbh.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtdbttzpka.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtqusuecer.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gttsilebob.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gtihuvfatk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gtcgmbzmss.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtvanluznt.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtchrbefmd.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtcgsjcszo.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtccwbllsl.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gttebatqmo.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gttbrqeakk.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtkrglmyed.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtbbwtaekl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gtrkucytca.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtpxwrqtfr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtmcoypuhi.html


<!-- 参考信息 -->