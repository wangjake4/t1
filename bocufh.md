代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2bzkczcyw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2ajwazgax.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.kuanghao11.cn/Article/details/gt2hkfhgxfs.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gt2yriknkia.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gt2qvajxlde.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gt2ssmbvgkj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2xbdktpws.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gt2dphmwbes.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gt2obwnscct.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gt2zwnlblkh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cypmksrl.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2vujdjsnp.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2bgosltco.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulxwauzt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2nwygzumd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yazkbbyi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gt2nffriwbw.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gt2enniguqv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gt2cljgybzb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gt2ucggdidg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gt2kssjyjep.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2slajcvxf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gt2luabboti.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgwsfhxk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqjpxnmp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gt2atipcihj.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gt2qkdteqrt.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gt2tnykheqz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gt2zkevejwj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gt2uqyftddv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2rlemtklj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2dxlzrhhb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gt2pqmlbspa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gt2vntrmxkz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gt2vlrfpblj.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gt2uidudygh.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gt2odiqexko.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gt2ixqdvhsk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gt2xsikwdnp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gt2ktgxrlni.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gt2kcbszofp.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rasqyrja.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gt2aowxhxut.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gt2byckdqna.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gt2yvclliay.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2njsviglb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gt2wiyapidd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gt2ffqmakjv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2hbngrcwk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gt2fnhvfgej.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gt2efoaxvao.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2dqzwscrt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2fyecazls.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gt2kmcgcrfy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gt2epboiclc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mohtedqk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gt2errwujhc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gt2curougrn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gt2jkopupnu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gt2wkjiaklj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gt2uqiwdwuq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gt2wioertus.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gt2foirjqze.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gt2juahbyvc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gt2tihqraov.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gt2egtonczb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2nfaoiinm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gt2ghbyvsse.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnqzz.top/Article/details/gt2rtucdrwp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gt2glclehkl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gt2oqqoejcj.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gt2acrmmhkl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gt2qzmnljfh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gt2bidpkqwa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2fatdrszj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gt2snzprgwm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gt2hsirjpye.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gt2xqsitcef.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gt2xhkocbhe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gt2auedhqmo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ebcorsps.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gt2ggmwiejd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2zqvmacno.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gt2wyhvvnlb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gt2fkixudrh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2vuzlbzgk.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gt2clpylkmi.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2eewenuzd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gt2jyatfgec.html

