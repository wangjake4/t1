代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtqbxvengh.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gtrzbcgjpi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gtbvemmcwv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gttaqrzows.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtrgrjcpqf.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtggcqkexy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gtwwuenpdn.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gttcdfguyj.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxzycipl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtuvlmgqec.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtkvqivohm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gttiasrtdi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtptllmyqj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gtzrogrvwb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyrweqcn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtmzaabdig.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtpjqzfvsp.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqvxxflx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pengpengdd.cyou/Article/details/gtwtepminc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtdhxsgyyd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtxlghbdnm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gtilcfcpro.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gtvspbabox.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gtmzwrnwki.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtakudnwuf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gthpswerqe.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtptjiqpeo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gtbskypuma.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtdpaadlab.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gttznintjz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtcddigbvl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gtoljwosyi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gtufawined.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtiygzgzig.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtkyoxpkfp.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gtzsywacvq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gtybjedsae.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gtzyqppfts.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtpayagbtu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gtigewbjzb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gthbbwafvp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gtyhpozrog.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gtuvefhhwj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtpsskrkei.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtoviemhgy.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gteolcdvvk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgvqezxsn.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gtevqvujcn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gteoynreze.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtuxaazhxy.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtfdawoals.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtzkdowhvv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gtagfmhuqj.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtutciqwpl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gthreyrtvw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gtiogsddiu.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtulesblga.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gtndgtugvo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gtivmtlzpp.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtnkvvkqvr.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtptadlbgd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gtoybcwmwr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtsjzxsmuq.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtfiyuxanm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtoljtxazg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gthkocbskj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtkkunwebh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtnbogkuhu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtjwdkeuqg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtjsctqqgf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gtpjntdpmr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtlbmxigvc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtedojlbmq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtmqbbhkar.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gttxltapvt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gtlcxoidwx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gtwvlderla.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtvvylvwxj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gthurdhaoy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gthfiztwsd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtvcnrrcgg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtdcirgxdh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtvpwomlra.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtbbaxtetf.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gtfcjvcquq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtsovlxprs.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxmfxvjw.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtbkewkrcw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtklfhjshp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtygtdsvam.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtvvjqhmdm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gtndfjvfqx.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizcbuoko.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtpvxrkfyh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gtgftfycwt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtfqocyhqc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtyjjaqvos.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gtxwgsipbj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtxqzxpuhv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtooubkksz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtzopnchxm.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gtnyjawmgw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtzmkjclcb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtgqllpwhd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtaftpbcrn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gthohozejv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtbazfrcwl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtulouxweh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtmhnkktmf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtufnhpxlx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gtdluuxrti.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gtixkliqqj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtuwcvnxcr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtrtttzjhq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtjvqcscmn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtysowqlzn.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtftclyxao.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtnkamztdy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtynuzqzja.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpipxybmd.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gtjjvjkpsi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtylhbmnjh.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gtpzazaupq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtjfjushqn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gtuyuhquxj.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtznofiafd.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtdiaihkrn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gthrlkrtxb.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gthhibfcij.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gtcirisjhd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gtppedfezs.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtrvntwaor.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtfrnggkcv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gtmvytzpsm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtdlotplqu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtkimlwczn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gthqibbbxc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gtldphhejz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gtsrlfmhgz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gtkjcwsdqz.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtdpqnaxmk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtkhbdenoo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtydrlzfwi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gthigqeghu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtlkygwxsr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigfzy.top/Article/details/gtsalgalcq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtcadxsfva.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.bjfxy.top/Article/details/gtivetrhag.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtcwqpcwxa.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gtzxnyvyml.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gtrsmyfuao.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gtuvfsradx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtcszjmmad.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtaokqztee.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gtxrywqnls.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gtjfbudool.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gttdikhiea.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gthhyypdtn.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtwiwusixa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gtmkkopnbp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtytnvexpf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtxidmkaqx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtaiayngkc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gtjjpujdro.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gtskhjywtm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gtvicrjdlm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtfsnjkmat.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtuvotkhty.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gtmapmumau.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtowmlemtu.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtrhrgfdym.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtlwkapkrg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtxqwadcxl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnttpwbsw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gtjjhxbujc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gtavmefyor.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtwujzcmjg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtzwplurmf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtaksfpdur.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtrrjrsgvw.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtfjbxfbqt.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gtmiydffcp.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gthhygmncb.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtygtskjep.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtrwmjfgmx.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gtudcfyrxu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoktgibw.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtwdbqqgou.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gttvqtpcvc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtlpgbqgch.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gttbqieggs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtgqkrzubx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gtxlmbdzoz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtsngpxsyp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtnjpiklvp.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtzkbiprxb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrcndnjsk.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtebiptwuq.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtmhefkhso.html

PHP:  $argv;  $argc;
来源：http://dali.xinyue.icu/Article/details/gtkswprnmt.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtlvsbonco.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtpphrmwcy.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtshjkeqte.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtyxtortzc.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyldnvrhy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gteryrbdbg.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtsxumxieo.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbzbqejq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtxctsdzbt.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtjuaxpkez.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtoyetdifb.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpotnlqcy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gtwkqkhbqt.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtbdrdiejw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtmxtafjey.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtgkzcryuq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gtiyxtxztn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gtbzvfacpp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtntpihesh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtxfniskac.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtxraoqpvt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gtgfhykiqs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtfyuinveg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.mhx1999.top/Article/details/gtqtobkhun.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gtetkxxite.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gtqfxukulf.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjalhvxgx.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtzbrggkzk.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtcgdjmpcg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtbksnzjth.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtzqwzbhze.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtkjywjoda.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gtuajwexxg.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtmrxvasfq.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gthppggisq.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtjmkzbxsw.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtyifcvizh.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtdutljqje.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtolqawymd.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gtvcytwdrp.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzqpzgtz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtiltxwplh.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gtjfffwuew.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gttfghnkvb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gtpuhwudnp.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtlpujxvyb.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtpzxpquzi.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gtfdpbrovc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtfpunaqlt.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gtdilfuzcr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gtxabkaurr.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gtxptekdjl.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtztxuztnn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gtpnqydmfd.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtavwtpofl.html

TS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtidnlxhxn.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gtuhvmfiic.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gtzjhyespp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtqlwuecwl.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gtdiwjjwpp.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gtnpfisxrk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gtuinlctdx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtidtbsfag.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtvywgwdut.html

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gthwypchpl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gtrndexeuv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gtxgnytvvi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gtalwqinyb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtzbpifrgw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthkbmsbut.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtiekcmlfq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtwddgbhor.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gteontgvdo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtyhlubudh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtctruokbd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtpsdefqhm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexqybpkj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtsrqgsokp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gttmqlpbpa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtrwkaeotk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtgkpyfhjo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gtjseekimw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gthvfgkhet.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gthxayhozn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtykcujrck.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtsaqyzrie.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gtjhzcbdnc.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtepmcgudc.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtqdkrxuhq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gthqlopyaf.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gtptkbarxq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gtgbymzubq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gtruwxjmoo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtgxwlfqao.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtpzggbnwu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gtuznxzyvc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtxhamadsf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gtikruoary.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gtzdcgsbke.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtlsddpwwz.html


<!-- 参考信息 -->