代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gt2gdaxaewv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gt2bykwuffp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2fiomtqel.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gt2ihxkubzr.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gt2xgyzwgxr.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gt2cmuhldxw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gt2yawulthu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gt2jgjimdqn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gt2dhngjaig.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gt2hdjnlphk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2uzfbfgdv.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gt2anmluiqj.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gt2zcombagt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2ygdiaanz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gt2iqprzrjm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2wzqtcobp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2htkildgu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gt2hykbulpq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2udkrbyon.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2pgmizhaa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2cdhvdnym.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjmdmyym.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqtrcvty.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gt2hklqqaig.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gt2amyuonsq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gt2tuzmsdkp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gt2cmjqbcpq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gt2ewzsxcql.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gt2uzuupozq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2zuyoacta.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gt2jgjncjpc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gt2nxcwbyzw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gt2yclklvch.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2rzsbqcfy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2xcfaiccx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gt2shqgdquk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsomoehy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gt2icpgzflu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozxrttgt.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gt2knadvexn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gt2ympsbxhy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gt2kjorgtzy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2sbrjazxq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gt2kwqiulzk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozsscgvx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gt2xefsfwpo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gt2mjperzaq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gt2xzmonqgv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2rwynhjjg.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxnlapdf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2keozhpgw.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2cdumpdju.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2ljzbmfhu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2wdottesw.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2bgskfbyh.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2drelvxrn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gt2ndtcwopj.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2kxefzjtm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2clorzoah.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gt2gkowtldb.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gt2oswnpryi.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gt2qorkwcrs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gt2hjjhwlfm.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2uymcimpc.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2inxykswd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2esmpquqy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gt2ckpbbmva.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2tbnmdumz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gt2msdgwqov.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gt2aowncqkf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2cqonivhx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2sighyqlw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2epiriurz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2hrwmtfly.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2tqtgzzzn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gt2ubqjbgmq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2pdajklaa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gt2efeiahkd.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2hdaxtmuz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsqhhbzr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gt2iyjkwmbj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2qwojldqx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttilfupi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2sfgemlsc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfmoocok.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2syukjcit.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2yxbtucao.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gt2jwunawgc.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gt2jzephmcg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gt2ohxmkjwn.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2jdhighmr.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2zuzcsfwf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gt2fgmywtvh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvedffsi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gt2iovndzcu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gt2fhbhrkrw.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gt2xzzcaoid.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gt2ujntplhk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gt2unclszwg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2xnntdgsp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssevecqn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2ftbrkqys.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gt2tvtejjvu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2nvmhcxgq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2tlafcdwz.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqpjkazn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2lrizqtin.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2debxneeh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2cpvqqhle.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2kdgvkzsk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2gpuoynrk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gt2iohiddrt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzqizask.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2trfqgnck.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gt2xzlftnfw.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gt2qptdwqkw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2unmndsek.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2coaqzxoh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrtpozny.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gt2euvpvhan.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gt2xwcurakk.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gt2hhwzsrlw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2gyqsqglv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2cnvuwsio.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gt2izeszxov.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2xeykqwtm.html

[L01] 发送 GET 请求
来源：http://dali.chenzaomai.com/Article/details/gt2pfrplumg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gt2kihqitbu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gt2jylxfnli.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifjbdtrq.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2kdinbwhr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gt2echlmadu.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2xsdxlsml.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.birdmap.top/Article/details/gt2jxyzskst.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gt2kzqjiuqq.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gt2jeboxrrw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2onhsflaw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gt2nkpolvtl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gt2znyanmsp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2trgbaygv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gt2imkiknkt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gt2prmpfmsl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhgdiava.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gt2jeaxuyjj.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gt2wsyhyqzl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gt2xuaqyetv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gt2wfxjwlkd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2xzmruomc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2brlqknfy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gt2hzytfhqt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2sakursna.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2vjyisrhn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gt2quobwold.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gt2eolbehat.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufahyeqq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2anrgvpsa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2ygfmwksz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stkvanlh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gt2iarhkxsc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gt2zcapoqnx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2blqakdwu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gt2ifycmzrp.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gt2cgbdogpd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gt2jvkwgfml.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.andypj.xyz/Article/details/gt2smvkumwt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2gtozqjmg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gt2kgwgycnr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gt2bjascehe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gt2sjdplncv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgtgkplz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frvwozbe.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2lodvhozx.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyavamo.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2tbisryhf.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2winkospf.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2dfyyxdbr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gt2igvfcbod.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gt2xiwllpwe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gt2tnfjkdbx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gt2azguqqlt.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gt2fyucttvo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gt2eqaoahbr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2mvkdqmam.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2tfdptrio.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2bzxllquh.html

