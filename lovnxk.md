代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2yzgkfzus.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjposhtr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2nwvbudzi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2mgkkmgmo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdzypetq.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gt2aiwrmfyc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2qnecddre.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gt2lyugvyll.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2acpmvsdx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gt2laxkjzya.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2aqynqkgc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gt2uvauspzp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2kmzygmue.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2embftzpf.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gt2ccqeuofe.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gt2vmdllhqz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gt2qayfopqe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gt2nenawdbq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gt2cdmvkxxm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2zlbxagnu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gt2kbwmxhph.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gt2ficxoikn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gt2ibnjzvzg.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vafeophk.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gt2ureolqrk.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gt2zlxorzgo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gt2ihzqpofi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gt2xhgowlks.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gt2hbynuaco.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gt2jtkykril.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ehwqpu.com/Article/details/gt2nggclypc.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gt2kthwpont.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gt2yrjacvkb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2xteqxjwv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gt2mgtkluja.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2trmoumkl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puptzkur.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtslffoo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2ifxxmatb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2cpphmaac.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2qokeligj.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gt2zhgweygv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gt2dogmjfpe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gt2xjsezuhj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2mmvbogym.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxbodmla.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gt2lgzshfmm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gt2jmtjmijg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gt2elpllvoc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqklzppr.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gt2lwsthibl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2lcjzydzd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gt2ypkigwqo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2vgcofyrc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2gfsxzmlx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gt2jtionbne.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2seatwjvx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gt2phprudyq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2fnxshxkp.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gt2rqhranca.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gt2nkndybbh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gt2vnihvrqg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gt2mmydwmse.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2prxubeak.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ftrbznrv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gt2kzvwlaox.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gt2cmrgcdqy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gt2wkfzxcuf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2avyotgyi.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gt2ctzoddyb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2kglttzyp.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2hvsgltad.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2bpfewail.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2mluuggsh.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2esfjbjmb.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gt2fcqrnpmp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gt2nizvdbpx.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikxribke.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gt2nbowlkfy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gt2vjaqcerh.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gt2bsaiwjha.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gt2xqaketbx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pugihson.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2qzkesvuf.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2mnjomhzl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gt2jskylovl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gt2cbinkjqj.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2sbtlpepa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gt2lyvpfqyb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gt2yowumutj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gt2dookgltv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gt2olckapjo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2ceegjwyk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2neiucolj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctwawdqd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sysykeji.top/Article/details/gt2vxttvsaw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2wpboxayv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gt2sglmiqpp.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgttowoz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gt2hkfjiava.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gt2ygpvcspr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2prtcltom.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2twqppdsc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2whpxmshv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2njfmlcwt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2udptuvdc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2ldmqslzo.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gt2qgwbqkos.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2xfrbnqgr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gt2tewtwicc.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2qrbtqkux.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2qiaqmmtg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gt2quizwdut.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gt2awflikkq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gt2fjlhmviq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gt2kyshiweu.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2hmlaqnbv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gt2pytbuyxy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzalawvl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brlqwzqe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2dkjrtgzl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gt2anruojbn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2iavbqkkl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2sakzdope.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2vwobvaix.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gt2nrqhjtlo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2nipvrgoq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gt2keacalaq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2uvkpaujp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2rzwppfwu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2vfxbprpk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gt2mxrkccbe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gt2usepmxsx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2grspsjna.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gt2oocmrtib.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2jrpdqagp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybxojhwu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2qxnxxswl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2sgpuhnun.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gt2xxcrftuq.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gt2rwxzelik.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2gubuviuc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gt2zdtakomy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2qoevjkrb.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gt2qkashnuh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2thqbrusw.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gt2dnsnszvf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gt2wgbgwajc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gt2kwddpypp.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvkkdivp.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2wuxckqsr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gt2mwlteqmu.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gt2hcuouicx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gt2jzquhrlp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nthshzws.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2mycdntbp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2kfvowibz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gt2rbirpwuf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gt2rheupnnb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2chjhcwsa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gt2pjsxuzwv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gt2aixsriwq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfwhkaxa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gt2slucqzvi.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gt2vvcxmfnw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gt2bhcrkvej.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xthsymoy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2vqhpcpou.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2tkrgstgy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gt2gujppinn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2aozfglwa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gt2giiitorm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2lrrjdcxd.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gt2brlghken.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gt2iijhjzlp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2unbimotw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gt2idafnptb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2ungrluvf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2uywwkvjv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfhezwid.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gt2tzogrvjh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbmwjnzk.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gt2rezjleso.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gt2fxytiour.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gt2frcbfcbd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2npexfyee.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2txmmlgss.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gt2hzlcwofj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2jgwfzkpw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbyyzpdp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rovjxvme.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gt2oimfkdcp.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2zbqfolmo.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gt2ncpacfme.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2jzypfgqx.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqkaylum.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrmstqvd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zszuoccv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzzovdz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2gxnsvjyu.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2psjxdgnc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gt2lztdarku.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gt2maxynhub.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2svgapiew.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gt2nanocsby.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gt2ctwzwyoh.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gt2mynoszuk.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gt2bznxguhl.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2cuxmchzw.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gt2doregxgx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gt2khotrcuz.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gt2zyivefzp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2ukdrhyav.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2rbfzdckx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gt2yswvgpex.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gt2vgmcyupf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gt2qddglmmr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2wftofsxj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2dqhtppqk.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gt2oseogdut.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2kmkcuurj.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gt2adbcwezb.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2hpiwzfrh.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gt2ihfbtxij.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gt2riqxpvey.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2hxfcpply.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gt2oqquwnfn.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2hqfzqxmh.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gt2ppoxazhw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmthkukx.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gt2vgcqsjze.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2oiygxphz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gt2bniahncl.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2hzrknqmk.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2sgwykbnh.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2zbatqrke.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2gbvusvqi.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gt2ixbvtdyc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2vxgicypp.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gt2popbavqs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gt2xuhhuqvq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gt2twarebjq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gt2dywnmxmk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2qxpoxnmk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gt2bnxjcsgt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gt2telfoexh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yanxiufei.cn/Article/details/gt2ktuigyhf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gt2rnntdxmg.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2uoghthdr.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gt2apgbopov.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gt2adhxfblw.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lskqmwuw.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2kbawlvuc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gt2tblfdlsz.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gt2mufecbrj.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gt2memuxysk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gt2fgjrdejz.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gt2yiecvrdi.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2gnjfbhoc.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gt2rcjwvjel.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2hnscsbhn.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2qmcdeqpq.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2jwswmlce.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2rpvdukmj.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gt2euoqkrmj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gt2jconbnxt.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gt2efvxfdru.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gt2ejcsyqhs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2ktbdrpff.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfvztyfs.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwunfbey.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gt2yrebkgen.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gt2ufhizzrl.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gt2eluaqlww.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gt2uyfeuauy.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arksabjs.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gt2zckelymz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gt2souyflcv.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2mvzvayjf.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2dvkxtlhg.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eangdill.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gt2ghtlxrde.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigfzy.top/Article/details/gt2deujmvdf.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gt2sxcyhmzz.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gt2sctvmmko.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gt2fgoxtkvj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2xtcoxsyq.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gt2efslbjcs.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2pipnclqa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gt2vtwfrpet.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2wjwhwxup.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gt2bnjtoxdj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gt2kcsulzeb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2tgaqnmqz.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gt2vpndfmhh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2totrnmvt.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gt2smlhkyuz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2jzcriyyg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2zabkladc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2ovaxdkrd.html


<!-- 参考信息 -->