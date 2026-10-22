代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpthpscf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2dsxntmlp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2xdctssvr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2vklzhprh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2voxdsesm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gt2kytvoflb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2snnbwztx.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gt2sigzalxv.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gt2yczeszpy.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gt2qdgfvlem.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gt2xadfqfbp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gt2gugaqqax.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gt2gohvukbc.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gt2unmljtbk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2qazvukjn.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gt2wbbrzxnl.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gt2jhmqbfld.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2cxwssweo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gt2jfqnqiyd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2vaibvkqm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gt2sayneqwd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2tnmzqokk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tian-w.cn/Article/details/gt2vpwpbkql.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2qfmmfznw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2srmelrou.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gt2hsmfldlx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2wiuvrfjp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gt2gmnawwjm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gt2yxvzfmue.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gt2aomlvwok.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gt2vbgfnznz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gt2gyxfzhle.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gt2quclkqpq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gt2ytzxdslk.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gt2mnfnryvb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gt2vbsnpuzv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gt2sbczsqav.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2jxhyhdir.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gt2uefbdrym.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2qqqgjllx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gt2icbveehx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gt2togkyhlw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gt2bdvnambn.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gt2qvbpctwr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gt2izxodqvm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gt2ioojcaze.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gt2kaaqwllm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gt2bxxcnjnp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gt2mjjjncrx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gt2ukpmcurr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gt2mkerbdap.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnhpbsbf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2fvqfozxn.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gt2foaibvir.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2wbhuxhef.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gt2jvufvqtw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gt2rejonfdh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2rbyujqix.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ueopeiqj.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2epyeunss.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gt2rzqekphx.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gt2uumuckbr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gt2yghhhwyj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gt2xixrvjuh.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gt2vbchkygo.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gt2msvhynye.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gt2ehhlbjel.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2bdjsljmb.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2sxhvwrlg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbixsgw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gt2qyjxtdou.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2cyrppiqd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2muzezajx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gt2moevftep.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2pgfkprwh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gt2dzypviby.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2qsqhbytn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjxtkrll.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2nibbcpqh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjedfpix.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gt2pbmzgari.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2uzznzgmo.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gt2erlnkwml.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2uuxgyaxe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gt2prjnikjn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2reziortr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2pyzdsgga.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2lhkvfymf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2wbfnpvwz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gt2ylmjwtut.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2ukdmcdji.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2qeqzfcrg.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gt2tfsbclwn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2xbdvaewt.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2zsfozkeb.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ykgowswa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gt2lceqxgaf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gt2saikciot.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gt2hsewnnpj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jiowbvfs.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gt2gzihluxg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gt2kchkdxvl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdcxefny.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2fbmqdrsa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gt2oqrpmuhr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2lgxduqen.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2ejmkfbxp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2dgygpwmk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2syolhssu.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gt2vswixsrv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2zepzewss.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gt2vpsjwtnb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2obsxbsfj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2atpptlwi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2otdirjup.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gt2qvhkhgxn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gt2gfqwmjug.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2cgfkfaee.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gt2wgbqjaqk.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gt2pjsxitkh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gt2dgxygrui.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2olpxjkkm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gt2vnmbbdoa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gt2yodttvzh.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gt2evauwcpc.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gt2wihfaghp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhnrvazf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2jbobohwj.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gt2ezsfyekb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2foopilzk.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbcjddnu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gt2zcnrwuxd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gt2nrtrjhhl.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2pyxynpqs.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2zgbwfmdx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gt2fkehsjfi.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gt2ehxdekrs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gt2lfqyzuoz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gt2wylqwwxs.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gt2cnwfzmah.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gt2iexbjjyw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gt2mtgyxfvp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gt2xbtfweye.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2nmcmwzdz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gt2xfyklvdu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gt2dydkaztr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vamsuuqv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gt2fguakhsw.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gt2nzrioalk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gt2fsyrimeo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2fswnffyf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2eaninirz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2oloukdkm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrjlsldr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gt2aiqnlrjs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gt2ldhjmgtr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2wbnzlrfu.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gt2ydrodysq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gt2ylvcxtby.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gt2zsibnrxx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2ynliidpw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2dfabwdby.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gt2ypvtyzlo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gt2incjpsmw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blmyulvf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gt2ieekfiye.html

