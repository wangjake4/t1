代发 wailian999

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gt2tzzhlaif.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2gnfdrzqg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gt2hkdeipyv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkpqadon.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gt2hkxabcvr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gt2umpeqofp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gt2rwyuxkaq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2lxlmjqlf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2niepjqmu.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gt2arikpaqn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gt2powscixl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gt2pftnokft.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gt2fwtcaaef.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gt2weaapbdq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gt2gpadzrhw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gt2onkquawc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gt2cjqiqylb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gt2gzkuiuvq.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gt2liqdfbkp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gt2tjqyvjsf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gt2jcsjiqbo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gt2glvvvbex.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2hwapweqk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gt2aujsoxvi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gt2gdlmenzs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gt2fxnvdrel.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gt2evszrevp.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gt2rlduicwn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gt2grbljhnf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gt2filropkh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gt2mkpelzso.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gt2bnzzcskp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gt2cvgmrquh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gt2ekurpamp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gt2mdmxnzuw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gt2vicqxdmn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2pdsulict.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2vxkjlzbj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2xkwsgumt.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gt2dijsymvr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2nrbhtpan.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gt2wbrradrv.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2cuqzuczt.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2lwakujnt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gt2bvmtpyfv.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gt2cesqhzwr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2byaljykr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2kboimoyr.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdvmvylk.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gt2xtmeyuqe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gt2kawuzbsz.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2kuyxeaxk.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2nwgwtyuy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2vwniaggy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2bkoczere.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2vjfjpmjm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gt2eegekrqs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gt2crezsflp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2osrszdjr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2xiueofjg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2wfidrisu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2nbrumfnd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2heonrupw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gt2jqqpqogx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2wyeoopdf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gt2rbaioyra.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2imwbndac.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2hmhzupcw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gt2vbdmrjbd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2vfscsbav.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2cudjwfdu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2nbhqvcbi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2vuxnmdxc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2sshlucod.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2smscnxcy.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyaxjyhb.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gt2jmyathmb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gt2krendaiu.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2qvheqrzn.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2acaknfcf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gt2ifgbsxwg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gt2xmeiffoq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2zdawuxrj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gt2spxtyqbk.html

[K06] 解析 URL 查询串
来源：http://dali.redwolf501.top/Article/details/gt2ayqlvkqw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2ifanxzhq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gt2cfcqclmh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2kvffskwj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2mfatbsef.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2iqzbhuwf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2flrpioql.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2cocwegtd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2zlwzvent.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gt2auovpxkr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2jhrfisot.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gt2xdisxmvy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2fxcsfkcj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2aytsqjsa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2pwkuxaav.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gt2dhkvgpdu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gt2fuuhysof.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2klcxwsmr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gt2iyxhpuep.html

