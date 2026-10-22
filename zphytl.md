代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfaiatsi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gt2nbuahldo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gt2gbbweeeq.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdfbfssp.html

Py:   (end - start).total_seconds()
来源：http://dali.chenzaomai.com/Article/details/gt2ifvaicfm.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2jueylmfg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gt2pfirwxxk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cucudq.cn/Article/details/gt2vyfxedue.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gt2fvypbluz.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gt2qlpjlrcq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gt2froamyws.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkriximd.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gt2orgaakvr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2derusecd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gt2tixedwhr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gt2otnpdxjr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2xtmmlqqs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gt2dzbgmvkt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lygpvfrx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2oqhasomp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2rsskoxqe.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gt2yvrwkbpk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjhvwxum.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gt2vnfxgktf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gt2jjgmfppt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gt2ewggjzpm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gt2gwybdetr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gt2utojcjry.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gt2hipkkjpq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gt2spapevwe.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2spzznanr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gt2izpgyyju.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gt2pcfhzckj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gt2fooxtkxu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtxeaiz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwamvwjf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gt2ywtptova.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gt2kjohqvaq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gt2rtvruuft.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gt2zlpnycpv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gt2defmhcqy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gt2tzznypza.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gt2jmpmtqzb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2nltjzoku.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyescsna.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gt2nzhulyzl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gt2ltdzitza.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2adwxevrk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdhwpayy.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxslsoss.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2guoycdtz.html

