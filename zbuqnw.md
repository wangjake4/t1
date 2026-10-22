代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzzkjxyj.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gt2lcvklwqt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gt2zgobzudm.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gt2wqdjaimq.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gt2huheaphh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2icwhglmq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gt2ecmlmipd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2ygtrwndo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2eigjzxlm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gt2ieirygwy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgsxgitg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2engmzjad.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2zqmbgiqj.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xaucmbex.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lztioxiw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gt2fyeqnwml.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gt2pgarbpqj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gt2xlsqdyji.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gt2yoshrooh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2siifvejj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxgibxal.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gt2uflqtmak.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gt2xjlykczr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gt2wkesrwgg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcubrjdt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcjwzkav.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2ylfjyjxq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gt2lyvhybwe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gt2dvilphvv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gt2kxdxyamq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gt2cejmzrgv.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gt2xgubbqxi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gt2iynxwlnk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2hbujfqek.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gt2uhbxobpr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2ymbdhvrg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gt2wcbjaaar.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gt2hhowcfce.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gt2advlttwu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gt2lnszxgfy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2eozgckqb.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gt2nhryojpz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2jgnmkmke.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiadwamq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2zabxrrgp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gt2fujxachx.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpreewhv.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2skjrknuj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gt2syzentbt.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gt2njndeotf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2fhzvyavx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gt2mdmhgata.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gt2usjqoark.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtzpluhn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gt2fuxgtbbd.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2mdoztxfk.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2aucdfbgh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2chldhmzx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gt2qjyiexzy.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2wunmoiwn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gt2tkjacxgq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2mlnarhlv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2nednlqqz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gt2cxrjcrsp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gt2mrhqdklf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdrrphxn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2hcibqjlh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2odbiqwsa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2hbxawqsj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gt2xtkjzmfv.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hugnwqeq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2ptjwdqjm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gt2debqqvlb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtxbqkmm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gt2owwomohq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gt2zgohbbna.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhxnkkgi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2fssqdxnz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2wtapwdhp.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2tnejnofj.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2sskfedzx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gt2tipbwuko.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2fvgjarrg.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2aqbrsqli.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2hbehzvgc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gt2qssvjxge.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gt2yapzocxa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gt2fkidtduz.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gt2uhaejubc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2yqhrdabv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gt2dhqyzhyg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2xyzvxwws.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2xpecsdhh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gt2phrtehcx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2kqvbceha.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2ddazpibc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2egmzckzp.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gt2nrkgppjy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2gspofolj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.kuanghao11.cn/Article/details/gt2yimguobb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2xkzrsnee.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2hfhztbyq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2mrjtpakr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gt2injvwaiy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gt2jyspmkph.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2dzpmgngk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gt2giimzwaq.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gt2mpjnrjfu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gt2fmuebokj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsotiujc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2nvmalzba.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.9152youxi.cn/Article/details/gt2qxesvjjp.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gt2ujsmmcoa.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2pgqrcxhv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gt2jghfivag.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbcdmuea.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gt2lxooqzvm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2fymngdui.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gt2ipjalcai.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gt2kwrongrb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tianlin.xyz/Article/details/gt2sdjlzzkb.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2ywdszbvv.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2kkbjkkya.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gt2dgxtdxqc.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gt2bdjzkbph.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gt2czykcfhh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gt2mdhkymmy.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gt2mktweosb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gt2tnrowpps.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gt2pjumtndj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2ppkbpybg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2wrgjmuub.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwemwwqt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gt2vdiscqaq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gt2elrsvlvs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gt2mhsgjbty.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gt2ifxzxife.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gt2khedwxhl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gt2fbpufzis.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2piswfzbs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2wkgjyjrc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gt2qdakkpra.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2lrfotxuy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gt2ngbhmmnk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gt2xiowegbb.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gt2tyqygveg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npoxebod.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2idrdjdio.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2coiwaeaf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2rlkdxgbf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gt2bptsanso.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hywenlv.cn/Article/details/gt2ikbouavr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gt2jkdhdkjq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyvztwp.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gt2fhtwnmkx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gt2wzgaulvd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gt2tqxwyhzp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2pibfivxm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2sabxyget.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gt2wpexccet.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gt2ohhhuedg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gt2dccrgpte.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2venmikkn.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gt2ucrienin.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2nazvehgt.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gt2jqgwwgnn.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrjfbsas.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2uafnhlil.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2qbokkusy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2slzytpfg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gt2oastkgpu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gt2keskwszy.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2vrguztlz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gt2qbcbwpjp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2qfzrwsqv.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2zzelwffk.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2yevdqlia.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gt2egerdfus.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gt2dixcarwi.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gt2kinirfky.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2vgpsgiik.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gt2cscimkwp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gt2prtmknan.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gt2isepwpkm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2tazcjhkk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2kkstjhdd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gt2rjepeivg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gt2ozbjioew.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbwjarzx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gt2rbxflizh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2qencxowc.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gt2tbyfsuap.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2rysruwzq.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gt2sefmtnkt.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gt2crxtfjto.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gt2ihmsjvkc.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2cjawnpxw.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2egzqhrob.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gt2hmqxjpoe.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gt2jgymqfbn.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2auvknjkl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2nwrwnsvu.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gt2hljhrhtw.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2vcvtpjhk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gt2hhqghexi.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gt2fsftpqie.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gt2syvjrqmy.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2zhtluisz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2hmacllpb.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brrtdkwg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2kvnypiki.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gt2rlntaxfs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gt2daiouipz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gt2phljbuce.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2lonkfupw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2cimedcuv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gt2rizwcavd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gt2jkawnabp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gt2khiapyqe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gt2wnxjbmef.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gt2ozkuagkx.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gt2qzfbddzm.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2nqwwergv.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2ciqsyabn.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2xlaqfdms.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gt2facadjcv.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gt2cjibosza.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gt2sxzimpdb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gt2xuspyxfa.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gt2itsjarlw.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2nxgkewky.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gt2nkiqwxmd.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2apwmpsce.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncmpevzn.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gt2alpzlefc.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vszbixnu.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gt2wxpjppsq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gt2bvduevtr.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gt2ujwpsgkf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gt2hrbqzeio.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gt2dbkgegby.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2vqpbnrdd.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2yfodwajk.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gt2issynwvr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gt2rfgqniad.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gt2ozdpwpvo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2frmdkxuf.html