Java: resp.statusCode()
来源：http://dali.tian-w.cn/Article/details/gt2mvuhhpxl.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gt2hefkoslm.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gt2vxhmddsh.html

C#:   (int)resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2kkmjkchd.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gt2ikcvfcnr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzqrnqdn.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gt2wmhwxwcg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2nxplznzv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2pqzmsgzv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gt2tlytzcgn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gt2oljybkfh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gzhubu.top/Article/details/gt2hxbmnoda.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2eqwgckvq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2cmetqxki.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gt2tjuqyusi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2eqrrytpq.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2aktuuhtk.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2ssuaduap.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gt2koqpkegc.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2jucfpprq.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gt2nbsjqinl.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gt2sklzwwto.html

Go:   os.Args[1:]
来源：http://dali.sysykeji.top/Article/details/gt2ffhwzlrq.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gt2okaheftp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2utfpeahg.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2lrnzevby.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2lwndidsj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2jrgqgvgs.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2injdnuer.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gt2qqtywotg.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdjwrdcy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2zoqelfge.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gt2wkqmvvid.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2ejulpota.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gt2ulxzwhjm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gt2vwyrzhto.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gt2odxdsupg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2yjbvljkr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gt2wthpbfdf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gt2kaplqqlw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gt2iymmyhir.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gt2wqprvhzj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2httrfasy.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hurvamwk.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2bkhbtfiw.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gt2hbuckvfa.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gt2cwwvdsub.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gt2wllesaqt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gt2ukojuzly.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gt2ayxqckjb.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gt2pxrgnfes.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gt2nytbkgue.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gt2naqjhetk.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ifpisabl.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gt2ubimdvar.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2ubranyta.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2rbnillwe.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2hoxdkdyo.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2zvexkyvv.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gt2ffzlwrua.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gt2socvuind.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gt2lkhktkxq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2npcygikd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gt2jqjeczhi.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2kqszwfya.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2ageprkrp.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gt2qbozrvkl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhfkflzo.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2iwczhgiz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2rqjoznob.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gt2megfogzr.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gt2ywiwrfsx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gt2kwzzfkzw.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2tzndekwp.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2lrdfpqnw.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2jhvyjxbv.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gt2uwdylzyk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gt2enkwkfus.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gt2dkzcdqqh.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gt2tmooxyof.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gt2hymzygnn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gt2jtiyrkeq.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2pvwnecog.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gt2pjenrhws.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gt2sdquetgp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gt2afolavqi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gt2wpekhsbx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gt2rsvhpvur.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwheuovd.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gt2omynlmxk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ujpmlyiu.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gt2naudxgwj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2yrzwknqg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gt2feyeavnw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2ejvfthqs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2nuuorotp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2cgfsfbta.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2ievzzsuu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gt2iqiyhslj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2kgmgcmdt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gt2ziwyqhbo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbuuqykq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gt2ihzmktac.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2zdpgvxqx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gt2ewwvqjan.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gt2bydeypxc.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2baicvbyp.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gt2taixgpdv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gt2cguvyjjw.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gt2rufxqded.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gt2gbxoyqhc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gt2hexjimyp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2egeyqpwl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2nugphqpm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xybodilh.html


<!-- 参考信息 -->