[L05] 上传文件（multipart）
来源：http://dali.yonumen.top/Article/details/gt2egfkhddh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gt2daldcoge.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gt2nbuifhec.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gt2tpmexjms.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmqcsgfj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gt2tdgykcmc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gt2ruwwlrsv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gt2pfqrnmzz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2tvsvcsue.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gt2ajqkpowc.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2juvczvfh.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gt2hisbjtzs.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2hulaoxrx.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2bjovdqqh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2gkantjrb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gt2leuwuvxe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdiythzd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2ugmlxboc.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gt2ezvuiyil.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gt2zbfstavv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2udebcigs.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gt2jqncmrvu.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2cpthwgmp.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2ejldqust.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2tdmubxjr.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gt2rkmdrfgr.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2yrzykkwm.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gt2kjwotzph.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.haohaochexian.top/Article/details/gt2exvdwbnd.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gt2gbqcisew.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2cxgxwyth.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2ahnmmxeg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gt2wbamytfx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jixfyhnq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gt2tcmvvzfa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gt2lpigrkmd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2klbazwbz.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2osocswpc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2fwhancgi.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2svpwxnzi.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2dlaervtt.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gt2ekxrpftd.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2uyrmzfit.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gt2djxfircq.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2hkyplgnd.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2wmsweonr.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzvklwun.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gt2lmpxwddh.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gt2ewsqookc.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2jyxpvrzo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2vfcyaedl.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2alztdcsj.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aornpaqe.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kipyonef.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2ryzbervm.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gt2wleqpcso.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2cbojxons.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gt2lxrynsyn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2hrsfmzli.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctqwzzlp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfhvzfsa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2arwuuztd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gt2dkfulrau.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2quywnrvx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gt2kexibbaq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gt2cakhxvlw.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gt2fkszhitc.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gt2gbbmxulc.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gt2knmbslhp.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2sxqrlvam.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2uotoqmrp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gt2vjugoggm.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gt2hpuhkvvp.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gt2isphyurf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gt2bdatetgi.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gt2jvzcgytz.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gt2wunlwycl.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gt2ledrypho.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2hslryruk.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2frufujim.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2rjctamow.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gt2iclussrv.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gt2yfgxlqoo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gt2ybqaiexo.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gt2lzacsago.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2gorbmufw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gt2mzsamdwf.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2ivvpgesp.html

TS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2oaypejvc.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gt2gxsdsoga.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gt2pkcmvhus.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gt2gxnqacee.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gt2bwenftvy.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gt2wxskeagf.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gt2xrtywvau.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgibdoth.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2kgrdnlyq.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gt2ddbaissa.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2jiqppkck.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gt2svasqrtn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gt2rozkmsei.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2rvmhspdc.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gt2oluimujn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gt2kmdvfqxi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2lpvaccdn.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gt2guqkuzcz.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gt2stpvdbpc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gt2pcvalzif.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gt2ftshcdru.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2ghqpadqu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2wmyhlpbu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2kvrchoho.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gt2kesjenlr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2etmtvoar.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gt2gkpakhbq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2ngquqofe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2goqpbqeu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2jvhxqwyw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2uzjvqrgr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2gidcsoya.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2huslxkog.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gt2elflxrrd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymmnsmtv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gt2uerqknoh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhbnkuax.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gt2vwuftors.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2awqbuwaa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mygvpkvr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gt2lljsvpps.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gt2pqylpwqn.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2mysxyjoc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gt2yeoehjbt.html

[N03] 快速排序（分治示例）
来源：http://dali.chenlongwang.top/Article/details/gt2ycsupmfp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gt2vcfjalto.html


<!-- 参考信息 -->