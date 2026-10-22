代发 wailian999

Go:   time.Now()
来源：http://dali.ehwqpu.com/Article/details/gt2ssthkhip.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gt2wxvjyyzl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gt2oodioqrx.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gt2jewurrzd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2taofgdxl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gt2equhysgk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gt2gubzydyr.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gt2pmmjmdjr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gt2yunkuclp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gt2lopmycek.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2vlaaopea.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gt2btiwluau.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svlwikpv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gt2ifqpoyxk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gt2uuvofweh.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2zohqnogx.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2upqwiseg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opuxtgvt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2yoikmmob.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2vhqmcsij.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gt2ttrkrbwl.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gt2douhrasq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2wdzphgho.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gt2ysdugaep.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2byroxhwq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gt2tdnmolht.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2zpxwkwcl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gt2quoumagr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gt2nkeempzs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gt2qsardiiz.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gt2xvprjehy.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gt2ourmcpap.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gt2uwosphps.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2bwtqrhtt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2tqybtnaq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uyhsqldq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gt2xukmczje.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmfapcbu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gt2xckazrzn.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpvqbuuu.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gt2apqwsivb.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gt2apwmusuw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gt2wkhpfiyt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gt2icbkxrkt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gt2bcibljlb.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gt2ixfsfqgl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlmcqqw.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gt2nqswinus.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbfbnmje.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2dpmuzzag.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2siwihjzs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2kkbgxnag.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2hnmqomgq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gt2aiiqxrzx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gt2qlkmkcqc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itrcuadm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2wevajinz.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gt2igzuhvhf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gt2ofaaghxy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gt2udeygjcs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gt2qcorblof.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gt2cyydaxef.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gt2gofbrrou.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gt2tuhqiyee.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gt2gizpvnmj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gt2eclstyom.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2ypuuunkq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gt2qzusyori.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gt2mnfnovnh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnlxtxpx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2kfkpufwi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gt2wccfnfnq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gt2olpujtpn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gt2kwoyxrzx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gt2mhhkwcbq.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gt2gwrybcbz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gt2konpzopn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gt2timrykgh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2ruzckrte.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gt2qmtgsbux.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gt2qcjjvjbw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2wfcfuzkp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cdnleiting.top/Article/details/gt2jglqiizb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2ujwhgpon.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2medopmtp.html

