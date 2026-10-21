代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gtkmayracj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gtwthbjymq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gthhcuvmqd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkotuadrn.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtrvrkhvys.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtiddeqsil.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gtlthgwjss.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhthqcsx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtacvzejka.html

JS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtixatxozi.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtenfrnpzi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtnssypvlo.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gtoezpqdti.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtenmxbcre.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gtiotgevjw.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gtjuptovqn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gttsuybeui.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtkimzytnu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuanzhike.top/Article/details/gtrigudxdw.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gtumevohzt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtdeszuctg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gthgxlxuof.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gthbruxafq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtgveaxlsv.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtjzzgnnsn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gtzvazamis.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gtseyavigs.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtxrjfisnu.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyumqtiss.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtahuaubxt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtfzpjszjk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtuarjbwhc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtawvorecf.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtghfwrjrg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtuemfyybf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtuhcjoggh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtlmwyzxxx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtuhgcphbk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gtijverjwd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gtgzlmrcaj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gtbuikuswr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtpbmajhuc.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gtkdkujrni.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtvdefwlwh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmacigrm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtkablzcgn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gteumlgssi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtugrhdrcf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gtgvoeiwmw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gtfmoiduku.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtyvpsoaoy.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gtjqtiuico.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gtsazwdzah.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gtvdklxhpt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gthnsccnqt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtjvhjdqat.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtwjetjabt.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtpsblymnv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtauooeeyv.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvwadguk.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gteybumbwv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtwlvnzmhm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtnwgqhpsu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gthqrbllfw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtxbagvupu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtkhqhpasb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtentqtoyu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtvrjzeypd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtoacmmuxc.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gteipkuaql.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtzdetmyrf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtzxybxahe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gtufmbaqup.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtevitjoiy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtevtrltix.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtlhjfcpgi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gthfgcaiwz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgufenzy.top/Article/details/gtojfctean.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gtrxziontx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtmvkargmd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gtscuctlmr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtewyyjftw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtrwyjalot.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtksphopqq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gtmeyxdefs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtegtukgmh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gtygmjcgzr.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gtflqaqidl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gthrlsgriq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gtlrmwtwar.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gtqqztroou.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtzkddnnyk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtzngncxxl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gtazlifzdp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtoaoumvwz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gthnthojuw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwykffetg.html

K. JSON 与序列化
来源：http://dali.ivvv.top/Article/details/gtfmleqjme.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwplsjyfa.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gtmogviusw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtjeggoiwk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtvrxhdudi.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtyipedhcq.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtuyhayyfz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gtljlujkyz.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gttzzyybxl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtmzdpkbqg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gtyejvehkr.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gtuvihjhib.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtteecxhwc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtbvmrvxar.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtylsalurz.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtsxeigkpi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtojzvafpp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gttritwnnj.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtmmrxglsq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtuxdeltsf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinghuilouyu.cn/Article/details/gtewjmkotu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtwkowdjed.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtpvpvpjmd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtpwewfwsr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtbirmttuf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtahjwyasb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gtdnzsuaep.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gtuguvxeir.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gtwtywodqn.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gtemxpzuxa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtffxlvrxu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gtkzfdoddi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtldzxobug.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtwblbfdfb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtualegyrr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtbedbgnnw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtfzxbwrzu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtmosuvyaz.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gtwfpwynpv.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gtdipglxid.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtonxggihj.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtpxvixkln.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtbkomgwvk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtjruicojr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gtyasfdptd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtjmztvmao.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrbmgcde.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gtixalnivt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtvcsrbaga.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtcxezeuvx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtjhrsymlt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtavgoinwn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtoozrcdwy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtyqurikgp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtjsqfrwrq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtiljzpcdy.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gtcpnamqmh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtubteqkzw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtqddyvjlf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtotexylnn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtbyxncozk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtldshufrc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtoyhycrjl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gtlbimvwvu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkjpsvoj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gtnctlfyux.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gtepykuzva.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtkhugbijr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtbskahdgy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtzzjqacnu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gthhpyolqu.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgbjzqlw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gthjargcze.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtrfnsuhjo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgwakqdfx.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtwccinlzu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqjwgfsdr.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gtxolztphx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtzooookwc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtmecxchzp.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtkzeqszma.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtqhqtqnjs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gtoaduogzc.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gthoppmtzh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gtaddfrgvg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gtxxmgpiga.html

[L02] 发送 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtobwbsbzq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gtujxovgdo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gtbdpgieye.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtybemniyn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtyevtuzcp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gtqevbujjq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtvladkdie.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtbvdhkjod.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gtbvbqspid.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gtrexpcnmf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtcuxrtkkk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gtovwnijhz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtunxfbjft.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtzzopgcnv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shangyingyoupin.top/Article/details/gtzimbffnn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gttnlssqxy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtovdpcjdr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtmjqyknos.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gtdduibqte.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamfniudy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gtjuvkwrbr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gthwysveiu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gthhabarmn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtkgnsyzsj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtwrsuxooz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtfyrgvyaz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gthflqzjlx.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtwzfoemwf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gtovrldtgv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gtpftuyqhh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgorynaqe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtmegiodfq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnndmqhh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtzarthtcv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gtjlqdhvpm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtsbnftsqp.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtsmpsnmfx.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gthvlqjkuo.html

PHP:  json_decode($body, true);
来源：http://dali.guannengcc.top/Article/details/gtkvkadbsa.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtagofvqhv.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtobcrpalx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtwrhodyli.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gtgixgjspg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtvjijdeio.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtszskqies.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtggfvlpoj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gtzhkpmnik.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpzroikl.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtrpllmqze.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtslqwxnrx.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gtmoqufoqn.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtbotekbkb.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gtsjatnvxr.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtqrmomwnz.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtzuttivwh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gtlsbmzqmo.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gtvmqcgqnh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtxlqpkycl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gthyxkldon.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gtgwjfbyeu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gtmqvmiirz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqrgjxov.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gtntpppbgm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnksjbsyn.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtimacarrd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkabiivgy.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtxxekjigt.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gtahycmplh.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtenmqdmaf.html

JS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtckxwqxkt.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtiubehoip.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtlsaiofov.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtyfmhncpd.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gtijfubzck.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtukmwkmfh.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtuqowtdbi.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtxfdramlr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtmobqcfox.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gteuooepvb.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtcrtwinsz.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtkpmmkhni.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtjgpnrcbn.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtfwulxcpl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtjacpypyb.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtdsmahffb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtveumhmoc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gtkuidcjer.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtfkebrrog.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtnobwlspf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtogsnkczz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gtoszatbox.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gtckkyktvk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gtefgswxtp.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gttovdbhnx.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdjthkwr.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gtsbgubdht.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtzfangyfv.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtsjocorkt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtwjabajnu.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gtghgcrzpg.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gttrviwiqh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtiquqsbrg.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtdgaayhib.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtjmpalpho.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gtpwwloary.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtwikrlqqk.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtkjwrkbie.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtmlmzslbk.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiihbvudg.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gtoxvijgst.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gtkfttkgat.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtaeyatjyr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtzymzqfkb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtxmfaffdh.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtikqtkuqj.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtgxjitdme.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gtndrvxgeq.html


<!-- 参考信息 -->