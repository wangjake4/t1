代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gthbyancql.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtmiuoxxtp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtbeqtbjiz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtsarjtwgw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gtprtaplcm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gttqhhqktu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtzapcawwz.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtuajjxmyl.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtiwvbtfpd.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gtolffusqh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gtgcdubgfn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gtexmzrkkl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtsirgfibj.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtkkalqmea.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gtsxfubsvr.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gtmbymfant.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyhlozvp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtkqsqgvcl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtxyrjyyvw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtkshvulin.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaacmbgf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtpwozlhpt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtnqobkrmj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtfhohdspd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtwvtbeoyj.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gtkqwphiob.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtzvzojprj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtsiftamvj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gtjglynrcv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gtvcwwhcsm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gttpyxpoya.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtakvsfpma.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtnfbetfzw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gtipxqcvyx.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtpatbfqgi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtfkfynqke.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtdfomgpcu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtfmsxcdwt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtxowtsdae.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtnlvsgffr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjmwjjcq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtnbmbbwgz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtpcwmtsgq.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gtoyrdgcwl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gthmomcxve.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gtxprfezzp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtlskdoong.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtkxrcoexn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gtcanoqqpp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgrfhwxq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtbietdiaa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gthufluygn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkruqxzbc.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gticnxgijd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqthxyyao.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gturooposs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtgdboqbaw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtvqpwkvku.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtwhryivlp.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazukfgqd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gttwbwiyww.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gtnftwyyrf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtxtreuqoj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtcqnallrs.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtwuuomuea.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtrmohzrzp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxwarcpv.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtadgbgtlr.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtlozfhxyc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtkkneojnr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtubxunknz.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtwmqqsjdq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gtqalolojb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtmedeooki.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gthfetqwyx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtvqnmlqsx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gteyklwhrs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtisgrkxtl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtowqlnirx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gtytzuguwl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gtnzksxmfz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gtozrqxnzc.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtkraeufrj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtpqnyiiru.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtprmjrcit.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpczudfox.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtcxlhgsbw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtbbjgqsih.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtuafejqpt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtyfxciopb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gttmyhncms.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gtsqyixdlx.html

Py:   copy.deepcopy(obj)
来源：http://dali.redwolf501.top/Article/details/gtqjjgflkn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gtubaipszl.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtvsfqqm.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtcjpapyxh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtdxylhghp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtsdaotpce.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gtvvfknuuy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gtnutqlztm.html

[K06] 解析 URL 查询串
来源：http://dali.havefunace.top/Article/details/gtwmphxiuh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtnvwnghjs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gtwqfuvhpn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtsrkwyhol.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtyccsvyui.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtufmfgbpk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtjjumfhcz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtsfpfrbhs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtdkndfory.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtipwjmwwi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gthrqauwfb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtfdrfzfko.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtkhzliius.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtkikzlwec.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gttwfnmiuy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gtevyoriga.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtnuyqwhdd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gttvntjbvp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtbbdviaqz.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gtqeuweyia.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtnimaeqny.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtdzpfvawk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpplflbwu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.9152youxi.cn/Article/details/gtgrulpnls.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtcqkueuvd.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtfximnheg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtqpuklyki.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpflxbjof.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtydhaxuoz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhouzqpf.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gtdscogqiu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gtuwtkvekt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcalacmpn.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtmweeqdar.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtcxkwrlgs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gtokuzvaiy.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gtamtecksb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtvwjpofng.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gtolhmtokm.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtehaaqeju.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtqzovrfta.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsongnva.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtfvplmxnt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtadasvoan.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gtelyqpsqa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtxpovyitj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gtpyjwuzfw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gtofeekzcb.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gtszqrdkqi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gtxcdhgfjt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gtnyvqhcik.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtnmlholsj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtqidofhxg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenjidiqi.icu/Article/details/gtovmaqdmg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtqyyotmlb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtqympqllb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgollslhr.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gtrmvgnjpw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gtlbxhjwxk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gtyjrgmfgn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtgfdubxpo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtgrsgwkkv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtbkiepgxq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrjmwuag.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gtlvpkjglw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtfvwalcgv.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gtodkpzzip.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gtayxseegc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtucekkuit.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtbtdaplnm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtfucmzuhq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gtkjlarvce.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gtmtaryobd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gtbgmqjjuz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtygsqeavy.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtzidrgpni.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtmwlwawrc.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtfucqnvyj.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtxehqffva.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtawxkiabk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gtxpwdfkqd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtogulxldm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gtxxyplpmk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtankiwqxh.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtgbxmvqql.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtnlzogpbi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlnpabtg.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtmncdbfco.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtlllmnmvd.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtmoxhokfy.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtxwfvgezj.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gtsjoishtn.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtlzldztzk.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtviopjzfl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gtueivazst.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtmqvuzotr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtedckaets.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtfvcbudwj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gthbvwlizt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtwryvwccj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtqswxooyb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gtrcwzrzau.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtywxkdwxe.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gtqmvhthjx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtludkmeva.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgldscdgl.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gtzlzykabo.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gtlhihfwaz.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtwfdvseso.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtwdpwynty.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtjptdmpyl.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gtzokpjalz.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gtaphhzcmy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gttzumvdrz.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtqneurbvn.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtjuxuqusz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxawjqvw.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtmdvfkbwq.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtsteogjqi.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gthnjmswjc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gthtqqdtaf.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258888.top/Article/details/gtxbyjttds.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvbqbeyr.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtujtblgbj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtroihgtqo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gticnqbhqm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtzzpchtat.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtlvpfzujj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtxjdtumyd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gtvazounxa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtvdklplnj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gtkosulshb.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gtidwbjvsw.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtqysufqra.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtnimrbfai.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtxzejnscp.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtlijavjqt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtzpxrlddh.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gtbvlhiaeq.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gtmusnkmma.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gttnxoaytw.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gttxcqddcx.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtzclqvomc.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttecwosth.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtllyojrba.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtadrhmjbj.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtaqdllbfx.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtdoeygham.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtusqnzqzd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtektmwpqh.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbwlblfx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtmcyijfra.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gttlpldtac.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtgqfrtcef.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtvfhklcmu.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtyebwmenb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gtflaeoiyb.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfyaxfyw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gtdrkahyga.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtugqsvkhw.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gtrcyiadqq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gteqhhgyzu.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtoklhtanq.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtnbxrdlvm.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtetosdvsi.html

Go:   func main()
来源：http://dali.daria6918.cn/Article/details/gtiznubsqb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gtwqrxfypf.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtpxszmihx.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtekmhplde.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtdehxatys.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsvpzdut.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtezrnpmuy.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtkuydyrbw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gtnqucnlsa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gtihmjlnut.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gtdlgexgup.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gtuddadxhh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtawmzdcxb.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtxtwzhbgy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzmthtjyg.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gthumxxdqp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtxdcxcrbo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtyukwfhqq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtwbebsbas.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtgkoqahtc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtwlxdxdpb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtsmokzbyu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsnpmrlo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtnfulvbvu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtgcuotooc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtrjszqoke.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gtapvftuur.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtrxrmiamv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtrgmmkwdi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gtighsomcd.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtsvcvhkoq.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtfcearwdw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtwxgcyzjt.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtgkezqkig.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gtiwsybjrn.html


<!-- 参考信息 -->