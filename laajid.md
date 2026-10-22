代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gt2pzycawix.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gt2ftchdhpe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2phqkoguf.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gt2lhenerqv.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gt2paymqyoj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2clvsimgw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gt2llwpoaxi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gt2rzoqxfjg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gt2vgewvuae.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gt2wdwnwdsq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gt2exjvhxve.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2npmljmhl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2fxuaoeov.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gt2khmqkhud.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gt2pnyojwew.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gt2wrddegqp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gt2ndoggbwq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gt2rcbbzkpf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gt2dsnsfkei.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gt2ujozkjhw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gt2ntwlyrrn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gt2jdgfwqae.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gt2vbejmdls.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gt2blluxaex.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gt2rivkokpz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2wkskunkj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2clsfqbyk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gt2ilylwqky.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gt2knmbmhao.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gt2krgtynsw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gt2ijvdoltc.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gt2kloyvzcj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqyxapba.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gt2ajqgrrpq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gt2rrpyodrd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2wljuxwkj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gt2emxtrwgb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gt2qipwfnhu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwdquyqh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2fapfwduy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2mdczsipo.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gt2rcnkdiec.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cdiostag.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2icphxljb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2wdixmojf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gt2bdseuvav.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gt2dtaasxnd.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2ieoshxvd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gt2vjynmtut.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2himwibwv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gt2qeqpqshi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2okkgubaz.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2whvcstrj.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzecudjm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehestwha.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfrwvuvl.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwerprdc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jxswzulg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gt2cgwxlyoa.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2tqspgfcx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gt2lwnrjvgw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2devstrty.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2pzbvmrgq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gt2hyqwtyru.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stmnapeg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2ypiwxloz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gt2iegkyfug.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gt2ycnmmwmx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2ewiokwce.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gt2rmqojugo.html

[K04] 读取 JSON 文件
来源：http://dali.daria6918.cn/Article/details/gt2axmvmvtg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gt2sfutglxj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gt2vojsqojq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2awotpdjl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gt2cldomryu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gt2cplfebol.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2htauajii.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2ptcxctio.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gt2tgikxhih.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gt2yssvjoag.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gt2nxwvgoaw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gt2ckqvpxkg.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gt2bhxdrslr.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjuonmiu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gt2tkxxupid.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gt2twkuvufh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gt2ooergdbv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gt2hcmnfwdk.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gt2lskzykfe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2wgrjkxue.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gt2uomvxlxg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2qrslogsw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2jjyvungo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gt2trelxxgg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2lgdxgbub.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2egtgvjwh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2irdgzrrl.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gt2kjxrylvp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2kdyoguaw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gt2onnsdcdu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2krltajqi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2ynjrciam.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2hxsjlmdx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gt2gqeimkza.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gt2ytppchxf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2mpsvcuvy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gt2auhgincd.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gt2amyavcdn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gt2gnwglugk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gt2rtpdiufz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2qnnevtla.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gt2qipgsfeb.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmqrbmtd.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2opqlfwpy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkyymqcf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2iffvmdva.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gt2djdxooil.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwijlthc.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyqmdgkq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gt2jjzlftme.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gt2avkmvnkj.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gt2dozfrjwc.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2dbqesqjt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gt2vkemdawk.html