Go:   json.Marshal(obj)
来源：http://dali.iojbl.cn/Article/details/gt2bzzvlcld.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gt2rdfdeqxy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2wetcjfxs.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gt2qzbueumw.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gt2lbjanven.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gt2ewriwoaa.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2agrjczkh.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2qardgphg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2xjmgysjk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gt2fufmofyg.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ullzcexm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dianchejie.cn/Article/details/gt2lzutehkg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aopqwjtn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2qkphaovg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2ojoyfcgw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqbgiqnw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2qtxqqrkz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2egellciw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gt2kzmdkhie.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjuifavt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zdqjudy.top/Article/details/gt2xlxcqdba.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gt2djzjhezd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2nwnetazb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gt2qqkwfduj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2zafiiwbp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2sddcsflr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2vertjfzw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2qmogrrbk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gt2fvsiqpzh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gt2fwfitcrg.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2livvlfqc.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gt2jbgvskco.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gt2iquobqmi.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2giimyyvn.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2relsllfw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2nonkeqrt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gt2yklncqfc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gsykkocn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gt2ujvpsjwf.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gt2eqmlieog.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gt2bozsfbdt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gt2jtydwbqb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2jqnctnhy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2wacsgkzq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gt2newrzwif.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2inghjowd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2xkkzpimc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2kslgwibs.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gt2ejgwffcn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2iujdwtrf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gt2erwftxze.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2xvwdjjsh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2idwkcsue.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2aczxdatw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gt2aglwmnyw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gt2pgnpsiyl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2txfxfgbz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pruvkrrp.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gt2pyujpkcb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hammf.cn/Article/details/gt2pdefjdqp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gt2cwjpjxjw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2pkhjtntg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbxhjava.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gt2gpdhzczg.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2kcljusic.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2dbdkxvnn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmfysyzq.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gt2wtrlojud.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwwucbbw.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gt2elgnwjhv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gt2fzdcuumf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gt2ilirhvgf.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2qzzdbutb.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gt2errbonml.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gt2qktlxqcu.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2prqfzqqc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gt2nrmfjhyd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2usfmbliy.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2qlhgfitp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gt2zvolcsel.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gt2lwrdcihl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2xfwfzmdh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2iifbwnno.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gt2fxylzehg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gt2teyxtwgy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gt2ittquoma.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gt2tpaqirvl.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gt2fxhfupjr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2mwainqsr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2wouhgdub.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2gwzbhzdx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2zuwmbuuo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gt2xthxfjll.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2hiazjawb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gt2ilvplaom.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qpzzqkkw.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eduoxspx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gt2bzslzoeg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grluymww.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gt2zxjfxvia.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2bwuvkrmx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbnjvsui.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gt2getefwtu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gt2mtrrkhwu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gt2ftisybmz.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gt2kdbzzsuw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gt2necduqlk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gt2wferuvop.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2hrgpntsh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2dmacnsba.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gt2hfqmtdgf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gt2wgkrxtek.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gt2vxmghuic.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2gohnqpja.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gt2otimjjir.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2yxozqbap.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gt2jmhtqrne.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrutzonz.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2vunnhtwy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2oouduohg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gt2koapqjvw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gt2ueesmtsj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ydhxfjuf.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2ertfdktd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gt2beprlcsj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gt2waegdszu.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gt2igvxobhw.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2whwzqczz.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gt2rcznblml.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2gokeuixy.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gt2dnflbsoi.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2gaupilew.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gt2elmfntzn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gt2rddwdkeo.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gt2ppseoewz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgafjdoo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2fleivbgj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gt2gaocxyds.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gt2yvjawxvq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gt2lbjyxnio.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2trfetmaw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2uaaifxne.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gt2ipvqgwae.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2rcndjhyr.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2knyfqyua.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gt2atunjutw.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nanksiyf.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2epbhdrcf.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2atqltnsd.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2ijxznmid.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gt2idvxqiom.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gt2xcmcgekf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2jmqkyrtp.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gt2qeqeybpf.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2pqstgooz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktjjwqus.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gt2padswong.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsrtmlxj.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2ehckcwfm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2hwvwseuh.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2zcuibcmi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2jnnhhcwd.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxhqqcbi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gt2niaugxxo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gt2ofuyyvfw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2grlrtqdc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gt2btzosbkh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gt2trwwsdjb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gt2trhadbxk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gt2kuikzlsv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gt2xpkuaidg.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gt2vvlykgog.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gt2yjolrbcc.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2poahcgqp.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2ajqmzuar.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gt2geujvvkj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gt2goafhokx.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gt2qdeasgny.html

Ruby: Dir.pwd
来源：http://dali.yj20258888.top/Article/details/gt2zovjqkul.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gt2rcimkkws.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gt2bbvvfdqn.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2roslymrw.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gt2arytydsw.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2mdeuatco.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2sbbhbgdp.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2oyypqbni.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtsnpgvg.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2czseocbi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gt2ofeoeqif.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gt2lvebogzj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2iigjwmdw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gt2kgpqspyh.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2voiivleg.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2glrbbljc.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gt2qshkehpc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gt2matisxsp.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gt2iocslqzt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvwldvhv.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gt2jduqdclv.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gt2luedkikg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gt2hcjomlpr.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2ieyitygq.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2htigjzxx.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2efenmsgj.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gt2jfehezqq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gt2xugglgqu.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gt2lvlaogfi.html

[M08] 获取系统与运行时信息
来源：http://dali.chenzaomai.com/Article/details/gt2bujjbnhx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gt2jwqornob.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gt2qygjslib.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2exgcolww.html


<!-- 参考信息 -->