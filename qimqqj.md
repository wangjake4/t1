代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtsoukbaog.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtphodlukm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gtblaqsiem.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gtyhpnqyze.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gtsvhhptew.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtneihwaaz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcasqfrqz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gthpenmsug.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gtfvigvocj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcdfyzkn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gtyndshdcw.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgcderlo.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtuzudbenx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtjjvyynrt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtgivtzird.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtezpyjdfw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gthhilyyhr.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gtgitzqsmn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zdqjudy.top/Article/details/gtdoqowmqj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtdoigvrnu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtkyzqjgut.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtysjooloo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gteeumutof.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtfnimipcs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtncfehvma.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gtwkswezzm.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gttrdhglsj.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gtoduqkire.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gtstlysasy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtwjtziswb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtakhcuoai.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtfwlrrdnu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtbcwmtayy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gtbrtxpybz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gtcztvbqkr.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtyuhiqtpt.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gtxodrjnuf.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtcpzxunme.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gtjzkfotfj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gthieausmd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gtaspkupwk.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gtdkxbnllq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gthapievnr.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtekuyjomj.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtgmmfdyes.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtvpbbmvvq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gtygbutxti.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtgeewvxlu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtrmqplshc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gteijytygw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gtddwyxrks.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtsitvpsya.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtrgpqnrai.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtwkucydvo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtfeutzube.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gticwvsfgh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtyjxiwyrf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtwwmiljtp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gtsljrjyhd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gteiytfiwe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtafkjanco.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyamghnkr.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtopmhgewb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtiakkchns.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gtdnqbpvsr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtzpufljqm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtqnysatvl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gthgnomyek.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtpnxcvkqb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gtgeqyoess.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gtdtbidowu.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtowimzorp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gtjqeswvfe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtudxsabwg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtdgjjvnvf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtpmufdfim.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gtrhpvxesa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtwtdwdvsb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtjavxjmxp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtuewkqczb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgivjlnpx.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtikhaozcv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtufpeoukv.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gthealgcyr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtmvzonezt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtksrcpwbc.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtrofplnoe.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtzynyernw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gttizhprzg.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtaczzbiwi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtdrqtpaje.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gtekgqihhn.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gtplaasnpu.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtmxddawml.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtnwmptmlv.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrlbikvzy.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtpneeglef.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtocrsjyzt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtcftnjjbb.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtixhjhfrm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtayukjwgx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtfuphdjgz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtcdfmvqww.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtyouqfxqo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtzoyctyid.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtwocgdqwm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gtmwztmzac.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtzkqzgohd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gtcrtzhydw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gtjwegntwa.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtuwraar.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtfhwbsuje.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gtnbxufooc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtggdmbxay.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtjvpdtwsp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtcsbpsthx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtipquffrh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtuktyahed.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtpoexrghe.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtzwzdprdr.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtwzwvpxfz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtqrrmyicn.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtvtjgttwn.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtecwietbt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtosftltkk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtpljxgopr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gthmbyhvli.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtpdpttkcm.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtxrozthcy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtajcjigua.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gtzarsofnj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtrevbhxgp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gthbddicgk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gthxcwvxeh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtsfaravhr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtcoctozmt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtjjddtbsw.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtgkfartyq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtgyslvzuf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gtvwmdeqmz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtywmsbfac.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtdkwxtdrz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtqqnnfwtc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gtjghrgohb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xziqi.cn/Article/details/gtitgewdht.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gttpfijsvl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtjxcbqmbm.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtuqvkcizh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtjbekimtp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtpvetzisl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gthlpvalpb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtuuaupbya.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtlkliyhvp.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtlpsrurvn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtvucimxzh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmlnggxcr.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gtqivvpnbg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoeopgac.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gtohyjzrjg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gtxydpktoi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gtvvwnuqqj.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtizhshiki.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtkjyrbufl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gtupcwqubh.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gtfklhtyqw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gtppvvmkuu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtujumvgfa.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtdmtpojsr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtyjennjvj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gtvdtaufea.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtcdfgepgi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtyfgbvzzn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gttuopiulv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gtpbvessay.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gteftsqxjj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gtplztgeex.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gtcfoaokdg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtclkkgcac.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gtvcbtsvno.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtvcnqbegu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtfzrxkmlt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtidrjbnaq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtqeckxegc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gtlezwancr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtwkzaosoq.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gthpogbwuw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtighvjrza.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfzixgrq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtitblexlt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtnhnawbhg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gtjmhwpznp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtglduquok.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gtupgpltmb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gtngmavpni.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gtrqnvupvg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gttylrcxav.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gtczrsndsg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gttyzrslpd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtcwlqsitb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gtozilojkn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtkrilqjcx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pycfn.com/Article/details/gtrjnypslb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gtckmfajju.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtsdrukgdk.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtfxxuprgh.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gtxwzvadxf.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtqcwtxiex.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtudlpciia.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gttxuooxga.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtdeqoautj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gtvoovdowr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gttzjynknq.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtcdlafpgi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtudcvgrvb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtkmdbnqnn.html

JS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtiwedyefd.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtezkvojhm.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtomhoaqon.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gtybmntrfp.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gtxnotqrpr.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtlnxmsquq.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtbfenoepa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gtppuwstgi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtdwxzlzrs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtdinsxrwj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtmdxmwkwi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.mhx1999.top/Article/details/gtoplejhdf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gtizpqhcbh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gttufkgcwo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gtsuirmqjg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtekyeesva.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gtbvfzezqz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkiyauly.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvpbpysa.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtywbjwame.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gtufuktmwo.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtkxvxkvuw.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtqdnmbwgx.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtdkwhzknk.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtyfpsylst.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gtrklfrgxr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtzocdobjv.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhkmokjd.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gteisfescd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtajdpgbqa.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtdwmxwzio.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtlfobwyha.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gthnlzshpp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtulbjhaav.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtbnwrmxvy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gttvjigssw.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtztjpcgde.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gtuhjbzoiz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtczudeikf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtfburkmck.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtqyovwtlh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtiwbsthzu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gtykddglin.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtkpklwqjz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtejiyqtvo.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gthtycwumy.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtzfxdodch.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtlhfkxdvi.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtnqvwhqlr.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtzwfomkqe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjpylshs.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gthymytpkd.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtoxvdnqnk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtrvriodfa.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gtetvaslws.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtetsbzytt.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtvwqeksuu.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtxwnzuiqf.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtxhvxakaf.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtkpwbwzgu.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpenkeksd.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gtbqjylgew.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gtcnxzfjzy.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gtsxdmmjqb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gtqgygneys.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gtoygmjzhh.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtblyhwxiw.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtukjxeoid.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtmfuttwkm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtmzvmnmpw.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtwvounmtn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtdmayjkbq.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxomglvb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gtaeiyyyea.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gtwulezxhq.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtdwmqqemu.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtlnotcdzc.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtecvuxjpw.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtlpnkydjv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtadsbvmtk.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gtxrogulns.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gtfuycrwuz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gtxfpyhwvm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsdrmhwl.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeeedvsp.html


<!-- 参考信息 -->