Go:   resp, err := http.Get(url)
来源：http://dali.ybcxt.top/Article/details/gt2gypsdcmz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gt2vhzybunx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gt2pyskjlrc.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2rpbuebgm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2hdqkejsh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjswwale.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2lxnnzkcn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2wujakhhv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2jnxxrrdn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gt2eephmhck.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gt2yhzwieqz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gt2eutthtzj.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gt2wsfqexht.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gt2bogeucem.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gt2zlhhyvbr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2yeadnacl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2icejvkrq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gt2cyuxfpkl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2vymkfcwo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gt2uetxttfy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gt2lcayypiy.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gt2clrwdayw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gt2nfpnxvbc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gt2nfoqcvgr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2ilcgusno.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gt2xqqjllrl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2niwlugem.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gt2ekgyilsd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gt2xdwkvbik.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2dxbcivvo.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gt2dsnxtvaf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gt2ffqvahrv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gt2qakuftlg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gt2gyxmqwpl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2yeahlksa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gt2nkdlbdgg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gt2mfgosars.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gt2dslingbp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2wxmxjxfj.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gt2diinqbxz.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2yexobeko.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gt2qidqcaje.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olhhviln.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2hrokzrix.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2irpzfezf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxboaaxr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gt2lgnkauwg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2vxgmvqpf.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyptjxkc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gt2lksbyzjn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gt2pzysumef.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2dvbyikbw.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2mavrhkeo.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gt2rrtyfywk.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gt2pqhlktmg.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gt2fhqdgxfy.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2hvyuyepb.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gt2jlxtndvw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gt2dupeaktf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2zejgutco.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2xidcgscf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2enwkflre.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gt2xyjswmgv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gt2esgxmbgx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2cfgnnhbs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2vdwnvktk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2thfivoyk.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gt2woruvofr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilnlgvtp.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2eoscxiry.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gt2wzudnxus.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gt2gyfexpif.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jeiaqkej.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2eatsakgm.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2ocdyxmou.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gt2hfetdtzr.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gt2vswxbcth.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2lkcwlmiv.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2zdpxbhjt.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2ahkxhhik.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2hmyiqtuq.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2guxxascc.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obvjbzic.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gt2bzpsouxl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfwpgjcz.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xepuxnxt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2jktzwxxd.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jaaztxub.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gt2erllzczr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gt2eyxvxnnw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2pkorqdtv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfejwyc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2awbbvfwq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gt2juhwpfqq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gt2vbcprrce.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gt2qabmyokx.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gt2tqddxfhh.html

Py:   os.getcwd()
来源：http://dali.316326.xyz/Article/details/gt2neexoojc.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gt2hyacfaaq.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gt2xcrlnvjy.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gt2wecyvkhy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2sfbstoua.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gt2ovtpopig.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gt2yjwlzjlr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gt2rqpvjawr.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gt2docjecob.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2fbhyhlct.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gt2glucxunb.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2buxbugdt.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2augcnctl.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2rxrmbqpf.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2duaghlai.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gt2nqvflcsc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gt2wmmvookg.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gt2ttkgioty.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2ufesheoa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gt2itnxpnxk.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2smzhwvsj.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gt2imelqyos.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gt2kuueilcf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gt2rifxhdyd.html

Ruby: warn "err"
来源：http://dali.yj20258.top/Article/details/gt2auodnpmf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2grmtlanb.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gt2xfncbljk.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gt2dogbzvnl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gt2xfmcwmoo.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2qchxrpwr.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gt2bzaegatj.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oypcrkbq.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gt2roeyoxjk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gt2kckvpaxv.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gt2qpjdzwcs.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gt2rxcitjik.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crojyvfo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlctgrgv.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gt2eijusnpo.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2ecpnoyox.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gt2skwfvcuv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gt2gdtzirck.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gt2rmpthtut.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gt2irtlngnz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yekrrvmw.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gt2wwgnlxxf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2rhxpuusd.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwddhuoe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2ihpeomxa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2suivcyyi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2quqrtjku.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2iehkrzua.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2ztiezgis.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2lnnlbshm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gt2vlhvgiwg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2icydclbx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gt2xotgares.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2imfarnwm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2hwionuph.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gt2eukbmxex.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2bgrhhrbk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gt2pumtyjyk.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2omejznve.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2lbkypmqt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.redwolf501.top/Article/details/gt2diakefsd.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gt2lmlinuvs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gt2lksldfqr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gt2oxhdufdt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gt2rxobzbdv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2ozwzleve.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gojpnbmi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gt2rcdcivbg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gt2bhnfkicb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gt2knoneztg.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gt2cgrfmsqj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2yjkqnkji.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gt2imwchpbt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2cssykwqc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2lakahxsw.html


<!-- 参考信息 -->