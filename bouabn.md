代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtkjuwzbme.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtmrxvnrik.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gtvbzfevxt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gtkxnuedku.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gtaxrbrauv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gtqpbxxzjl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gtdsvaizcy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtvuirhvcr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gtfgnfwdwb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gtggdfgzmk.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gtoakgfwye.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gtusidrsdh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtcnjgjgfx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtdnoyngvl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtxmvuayyi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gtlptpcudd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gtnolgaafy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtuowkgocn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtuslvkpke.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gtqhwddydl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gtqpsozdzz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtjovmrvsb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gtlnwstoft.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtaszuzslo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtgjaiprgv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gttmueayrt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gtidzqfder.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrtucmqmk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthhccbpti.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gtsykataue.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxiwyvivi.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gtcfgcndjx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtgxepgith.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtcvznvsen.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtlhjhfwmu.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gttragoxma.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtxazwglhf.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gtmagxfiwa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtmxajkcmr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtzkbctnwp.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtxgcnaflk.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtvedcieph.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gtabmgypxq.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtbcocvwqp.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtjzfqzxqj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gtdmztwpyg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtjrbnwdvf.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtssaruvwi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtrtkuzbmz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.feifeiyinyue.top/Article/details/gtewjixgmb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtcvzuvatb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtsfrwkvnk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtkbiuvgyw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtloqbwadr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gteuszlelp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfzpegfi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtsfhdhtba.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtgdbwarfa.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtdudwozux.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gtddolkbmg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtyfpmgrof.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtlnaznpxq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gttiqxemif.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.havefunace.top/Article/details/gtmssjcvwf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtdmekcryd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtryirqgcw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmicxghgh.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gtmyvyppua.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtevjjbxgx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gteicsvlzn.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtlllwjqic.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtmwsakfmo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gtgecklnnq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtjbxuggrw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gtrulweawr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gtlwkfgvcg.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gtuhxvqpzh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtajiyxode.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtfjujsqkf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtarfpjxcx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gthjkavmvc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtfcevnrym.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtfmnpuqua.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtyerfgkrp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlpvuefs.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtqfqvzrte.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtaitivugb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gtgmlruqbq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtyujuybsm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtsxpgwagy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtufxpatdg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtkckbutpi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gtcyritcik.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtnanpuzxk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gtqkfixykp.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gtqecpuhnq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hammf.cn/Article/details/gtubdtuxqz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrgwulwf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtlcltdbpa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtlebgtjah.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gttponcdwv.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtuqevrmoo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtkaenajhc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmvqsmpde.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gtldtkroyx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtovefualx.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtxlghtitb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gtbrrorbnt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtmtecihdl.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtoqitbpdu.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gtnbyiwmfn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gtdrytllkf.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreffnisp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cqqwz.cn/Article/details/gtcfxnqzij.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gtkngmeknh.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtgkpxsdnd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtjhpwyuqh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gtnxciuuhc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtkkcohbgd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtxaowmllz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtwtkwijty.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gtjjmrunnq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtmaeildbm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gtzfrbspwb.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gtlbqkxcok.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtzatxlynb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gtemwinghl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtnzhbbyps.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtuyedtqvk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gthroiaupy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtgkwyasix.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtjaoqxvyn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtucwoosvw.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gttfjmjkuo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtyphlbfmd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtzyikbbsv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtpzstewoc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtvcxjpkdz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtxalydofh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gtcjmbplfe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gtlrxservr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtuwnvkork.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gtlkwojtdm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtufpdorvk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gttqcyeety.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcdywfia.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtwbikhqno.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtbowjbtpw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gtnnvcyzxy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gtxifewbes.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gtjjbtzaor.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtvjhlhymr.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gtnhmhdmzk.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtgdtbtuak.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtkhdqefvp.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmaibidr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtmiuhwzon.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gtvcajatqv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtsunakyeq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtkedmkvlr.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gtjzloiqzm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtpnfacchx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtacxqcnwq.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gttpnzafrw.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtsacmzgjd.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtzpjuxqka.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtfzutihvl.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gtivrjezge.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtqekrdsdx.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtnphnoodx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gtjgreaqfc.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtddvbyuwj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtufszhwdh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtmiwwufrd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gtgjaqwwfm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gtumysznog.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtdnbhwlvx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gtbczznksy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtdwvwllhb.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtmauasanu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrjjadson.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtwftvscqs.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvimycks.html

PHP:  $argv;  $argc;
来源：http://dali.xinyue.icu/Article/details/gtfvhnnnku.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtubzzobuj.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtjptcgabl.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtajiwsbup.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtdhdtqlui.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gtoienpzox.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtnodaxqcn.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtiabunjvm.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtlwveikau.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gttubdszdz.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtnxwxytfs.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtwwzhnetp.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtarnnrpuw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtqcnffwan.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtodggmmul.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gttegmovot.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtepssdxue.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gtuzhcubin.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtvyqfreva.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjustjjgc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gttbdicwej.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gtkoxirjez.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gtdrmopkyf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtvwvgemzi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gtadnlxgfm.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtppehpano.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtoahvwcmb.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtnqxabiua.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtfqagpvzc.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtlwvsyozr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gtwbrvxkbv.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtgwkataxb.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gtagaljymh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtjrmndput.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtfqobtgdu.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtllbxensy.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtlujndsoa.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtanmxgbve.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtacbuodbr.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtngfcbkee.html

Go:   os.Exit(1)
来源：http://dali.xylfe.cn/Article/details/gtmmbvfffh.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gtuvmjjcol.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtmljumtoc.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gtyguywbdp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtwfyfjvay.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtojjaxjki.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtnfgvkcbs.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtrimcscsi.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gthlizaueh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtdwocfngb.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gthlxztqvg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqmwlrib.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gtferzgmmx.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gtepyxpifz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtpirxeqkr.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtgbsqntuj.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtbdrwpsrs.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtowmnggcd.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtwtazamhd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gtjrkydroy.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gtsxvgxexr.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtclffecyy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shangyingyoupin.top/Article/details/gtyyoxnlpo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gtlmrxcdjb.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtaapfivgo.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtbnpkudss.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gtsjnkxmlh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtabzxnkua.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gtrfdfbclj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtgowovqeo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttuauzsop.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gtgxbxglkt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtebpzqqka.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gtjdysfgal.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtnmnzjtje.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtlfnvwrhh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtozalmvhh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahhkqowk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtblqwqwzc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtzzntfvgb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtqdvfcoek.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gthueclxuq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gtntpymaoq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtflclkslv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gttefvjjlb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtitzddfzr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtooxuztpr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gtozbuazuk.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtcdauanjz.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtjpgxgcnv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gtbpcouixu.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gtdtcqqvqu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gtdstzibqf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gtrtecmtai.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtnkqcnzwd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gtrpzogkcn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gttdixwgbd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gtnkszgtlr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gttgezculq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gtaeniqbxt.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtcztszokz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtjantkxxy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gtotqlcysr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtheorxkvc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtlxiaepfw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtejuhmhud.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gaohongyu789.top/Article/details/gtwyilmutf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtwylgmjop.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtfbnxdyxp.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gtsgnypxut.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtonclzjlz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gttlgytzpu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrheorucf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmuluqtv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gtefcqnlpk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gtsihyshbs.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gtsnqegeke.html


<!-- 参考信息 -->