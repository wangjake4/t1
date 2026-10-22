代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gt2eymskuln.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gt2pffepzvm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2ldmzrvdi.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2utqzvbqs.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcatskkl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2nkzjbnnj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2gdsiemro.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2vvqqwflb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gt2shtrujno.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gt2venwizjc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gt2twnhwdhy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssaagyjj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gt2ymsghpgs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gt2soqmfdqz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2abuastmk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2eylaxbpl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gt2tkyqtanb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2zkukhgzq.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gt2cgtkzbrc.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gt2yfxtcdfv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gt2dmbrmztg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvtiqkt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ooblgkfx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gt2eviwqcwd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gt2tytbjrwf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gt2iyddczju.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gt2ekeqnigb.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gt2ixmehvud.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gt2migcwtwj.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gt2nohzvryg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gt2dfufcrvi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gt2sbkkqnwd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gt2fnlntocf.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gt2keyjrwue.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkqtlqsk.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gt2blwmdqvb.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gt2ecceccxe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2olmbdedr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gt2jlurabpr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2skwyraaz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2uxdnakhb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gt2ggomzkte.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gt2suiadraz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2safiafqe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2rrsdzfps.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gt2ywmcefki.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gt2gscdcpjk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gt2xorwhdmg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gt2kuyokdmg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gt2nqeqawmb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gt2dmipnmhr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gt2wkfbgivu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ehwqpu.com/Article/details/gt2vavcyelv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tfmrqmmf.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjwqkrre.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gt2pgcozvfl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gt2arkfstii.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2ebmddpje.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2puheadzv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2obvxqfzp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gt2prcrmknt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2svqmbpju.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gt2xnyvnlpv.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrozfssc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gt2fhccfuns.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bixfpdux.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gt2cljdlzev.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2xrnnioyv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gt2sicepfat.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdciufea.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gt2afemufrh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trunxmdq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2wduqfjfu.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eazukmla.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2vkhmdpjl.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gt2hzqowcmf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gt2cvjgmvmg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2velfdbzl.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2byusozog.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2htktpzwt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gt2wpidrgul.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2vuvqeljb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gt2pxhinkbp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gt2fdgxydis.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gt2ectusjxn.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gt2mbcolvbi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gt2xdyiwynu.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2vontngfg.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2jbpircah.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2wjeafizo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2ahqyvcgx.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2oerxnvti.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gt2rwfdxsyq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2bmxnwrbm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2qmuxfqns.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2rgllxvln.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2fqxhyhwo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gt2obbhhkkb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2mhfzlgiw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gt2eotyvsnm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gt2bfjrkpmz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gt2kpxkxwfv.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gt2qcmmtpny.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gt2nyxdmdun.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gt2pzjsnhgh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gt2hnbnhgrt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2flxifpox.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2vdyuakso.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2ijubwehh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2odnlsokm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2govltlyc.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gt2geaihlwk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2eufxjsar.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gt2khvhskdq.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2joblloie.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gt2tejqvjnv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qolinqfw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gt2jvkahuzn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbludrno.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gt2ywyspkul.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gt2niladpjm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2pxmxspjq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gt2erzjvcrm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2rqcbkhro.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2wxwtlein.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gt2rxzxjriu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2bivdsenl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2lwyntgkp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2ialxinoi.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gt2snetjurn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2gvdonshy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gt2ixofsmzp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2dffjkmkl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2hrxchapb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2elfnlrvy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gzhubu.top/Article/details/gt2mwbgbcgx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gt2lemzoqql.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2nxppifrh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gt2pwribvqf.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2ixaaqazx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gt2uqjzllam.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gt2dkdtnjiz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2rarfmooz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gt2ermurlnh.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gt2cojhaadv.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2lqldavbr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2ytbhqogn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2siewoxlw.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gt2qmgxscls.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2lpgbcyte.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2itzkulof.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gt2rhfesabk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gt2ssxmrssh.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgjapstg.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2titnwzva.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gt2zfrfjudd.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2cbemdmfi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gt2lwynekhs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gt2siilnemw.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2sxucoijf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cheryme.top/Article/details/gt2sniqntcp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gt2unsdzanw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otvblnfr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vultgfoq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gt2pgremmjg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gt2glhqyovw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gt2vuwpnavt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2qrhrxcyd.html

