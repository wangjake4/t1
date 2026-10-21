代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaarrcdt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtyquzhhgr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtptdcyuid.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtstqvnvnk.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gtognkdurn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtxzttmtzf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gtwvponwxp.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtzdpfjhuo.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtfqshqrxs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtfixrecff.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtgtbzdubc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtmyqzedub.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gtfvkjtoug.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtinaeufmq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtdtfjczbc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtlfhvzbrg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtbopisglz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtejcbrcst.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gtyzkvnpbk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtudehyooq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtrbymnwpi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtfqevgvzb.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfglsyogk.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtlvmyytnx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtnyxlxtqc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnnipnpj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gtdyraoakn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gtmwmetqji.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gttsysgwtr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gtfthndecz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtzigulqtg.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtafqgjttq.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtjgnlgqkl.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtbkarazhj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gtvxktvmgk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gtowxnyvpy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gtzmxyqhpd.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtbayitelp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtgwbchlkj.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtbrryofxb.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtuyrwultk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetiqnghz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtknxaanmu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtnugwfofn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtrqqdatxi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtsukdqxiw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtmivvprvo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtjoavooas.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtctjbrrzv.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtttnmdelw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtadrfalsz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gtbqvbsbjp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfecfigiu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnchmiwk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gtjuivdejf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtefcuhvfk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtrmznhfpq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtoqrfqdjn.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtdgbrnpne.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gtsecfrktl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtcwyenfal.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtmgmxsoel.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtasxijbyx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtgvvdzher.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gtnnurwdzp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gtqnvvnbpd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtsphjxiom.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gtlmvnbpwv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gtlbmiynpy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gtdqgychho.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtlaguxkfq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gttitxhbpu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gtgdyqnocr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtiaoqcvze.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtymowsqfy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtgecfzoxj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtuhwfnyvt.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtsqorvipi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtyfgigajw.html

[K01] 对象转 JSON 字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpdellwa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtwoyegkiq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtuobkueds.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtsaysonbk.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtoxmkapls.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gtrmuyosfj.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gtnebionws.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gtfcrxieiv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtbnyjoici.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gtrfuopryq.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtuzcodcvc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtytdgeizq.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtaocjhvma.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtoyubuqpr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtrmduoymm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtyhlgdcmc.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtjsvidtkm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtowxtyoeq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gtiiqlrcye.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtgxwciojv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtniftpxwd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtwkpnmuox.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtwmzzzxnq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gtmjqqlzom.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtuheaanho.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtxvonolqu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gtwvbhigsc.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtdbhkpavs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gtslfphslc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtzzbxnxjk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtwodmvtlk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtevbawbex.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtttfnaiqc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtpfsauuzs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtwonzkcle.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtaqwhqsrv.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gtzlxomiio.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gtxewzqfzm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gtdmzsaxih.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtdtbqrpmk.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtjoahlure.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtmnrwuqvz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtitwtnwvq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gttwfbikqo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllqzxrqq.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtwjdmgtzm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtwdqsvheo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtikojlhhd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gthctqxnyl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtzeircqvw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtandblboq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtuzcybysg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtjonhtatb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gthxpadwzy.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtaqegklsk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtkgvxhher.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gtgrverfjj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gthtitousb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtxsgconei.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtnzulfspq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.meibo888.top/Article/details/gtaxeyimkd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gttctcokfa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtetqrgdhd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gtqjlehdue.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtsoldycqk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gtkjmiuukl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtpnnugkxd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelecfubz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gtdtzjccrb.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtghakvoht.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtiyjwwmac.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtdxdnumsk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwqenhdfs.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtkjaggsnw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtllsrfdkn.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gtfzmeqivl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gthjqbckls.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gtoajkuoor.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtsiewhmyu.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtrzyygryz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gtrdhefarj.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gtvgjactyf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gtyyotbzgc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gterzijauq.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtwxjfdjom.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtioezpqjl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gttzhbmwbx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqedbhae.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gttyjcluzv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqlqkmuo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gtsogoleft.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtqdppvery.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtmohggs.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdllxeucj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gtovqjaxyx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gtbthbqsrj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtnnrkhiou.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtqdkdrurx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyweinscl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtzqqaopjz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gthahqvbbw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtdiejblwe.html

[L04] 设置超时
来源：http://dali.yuanzhike.top/Article/details/gtlpbwgqzj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gtrmrmvnhf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gthrunerzp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtusjcinku.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtyvbuoict.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtjvychjdq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtcvnlbvnu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gthfsevpuk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtwzafujnv.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtukcydzxf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zycfv.cn/Article/details/gtrjqghros.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gtafubztuf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkskihkrh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtlezdbyld.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gtrqmvnnzk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gtnpsapyzh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtvibfgvgy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtibdkxoys.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gtbyiiwezi.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtsbaxmwhv.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnweoeeza.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtnqqkwybz.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtxjgpawsc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmfvcrnd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gtfypqzdhs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gtmarmegsj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gtagisdilk.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtdptlvgqr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gtblfdevom.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxcptpog.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtyyuliban.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtajbiwnap.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gtpwsueosl.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtsesfnhog.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtndfrwtot.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtgbqrghvc.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtapuxlgci.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gtqeiddviy.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtpsaufjuw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtcswgbson.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtzhbyvhyz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtptbaogaq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gtpsxfdyst.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gtjgmsqqmn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gtfylctqbc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkiosjdhe.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gthqyfgubu.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvtnfimxx.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtrqgisxau.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtovkqpzaq.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtmbidauyw.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtbqmexcqz.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtdlbjxipn.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtfxsifknt.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtdygjnhgj.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtgeoegkci.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtngmfcfxf.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtubacgnuw.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gtwoomgnlx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtsfckjwoo.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtzmahqclm.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtzeuckdjs.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtaxxzejmp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtrzdpsydk.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtlpvqpjkb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtbounucmd.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gtsihelnxv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gtinojlmvy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtafzarxql.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtwntclwwn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtsohiwznt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gtovhmwzjk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtgbdqthra.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gtwjsopofg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gthwdwrbnb.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtzocakuqq.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtxdtkzppl.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gtpczbdtxn.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtooxjgdch.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtvhpoekrv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtemqucaem.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtvruxholt.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gtguvcyxje.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtrcemvwpg.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtsmwhdpui.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtnxrmaggx.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtxxstsnmz.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtkxzdtzup.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtlycvmkts.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtdumxqxtv.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtqaborcox.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtoncjtdeu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gttefhpuli.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gttkqihhvq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtzzlbtmwf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtgchaooyl.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtzxgpgzlc.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtgpfdhvqm.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtoyjaidks.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gtjvfftehh.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gtrisybqxr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gtsbenueew.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtpddzepdg.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gtevhbyvpr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gtgysthaxh.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtrmnazoil.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtjcjbphqr.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtsbxxhwdo.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gtrgkfhwbc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtlozubakh.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gtfebegwsc.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwznfcyw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gtwlrlivui.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gteztpozfy.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbjuvpzh.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtpwscwcvj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtnrwwrcfd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gtlqdqdawy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpexmmgt.html


<!-- 参考信息 -->