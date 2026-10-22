代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2jhpsbukh.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gt2dxlycgrq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gt2psrtlyei.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gt2nmgsaqwa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gt2njarxcuh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gt2bqzghyjr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onjuzgsh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2irhriivf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gt2rjcrirtp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrixiqtw.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2wryvursk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gt2yllcmkyn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gt2rxivcdpy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2jknfyeoi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gt2umaolcmv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gt2bjxadvlz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gt2hunprhgn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gt2kzezdqrz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gt2sczgalzs.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzlnqft.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gt2frhuhhlw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gt2ittyjxeh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gt2dethbrzy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gt2qafuabas.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gt2edyvpowt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxlbjpzm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gt2kcjzigxj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2dyajuofw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2moxrvoyz.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gt2gbhjeulk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2gdbcuvpb.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gt2iynlugbc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gt2zthwrdet.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2qlnitijj.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2ogxhcizr.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2lykqghgn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gt2tklsfmqu.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2phbpahjc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gt2sudoyljq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2isjwqemu.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gt2xmohutpw.html

Py:   json.loads(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2liqryfne.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gt2vwznozvx.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2rlkngpfd.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qazrralj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2czgrjmha.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2fkqrpsbs.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2agbrwyet.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gt2sifqphmg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pprydslq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2ejqlyneb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2fmaabnra.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gt2cugdortu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2dwodrgmh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2znquthyt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gt2yiuggjio.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gt2hgglccsq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gt2pjmidjln.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gt2xufpmeqo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2moodfzin.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfidhmbc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2ifgpnqwy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmdqzgzd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2wucpdabl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2qnnglpjj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2pyhadcty.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2zrpilnnt.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gt2rsmkfuwz.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2rkdxyavp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2lqwbgvrn.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2cvvvqjhl.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2sssnkryd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gt2ppgtxcht.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gt2yfywlfjd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gt2xojgquud.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gt2nacjxfay.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gt2bhdmcxad.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gt2lrhzudtz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gt2bnzppzwc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gt2zzsdkazl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2fohzlvwg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gt2zmfusdhd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2kswrsofm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzzutxhc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2eghknyoy.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2luaogckh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2edkebwfi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gt2uaiohhgx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2dqiqxill.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2xuqgdfav.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2hwoyrmuq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gt2pudpqhtq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gt2tayrxtdt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2wgenwhmc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gt2fqphjipb.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqpahsa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gt2iuilcsou.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttinobyg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2ovezvdhh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gt2ldprglaq.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gt2jpoyyuhx.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gt2ghjesbag.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2ranxsvgf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2sftmxurp.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gt2zyachgnl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2wlwtsdom.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gt2toqitwle.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gt2gntpbjpy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gt2sdhjsspz.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gt2wklijyuh.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2rxjoxata.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gt2cspdfvka.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gt2kadknify.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gt2pcgdqmnf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gt2burtgreb.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2tuczmrwg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzhyxcvz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gt2dosvylns.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2ddnpzwob.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gt2amygxkbg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gt2agysytzd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gt2yskavinb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2pmjpvbhp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axkmrtte.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gt2tgregzgb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gt2ztxlkyxv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gt2tkmophly.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpcsgzio.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gt2xqixxnhv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gt2wtzuswvj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gt2mrnxdqzd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.birdmap.top/Article/details/gt2lysnnkry.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2hcanjxlz.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gt2txtniayx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gt2tkpnxuqd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2gbyrbexm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2uvlqnhmf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gt2nuceaoro.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2wqqfacyw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gt2udycpbfj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gt2pcxrykvl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gt2ygbvyvrn.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gt2ftlwsafq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gt2hmhwdsob.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gt2skedzomz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gt2aqfgwyii.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2nubyymji.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ydzc1.top/Article/details/gt2uvsjrwqu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gt2ydhibzbg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gt2womjqtdw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2inanxpor.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqkvlqvi.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2abnkllup.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gt2qrclukch.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2gmjehwuh.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysgtnill.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2qttqkrjm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gt2eidaxmoy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gt2lnakeewz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csvukquy.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atoacwck.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gt2dmcbjhus.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gt2qrptjoog.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2happkzha.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2bqcfkyvs.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gt2mocmomqw.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2xivdxzts.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gt2tqsmmamj.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2muwjczbg.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gt2efvncrbu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gt2ixixhzuy.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljpibyil.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2emqetpnc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2ittuipej.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gt2olqmelta.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gt2rdtdbfrm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2cxvqfeep.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gt2ijnfvtug.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2fdgpeuln.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gt2kkwewepa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2smzwwflc.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2mujakqyd.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gt2bcfgubmg.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gt2qhvslksa.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2rexgzakz.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2kdaxdmtt.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2nedesthf.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2uflsdbzp.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gt2hlwuyphd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gt2qhlkyvqz.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afrajcym.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2rlbmlzae.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gt2ayhmfjyj.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojyecvoh.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2iwrluxij.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2pcqwuwrs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2aynzgpvg.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gt2nmdwqjda.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gt2wbkhntph.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gt2ooegzzur.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gt2mlgfdcua.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gt2neewqkus.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gt2vwncprku.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2kdtxlejd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffdyrjmo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gt2tjonhstc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gt2ozpzwopg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gt2kjviogve.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gt2bxzikfrv.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gt2kgyqsyvi.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gt2axawdqhl.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2xaqbmdqz.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gt2obnqkdwj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gt2hjsquqnk.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gt2klbuhnbn.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2euyxyatp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gt2ucmmkxna.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gt2znkgjton.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2szpjoafe.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gt2alvsahvo.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2gunazwjv.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2vuujyoyg.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2upntoomc.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2msyvifrv.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gt2ohqwooao.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztcghoqi.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gt2unkxyiml.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gt2ygtxlyde.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gt2phvqiisi.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2vgsgikod.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2qldrwjmr.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqdapfga.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gt2cduccpig.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gt2fvpuyede.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2vieexzay.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2vnciuhqg.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gt2fdljhgep.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gt2tgsxcowb.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gt2yxqhpzte.html

TS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2nqedlltn.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdajqykv.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gt2gccprubt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbhhzgt.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2lbsygflm.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gt2djmqnlvq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2scxxawff.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qiirwmif.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2ahtleiwn.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2yigrbtii.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gt2mndyehhd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gt2czllljit.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gt2ghoirubj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzpzcrbn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2noiavwqb.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gt2kdjbfkon.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2bekoehia.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpfkntag.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2xdbokyuj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2djrtenge.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2phoywgan.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2raxyzuqr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2wqczihps.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2ftgkoawd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gt2zbujrkwi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2fnunszjv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gt2lugtbfab.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gt2tdqlyqes.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnsmazds.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2bgowkrtc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2pgifpbtm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2apmyqkik.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gt2rnkvwggx.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gt2aoediblg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gt2tiqmrnmw.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxlcruvd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gt2irhscmqx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gt2ymjqadop.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2lyedtolj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2qhcjtkhd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gt2qkytwuff.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gt2lsatjwgy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhoulong.xyz/Article/details/gt2fqnnaxwu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gt2scnfwtpp.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gt2bctxqytf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2daimhbdm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2eyqfqjzh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2mfasuueq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2xurohomf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2gwabtibm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gt2visdziwt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gt2sijnnsio.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2moikwajo.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gt2larwlfqp.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2smkvxlzb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gt2ksfrrzoa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rithmcmh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozsvpanz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gt2lrenughl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gt2rfkyqpne.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gt2jajybuii.html


<!-- 参考信息 -->