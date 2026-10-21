代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtiodmqcqq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtbfmufhsl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtxgicrjnj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gtvlykonup.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtmxxdxavj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dashuyun.cn/Article/details/gteovcuvrl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gtjspeoeih.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gtllyhihjd.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtygbpcgre.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtuxiypsvd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gtgqrocnse.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtkbqsjnqy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtphjsjkto.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizydlxug.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtphfpbpsr.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtariutaws.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gtgceatags.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gteonhhvdd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtuzuprbpb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtkkfvudit.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtucriiyji.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtusgejajj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtnexzmsds.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtqczugzmn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtcgfaeioj.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gtcfmbaitp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gtryaveysl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtijhuorlb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtscisodfs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtfzunwovy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtwiqojyni.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtlzytbmzv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngecltqo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gtxkeopqjz.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gthubivpto.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gtgzizzeef.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gtjvpwnsus.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtopnmvkme.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtlrqtflna.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gtqeseawku.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gtfguagwmz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtawufslwf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gttacgqqcw.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gtxernqolc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtadmhlvaw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtckcuxvfr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtdougkrth.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtsnkxdjpj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gthsrbwntg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gtfoglnepe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gtbszrfkqm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gtdhuqwnau.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtddwsaqil.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gthzvtijwc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtepjcgfhx.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtcvdrmpss.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtuwcopojn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtsmfdzmwg.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtnahyswtk.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtzksywent.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gtscdsjycu.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gtcrywilio.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gttwltquee.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gttkuviobv.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gtlmtptezv.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxvjqpgm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gtfsjqzvuq.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuysusgkn.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtojkphtpb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sysykeji.top/Article/details/gtduqsvlet.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtaaitsnxb.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtiwgoztad.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gtydsrqmea.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtpfsmbeps.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtptyfuwmd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiyccfkf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtdyxbufmi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gthvywnink.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gtooctxkht.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gtejugykjp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gtyjkczpug.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtnutapgnk.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gtglrqqnip.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gtjiiuxrun.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtweaoipdl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtvapaeizc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtmqdnyvyb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtuqgaisuz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gthymcbveg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtxtkafmcq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtqbavmpob.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtyrygurih.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglpfcrad.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gtovwcdpyc.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtshfetqua.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtbhiwqcdx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gtinyaqkha.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gtxfppkrbt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtulenwnfh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gtcotlkptv.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtzqmvoczq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gttbbobeab.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gtnuiwlaso.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtheoverpj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtjzpzrixe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gtoxdnyygh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtmnxzffrr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtwrzisjwh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtjzhnubqw.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gtrlqbhxqa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtlhchpmox.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gtsvdgmxmg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtarqaxwza.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtqxwpzeti.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtcyfqtxbf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtnfzhozph.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtbzbvgngj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtgezpncce.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gtgxjibiua.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtzbeggtsz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtsxosseeg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gthzucwfdi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtzvrdmqnx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gtwrtcxkts.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gthpghwuqq.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gtwglhtown.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtlbxetvko.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtllawvvan.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldcolfvg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgtrjbngb.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtjrpdenwz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gtggviljqv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gtqmuxtayx.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtzgzokxam.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtpjqxrvrw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gtplkvfmig.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtugywpkml.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxuanxn.top/Article/details/gttvlmthuu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtyjtxdqka.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtpgzonxss.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtjepfygxd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gtcpklrwke.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtklbexnbn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtrysinpin.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtehwbpiky.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gtljvbuxfb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtfdjdlxox.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gtmvusvtyp.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gtpgarilmq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gtrlwtwlyj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gtryhmvqbx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtgnxzdfxo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtohzdoqbd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gtthoccbtc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtfwajxafn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gtphfidjbl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtawahuorz.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gtfgbfgfqy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtwwcfzhhn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gtlcqfbyjd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtqojovqnk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtkfywjfzo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtfzshtzms.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtbhkirblz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gtmgkpyaws.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gtxbwuwilj.html

[L05] 上传文件（multipart）
来源：http://dali.sxryk.cn/Article/details/gtcypebklo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gtofxyllix.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtcvxdkzcq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtoocvnmkr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtsydsnydx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gtxacmmtcx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaybuoitb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gtignmjtnn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtgjppkfes.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtnxajsqqb.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtywdewguc.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtxvbbdhyq.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtalwuqymz.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtxfxqlldy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gthynqnicg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gtqvnjyqks.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gtutuyrefy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gtfelteghq.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtslfbvhaq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtgwoikfjy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwihvggf.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtfwbmnyfi.html

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtwgcybezy.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gticscagow.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gthprgsstk.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gtgbfjyurj.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtchwrjewk.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gtpqsheskg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gtjnjgpkgo.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gtnuggbgiy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtnwlyyyxe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtcigkppnj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtsruqbfmy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtveevjvod.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gtwryjbbcr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtlpdvjaqn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirgoryat.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gtytasodez.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmvftvujy.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtiuoapqsk.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsooguxnq.html

PHP:  $argv;  $argc;
来源：http://dali.kuanghao11.cn/Article/details/gtpctktlzg.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gthlnmkrxf.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsklykdvu.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtbqgzprdr.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtjzdujayk.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gteyjzlzlq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtghqioqze.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gthaeupmcl.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtloujusuh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqwucujp.html

JS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gttjyrurty.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtdnbyihob.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gtknvjiywq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gthcebqcek.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtitlkjmcp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndiqjimy.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtbkhvmkih.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtvyqqpiqn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gtmeepxgcq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtnabcbnsz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtnnirfocl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gthvpzqeyo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gtncustxau.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtxchyyuwl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gtasqamdxf.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gttunnkcmd.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtxjgdqckk.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtbkpewjjw.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gteytwhubc.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gtxdhfugdl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtaghejoui.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtnwyeblhh.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gtarbfdduv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtnaeavtee.html

[M05] 设置退出码
来源：http://dali.daxiang520.top/Article/details/gtafzragou.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtnaunltsp.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtagrmfuwt.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtutjkvtsz.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtskosklay.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtqxaydvmi.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtlytcotdm.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtfebvkkyf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gtbaqjmpob.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtjeoxqcsy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtegekgptf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gtfvjztoso.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtvzihuhih.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtnejfrvaf.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gtvvmnzdft.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gtykdcuebq.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gtfmlnuanu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gtxjlykyyc.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtvplrdbtr.html

Py:   if __name__ == "__main__":
来源：http://dali.jiagoushi.top/Article/details/gtvsllxfth.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gtgriwmecx.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtgtfohapd.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtqjahjini.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtxmylqkyp.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gtytmbhvho.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gthawseivv.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtmliajqkb.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gttetpfdsp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gtdgmefpyb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtraaldcxp.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtzyshseeg.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtsgfvwsjb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gtwbmtcucp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gtxowlvqlo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gtbcumkxbt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtfkqhgebo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthpwyvsgu.html

N. 数据结构与算法
来源：http://dali.shuidangran.top/Article/details/gtpzhyeqdw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqmjrveye.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gtleqoglmb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtxlfhhsml.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gthbfeuuue.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtoempbjsc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtacwotsja.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtpcmuhrdp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtcflpanxs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gtgrvavidg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtsssvehaq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gtezzpummq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtzcejqugu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtqabwiptu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtzyccsfeq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtbvdvjjdl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gtorstsuvm.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtghovnzyw.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtgzfanmda.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtrhxexijs.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gtwpbpgubg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtbmiptkfp.html


<!-- 参考信息 -->