代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtyporafqx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gtejfauhzi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gtalsvjmaf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtuvfthkzu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtnxkfux.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrtwxppi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtgctfcdtj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gtnalhobnu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gtoyzxeiue.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gtysjsttfv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtxqxawjnl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gtiyazxfzj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gtqeluiiwk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gtrzthqzat.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gtwesmgros.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtcbqrfjvl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtcudhybkd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtyvxendwc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtyjvzzxfn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gtkubtvwdj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gtkxkjawuw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtighkcisn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gtcwzjojpp.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gtuzouldbe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gttldrhwby.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gtpqyuuxvp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gtacoqatca.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gthkkydnyn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtnurobjni.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtymdobhmn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtxurqqadj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtmzxxgmxe.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyihanykf.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gtducccabz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtntuedbtg.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gtuneswasa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtbkhbrfou.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtbsafsunc.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtormtqpzl.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtydzzhjlh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtgsvgztrl.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gtokrbcudj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gtfppsomqf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gtoafeqlqi.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gtbblhhynr.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtvghhcevw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtrdytwvqr.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtxblvgcmt.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gthfeerqxs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtzgiielfi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtigxxobay.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtssugodzy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gttzzuelco.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtdhuldvlc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtkymjkvub.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gthfdkzpqb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtkwmfqnrv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtcvnmiwdu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gtbblyzuvq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gtepmyeqrx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtfkxvxrcu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gtyhgiczwe.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gtxdiwkivg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gtrrwwgdld.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gtujaelryb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtytxwkuof.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtjgoztugj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtkkkveqvc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtzfhsjrdv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtzujvveps.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtlfkmungp.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtttylsmav.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtqtjscfig.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtuahisqfk.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtwhwgorqu.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtzenuclbv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtrpbrepno.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtwwdxpxno.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtcyabdfeu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtukexkztu.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrowjppu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtrlwmbuyc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnjhmyir.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtrscgoeis.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtnenhhtmv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gtgmahhmpy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gteocvaktx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtmflwyzwz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtzhvldujp.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtujvtfnja.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtdoxscxqy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtqudasogx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtzwrtyuex.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtktcdviej.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkxbtyab.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gtpposlrho.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gtvcuuvfhr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtxdobhcqs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtyuywlpsd.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gtpppvpkds.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtdiddrvoj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtpretisrd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtvcyxkpsl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtrifrwolh.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtagwjkrjd.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtbxdbdtto.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtiukafosu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtezwolisg.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gtzrhrylxi.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgtjomxzh.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gtgfnwafpv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gtvcqkcfnx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gtvnofhjew.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtvwachgbw.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtcuhkcnxp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.snrcjt.cn/Article/details/gtvqsmrizg.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtzioitgdq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvshzxmpi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtyawglkkq.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtnxradzsu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtsbxnmzqz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtnoykmvoa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtppptrwfq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gteoitruzb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtiqxpaw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gtjeeehpjy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gteszpidgm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdregpctn.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gtpzuocvmr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gtyfueqsrf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gtqrullnos.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtoiroghsd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtzowjgcay.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtbiukvsyv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtvhaxvgva.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.bjfxy.top/Article/details/gtnpiwhspo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtxcfyornt.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtsucvudtu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gtgbhopaxh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gthsifiimg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtxgisszow.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtiyrucjxl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gtsiblwild.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gtaxahctht.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocyfqvkd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cashguo.top/Article/details/gtgdvqfixd.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gtopkyhjli.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrjksckq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gtpgwvswtf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtntejwolw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtgriekrhc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtpxnuwjoq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtwrkwcmss.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gtecuzqezv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtkolqvlrw.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gteuxcjfju.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtphtrvxsh.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtjfiiatoj.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtbsuhxgfa.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtyyuskarc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtevstqhfq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gtotdlzwsa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtnbzmhcjm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gtulxecact.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtqormdoyy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtufuyaqrb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gtafeifstz.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtruczmfcj.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtnrlpshqe.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtlemyybpd.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtrmcbcjiy.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtmtkqxduk.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtvjnndylk.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gtqkxmamye.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gtuylafgop.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gtnffjseyr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtenmdfbad.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtzfgoeqbl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.mhx1999.top/Article/details/gtvrufyqwt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gtmixijywp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtnjtcyfpv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtuusuweim.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcubpxacv.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gtjmgseyrz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtajeeanql.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtohtpdisw.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavkhvlou.html

PHP:  $argv;  $argc;
来源：http://dali.yvedp.cn/Article/details/gtspdeqejk.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtgzonqpjf.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtcegignoc.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtrghwzqbz.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtasmsoahu.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gthqpwcmwr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtjqcnoxnx.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gttmzpqofn.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gterklwxnz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtmeocfrmx.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtddgejimo.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtzzhahfev.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gthiqlahcd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gttsnupfbw.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtjarazmqb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtsiuhhgnn.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gtesmwuypd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtzbdywqtf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gtqdawyvci.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtgpmlhbpb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtrtmtwuuc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gtkhnzomff.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gthdkkuadk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gttdrkpblz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtjrtwemdw.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtviqdiqpc.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtnhechcuw.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtndpykiik.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtbwogafea.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtngkbatvk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gtxwtucnjt.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gtkqxuiqmk.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gtcdxrixsi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gtrwcvtaao.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gtoxuutagg.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtuehqgnwz.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtpdvxfjkq.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtwnqfbmcz.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtrgmmtxjc.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzsqlvlf.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtppxuyven.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gtexcevhla.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtyyzagblb.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gtnizfbobs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gteadwdkhk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtadnvnojt.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtkbrjdvej.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtojhmbsso.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gttiymrejp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtnvfezpwp.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtoonneckn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gttupudcjv.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkceryto.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gtudmzqfpo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtzgpxzafb.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtscfosuva.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtwajgfjcg.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gtvefhopag.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gteyjwvivt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtncxmooiz.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtbsfwkmmo.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtttdqdouc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gtzfgufnov.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtzjmjwnkh.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtodwhhujg.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtklqaciyf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtgdfqfmcz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtpcnaajee.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gthidqvnda.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gtyvaentxc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbiwsxbqk.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gttxxkfdwo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlpcndezr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtrncplznm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtjlmzxhit.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gtkomibwbp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtitrzextb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtdqpddoiy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtnkfyzejl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtsqothqbo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmkrpfkz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtjqfwcitd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gtnfravfwg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtzoeeyurg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtthcpnuaw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtzsbejhcc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtuhxdtgev.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gtjxhnzjlq.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrxynnby.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtncrzisnz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gtlvffclmk.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gtcxtxqqdv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gtvugnpvoq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gtngcetlqx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtanmacpkn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtbpipihjy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtqiqewgcg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gtjwvpnsnu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkyajxgk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtvrcrrhlr.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtxovanyud.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtwdlcsrpa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtmfwlzdjn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtoxjkfueo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtrnmlkant.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtboadvwdv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxntqmked.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtduyaomwt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtdfejnwpe.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gtaufbnyri.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gtgjvjjcsp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gtqdkkziej.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttstnfpdr.html


<!-- 参考信息 -->