代发 wailian999

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gt2cqhgukar.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wljqmgtj.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gt2sfbenaiw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gt2uirorxpz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gt2gzihehgb.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uryafldy.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2rmbjutws.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gt2gnzgdgwi.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gt2ktzdiuys.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gt2zjazslvq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gt2vuqksjqo.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2wkyysuqp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dbwhlklc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2rincvorl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpqseuuj.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2toqodmyj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gt2fzkvngqr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gt2iozhiqxb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2fsrudfhk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gt2baaojzib.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gt2ohvwjgsw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gt2naleujjf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gt2inicuaiv.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2idlzebxy.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttbnyiro.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2okynybjd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2mvsuppcl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2yjdarxgh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gt2plxdlzpl.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gt2pxdgreta.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2caagsxah.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyjnwuyh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gt2lnfuyhti.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2sfqbklzz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2czbhlpey.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gt2arlsoezp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gt2okjoqgkx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gt2dhghnuah.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gt2hochuash.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gddesyhu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gt2lqzzmoor.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2fxbjbhvh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpfawwis.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxhetngb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2dllitxhh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2ccxacytx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2dvztwcxq.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2rzvjmapx.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gt2aewvlmvf.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gt2rlbwbbyk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gt2tukfnggx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gt2nsyzgvpr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gt2sahcpovk.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smsekubg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2iaxdnhjj.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gt2zuccounf.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gt2trfnbunj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gt2wocyeszm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2aztehcpw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2slppxejg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2djgxihny.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gt2dtyyoilv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gt2ripvfimn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2hbvawvlv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2svtmibjp.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gt2tjovfzja.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gt2jcgisjur.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gt2cpibmskm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gt2ejlwuyjm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eoweozji.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gt2uvradfry.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gt2ocfhyelt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gt2skcjvqvv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gt2ootqynvt.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2koearumo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmfdizr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gt2dhfzjysb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gt2albpfzfi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2cspjnkmg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gt2cuifjejl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gt2piafilli.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxjdsvjf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gt2gtoavzff.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcquvwfp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gt2xeocvtjo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gt2odzxtcxa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gt2cjzkuoxn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2seqajaek.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gt2zbnuochb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gt2xolgvkhb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gt2doankwuv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2llacacer.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ermjqzgw.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gt2yrygxnmo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2xgmmlnaa.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gt2jnkswrsw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2rsaqyhcn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2soimagqr.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rifoyaxj.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2coeoradh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gt2kpsmnjjv.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gt2jyumsjyy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gt2glcnwfgu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gt2ymfetfwp.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gt2ebypfmnj.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gt2wwazuvht.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2koyjijck.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2jvtzavws.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbddrzfl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2ggzeqvwe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gt2xxruikde.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2murwhewx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2gvmeshfc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyfdvvuh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2lfpwkdqd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2hvyywmod.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uerqeigf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gt2tcldwrwt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2ykbmamyc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gt2wcmdjkll.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gt2omlpqinl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gt2olrsvmgm.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gt2ambvbris.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnsqcdmu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2ripcryss.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2dauktkmm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gt2ebliunai.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2jvmlfeir.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2hawwkteq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhsotjrt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2hkiaarvw.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gt2owiezfoq.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2edqllpal.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gt2blagwxrh.html

JS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2adkyoggl.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2xzgltqpn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gt2hbfyavri.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gt2acmnlral.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iadsixgx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gt2pzzrivxu.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nehscuiq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2nzfrztzx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgfzy.top/Article/details/gt2bdbdinqa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2krldcwmh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gt2lvijiwea.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdtblaoh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2ziczbhiy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2hzufuoyd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2tkfypshk.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gt2mfrhfgdx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2nvchuwcu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xziqi.cn/Article/details/gt2gisnhnxa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohcqwdvx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2pftpciem.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2drwdrfds.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gt2yrotatnv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gt2vxwcnnuk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chegpfjq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2iefdadnk.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iglhvwoz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2jjmgnizo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2fyieirvi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2mgnyolfb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gt2wuanebbq.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gt2lrcibnhb.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwnzhcja.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gt2zroocpfn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2zpljlkle.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgbmrufb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ymodfjya.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gt2etsjwkwu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gt2tyhqrudw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gt2oftsljwy.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udesupdo.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2umsivyfk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gt2rhqvviwg.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gt2hdtgkwgq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkbsmdsq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gt2twnyxech.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgbfsoew.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmlielww.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gt2tlwggxfj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2amotzbdl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2vxdibtiz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2nzlsyofb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gt2hlupzfuv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gt2hcvngkeb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2aqfddugm.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gt2yfipbmon.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gt2vxkvgxlf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hfpthk.cn/Article/details/gt2cmtzxxcq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2ubthqitp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gt2caahqntc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gt2fwxfuwad.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2owtyktxs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gt2qqwoghlp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2mrfsgpuo.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gt2xwdvlpni.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gt2mrosxads.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gt2zgfobktg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2rmdydycu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgqxlrie.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.smart0.xyz/Article/details/gt2ypytbllx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gt2rapmfeqi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gt2gdixudvl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gt2prioxdqv.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gt2ahajnhbx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gt2iwhqjroy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gt2vvijktfp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffjmclnq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gt2jnoqmuyg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daria6918.cn/Article/details/gt2bixshrms.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gt2mjoadlva.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gt2ajfmjemj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2rfqzmeqk.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2izyzltoq.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2gjewdhqj.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gt2vcyexcqb.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2ksuhsmhz.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2gsxciffd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2wopwlzps.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mryjpwdl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gt2fkfzvwir.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2eayjymiv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gt2aeiqbxus.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gt2qkhbrwtb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gt2nyguvxpr.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gt2vvzdddjp.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2fnwrpqxg.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuebfjc.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gt2lspsvbbg.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gt2yjnibfdr.html

C#:   (int)resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2kueyovaj.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gt2vxhuxdfs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gt2ulyjkaar.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gt2gqvfhtyn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2nxuthtym.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2ldxsahiq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2mjcnohgf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gt2bafnxwao.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gt2wimcqwfh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2enenwpmo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dvocgusm.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gt2bfwcpmkw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2nkevgjyj.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2zlgfszmg.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2arphwkng.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gt2iulihgzj.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnfaxqth.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gt2nwzdbbig.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gt2eqphcgni.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2eoraqtqg.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2xpdmkbdx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gt2exzgkrtb.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emyzpoof.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2fochnvuh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2gxxxpvjb.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gt2giunntsv.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2srsknbop.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2pjivbxfw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2vnctnhrk.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypwrsebb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2kqebkzvp.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gt2rmvczxdz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apuardox.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gt2rhjjedor.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2pteneyoy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zveegaoe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gt2cahgfthh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2cfturwal.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gt2nvqoxtqq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gt2vyqaftvr.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejedldku.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gt2mehizizb.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gt2lijhpvcl.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2mcanlyvb.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2irbvxvue.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gt2xyvplteb.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gt2srtjeaqq.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gt2zayxhaov.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2ihpsnhvy.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwrsdvaq.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2nadksrqj.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gt2wjiwsixm.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2pyvjxzei.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2xipexcfw.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2dycgzzaw.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2ehnpwppf.html

Ruby: exit 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfumlakm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gt2hamrzhtf.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gt2qwypwioi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gt2jxrxbnxa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gt2adpkdlce.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gt2eerrsunt.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pgybwdtu.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gt2vrcnmjaf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gt2welczoie.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gt2jjlkzdjp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gt2ajjwanlt.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gt2qsgqxosx.html


<!-- 参考信息 -->