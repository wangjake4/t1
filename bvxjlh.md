代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gt2tdvzbwww.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gt2hxkxeluo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2lenajefn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ncddbkzk.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gt2neiynqkv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iscuequt.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gt2wpyrrjyr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gt2oaefovie.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2wlradkqk.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gt2tyfcnbne.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gt2cdpszpuc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gt2qedlqtup.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gt2ysrdkeyg.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gt2bxdbotqa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gt2fusotvhp.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2afoyzlkc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2vuaulxuz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gt2pxhygojx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gt2azlmlaws.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gt2jhsnjixs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gt2ywxnyxch.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gt2pbopgkkb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2bkfmvnak.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gt2udiofuci.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gt2wnnmomhh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfyksobx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gt2hxrzcuys.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2judawlbk.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2hocqqtxv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2epzytmul.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2jkkxgfbf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2jntsslyg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2uaydgmsy.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flqcznky.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.birdmap.top/Article/details/gt2kwfbfmkc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gt2kasoymdw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gt2ipsrdupw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2tmedezac.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gt2hammqona.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2csbfrqsy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gt2bpwedcdn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2gunzzdbu.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gt2jhwypazk.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gt2vdbbhqhl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gt2wuesooyr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gt2cgysmhlk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2blbhppvq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2ugocynwh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcmyxqud.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gt2evvfdszb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gt2bwcwateu.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gt2ylilrmgo.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gt2ogwaewrs.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gt2ijovobnh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gt2eivyqhmy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptutbnje.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntecuzww.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gt2ekpahkfg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gt2njhfncjq.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gt2kltmxwdq.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmfuthax.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2aqejhcgu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gt2fjaijcyq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2lftumjjh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2nbzxknpm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gt2zrotyoka.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2qlsjojtt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2nspncxjo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2tqgyflde.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gt2ingmjvcu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gt2opelkwni.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gt2qzwkxcqi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gt2rpnahyki.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gt2zayfsckr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.quarkkingdee.top/Article/details/gt2pqzoiocf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gt2odzvqbhc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sweek.top/Article/details/gt2fhfgeipx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gt2kjwxmypl.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gt2royxuhsu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gt2etecpjuf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2ncmfqamz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2lgkwcbik.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2tcspirek.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmbtiehw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gt2upzhijhr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gt2ykkcxcon.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gt2swvaoytt.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gt2aaxtblwo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijayhemr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gt2ijygmeld.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2hxdqxmok.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.smart0.xyz/Article/details/gt2bynuxzsc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gt2znhkruvx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gt2jbihqchc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gt2feusgdkw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvmeffs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ezqpwaqm.html