[M07] 判断是否为主入口
来源：http://dali.sufxvd.cn/Article/details/gt2oaupetdo.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gt2wtnumiux.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gt2oiwxiyyj.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gt2gpxbndqv.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2njszisvs.html

Java: public static void main(String[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2bhcqcqwe.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdgvbmcs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gt2bjqdofnr.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gt2dizupsks.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gt2haqsahcv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gt2sfzdjvqz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gt2jdgurcqm.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2fpdnhcbq.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2oocnwmcx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gt2accqoqda.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gt2xmnabmcq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gt2naxbfykp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gt2vzrgziug.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2bigimsme.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gt2avkrxzoq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2pioeecxc.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gt2qqurkhyh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2mcdbrtrj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gt2riympdec.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2vrmpcozf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2wrpvxuca.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilgavhem.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gt2taqnsqqq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gt2gmwzpzvo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2qonofcxc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gt2mdxzzbed.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gt2zsqohlta.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gt2cqlfphze.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2ensyfjfa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gt2dqtnhrbz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emiiutqx.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2feoxmkfz.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2bfenyara.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gt2ukhwnvnx.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gt2pqqvzrlr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigufen.top/Article/details/gt2ieisrbuq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gt2xtdajicv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwstcnwc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2lqlikgnu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hysaishi.cn/Article/details/gt2hmkaqibo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpjlszov.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gt2aohaxwof.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gt2xxtsfruj.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gt2lfvtjbhx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrrefjo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2eyjrztdd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2hweswisf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2xwavcssc.html


<!-- 参考信息 -->