[K01] 对象转 JSON 字符串
来源：http://dali.dashuyun.cn/Article/details/gt2rtbhtobd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtwvgkdf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gt2pbvklqsb.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2qahygiee.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2ggesxuvp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gt2nqxtclnd.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gt2tohbirhu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxwtktbc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gt2kadfnhyq.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gt2zuhysffa.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gt2jdlgiqkw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qutqomni.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkwxpjul.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2lvgwpxfy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2zdnorskm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2kpuqhebx.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2osxfnihi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gt2gqhbhhuv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gt2gsotzckn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2ixjkkyam.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2qfgrqzxj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2hhjfsiui.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gt2ifphfvwe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2mzqllltv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2skzkfrpc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2rrjjcajx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.0kj1m.cn/Article/details/gt2uqwjxixt.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gt2tayftvgt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gt2irwnpnub.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gt2ttxzyehv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2bhormbld.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2ibowlidb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2cjbtqrbn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2ukfbzkei.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdvenmip.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gt2tqnbunmm.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gt2ygfxysuz.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2ouphcyct.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gt2nnfxphdz.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2asrfqcph.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2fxuhhask.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gt2wmmwyzut.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gt2poyywkqa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2fxjqgfyc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2yervpjuu.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gt2vzxibrut.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2ryiwpbxa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2keyafvlq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2uutzlsos.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gt2wcfhtfcl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2rumntwqf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2vurezydx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxugsyuc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2thtccgci.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gt2pspmbncv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2agzrknbt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsglecdx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2yfnolbjl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2xcuwxqxe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2juratzmi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gt2xvhrribx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2jjoggimw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2pfkfbihr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gt2bsavydfc.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2voenklki.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gt2sqwvhhok.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2uxaeeqcs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2pqmszbqs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gt2umhficux.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gt2slomkjyy.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gt2uwaocsyq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gt2adbxxsdo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2uzvpqbpe.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gt2aapfmhyb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ekwlngqn.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gt2gktifxjb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gt2ystxmwix.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gt2uwmefehf.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2yswdedyi.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2gsbhqbcn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gt2tzfhiwcx.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gt2veespniw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gt2bidwjjqk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2gwbbzyux.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctrgpqzl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gt2fqlnuvzy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfwokfzv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gt2sabzuhlf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2sahmsjyd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2vxyubdxp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pckbhswi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gt2eyezzjrz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mawgkzcu.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gt2nlqaxqou.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gt2yzmkfzoo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nwbrower.top/Article/details/gt2khftqqcu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2nmjazvau.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2rgztxiyo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gt2chmoehhr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2zmlfpwga.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gt2vsjppllf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2reeaseyx.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gt2vzlhratg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gt2ebdmjngh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gt2jhyqfbbo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gt2bvlqcswg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2wapvmpcn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gt2zodqoqdm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gt2ritqrsew.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gt2yokufely.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gt2jfdiuidm.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2arjemxyq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gt2ahoumrgo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gt2dvdfglug.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2meyywgqg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2jijqtxlq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gt2zrhqmbad.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gt2kmhhujdz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gt2fjxxydtp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2sjjbqtqs.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gt2mykgjiko.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2mvsznoff.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gt2wiovsdun.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2aueegbys.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2estydqbr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2xhiqnvcp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gt2vyapzhrg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gt2zgvgbggy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gt2kqyyitnx.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2lytlewka.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gt2crnakzly.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2opntuqie.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2weoyewor.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2qcursnet.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gt2yeqyptuz.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gt2aibnwviy.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfqzqqtt.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2vwdorplr.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gt2exqihzpr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gt2xceruvwc.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gt2ulgxjucn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2ruugkfpm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gt2utlodvbs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gt2wgwckvic.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gt2wkplsckt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2xtpethqm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2fsfksovy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2korsigta.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gt2qhsnbmhq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2yohlfysl.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2zlhbttot.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqrxzege.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lcarbonc.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2uhhopfnf.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2xtvskugn.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2bhpttorb.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gt2xodlqqlv.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqdnlkus.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2sbjvxqkf.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gt2xkdnkruh.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2phlviuzg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gt2rewceqeo.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2dbpipiel.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2zzlecszh.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gt2tjqxurcr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuqfdkrr.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gt2dbnruyya.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2fsrphzdw.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gt2qegswdld.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qirlotfw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.bjfxy.top/Article/details/gt2anszejsi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2nsojkgnc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2ubhcmvxn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gt2iffqoxgu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gt2tcnfmvoz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gt2dzkxsjzk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gt2tuabgrzy.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gt2uittayyq.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2zazbmhcu.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gt2rjdlkxoq.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2pnimmbgf.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gt2hxeesbvq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gt2iaprgzwc.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gt2mnerynwe.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gt2zibfrlpp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gt2ngxkibwr.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gt2bwpcdepa.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ntuivcrr.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gt2cjgqlidt.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2clhbmswf.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2jsoqxngp.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2henacrqi.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2opnlzpnw.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gt2mgrpylhw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gt2voipveex.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2upcgbdxb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gt2gatjmaje.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gt2ksnrijcd.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gt2ahnbxjxy.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gt2aulnpjew.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwrcsztt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gt2eenadisu.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gt2ewzljgpx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gt2shsarzsb.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gt2fgfjnorx.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gt2yetjqklf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gt2jafdhczv.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gt2aawijght.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2nsezmbhv.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gt2ifftvbkc.html

Go:   func main()
来源：http://dali.chenlongwang.top/Article/details/gt2nzlidpjd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gt2gwikmpab.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2qbthbaut.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gt2enerotbz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gt2kmmdrgrl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gt2kkibatjk.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2xndhxyot.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2eukmuzag.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2feccljgj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gt2maqttnwy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gt2uwjlvlwq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gt2jfqrcmrp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvrpadti.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gt2amxjiehb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2npllceim.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gt2fmrivadn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2utkvkhtr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2wosrzmcm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2ldiuvpkj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2frihciha.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2dcilxqif.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jszdhsuq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sufxvd.cn/Article/details/gt2qvisgjxl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2pdhynttl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gt2rehjmkip.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gt2clgurhfn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2etjmlxwz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2pymjwwpr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2uuvpazgi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gt2uwqlgjga.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2rukkgbwv.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2zsihtmsa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gt2wxgalxmt.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gt2ojoalndx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gt2bfsvrgqb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gt2kzuklotj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gt2xtygnxbq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2kdmdmjtv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2bhdpbbjg.html


<!-- 参考信息 -->