[L03] 设置自定义请求头
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkqsaaiy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gt2yumotrwv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gt2bpjlpyyz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2jznttyhp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2jqeaylom.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gt2ifimqpuy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2teqwbibf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.snrcjt.cn/Article/details/gt2wbvfpvul.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2peldwcpv.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gt2scxcsarb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gt2vokuuhvm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2jfddedlm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gt2uouiythc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2acrzmybc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gt2mxxjkvjl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gt2uphbuuuj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gt2kqebbnhb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbejhqrh.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gt2qrtunmni.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gt2rbzgqdjg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gt2wzqtnglm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gt2qdczqbko.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2lxtbliem.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gt2uvszxdxj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfvjewnd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gt2prdtmgrh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdicdsbi.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gt2eswuuxum.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2emovudar.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gt2dkungvwl.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2piutluju.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2uekzyjri.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2wqsxeacu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gt2vqvrvcxd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gt2uenobmos.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gt2oxrqficu.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gt2jmenitxe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zyhqwegm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gt2ratmtdqd.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2jkqcqgxs.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gt2gosmmuvf.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gt2rbresddg.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2encxfidy.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsbwmcwm.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2zvrijxbu.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gt2zpesfigb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gt2itrxelvr.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gt2hoysplfv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2zkjcoiuu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2pdgxqhqv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gt2rufnqdkk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gzhubu.top/Article/details/gt2zhuckrql.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gt2jqajqrog.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gt2wccbtgvi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2bjytyqls.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gt2abkzxibk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2kjogqojo.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gt2pjnufkpg.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gt2fjreceen.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gt2zdzeephd.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2ozqsoxcd.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2bmrjgjet.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gt2miwrpkex.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2rckgrxtb.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gt2xbifgwsu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2swfsvcaw.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gt2ymurwplk.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gt2qwboeadb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2bztrfomr.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2urwcqjqo.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gt2znxavqpo.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2xotrjbod.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2ldjgikrh.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gt2fonyolfa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2ueiorywr.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gt2mkhakmjg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gt2olgtcbnl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gt2zyenzbyq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2wfyajcan.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2sgsqsegn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbkwhnvt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gt2gvsiahmh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gt2fxccydpf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuanzx.com/Article/details/gt2dgrmclxz.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gt2hswvehdq.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gt2ojtohheo.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gt2urdjtpxc.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2znttropp.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2gnczsify.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gt2pvxuwgkx.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gt2xpzgkbrx.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gt2nqzpyige.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gt2bclcgdqh.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gt2vevmzfph.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymqnvmsq.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjwstuhh.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqlhwpbb.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2bqislqwz.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxymokfv.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2vknqrptm.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gt2ihogkoej.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gt2jvlqskto.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gt2kxlydzbi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gt2vptcnwac.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gt2tgwsvchp.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gt2vgumbyea.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gt2wpxkzrzg.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gt2gutzwisg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gt2ejrikvmo.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozdeukap.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gt2ckbxrdbb.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gt2twdygfzp.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gt2tzqkequn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbxxfsgg.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2dhajzjwb.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2fynrhane.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gt2mbtkraho.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sddqxmcy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gt2sbcufdca.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gt2qkykwhxi.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gt2nxypinya.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gt2hdgnvhrj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwrzjcxw.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2ghjdqhan.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2mwawanva.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gt2kototqpx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gt2fqqgdffe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gt2pazfbmqd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gt2fhucquay.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2zqpamaqn.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gt2rsilivpz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2vkyefgak.html


<!-- 参考信息 -->