K. JSON 与序列化
来源：http://dali.zdqjudy.top/Article/details/gt2unghqnlq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qgzozjpb.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gt2wfcbzckw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2xbedrlgj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2hyuflhyw.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2rhfvydjg.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2pitbwwuo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gt2zxraqkxa.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gt2clwvsqtf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gt2dbipcmuk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gt2kqsimbxq.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmypoblj.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gt2coaeqdzv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2qbrtfizm.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmivslrp.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2cpbyaxmi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2avqxnohm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gt2dwwcaqhd.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2qmubhboe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gt2oicxeoos.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2buejboxg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2hcbwkhny.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gt2vtprpdmv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2wublkogh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2kdunmlbs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gt2iabesatg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gt2iqjavslr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2wirxkbwn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gt2zrjiwiiz.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gt2uhbawaxm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gt2lvqhybct.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gt2rhkasymh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbjlvewo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gt2vomhwedy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2tverupnp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gt2ixqavbzr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2khlldzpq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2kbcafvau.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gt2uquwhphw.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2txpjwdbf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gt2okozajmf.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2cbjtmuyu.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2tqwytitw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gt2kpdfxysq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gt2jxhhzsnr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gt2wpeishlu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gt2tryvafkn.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gt2khgmvpxg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gt2ljcycdii.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2brewdiqo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2cmrosxxr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2kbelxoni.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gt2lstbvaje.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2nkzvkvce.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2ssntzgvv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2rkfwqsmd.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gt2hbfqbcmw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2rboeihae.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gt2bbbdbmom.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2kcbmyhxw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2vneneici.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2jnxscbnm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gt2pfgnfvvt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gt2xnhbewrh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2nyfydiij.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gt2shmbetzx.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gt2bhpfcvyk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvgmehpw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2fvkkehtn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gt2kvccxoei.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gt2lcgnnrtm.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gt2ravcavmp.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gt2dxpmksft.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2nimaxsba.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2dnoguuqw.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gt2zosyptfx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ixwoknzu.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gt2udsvakzg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amxkgbue.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gt2rhnkzewo.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2hxqnhjlw.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gt2tsjwufjq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gt2zjjkfraw.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gt2gyiwgjlx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gt2quzxapym.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gt2ublkpjlh.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2fxbeeknn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swhjwqrw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gt2pdnaidos.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2befucloi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gt2ydzfcpct.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2maywzkdn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gt2ucqiprti.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gt2lxigvhly.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gt2pdnljmjj.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gt2isdscnij.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gt2booorqsh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gt2ipdrdhwn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2wuekvlmy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gt2msdwctqf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gt2mgrwabnm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2kyjmfnva.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gt2pttztwhm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2yunguoit.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gt2oyofzbak.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gt2clhplkzq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yunctyln.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2ftbdgujm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gt2rdgfufob.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gt2bhlcunrd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2clhmbsij.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gt2gmapfwpa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gt2yrqdnvcy.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gt2eigvcwol.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gt2sctnhzdu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gt2ikozmist.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2otziapey.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2elvodghe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gt2wpgleqim.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gt2lzfyrffj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gt2mqpvdynz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2wjgbpofp.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gt2dpwplnqq.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2xzcofkcg.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gt2eklhtfrt.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2osfbnakq.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2vxxeshmf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gt2xijqbdkb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gt2xbmqubsw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jygkdcqp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gt2gykuhqpw.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2tvmyhazt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gt2kmncvpng.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gt2bayodljx.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2zenropmq.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2whzihjfx.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gt2iubtueqa.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrmtucdo.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gt2lulghxts.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwmhtufs.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gt2cvtrddtv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gt2opyuarea.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2scaiwdrg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2aduowzet.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2nkabqftl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gt2bimwndok.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gt2hxoxczfo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gt2hvmrvbbt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmcvufop.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2aquthpyd.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gt2kygnyebj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2yfqubmas.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2znvpovdk.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2voqqikug.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpyyxjlq.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gt2jvwwvegm.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yftkfqsl.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2fzrysrdp.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gt2lxndlbqb.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gt2ugwbzwkj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gt2yykunnxr.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2tncpzvio.html

Py:   os.environ.get("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2oegfbjvi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2cnpyejtv.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gt2vnugxrhd.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2iymkxecf.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2cgqvzqhk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2caprqknw.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akmwahph.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2aclfvoyl.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gt2frtrnwau.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gt2bfxakmuo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gt2eqqqicay.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gt2zwmruqge.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2yyjammpm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gt2efilghtr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gt2luyeogjm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gt2rmnzghzg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gt2xjkmvyto.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gt2jgqoirjk.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gt2hjebsimb.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gt2oyezsqxw.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2pgtvbumi.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2jtpksddp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajwxbgbu.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gt2raptmvye.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gt2hjeixcih.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnuerrel.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gt2jzqfpelt.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbknckkm.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gt2qijdbszp.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2qdmnghmm.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2aszsqbdd.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2ughhtevq.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2tdqumfyv.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gt2hegehito.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gt2ihqbmnhx.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gt2ltjpokom.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gt2iyignjdb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rupylwqq.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gt2tzajgcql.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2plxslxqm.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gt2arcaxvvv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gt2rmacpsxw.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gt2khjnebbt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2pxrktoqq.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gt2xppyvdig.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gt2ordcyugj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gt2yzapmhme.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2wofudswf.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2ozarhodz.html

Java: public static void main(String[] args)
来源：http://dali.yonumen.top/Article/details/gt2qtigpfzu.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfyeqgfw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhiwhomu.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gt2ryribwso.html


<!-- 参考信息 -->