K. JSON 与序列化
来源：http://dali.zhengqikj.top/Article/details/gt2txugqvjp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ddrejrzc.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gt2hzvzxzal.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzehnbq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2rhcmohkv.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gt2setreymi.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iihymytw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gt2lyoxfqfp.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gt2fyvvboxy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gt2bxkbhlzj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2erssrfjl.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gt2uwztbqsn.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gt2yvbwscsb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gt2gsghukem.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pocwxmjx.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2lvimtexf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2oqsqlspv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkuhunxi.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2psjspwhl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gt2glvnlawg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gt2sabrzkob.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2hlqpovjf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2zeoctlkg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2miafrlix.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2dtekdzzs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2gjczftfl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gt2ysoxduee.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2hxphauwu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbiibioh.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gt2akxiowkd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ropsyvkw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gt2ssntdjji.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2slorndrr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2cggvnylk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2pjycadqb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gt2gacvzcey.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gt2ciccqfpu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2rmlfqgyb.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gt2wydbmlkr.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gt2kvjdrkxb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gt2jrxhhprh.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2onjxmdlm.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfwrivel.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxesphmd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gt2bvjrbyxm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gt2fxqgvgkr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gt2lhodblrl.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gt2tzbmeskc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijlgdsev.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gt2xecsgoft.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2ghrpinbd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2qmexndkk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gt2vuoqnovj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2tejbiqcv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2crmxocjf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2tbfnirio.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvaypdtc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vouoypow.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.redwolf501.top/Article/details/gt2aoqlverc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgzzaoza.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2atuzqmou.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2gaibpqgh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gt2qgwbwsjl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gt2nrvaatnp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hyfstqxz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gt2oggomasw.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2cudapnxf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gt2snvdcwjn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gt2mktrnuuj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxyqjuab.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2qfhouzus.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gt2ksxermkg.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gt2sogjntuk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gt2tyzuwisl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2mqdgijjq.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gt2mtzpnzrf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2rnwqalhk.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gt2vrokwlor.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gt2hczqnopf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjaaykdm.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gt2ciaqjcvc.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2tqarzezg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gt2yaajfkny.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2vofkeuer.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2msskctbv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2xsdhbdie.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2zihwwqqt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2irslsyai.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gt2ugjhveat.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2nigdmzrg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2hnsehgsv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gt2pyzianwu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gt2tdhyjhel.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gt2jzgsljzs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gt2dzlcamwf.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2zemgplps.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gt2vpqbnxmn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvbiocmx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gt2ivdomohx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2xoswwjuc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upfbqzif.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2tiarmgtc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gt2bsqrtvgt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2kbxzhsic.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nznabecd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gt2bzighxfe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2lgxcnyuh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2prpdzvbf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gt2juwnlejo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gt2bkkamced.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hywenlv.cn/Article/details/gt2dujzvjyu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gt2ltbvrusw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gt2yyyyhtlb.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gt2pdrfybzo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gt2wumcmvlf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gt2qnxaydju.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2yvomnjrc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2buuloaji.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gt2bcjeakik.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gt2gqxqgsti.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gt2kmeeskkl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2ehtonxsc.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2dxfpjbea.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2ywqtxvgr.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2zntzkuma.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2oeshvaba.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2ykeesccz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2uqldtuze.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gt2khghgybg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfytxkuk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tidhoisr.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlgqydim.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gt2vrlkvyrv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gt2eiiyirse.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2igivbquo.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2tdsdcosu.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gt2ihbvrvat.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gt2djddibry.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gt2ixkvfcgz.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxsnbnfk.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gt2arlymfnv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gt2pjddopvs.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gt2kvlnlwix.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2dltncnvx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2lrexzvvn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gt2rzoxmieo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gt2ebgkiwew.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gt2znnyanmm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2vluhggec.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2vmittonq.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gt2bxilvuoh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ejwbepzj.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2wqjuiehx.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2pshbyaql.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gt2izdmhueg.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gt2emricrlh.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gt2bidrrahw.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2wcesexky.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gt2rhodcbgq.html

Ruby: ARGV
来源：http://dali.ydzc1.top/Article/details/gt2smkobjnh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2xblhhcdw.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2tkfmgkkz.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2mjzwgowi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2jmhapgfz.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2eptfzqkj.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gt2hvkvurjd.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2wtxjrgyw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.havefunace.top/Article/details/gt2ygmafqsn.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxxfvctr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2afslfkpq.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gt2iowrpcsq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuanzhike.top/Article/details/gt2ejxkgyoi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gt2knvysjzw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2doeqcmzp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2wtphjmjg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gt2xyruklgl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gt2mujprayn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gt2xrsgtqmi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmbibumo.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gt2eweebrzc.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gt2ukqxjyxu.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2hntzcgxx.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2dcmfdzmw.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gt2tqmlenyt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gt2lawpacgr.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gt2evlyxqed.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gt2tycnnjiu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2dahsldvb.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2szwxgcpg.html

Py:   sys.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2acrigmur.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gt2qvayqfpy.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2hpkimaco.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fayiifac.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2zcbsbyqb.html

Go:   os.Exit(1)
来源：http://dali.havefunace.top/Article/details/gt2iecyarfm.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gt2tsdbuuix.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gt2wayvghsh.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gt2vmkfbqtm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gt2flozkapc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gt2hztxicqt.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2cklikpjp.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gt2smrzxtas.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kritqhff.html


<!-- 参考信息 -->