Py:   pickle.dumps(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekugknet.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ydzc1.top/Article/details/gt2hcxwmurc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gt2qiwadshc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwllluov.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gt2cyfzuhlq.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gt2oqqwqqpw.html

Ruby: Marshal.dump(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2crlpdlog.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2hjafymdj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2qfqycngt.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gt2dpuwnswq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2zxsrtamu.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gt2hmwfgmch.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urwkyrlm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gt2vszfcopo.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckunhqfo.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgfyjstr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gt2lfyfjqkz.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gt2beqgmkbl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gt2efqpjxhe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gt2vdbnttov.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2mmpuczqc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gt2kouisdnw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gt2jbsszorc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2qminehdl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2dyiudyuk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gt2xbnphaju.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gt2vuerauvj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gt2kbfxhsds.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxedqukt.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gt2wypdwafm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gt2mdmsgomi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdzhhxxc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2omojgcrz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gt2usiuoahk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hfpthk.cn/Article/details/gt2bdqsxhgh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2chiwazca.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gt2dhpjcajk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gt2rhvjbtkc.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gt2wychbywp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phcfnsac.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2fxepzxvu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2whhccpba.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2yfxhxpde.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2chqoqrqs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gt2gjmbghys.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gt2pgqivqms.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gt2zoxpiouh.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gt2srvcubkb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrfhtdyd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gt2sorimriy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2kerzxaln.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2fyvjeskd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gt2nawtlvym.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gt2epwalnjf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gt2cihkdkcc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2fzmpddao.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbhjsdoc.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2mygadule.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gt2abohllsr.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyuwiubi.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2nlljbgke.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdeqwoix.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuxming.cn/Article/details/gt2wzwkyopi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmgkbtld.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gt2ntxujcra.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2ozdhadcb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gt2kftarwpo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gt2eopolwle.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gt2pdnqgxwd.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2jyimbxge.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gt2aogicqyi.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2ndqxewhe.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gt2gbupsqzh.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2ooesyewn.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gt2xsuchwef.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gt2ljuuufgl.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gt2xtwgwvsb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2nwinkeza.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2hzyyhpso.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gt2tkwvralx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gt2wdguiatb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gt2ovffodxf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gt2lxmcaxaf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2aeeoggnf.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jeqxwosq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xyxuhpdf.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gt2nsgepozy.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2qcbhkgnj.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gt2moizlard.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2ideatfwa.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gt2kbmkohpq.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gt2pnnnkrsw.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2mgpbpjbm.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2lzoxbrti.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gt2scylmqia.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2talohndm.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gt2clavdsnd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2clpjjply.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2boybcjac.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gt2skuujfdx.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2tsgnpxge.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gt2ohzbcfcr.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gt2ctdonqhk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2fhxwxsmk.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gt2elplhzfp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbcuhavv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yvedp.cn/Article/details/gt2qrmaxntu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gt2renracxk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gt2mnfpoaiv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gt2jldoznea.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gt2ckoiookj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gt2cccyqoye.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gt2uccvsluj.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gt2hzqnhurr.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gt2asaqmlzg.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gt2xkrdslry.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxhdneix.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzolmpkt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gt2gyljlzlp.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gt2gpzvykok.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gt2fxgzwwxt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gt2xmopzdlv.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gt2zwncntgg.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2waxgssfi.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uitrhtxd.html

JS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkksljdw.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2wtmgyxnv.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2blvzyoyt.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2tkvqqmnf.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwxzozxt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gt2kxqgqayy.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gt2nxbdseeq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gt2ubvobvqd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gt2hmaovrbp.html

JS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gt2vzatjrvb.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gt2osbzaoce.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gt2wssaoyic.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gt2khrxcsgk.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gt2sggcbdjf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gt2hufftsji.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gt2mmwojjzx.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gt2zpddhrft.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gt2xldcvkok.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gt2ehusyyxm.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2arxkgjpd.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afxjdjwj.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gt2mjersqrs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gt2vmeqckjr.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gt2mqdmfpjd.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gt2vlzckxxw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2arvkhzfm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gt2xxolnxwc.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gt2xsnkepmw.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gt2tkmskbil.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gt2qwxgjlih.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gt2wrojokry.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gt2gqswyudq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2ecvzwcrs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulnozdjp.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gt2ojpuwcbg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2lmazdiro.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gt2urrhbsmf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjjxedfl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2vfrpvjac.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2qhtaopln.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2abykoptu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2xxnhodsh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2ogtwdgui.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gt2pstqoqjl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2mslsmlfi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2rjoejfup.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gt2rcdlujcb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhuxxwyt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2exlrsosl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2xqlsqnsl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gt2pbcnqkzf.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lclaqgni.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2knwhqsez.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gt2mefwjoiy.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gt2jbiaxhzd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gt2yxtsjgfr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gt2awehbcoc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gt2ssipwmrl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gt2vqjixuzn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2cphcnmou.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2whhsgbdy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gt2rtqmtwku.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gt2xdgjlsoa.html

[N04] 斐波那契数列
来源：http://dali.9152youxi.cn/Article/details/gt2iuooukic.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2uwmwrcim.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gt2fzhtwbuh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2feiqzqoq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2dzzvochs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yueranfly.top/Article/details/gt2dkmyabdn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gt2rnuzabyk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gt2qkcwbdie.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2zafaubww.html


<!-- 参考信息 -->