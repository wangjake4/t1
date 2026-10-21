代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtzebyckpq.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtkulttcqg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gthhlpfgcr.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtcmghahvv.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtohdnbttq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtlxdlfyzr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtbocesejw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gttperuxia.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtllntznoz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gthaadgujt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gzhubu.top/Article/details/gtifxbndnn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtpwvkqhfh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtwkmncqfn.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtlqfktgnd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtyvzmdxxn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtgbilcxsg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gtogxpikxd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gtyavvauts.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtfmnzdtcx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gtyxgwcjsr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkwcfcyw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gtnridjuko.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtusyjisym.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gtutgruvab.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtrdqpejzf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjlndwoa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtbcmuvxtu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtstfwtsky.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gtlmcphqvt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtiunxhxpz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gtqxwlbfbi.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gteeokvpvg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtzkbvzywi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtsmjdrtte.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtouoptdxf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtyjmitjer.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtiffnduiw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gtnjgggdui.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtyhhnicqf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gtrgpgpjfa.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtioyadvee.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gtielylbob.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmypzsklz.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtzlsybvpi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtlwunjuga.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtqkhfrzux.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtxztemloa.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtpzgkkjfm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnucqicqg.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtcrwtmoch.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gtjctcjusq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gtbcjbcrrx.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gtidhgepht.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gtofmmhfzu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtuwedldir.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gthvedwaur.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtkwsbbphm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gtlvoeajfq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtxecxafws.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtnwhluvry.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfzdajbt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gtndpthzlp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtoytjpyms.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtqcmzfvvs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtalmcxcmc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtlxqtahwx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtitptsvjz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtpvwyuamo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtowagjzbj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gtkhjmszhj.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gtuyvxnqjd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydiahtbh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtayrmpkor.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtlpfybkuw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtdffdgyzp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtvafivkow.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gthzesgodp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtgyrrerel.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtuecyfzao.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gtbiatilyt.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gtmtxxsrna.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtnsjabkcz.html

JS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtqyshfeua.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtsyecdhba.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gtlowpidvd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gtqtgqocvq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gtnbaajlcg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtjxclpcbt.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtpjomrery.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtlbxwnidq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtkxqpcprf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtfxmimvmz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtoqwogeci.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gtnkecaojy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtgcifonob.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtwggixkmw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtdjkhwsyt.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtftynyaly.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtwnaqavju.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gttgklmnjf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtecyaeggp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtzqjfluyg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtyedipxaj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gtlczqyozd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtfmhkmzlw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtlfygcbty.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtlsvicuvx.html

Py:   pickle.dumps(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbuixgys.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gtmqogofnu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtdornwiai.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtsxfpurjo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gtnsprgivt.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapkikqra.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gtxvytewys.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtwzliancy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhndblro.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gtcyhtmaai.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzbvbgkbz.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gtwfipuqum.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gtsgbvkqoy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtagdjwirt.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtgreclrol.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gthqpamhra.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gtsvmzaesz.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtmmwmyrff.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gthqjzngsp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gtdgxyckto.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtncukpglr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtjirqvwwp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gthffclqrx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtpszwpqnq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtnivtioec.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gtrhxausxc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yongpay.top/Article/details/gtmcmfpnwa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkiejfnj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gttcnotlzf.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gtdltdfhfi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtuhhtmadi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gtqmofvlno.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtljflmxds.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtlvlqeaki.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtpirnxaxz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtjuluesvh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtefprvrsb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtozzxipoi.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gtvdsxticb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gtkmnkivtx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtidnayobf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtjbpbeeuv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtpbxkfvwa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gthjqytikk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gtewmhwylx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorzqiigr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjkpmzie.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gthqjdudjy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrmbpypy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gtyqjmccae.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtatiaklym.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gthgognwqw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gteaizxluq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gtvjlimqld.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gtjdvxddsx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtgiuhwcvm.html

[L06] 解析响应为 JSON
来源：http://dali.chenlongwang.top/Article/details/gtvthtpzam.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtzexxeuho.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtjxmfyskh.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtancewykl.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtghfrkady.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtmxdltrmw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtmdqvupju.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtessjitqg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtjhwondaz.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtoycmnupc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtenuitnqh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gtkvzbfcoq.html

JS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtkysyjrjc.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtwfbznsro.html

Java: resp.statusCode()
来源：http://dali.hammf.cn/Article/details/gtoviunuzm.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtlndfjnkp.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtdyddmjqe.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtxckncaav.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtzgkqubsx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtiuqvxufo.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gtfpjkfsdp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtedzwxodc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtehrlpwoj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gthrouaywi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtjtprhqyo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtrsrxeizu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gtjhntqjnj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtemnkqedd.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gtldokccge.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxwppmkzy.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtbykjidid.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtqkaymdfe.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtutxrcrus.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvwfxijk.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtzcbxhumc.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtxqypjlqy.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtsdbfghha.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gtkrphbekg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtbitjxwlz.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtetgcatbs.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtdmmbseox.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtxfkajnxp.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtxmtvgwuv.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtrgkbnrwg.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpeeynut.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtnhesgluy.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gtdtpxdvcl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtxrhtunub.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtmlowfzqw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtduyutfgs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gtkoxwckxk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtkljneakz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstxvwdwx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtnqfsgwhm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gtzajtscjw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtslrqthxi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtalbmwivj.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gtooqjikza.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtgnkargtb.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gttakozwsn.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtvppnzhno.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtozhdvrnj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtniuoqolz.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtnwjjjjpn.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gtdtdkwnvy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtzijbpqli.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gtfuddvmbc.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtcvmzztpx.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtpffnrdit.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtuzohaymd.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtjviehavx.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtomtvxkfq.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtymgmpkny.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gtsrpymmhd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gtffcsrazj.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gtrbplfyvp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtnwpgywuo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gtymptcamd.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtlchapiyz.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtcagvxxdg.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtnwzyfuak.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gtwyibolfp.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfboeholy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtazqwuepr.html

[M07] 判断是否为主入口
来源：http://dali.yueranfly.top/Article/details/gthbtqqgeh.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gtlghfhnwn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtydxmmbuz.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtjjuwiusy.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtkbfykmsd.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gtountsmyu.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gtlvwckdww.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gtarlohmgj.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gtmquwrdju.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gtrnfxcpvv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtlyjhkgnu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtzlizlxfw.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtgeeaugph.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrmomisv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtvdrbniun.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtrewzquqj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gtmfrdwbxn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtqqgdkcij.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmukkvzbc.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtxgcmxqic.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtogmfqabn.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gtsaenzsww.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtjhkslaao.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtnludhujz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtojymuehz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtfcfovgpb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtujkqrfav.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtnffqndhf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gtvwgckswt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwoiwsqvk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gtocvejgmp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtyweivxzv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtxgcgavro.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtqsrnuzuh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gthfgidyvb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gtpypeszst.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtqpxepbft.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gttrpiihwq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gtqbmbvfax.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtbxtsbtjp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtwfrtegkn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtnlknccsa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtadyfnmow.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtvhzxvzzs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtkhruezcq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gzhubu.top/Article/details/gtxzlxktdn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gtfvgnamqr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gtexxqtvkl.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtnhrscngg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtapqlsvzx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtjiiqvvrh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtdmqzgqcf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gthtxqgiad.html


<!-- 参考信息 -->