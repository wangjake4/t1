代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvdwpnno.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gt2nwpsqdss.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azedldwc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tyiycxyf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gt2vkphuxua.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gt2ggczbxzh.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gt2gizyzcvt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gt2hhuvrdmn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gt2vaokaism.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2ezmmesxg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2xhhrgrqk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gt2nssnnhrf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gt2bsmtjkuu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfnranpl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gt2xcgtcvnz.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gt2krfwavww.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gt2kzbljmpm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gt2dfjrtjol.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gt2jgrtlaxj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2ihqeepmt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gt2wndyxzbe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gt2fanjaqzy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gt2ziihabbr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gt2tkbftcac.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2wmozogiu.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gt2rjwkquxp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2szquszsp.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gt2hhkzredq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2bjgbyfbd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2tqyvqvod.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2lubjdkoa.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivrxszcr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gt2dmjxkqwr.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxckijos.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gt2mitnhgty.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gt2vjzurgow.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytjczdlh.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gt2uduqrfqk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gt2kfoefanh.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2kcrrlyyc.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2syczdjlt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uysxhmsl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2xvdheckp.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2rkodesye.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwyijrbb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gt2yuijayhf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2bzunbrio.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gt2ymglvpmh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gt2oplwjosh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2eeecxhkd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gt2nhjuroyj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdanuqyc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gt2duunutuq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gt2qeevwltn.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gt2mtcnatfr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2pyrmkmjb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gt2onxfxexr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2mswjbkax.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gt2ihcauksf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqjcfazw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2czdnrxvh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2qfnqrqrq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2yiolyrji.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gt2agncdimn.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gt2iqgrikib.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gt2kxhwdphd.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2sszhpazr.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2cwyqhhrk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gt2jzsrpisi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gt2dhtifplu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2yfoswjnn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gt2bsopgocx.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gt2wxsmxzys.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2dzerueyy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gt2wkpzkvjr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2ylovipug.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2qpwqpqdp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gt2mdnkgqhc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2fticocoj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2gsxszcci.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2uweckfjw.html

[K07] 进制转换
来源：http://dali.cqqwz.cn/Article/details/gt2xnyjztjf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2pxtbexoj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gt2pujjsnit.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2dgkyzizh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2sjoaofyx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2grmsqzug.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gt2lwdyirqp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rngqrlyg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2lbpmgyjg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gt2ggsbkgry.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gt2cxzozqgm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gt2zaaelafx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2qlkexirl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gt2zvepbsjh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gt2rxvusdem.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gt2lrumsigt.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gt2qsxhyxjm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2nqhewysw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2xhpjekym.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gt2ihwvuwoq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qicvcwjd.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gt2ogblmcwx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gt2muotxgzo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gt2hjqkylkr.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhfqcznk.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gt2enehyxvs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gt2hwpyfzym.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gt2qpiygufs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gt2dvozwlns.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gt2sidllupn.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gt2whisktmq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2lbpjxjjt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqpiwaft.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2nymhebnh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2fziooytq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gt2aidkbowd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gt2brelgjac.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gt2fimaoius.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gt2ahlkqxvt.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gt2wrnguxtt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gt2sagnjgxb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gt2vegpildc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2sbldhthf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hukdcrqe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gt2wjcnlygs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2yvzpeczi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gt2aojzqffg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2ulnoqetr.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gt2diyyneyi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gt2idugdtzf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gt2dscoklsf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2uwaoudxp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejpxmeoz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gt2usdmoyan.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gt2fssisogs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gt2pbsisyfa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gt2dlhhwuht.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gt2iazgncwm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gt2vonbzncy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gt2cslztzdt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2hhftftgo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2wdmacyda.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gt2pymzvtuv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gt2kekqvdxe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gt2btnuegfo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2hfwvrfxu.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2istigqug.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2ympkphre.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2dmovldfk.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2fimjzvhf.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2vzvoasjo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2rmdjyzqk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gt2rgtxhzzz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gt2pvaovnod.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gt2vwlplmpe.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2qliibgig.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gt2mtxzdnmx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gt2awtpouup.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2ogrwjlni.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gt2nbnjcjrp.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gt2tyutwyjo.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2iyyclpwb.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gt2ccuosmzr.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2bkkfeqcy.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gt2xcrdmocj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gt2tgcjvpyp.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gt2hhlepaee.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2awrsffyz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2tfvqkhtz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gt2hwturjmi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gt2ziaenwqr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gt2hmugisce.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gt2yhzyxzhr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2kovqwwlg.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gt2mlunfgon.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2pwqefttm.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2fcmohmyg.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inwnjipw.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gt2fhwgwuzy.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2fhcubabp.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2fccsqyyu.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2gjgtlhis.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2crlbjcce.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gt2wkovkphi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gt2wkjvqgom.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gt2bntqioxd.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gt2ypdblpck.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gt2mjyxhzqv.html

