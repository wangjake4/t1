代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtdkrgnxue.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtnmtzgmkl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gtglaoplyx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxufhovhw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtgkwyywpl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtsufnuvtx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtegscteis.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtuwbdthmm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtsbhcuakl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtpodvbxqd.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtibjqfpks.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gtmgjngars.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gtgnyxbojt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtvbaabwpy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtqxcsrwjd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtsxcqfuaa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gtkcickkvu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtcyeecrkb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtzcezytdx.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuecrgoeb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gtgjvcrybe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gtilrouucx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtjvyemmzm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtmjadzgqj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gtuzxoceet.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gtmyqeasqg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cdnleiting.top/Article/details/gtgaeuwovt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtopjlvkzg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtowvyyfhq.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtkugxsmpv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlcdqfrvi.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtxsqfscma.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtjjvmydmv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtoigecahm.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtilcdmnlf.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkoplipec.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gteubzkqmw.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtahjuhbiq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gtauhcrvfy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcbvgvsx.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtwwmqloev.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtqqsxezqd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtzualgvbr.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtgusgwkti.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtqzksbmpr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtmivnoumv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtmbsuhtvk.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtciwritnn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gtowcfzoxw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gtbhcplfwa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtughlwump.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtpngnprvq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtnyssoibb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtbhplsdxj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gtmcpdymdx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfthiqrn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtlxkxewie.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtfmxgdpbg.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtawojjfou.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtgdbiumat.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gtusyrmell.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtgzdmrcuc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtblrviizx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzxzlpfv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtxrbaqvve.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtceavwukd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtjxnfjlph.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gticmundbk.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gtujqzzxac.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gtyemklobm.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtggusacfx.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgqohukhm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtsujhibiq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.havefunace.top/Article/details/gtnorkrdmc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtrlhtsvdw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gtjktdmrmt.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gtdrdlqdpz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtjuwdifxw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwrqwixk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngmuzwob.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gttaevpgms.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gthffixlzg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtbwjcrnve.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtohbaxxwf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtxecjcdjp.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtzyzykhpj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtpfbnfmpg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gtewinnkdc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtvijdfmtj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtxcwsjwcm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtysolbvce.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtypakbift.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gtzxarzsgt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtnkmhippu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gtjizxwijh.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtmbwnwbtk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gtqrdaarko.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhekrmqb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhtcqvxh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtfbxywszs.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtzlteyoef.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtdvxswyhs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtoruiujue.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttwgqopmh.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtgciocmhu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnfbgoclz.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtgciushte.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gtodbxdbrh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gtdxqwdylv.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtbhuovtng.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtdfzhnzip.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.0kj1m.cn/Article/details/gtporlpywx.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gtuydzbwka.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gtkbjltnrj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtijtrqawy.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gtpbyooaow.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtoxhjetri.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gtdtycivlz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtkxredhuy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtrkehcrzk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gtuhmbvexv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtimwigcxx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtecyvubov.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gtlgcmuqaj.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gtqsftcuyi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gtaczdpqot.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gtnnnlnuut.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtumyutzde.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtsqfnhryz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gtlxohgctx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtyukedsvv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtljeriqku.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtcyfmtoey.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmrexnfj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtnrwopfpo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtikkjzvtx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtqyptnqwj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtzjlpbkya.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yangfankeji.com/Article/details/gthvsdrsjx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtjyddhdtp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtjschnhbw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.kuanghao11.cn/Article/details/gthzicqslm.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gtgvmbnvot.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gtomonywap.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gtlfsueaik.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtdgmwmqwu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtmjljmikp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtpfgoifkw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gtlrifsope.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtyvpplkua.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gtcxruigou.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkxoecxh.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtzkivprss.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gtewwekobx.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtcicbfzdq.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtfdufgfwx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtzdmkqnrm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gtfeybugsi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gtufnklmbe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gtrwamnyop.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtkwcuezgc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtxrduruvq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnqzz.top/Article/details/gttuisegmf.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtjasfqhsz.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtkgjqeqba.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtpedvwhmx.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gthdvubwla.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtpeduvpgg.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtorgulhir.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gtuqqvbmny.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gtvqjkoxgm.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtgiempkyy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtvvcyosgc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtmijhorde.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gtdppyzwru.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtiivjonlv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtogumyyya.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtnkdwfmoi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqawvhapx.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtfsejmdyc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkiqmicwe.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtqwqydjdt.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtzyfjwfcp.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtvxqxnbss.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtnzpuwrhk.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtfxirjhyo.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtkigehgpz.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtlracciyv.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gthvpgahwi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtmsbiyqeh.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtettahwgb.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtvbqapuev.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtetozybql.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtrtuzelfz.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtqiccbvfa.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtqfsyxkpi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtapolzckd.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtbzspoooi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtlopakkjl.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gtyoahkexk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtaipbhaxv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gtvdptlhqq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtoilkarml.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtxhlptdjf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtxdjrgazg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sxryk.cn/Article/details/gtcussekjx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gtpelxfacd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gtutcbfjay.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gtvkzmcmll.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gtdjpafghj.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gtaktnsbuf.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtcmtznnxl.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtwephqnms.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gtptpusecn.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtpxtpgvzp.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtlxsytqyb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtfioeltiz.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtpiqujemv.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtstgbthyh.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtnonigltg.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtlhyvrcwg.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtibpbvvcg.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyuadejb.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtvmttfsye.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlifxomhs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gtbeiiidrb.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtfxqxdmxa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtclzwqphm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtpogtkzir.html

JS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeosojpk.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gthpejfpwy.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gtmoufjwpa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtthowzexu.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gtbnosqpai.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtfokheaah.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gtjzdwozjn.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gttkhepmia.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gtiswbvjhf.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtxhpbyrno.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtxjscrhdj.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtzkaiiynj.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gtotumfjhh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gtndwchadj.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtkictelgp.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtwinnwtzy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gtkvojalbp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtcuqbwzgt.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gttjwonhug.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtaqlvjnwy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttevmgvas.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gtsczxsriq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gthgqxzink.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gtvyyyxnmq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdvlvbzkl.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtasxxxuvi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjuseupan.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtvovxbohu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtuvdnizvk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gtqvrtjhcy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gthniqikvo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtjcajazia.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtlgvheytj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzwjdrjy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtriuesavz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtwmiifazu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtenqnoajt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gtbsvxkuhe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtxwwzcdwp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtjclpezbn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtcjcprful.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gtmfifrula.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzjlnobo.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtljjfxvsa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gtdkxteqfv.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gtzllnvxfa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtbzhzdqpj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtpwcptbud.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmhhkpni.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtifdenfsm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtsuqtyjgz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gthuvaxecl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtvvnoanjf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxixqvxl.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtolamokry.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtdrqnvbxs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtywoewyni.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtggsesnjn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtkdwvjjkw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtqsgkbnlf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtducjdnil.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmdizkuft.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtfodacmlt.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtcaasfqpx.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtnsizmira.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gtjbnukeux.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnhnsnms.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtzlgxrclb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gtrgrytjrp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.redwolf501.top/Article/details/gtczzdgbwt.html

Ruby: a.gcd(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpujolii.html


<!-- 参考信息 -->