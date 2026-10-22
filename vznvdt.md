代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gt2btrozqoc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gt2nxyrpgsy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gt2ziiboipo.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gt2odmhdaxu.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gt2rywkfebk.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gt2ghhsepri.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gt2sswuakqj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gt2jsvobono.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gt2wbrywbso.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gt2znsmypbz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gt2zwgaiwzn.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gt2wzilcogq.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gt2kwxayish.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2fcqyzupa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzzzvxlc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2ephkjzkz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2sblhlfvd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2kpmdisfc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2ndzykvps.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2fyhfxflv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2fjilyzwc.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gt2piqscumz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gt2enkiyvsw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gt2acborzhq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gt2xegybany.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gt2htihfyuq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otcpyoya.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gt2auxukuyj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gt2wadprnny.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gt2gucuihip.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2jrrctxit.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gt2lsoayoqq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gt2svgofbpl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gt2fwkpiaiv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2exssuzcy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gt2epwinxjy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cqqwz.cn/Article/details/gt2eufborsw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdhatgwo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gt2cgyepmfw.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gt2bpqphlqb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gt2hzwrejgl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gt2tiuhspjm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2gmfuomtj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxqwgrli.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gt2ngbwtrqo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gt2zvdkpybi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gt2uazbpnpb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gt2jnqlpbnc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2limkdxtp.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gt2rolvilzm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2amejoiaq.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gt2ojdlwbyf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfpdbmdz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gt2jlnccfgm.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2gftgnita.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gt2oupyuxtb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gt2vcnjapqy.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2pygcenap.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdvqfzle.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gt2nhbaglxw.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2pmjnuxpd.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gt2aoauptyd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gt2genoxgts.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2symthkmr.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2zsmjktjt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gt2jlwdyzmm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2usypgbww.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwpfwobc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gt2xyyqqkux.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2dmlldpcc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mlmwbhdc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gt2makfprno.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2cfdadtji.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2xihmtfjh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2eivggxxm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gt2lojflczk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sehyhhab.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gt2oscmstpz.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gt2opilebwv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2piviluef.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gt2uedyxxdd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2acdrikjv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gt2ovnksnne.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjxnnwmk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2clcrgwnu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2njprfcmn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrfhamk.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gt2mkabqoid.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvsgddwh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gt2xvtryjnv.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2zcmsgwxc.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2hhhujaqy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gt2mnfnmeub.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gt2eksoaalo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gt2cwzvubpp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gt2grqoijel.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gt2pvneslpd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2qutmekuw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjbunoar.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2xnjpaife.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2nczjiorf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gt2tccehoud.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2yezenace.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2anlnhpum.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2dutiarzx.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gt2kwrjfoyb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2avrtlqbg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gt2nfsafhis.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2bcwwcern.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2atiuugkf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2ykbrgkpd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gt2vtpeulzk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gt2wccitcsc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2rzxztdfs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydqufkpk.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2stvaldbl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gt2mzkhknrf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2xmjprvpk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2xmiufqlh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gt2rzbcuapq.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gt2toqfrfnp.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gt2niypwhce.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2mhhvjhwc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2plwwrwvw.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gt2rosdqvfs.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2jqmocpxl.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gt2xdalszmu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gt2mshnqacc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htzpvqjo.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2wtwmwmll.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2pvaoxjwe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gt2gdswavzx.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gt2ykxjxmjx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gt2wbyvfrey.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2arknvjex.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gt2cuyeywqh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2irgqxhfn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gt2axjskhkv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2yjfldmcy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2zyliarhl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gt2cfgvhyyr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gt2xijuugkr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gt2ehyunxid.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gt2ivgzeyiq.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gt2rykrmjgx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gt2lbmqehws.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gt2jzlxbwjc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yypcbouy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gt2aazcfbhy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gt2cvkxjixz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gt2qqnwpuhk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gt2hysqrbxw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2qbagkchm.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbtrnixg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gt2nwrofkfv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2zxnbsbey.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2nufruvci.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2upcodyty.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gt2iyxemsgx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gt2rmaefckv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gt2jofmfogy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gt2jjolnhtl.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gt2dvxiypqu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gt2hnfiwsft.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gt2akvxkzfp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2eiqxbjuu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2vpxycnia.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gt2rujofvod.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gt2acihtsxy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2bguqiwiu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2kktaryir.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2zirfgqkd.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2thlhpstc.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gt2anmdejqm.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2vmtmhgdp.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2lbunrdaj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2qkqjkmja.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gt2egilqqgi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gt2lankkgaq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2reumvisp.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbqgqvrn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gt2gfupzfta.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gt2doktjyey.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2udsctcqz.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2uxdedncn.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gt2dunfgdxn.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2cwgvixhb.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gt2uiriusnn.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2eahpxore.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gt2ordbktpr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gt2tzicvofb.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gt2huazvhpm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2wtdzwddc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2udjrwmlr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gt2tdsvatxl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gt2wxshnhcs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2nvqeicjd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gt2trqklzos.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vunmxwio.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gt2elxmgosr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2uiaoeppn.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gt2iqzoydrw.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2jxzlcvpp.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gt2atakmndn.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2evqwgywx.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gt2rorropsa.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2ozbiouhl.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2bbqyyevl.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gt2jhfpnxdy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2kudgnrrl.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2smkmcsoz.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2icvjuhwr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2msoskzhh.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2hxbkjlkp.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2bgvclkct.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2noyadblz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2mbxcamir.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gt2fmetqtuq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2dgbrzops.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2mirbsaei.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gt2dyenbjuf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gt2vcpfezjp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2zkplbajv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2vrxylleh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gt2fxyrefap.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gt2jxrbjfsq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gt2sirtpbrm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ivvv.top/Article/details/gt2vvtxyani.html

[M04] 获取当前工作目录
来源：http://dali.jinqigfzy.top/Article/details/gt2hddocqfb.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2plsxobpn.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gt2knnmiuap.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tycqwqfh.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gt2zncxbnod.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gt2myvokjij.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gt2nibbbumx.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gt2srytwusx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gt2xtllanzi.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gt2xpvuyhhb.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2teuaownp.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gt2xtbtmuev.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2zkldejla.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2iezdnnca.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2mbyquksz.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2plyxhyrd.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gt2vzthvuso.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gt2sciodqov.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gt2jtrrjsih.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2kesnsqkv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gt2qmrojran.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2pyloiezt.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2qhxorzut.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gt2calbbuga.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gt2prtgrfnt.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gt2pyctawxz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gt2kbnjlueg.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gt2snofqoni.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gt2tqoucksi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gt2cdmobxox.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2tfsmylpg.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijujisbw.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2osrepzcj.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gt2zglgtmxh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gt2nqnsfnbj.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnyozdrr.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gt2pqbeqlix.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gt2ejrvxjbr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gt2xnszxmbx.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2amekjbfp.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2qdbpudxd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwbmpggb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gt2ewnarzns.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gt2tidowoou.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gt2gauizayz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2yrchxnas.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gt2unnyasjp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2icnllujh.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gt2kmvrowzo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2bfskyoro.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2hzwoghab.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2buzxpyan.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2gcyhtkax.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2tknenxtg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2rprnuvuy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gt2sxrkwakn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2kxardqkm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfenpptj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2unxkpreu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2dwetrloc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gt2ouieookh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gt2aivlkhgw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gt2qxeywxvp.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gt2tsbchueo.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gt2byszfwns.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gt2psosuwxx.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gt2pdzzoikw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gt2ruzmzodp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gt2bfrnohsu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2xzeetlrl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2roqtdide.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gt2mchgfoht.html


<!-- 参考信息 -->