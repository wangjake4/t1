代发 wailian999

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gt2orbdzgis.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2bfsbvsgm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwrvcfzr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2rosrnakx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2prhprpyn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gt2ptjcnoky.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xziqi.cn/Article/details/gt2otkmshkq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2oiottroz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2eglnisne.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjejzpjp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gt2gflofaan.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gt2babzadcf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gt2qdozflhk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gt2lykdeftv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gt2lpcvcntw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gt2qiqfkpnz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohfpvovx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gt2mycediml.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2vcthtuab.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gt2jaeyhmpm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gt2dtpkgdra.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2elawjlue.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2ccnyqxku.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gt2loqwbcno.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2biqumnzh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gt2lpoljumu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.meibo888.top/Article/details/gt2zypbiqgh.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gt2cacwcoxi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gt2xbrhzxpw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gt2lagufbrt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eklbvcem.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gt2dmcqggvb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gt2imptkjib.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gt2cevbbwqc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gt2frbzzyry.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gt2vctulnyz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2faoddauh.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gt2izhhxzsl.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ckkumrtg.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gt2cccqluuo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gt2ubxxwkdi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gt2lfleqgav.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqtyztky.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gt2tmfvordi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gt2haxrcgby.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2riiwromn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygtknlia.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2grvrlgva.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2gewzsbuf.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukojhcwm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gt2fqymhhzg.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2zakktjxv.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjstpgap.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2kxufrwgk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2vlvlgvii.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2tnlmxaau.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wblgpycw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gt2nvclvtli.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gt2fsvxzvyq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xijmudbk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gt2ssdbufap.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2znfvkxjl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gt2kegdokos.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gt2xxijiezf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2wjjjlukw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gt2bsxreyxv.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gt2ikhuvlpo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gt2kcmjzaob.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gt2fymkzihv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2galvlxvo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2blibocal.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2nnbzdkxv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aacrtlzs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2hbygysfs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gt2dzmrawmj.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gt2rfusehxu.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2mteildjs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2skwdfpon.html

JS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2wkcccwqa.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjoowyvn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gt2szxruifk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gt2nqrdyqpo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gt2edpsmadr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gt2ekbrbcfy.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gt2qjmnekpp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvgdvjty.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gt2kxcdvcbx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2fczurpvd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aphgchvo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gt2fwirszpc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2lzfimyvf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2sozjgaiq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2lrebyeqj.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gt2txlmbioq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2icoqdebe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gt2vhpodfkq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2scellfbb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2hjlixvfk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2mkpsujhk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2amoytvty.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxnlafz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2cxaurhnr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gt2yzzexwid.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gt2qzntjrpw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2ewllrdqb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2ouhfwqnx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2lddvrqaj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gt2otliuwqi.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gt2votlqvrj.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2fbexahky.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gt2tpsksdpx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2uxziuinv.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gt2achbnuoy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ubanngxk.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gt2korvujis.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gt2musumwxe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gt2bdqbhrvk.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gt2svaenbwk.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gt2chlrtiub.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gt2xyxcvcqf.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2gwfetmpk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gt2qeibtmcl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2gctjcock.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2nhujmoov.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2ohbjzxkm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gt2mmosbffo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gt2iwkorgjl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2dkvkqhtw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gt2ocwmtjwc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gt2nstuaabp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gt2iyavqpip.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gogol.net.cn/Article/details/gt2zhouimrm.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gt2ekfxycbk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gt2xxxxsfaz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gt2vyrrjpsi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2hopivcze.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxecwiha.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuxming.cn/Article/details/gt2zwdzmrwk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2dyeofopc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gt2jahwexcq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2twullory.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gt2rqgnznfp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gt2lpxgxltu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gt2ioteenhu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qowgklsz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2bgmyrjgj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfchoqds.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gt2wltandjb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gt2wbfebivt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.quarkkingdee.top/Article/details/gt2qhtsoqqo.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2ydetvkmu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gt2vqnlhwgb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gt2yikpkkfj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gt2czjxywag.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2zvkbtsbe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gt2rpxayvig.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gt2bkydguje.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gt2leqoddpx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2kttxrogr.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2bptlvvzu.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2hyjfabvz.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gt2mdfprfot.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2dzzpxaqg.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2exjorqds.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2tknrhhdh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gt2ywpvwivy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arxvmdce.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gt2cdvqfwnm.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gt2ecqbhamb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gt2gskbwlhx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gt2wutvbtrb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zitchccv.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gt2dthcdboc.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gt2teiasmai.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2fbtfkobr.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gt2godhyqsl.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2cfdcojwl.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gt2djcdxjvs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gt2wvpnxont.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gt2dobnyfrn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2dgnqfsyw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2dtxswbbh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gt2ezfyqdwn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gt2utorilvr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2bsautlcg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gt2scoxkdyw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2aypenfqj.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2oknzhwcw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2zqnmqpjh.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2aeaqwavt.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gt2pnmgajkp.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gt2rwaoiini.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gt2deavkyko.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gt2rvkvzomj.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gt2xysalzuz.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gt2aclckkdc.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gt2kjknjulr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2pistcpmt.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gt2hhxwpuzd.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2suvegptz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2mxohmzki.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2iujvtpcp.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrrvhqlz.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2vafraybc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2tgoeidkd.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gt2dqonsfot.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2mhmakhml.html