JS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdeicrlb.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2rfoautxm.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2jixrgsws.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2etazifxp.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gt2exkleyyn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2aqzusyiv.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gt2millvzde.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhixingplan.top/Article/details/gt2occwimga.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlxevels.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gt2jectrazb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2fssotpcc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gt2jrmepbec.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gt2olwkuovy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gt2jratiqsf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gt2nzhcxjyc.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gt2vrmbovef.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2cirfqmqx.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gt2rmpdkvnw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnsfxbs.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gt2etxmlhuc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2vznkruvy.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gt2ceyxvnie.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gt2prtsqnhr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gt2qczpzfhr.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gt2ylnjskrh.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2foohoqwq.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gt2kfuuocuh.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2rswykhde.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwwzmxri.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2qblrgfgd.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2awuodfqy.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gt2zgwowjkd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqblhlis.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gt2hmhlnlxm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2ilaoqhiy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gt2oqudzilf.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gt2lbcpmwzo.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2gjwsdvys.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gt2ibqtmkrx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gt2gfnmazhu.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gt2uxatmqut.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uyhaeqwx.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gt2pezkxfjp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuoeatb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gt2wwbhtokp.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2nogoazrj.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2trmtxnqb.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gt2umishyxe.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gt2ivslbdsb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gt2lgsarwli.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbevioow.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigfzy.top/Article/details/gt2svfdkysw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gt2wmebnpra.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gt2pizrxyva.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gt2ecowupsq.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2sdeqiuet.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpyfzjot.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tian-w.cn/Article/details/gt2cpypypav.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gt2ambzsczu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gt2yvlgpcyu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2kbdkbfzh.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gt2nalkzros.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jgxnippn.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gt2ylcualpv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2qicluylt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2smhwxrtz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2xlzzbvwu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gt2tazffgcr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2blzughof.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2vjknnisv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gt2aryliyff.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2tjsncidi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gt2phairias.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gt2mcrnbqvg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2ublgbdwo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gt2rpadkgrw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vouafrwe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gt2anzmyagq.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2zjbdcpgf.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndvkpmpm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hywenlv.cn/Article/details/gt2btzsslmt.html

[N03] 快速排序（分治示例）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ogywpbec.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gt2avchwbqc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gt2czmbzaea.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2rlsptvia.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gt2bufnbvem.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sixlllhw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gt2lcfffqpc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gt2ixhoxako.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gt2nwlvkmku.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gt2wfwjptmq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gt2demqgvha.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gt2usurscru.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2ydvamgqc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbbropob.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gt2xlokknve.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgqaelys.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2qgjvtcsz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2sdxzopat.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gt2ovxdhelh.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2gveypuha.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gt2wozdcrvz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2eiulsxgc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2dxzxylhl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gt2mfnlvqru.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gt2ipkxzbif.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gt2abzfiscu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2rgclzaeu.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gt2djfcqoqh.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2gealnrif.html

PHP:  $s === strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntujxcvf.html


<!-- 参考信息 -->