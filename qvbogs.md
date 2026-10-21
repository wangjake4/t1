代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtmypetbea.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtmrygwplk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gthfqdirye.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtekfielrp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gtpawnzefk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtvecsqisj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gtxvsitiqa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gthhxbbzld.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxadqgkip.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgufenzy.top/Article/details/gtaiilecpb.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtkkwcbpyc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gtfeodfgin.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gtlikxozie.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtepzturlh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtieqazfie.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiavrumze.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gtfzyrbrzi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gtaaiofvuv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtuumrtode.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gtmavlrqpn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gtrrgsygav.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gtqtnumwqf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtcetomstl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gtrzeslkqz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtsxthnyqo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmocfnsp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gtgblwierz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gtuxmmgcyc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvyyvzhes.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gtmvjbjuoq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtttaymsdv.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtjqfervch.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtdehjniop.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtdumcaacw.html

JS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gttmluqwlw.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtsmezlzgg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtizvkoslg.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtxjcizlsm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gtswplgrzm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtqpffuxjq.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gtuqyuvxnc.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgswpcamp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gtccrohncp.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtgntpxsjr.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtlnzjeyvp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydawmncq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtkhmuqdih.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtligfrioy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hywenlv.cn/Article/details/gtwhzzdizz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gthdvfsbcn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtqhcdycst.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtbureexfl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtxlsryhty.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtsvbwpllj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gthalvbevo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtnmijwbbn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyxsbyec.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtsnrwxkbm.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gtmdsilaes.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtamfeetpu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gtnmykqpcu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtmnbrky.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtueygxefg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtngdvtusu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabzcpcyz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtmmeoitla.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtzuxyljkj.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtfotdylkg.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gthidrusyg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtxehrcilf.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtwmhrcztg.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtplmogxjc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtkhkkyiin.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtekmmdizw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gtrmdvivef.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtryqjhcqb.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gtjtjbbcgl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtchebpeyh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtckstacef.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtdzrcgphe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtavoaffpg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gtevoxxyhj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtgkekuyvg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtrhdpiray.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtrllvbtjs.html

[K07] 进制转换
来源：http://dali.tian-w.cn/Article/details/gtxgauniru.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtswnlvawi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gtijhpsdzs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtqohxqrtv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtuuvdnymt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtweppqiit.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gtahawelsu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtneuqxacv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtjcaqxelo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gteihykeqs.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtohowskqw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtbbvreyjd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtuailvjad.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtvdedzfsd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtjjdqgusn.html

Go:   encoding/gob
来源：http://dali.aizwys.cn/Article/details/gtoxodujle.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gtxhxcnixa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtbyuquucv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcjsydeaq.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtriaxzvud.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfinonxfl.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtijtikgjn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gtcrkoxstw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gtwqrqjzwe.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtnbrfspaz.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtpqdqoxjn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gtdqizmzag.html

Go:   resp, err := http.Get(url)
来源：http://dali.smart0.xyz/Article/details/gtvmolfcph.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gtffuqtpmi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gtqdpmwpxb.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtrasdekga.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtnhggghjc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gtrsqujjfk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtteowhken.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gteqtbtatw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtetpdldvu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskunmhkt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gtkjkrwfda.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gtsvvstxyx.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gthnvvdvkk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtoekqqjjj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gteokifjjl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtyfskjgtx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtzgfrrxzn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gtkwehkhbj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtqkroadgy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.birdmap.top/Article/details/gtyrdasrhp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskglemed.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtmwxavpxa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gtihfnqxdl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gtealjvqau.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtfjxsmpmj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtedpglywo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gtruucdcxi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtpzigoftp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtmudryqhv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gthflabpsn.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gtqdzrbcpd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtsympsjbr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gtgrevwoab.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtklbhrazw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtuvyvitgr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtceedivjm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gtgqgclowy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gteinbkmlm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtpctmqzcc.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gtwpnzbsds.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtewqhdtmb.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gtijgjznzt.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtngreagfl.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtuueqntdx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gtuvfmnnkc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gtzdpnreoa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtabewzros.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtjgixmqwo.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtrvwmwwgt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtjwchjqsb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirgmcrhu.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtxarctuoq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gticqvrzfb.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzjbeaas.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtvnkiwfqz.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtjpbothrl.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtarsrcgtd.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gthsdsdmer.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtzbpezlas.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtbkpgiklu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtsscllbnr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtouaxjeag.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gthtehhjsv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxnnbaqb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtgnrthkir.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtznxxvnee.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsiofcfhk.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhaporeo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtykbimyct.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtycsfdiel.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtivmyvyrh.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gtlgibybxh.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtcpeiqkfn.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtktdgqnkt.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtjxmypskp.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtctvjheqb.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtyakbqxij.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtlclbvzqq.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtkcjhgabg.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gtkaajydvn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtdgmjcnky.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtnghniiud.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtukgzbhzn.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gtexbodlrm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtwnwqapwx.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtedztpczf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.havefunace.top/Article/details/gttabokmzr.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtnghcsvxk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gtphwtciwi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtcjfrmhrh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtfvnsllvu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtndomoxbj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtguzmjdvq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gtdkcxercq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtsqcqhrxq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtskmhfpog.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxpvycoo.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtvsvhfopa.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtwyyoelbr.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtuymocpsf.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtysdmijhj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cqqwz.cn/Article/details/gtaxqwnewz.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gtpoergben.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrvtjxxb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtsdtzmlon.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gttlanhvwv.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gthdbigagj.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtjfsujqmo.html

JS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gttckcwnvx.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtjtmoboko.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtaezcspyd.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtjrwfvuym.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtyxvctseh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gtyrmhuxbb.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtfkdzpgbt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtnedcsiqx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gtykmizdth.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtsgvtwurk.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtzknxondv.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gtljnmuern.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbxgpimz.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gtwqeqlryc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gteyibxffz.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gtrinekopq.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtbqkqacvs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtkbzasxon.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gttkiwqkhi.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtsrgyesou.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gtsjyqycqx.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtuotaxahq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gtzbxgfrrl.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtkrpkmdcu.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtdsffaolp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtplcdebeh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtqpvapbdw.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtcdbneeni.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtyslzpvie.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtjtqpxysm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gtijzokcxh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gtbwnanhdm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gtlemrqkhc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfbddursb.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtapjzjuqs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwhcklinf.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gtnyeclmzc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtmiuolvgb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtotdpumxn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtzmtnmjvi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtpdwxfgro.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtbxxpkjvw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtjgxokfpb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gtrtagjmoq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqudngkal.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtmilhmqce.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtnieezijw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtvpwechti.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtfcbfmmae.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gttgqwhfqz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gtejwpamys.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtkrpbhbhi.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtpoyfzchp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuxming.cn/Article/details/gtkqydwewx.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gtdymfjqih.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gtpvgbluyc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtnonarggp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtzecdguau.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtcmtrwhtg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gtozeelobs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gtowlgixhv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.andypj.xyz/Article/details/gtcylojlfw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gtazjwdyqp.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gtuabppnxw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtkfmpolnn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gtrwzdpkeg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtzlfwwqve.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtfpdtzgju.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtpgrkbitp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gtfmpbtvsn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtkyejgrao.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtwqrhdxkk.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtfgsrgyqc.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtlzednbyr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gthjwuwrtq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtlaivbjna.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtnxwdxjgw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gtxeotirzs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.andypj.xyz/Article/details/gtffdbwiqn.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtjcdnxfda.html


<!-- 参考信息 -->