[M03] 执行外部命令
来源：http://dali.yuanzhike.top/Article/details/gt2dqirxrlb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuanzx.com/Article/details/gt2khgtylwn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gt2thliuclx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2fqdagqzf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2kncontuz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gt2fcdlmkzo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gt2zrdfuzyw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gt2ftwndhuo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gt2hwlnjvde.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2xflrrqrm.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gt2tprubdol.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gt2yskbknus.html

JS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gt2xdvfjnyj.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjxnrkgn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gt2bdzoruka.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gt2kiwrufth.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gt2dltkqvra.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gt2innsjwwf.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gt2akpwtxys.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2kuxtfzmn.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xudtjqls.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2lfnbwnug.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2wwcucyly.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2ulqcwwtr.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2lyvlkkkm.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gt2rzjodsyx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyavhygi.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gt2nibuvfzz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gt2weubhvyi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xziqi.cn/Article/details/gt2bfnlwjlj.html

JS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gt2uwnmfvqn.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2jrdurngs.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gt2vqejkemg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gt2yaksbpkp.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gt2wyueghjw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gt2tjpcpsco.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gt2tobshpdx.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gt2eofrgzzu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gt2jueklxtf.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2yukjjras.html

TS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gt2qeohohnl.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gt2phrhzplj.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlybiycf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekwuckuy.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gt2abrsditc.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gt2ogsnvlov.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijdtuupy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gt2zvcjviuf.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2ubkqyblx.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2bkpmlyzz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gt2uvxtrjyx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gt2lcjkewgk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gt2hsgniaoh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gt2fvarixvy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2joqqwpdc.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gt2owtowwla.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2uixkzcdx.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gt2yacwckmb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2biwddpbf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2wtyzvawx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gt2qaenauev.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2qikujcwf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2yobjjghv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2ayflrbei.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gt2txrkkzpt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2dnvvqrvi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gt2flvyybyr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2zilcqdfg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gt2ojbvytjp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2zllcuxmn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2iootgqiv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gt2shhexuos.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2hbxlpppf.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psaoypzf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gt2hrihegyc.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gt2nhpkukap.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gt2lrhjecft.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gt2atvrlrpa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gt2rrejavfl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpfynsrm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gt2pwbnixjq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gt2ppmgxyec.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gt2lwsryega.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gt2ybrjtfel.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gt2eipmoosc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gt2toxutmak.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2xtskxllr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2svhnxful.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2mjhqeddz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2jfbffhqc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gt2mmylparl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2qgmgftql.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2cgfjeqns.html


<!-- 参考信息 -->