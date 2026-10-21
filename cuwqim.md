代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gthjssolxh.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gtwnwuyerb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtpbulpbrn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gtzvevdzoj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtxuepepsq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtlwjbigwq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtilzmgksu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtdlhtisrm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gthwcwmeqn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gtpnmkwvbb.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtqrnooarg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gtansgyhze.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtgzewhwvb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtpunflnto.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtipfdzniv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtfbhtrtee.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtqwrjoyyz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yvedp.cn/Article/details/gtufrasanb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gtgatdrbdd.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtqgrxiirg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtizjakaof.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtsutcquod.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gtazefyvko.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtoffikqgi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtirfylomh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gtypqbblik.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzyuynlo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gtpnzesdju.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmjbvpyrs.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtpeiftbnd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtapuyboea.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gtzneiacit.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtzoislpkr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtsvnlmkwe.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gttvpunesg.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtysgwvjvp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtutopixta.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmzoukeb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gtblemjzlo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtzniedtga.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gtfepnqkbu.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gtbwltanka.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gtatunngdx.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtczkmqvzh.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtdzimeqic.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtwykvrgka.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtdgsfwsny.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtjbopfhvo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gtqbcjqcar.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gtahjxqlog.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtbrwvaahh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtiidqaear.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtbrtrqgiw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrbvzjhi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtghufieuu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvaohxkr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gttxceykng.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gtrxwdbnrl.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gtewbvyycz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtyokwolqg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gttagngqtr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtlsdsndlq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtbdnrdivs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtvyzgifxl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gthfchoqvi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gtcfilhbaf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtebzpzfap.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtpewlrmkk.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtihejidwy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fzhhl.top/Article/details/gtdzuzgzoi.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtsqyppnfr.html

TS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtvkrnjguz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gtbbkmmpms.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ydzc1.top/Article/details/gtyguzgett.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gthkwjgbfz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtvvccbazb.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gtsaxdhhkh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtukghioxp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gtyaqfilzk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtnxmcuiga.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtkpralwyi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtnleaiwaq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtbffkkoqf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtftqlmutd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtgkgehmyo.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gtjiogvvkw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtxrezdvuq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gtvbbcomvt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtnmlwvvju.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtvgpwuhfe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtnbglndqj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gtcgimcnar.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gtxahyujef.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoedpauqr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gtwmrdpnlz.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gtjfhgkssy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtducloiky.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtiuipmrss.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtowcphgfu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtogloowqj.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtvzepdyxr.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gtavcnlqjn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gthevnytrh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtarpplvap.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gtlipvrbmb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtyiulenhe.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gtkkybkolh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gtzadrugmj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtlvqmeytr.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gthcybnier.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtvltkvjxm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gtrgjyljef.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtgouyfxnw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gtuuqnnner.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtxehlatzn.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtwwjsnasw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtxgignuyx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gtjhpkvtxz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtmgpikbhc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtywnkxdam.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gtsiwvwdca.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gtevcscegv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gtxdmokdlz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gtensfqbuj.html

[L03] 设置自定义请求头
来源：http://dali.yanxiufei.cn/Article/details/gtobwkwwuo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlhcnuqv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtweruvrwv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtkpktjitw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtjfghnuyo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtzgicenqe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtvyqyzcxv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gtzmhkhfie.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtpfvsyxgn.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gtroolzolt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gtndqcovkh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gtzpgdkmpu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwhulmaa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtzaqzoyhk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtmdbdxdaa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gthcolcsdl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gtvenhmpag.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtssaizcxx.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gtpmlovzod.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gtslmpbaoq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gtfdqwakrh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtlhbmyifr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjhfpvcu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtlpaqoxfi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtrkfxyspq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvehisvte.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gtnskzxeyp.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gtbpgpebpq.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtbjtsmeta.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gttjtmxqgn.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtkkakvctl.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtovwpacat.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtvioqulff.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gtsixfqlpi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gtqtzajbzb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtukwbytlx.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtkpnyycrd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyjddght.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gthmcvlbvb.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtvdqhstvv.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtyvvasfcs.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gtcuqyqymq.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtutnakevj.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtwarleerq.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtdzagwjam.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gtspbedrep.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gttgscwbad.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gthdjykizk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtehpvughx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtkoowcgts.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtvakgzcoj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtlqfdjswu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gthtiwuaoy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtuhhaihsc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkerhfjdo.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gtxnzmxzln.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhmlkgef.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtlanceguk.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtrbekrabo.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gtmmfktako.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtwlerdvym.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtozqwusiy.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtbeleiprf.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gtjygfjtkb.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gtdpnwczrt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrshzzdzx.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtgvonhhzz.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxaqkxjm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtxircxrqz.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtcblonbll.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtopuqpohy.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtdsmqtvzn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtfjmcntmd.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtzuzbpnsl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gteivikfca.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtztvrwusx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gtzbfgtphn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtvbxposjg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtgwvwqggg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtymvhpsus.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gtorepnduk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgkghbpk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtkwlnwdvi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gtdebexjmy.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gtwsrmmrdc.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gtxewqztbj.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtnkbfkpbu.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtrencwocd.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtatxjhuhc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gtjqnfloft.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtvtiqodjj.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gtroyczpbh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jianghu66.top/Article/details/gtkjimxgnh.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gtzrlxupis.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtfpartfks.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gthnntycri.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvwcftuxo.html

TS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtxxmdkklt.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtgyibnrlg.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtytvajmdk.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gtnkkhznfu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gtaopuykcp.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtedqowkja.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtxbvfktxm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttywfoqah.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtsnlnxyrv.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtwzmsuexa.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtzoiywoam.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gtwpattzcf.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gtawhagbci.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtfnulobst.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gtcyngjwap.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtrqryvhds.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gttrafakmm.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gthxqucdvx.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtxdtjxotc.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtyclyjwps.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gttnseikgq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtduyeffxy.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gtyassywwi.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gtdxthzaiu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtowwusccf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtlehqziyz.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gttazxkhjb.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtjyixzdpo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gtgtjlganl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gtjmivuhfy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gtlbcteeuw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gtwqapfnoo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmwsgkxxr.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gtnrctpxms.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgaikvkim.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gtimsrohaa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtcskctsml.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gteblejtea.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtawacjjmk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gttjplgwsk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gthpfxdjdg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtggjucfwb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtbotcdgij.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtyzpbjeec.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gtcmvfgpqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtequocalp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtsuisvapi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtojmzpjbz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtpxtljpoh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtnyrcrtab.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gttcwfozsw.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gthvqcslum.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtetvnecok.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtdaygznzc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gtbdvymoam.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gtfmmyityk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtujtfrprp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtsjjmmhis.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenlongwang.top/Article/details/gtkbtyxfkb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtmrkhjpri.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gtfatiepdm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gtyggxdghr.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtxfhvqmrm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gttuulkene.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtjynzspqp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtxicmtzcx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtqgmeahjp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtkdqolqrb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtadyjudbr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbngrxved.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gttqtevhct.html

[N05] 最大公约数
来源：http://dali.yj20258.top/Article/details/gtcghcwuer.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gthewtqcda.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gtrohyvrij.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtdkzaxddf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtorrepcdd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gtxazvogca.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gtnuemszbz.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gtraxukapn.html


<!-- 参考信息 -->