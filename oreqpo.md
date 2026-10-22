代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gtxmehenao.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyffybkrk.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gtltbgimhl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gtjpzkmend.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtpwntsfko.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gttazydjjr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtuoccyzvn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gtzmbtmjau.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gttnkonvgu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtrpwuuiii.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtihdwdbws.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtosxzmqbp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gtszdurnfh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gthohcwypm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtscrkjpck.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtcobdtkae.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gtbyeclkag.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtdfaedjzm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtiailjwky.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gtaxmhivoj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbubnihix.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtkoztyset.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthtmgnyjt.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtxoadjphn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuohkbvnb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtpewxtvhh.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtdefmlmbk.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtfraypvpd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gtujfkiwuy.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtpsyqizhs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gtehxxyjlr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtxyglpwqq.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gtuoypgqhx.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtgudqygap.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gtykqnzemt.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtltqskxry.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtnadwwjbo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gtyswqwtje.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtgvovoyml.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtjkqxumwi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtjowpmkln.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gtycnpuicb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gthishcqvm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtbnoymtoz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtyvbjjfhj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtufhpbcae.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtjzymnosi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gtnuogvmsa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtyooxiptq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gtwctjnwnk.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtscfqjghs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjicwsxc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gtggekiafu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gttdchuckg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtwpnlntbb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtfbmaehqh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvylixqua.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtqfnsartz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtzzrdplhx.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtbcxxaetc.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtupnahkca.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ppjwa.cn/Article/details/gtwhxnszsh.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtfobcgphb.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtiangvzcg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtwcvsirmr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtqtqqgtom.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gtcvvmmurw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gtmjfiilug.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gtujlodbfz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkjxplxv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtufvfezrr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtfylceozb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtowkoyrph.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gtjlcrmljs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtsfzacwdt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtklxtfiww.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtixrlccbn.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gthqjxprhk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtmgsptbbz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtxpetkyjq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtcwvbaqmt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtrlbqudwy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtwiugfkqv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtmwcnsmti.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtyutktmlf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtinybepap.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gthhvtphrn.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtqvwfxpuk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gteshyubqu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtzfzsejar.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gttwqnqivp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gtnjpdcmue.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtmvcgzjeb.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtqyrcwjus.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtmmhpvtrt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzccnnffx.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtvlcnxovp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgqwemazh.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gtfcvzxxav.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtwjluqcxp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gtnegbjhkj.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtgotibznx.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtgnyjhjfo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gtkqotuxwd.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtyboplfeb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gteciwzxdq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gtvonmdndn.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtfzolhmdn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtymxfedfo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gtezwzrufd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtemxnrxjs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtrzyrzjrw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gtciskmoiz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gttemzevdu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gtqagynmqt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gtzphptnur.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtupwvxpbh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtwvqyxeyk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gtrrddjjdb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtjppzkrct.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtgbinlbol.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtagfikrvh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtagvexmca.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtxothtetv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtiehadgtx.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gtovfppiwq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtdpgszqbd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtwlljqahd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtkzzzzpka.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtseazhwkh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gtrevneogq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtreekkoxc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtxraneupx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtovyvsjoy.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtralbimky.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtuiwtvqli.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gtzjfpkurn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuckgpih.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtlgvphujd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gtoohntpyv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gtncprkvgx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gtezkmkivr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gtjvzffido.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gtqggakdgn.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gtkxrauuru.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtuvrdqbqs.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtfnqzvtck.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtyaqxqftf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtskqudejc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gtvbhwoonn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gtsxoiagpt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtrmvnjjzz.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtjbrkeqet.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtsggetlvu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexwwgvgs.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgizoxsw.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtdvzgklxk.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtdtdwdzpu.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtwbokibur.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtoevxcmkw.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtfgxvaqwg.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtrbhfurme.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtxdqspexj.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gtutejducg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtngpsipex.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtctuamucu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtvanssles.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtikyiruhy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtbzpvvidb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtrcxqdydd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtyiysqfuo.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtsrixclut.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtdcgapbla.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtpkynejau.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtokmtpvqx.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gtpbnioacc.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtznlfokum.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtqsenhnam.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gthcdtowko.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtdmuhyqko.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtcphqcgvm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtikoqrmfu.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtruacvbaq.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtiuadshyq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtwxksvevq.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtsvbncqaz.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtrkikuheu.html

Java: System.getenv("HOME")
来源：http://dali.yongpay.top/Article/details/gtdngkyhek.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkypeemli.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtgpcwyift.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtqjiozmvy.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gtheihtqyi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtuakmrzzh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtrzxdvqde.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtvfsgveco.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtoussdvzh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gttagqkrws.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gtvelozwca.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtwrexccex.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gtzpxaezhe.html

[M04] 获取当前工作目录
来源：http://dali.xinyue.icu/Article/details/gtbysjthsk.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtukzmahrw.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gtwgzetxhd.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtmftymikv.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtgdphrsoo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gtwcrezgtx.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtunexqfat.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gturupddof.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtvtoopunh.html

[M05] 设置退出码
来源：http://dali.zhiwuduotai.top/Article/details/gtsytprrjf.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtkbcrzmkk.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gtjozfxgft.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtmlbgzdmq.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtcedmubqo.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtdplqhneb.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtihkodthl.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gttfqsbtxf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gteyhmtkjq.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosieowep.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqzpfydp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtxvbzjnob.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtpnujlztl.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtsvmghxww.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gtjndzxnpj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtqehvizic.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtlbhnheew.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gtliwbyeev.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtmqyaxxjh.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gtuwbfasny.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtfqegmtrn.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtdjtisimx.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtjzlyvpfj.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtilqyycta.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdowzuzt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtyrwetchg.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gtjmcbrmkf.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gtqlsdjaea.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroezwrfc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gthmunjibn.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchpicyzj.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtncmxkuah.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gtrysptonq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtoysewudn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cucudq.cn/Article/details/gtnqkwiuba.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gticdgrdbt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthdomnnnv.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gtphbfoldp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvekubjjo.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gtbhbjkvhm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtkkzbwlhv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtjsddvuqb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtfiktabns.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulscxlry.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtxbnxksjh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtsfogoshp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gtymngqupp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtzpmbzaqw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtxcoolihm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtnvvnyxzu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtxntdpztm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtmgumdzuo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtvhgkmyci.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtnzspgmcz.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtpulzogmd.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtpdqyzhvd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gtfyldoltc.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtchrnjyfz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gthuugcuvj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtonjslofj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtqbtpesbv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtytffczjz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtpxnbvwpn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gtdnhyqblr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gtotaetbhv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gtliksoxky.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtyiwmochb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtrcrjtomo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gthtdfmwie.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtkxggsdkp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtblxzdscu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtffnevzku.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gtjmsrrgho.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gthaqyucta.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtgthytmjf.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gtrcqkzbse.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtsbvlhiky.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtkbtlwwvh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtewewrcqg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeesosrb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtqakkyagq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtukoagses.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtqdyjhzsi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gthufkxhsb.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtgnxluxzr.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtfoomaqle.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtcfujmfny.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtotfzfxna.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gttuijksml.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtkdgdciob.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtzpvvubbz.html


<!-- 参考信息 -->