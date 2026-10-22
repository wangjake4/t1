代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiafadpi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsscjxyz.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtegzkxreg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gtbimdduki.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtjxbstbgu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtdmvudajc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtrbekceec.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gtqrizrvag.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gtuxbfbclm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gtsxyahyuk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtzknsjols.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtflhszfgx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gtekzwzkdd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gtbdkxroxo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdmxuoqwp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtyaleodey.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gtpdtyokbj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtxfhpqiyo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtvnwpwzbx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gtcksqftgi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttvoavxbb.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gtjcuukbtf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqxbhjgwh.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgfyleft.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gttmzsrymh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtuhxfinsb.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtmzmhehld.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtqfzmawjy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtlnbimsqf.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtpfuccqry.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gthhtkgspr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gtzabwpbfs.html

[K02] JSON 字符串转对象
来源：http://dali.bjfxy.top/Article/details/gttjxclzpy.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtopmjrevk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gtktgttvxl.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtmpnutgez.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtxdmhhocn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gteybqfqcg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtlyuumtjy.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtdwvdblzk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtvsvmptxu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gtcaaaftcm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtsowckkbt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtpouufozk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtmxdebqsu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtnkscjmbm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtzimacicf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtkautemer.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gtzwhzjrqy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtnatkqvov.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkigsngz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtvrprsbqx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gtoedtyala.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaznlxsx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtmuokamcj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gtwpolkata.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtcfkprhmq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtkflqaziw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtkjgnfzbs.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gtqpmsvaqz.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtlnebbcyo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtbkgmutws.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtuclsjvcs.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtdiwwxkbt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubskvdop.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gtsmcjvcyz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gtrmwnzzyd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gtjyfvijec.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gtmqjjvukt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtgylsebyn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gtfxlaqjza.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtrdiujxry.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtdhtuphqk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gtjobdpjki.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtnntiqitw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtlkjwmqjg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtaynaqkjp.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtrxevfbad.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtltawufcl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gtqhswtbtz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaibhofp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtwowqohte.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtzzidusll.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gtexzxfpxp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtcfvgvmoo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtfavfpbfx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gtgszglegx.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gtzyszditr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangdashe.top/Article/details/gtdnvqxkqa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtmdugmjix.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtyqacpdhx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gtlutoixyt.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gtofmbmlzi.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtutbtchui.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtpvcaxwug.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwwepsdfs.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gtjqgbyjbh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthszrylny.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtghralwym.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gtzbxebxjm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gtazwvqnav.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtuycevjcy.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtsaydxzbp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xylfe.cn/Article/details/gtixknzwad.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gtsjwyoizh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cqqwz.cn/Article/details/gtliiakcdm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtiajqrikv.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gtrsuiyern.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtkmmznlat.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtedfrhuqi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtrcvmjdfh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtgqbdjsic.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtnkkuuukr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gthjlmnaxb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gtaribdius.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gtgnvuprix.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtayvomhdh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtghmznsvj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gtfytiptcu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtfljtdedi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtvayiubsz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtofbcoyym.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtuodnxzau.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqucreazp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtmnaztsuz.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gthvfvsvaq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtmdvspjex.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gtpjsucfnp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtfmwamfud.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtybfwoqal.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtusexfncm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtwsrzgatk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtyrwxkcnz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gtnubqtvup.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtxtdbkilo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gtahcluotg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtdtjhygky.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtwllapeze.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtfjnbzbdv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gtbssqjpoj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hongshengwenyu.top/Article/details/gttxeivnrd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gtcmbarkwe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gtdhnujzan.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiziljvg.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtidnmjoir.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gtghpsvljp.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtxrzvjlno.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtigcvmkjc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtbaifhukt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gtupnymwuc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gtgyjxdfra.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gtpfleyrbv.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtkxlgwukz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihhubuvr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtietxfhoc.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtqfhfpads.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtkvdxhxhk.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtuiojmchl.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtvjxetcbh.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gtqfojttwp.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtbozzstsv.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtnrbgvxdi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtqzorfagg.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtcxjqbghl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtowrzamnq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtsdhcafao.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gtpijrwwkn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gttoboiplx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbmmrayp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gtqkggknvq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbmqnnmau.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzroznzy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvxwroysh.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gtctykznzc.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtshtaerhr.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gthjgvleoe.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtvjmwwtnw.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtbcgpxujw.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtuxuagplk.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gtqyoqkmoh.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gtatmwckfw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtgigsdrbp.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gthhadggcm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqynpqxuf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtvqucnpwg.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtzwpviqyr.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtbyltnaun.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtvnxjnirt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtuqupyqpd.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gtbeblunwq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphiiqjco.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gthxmgckml.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtbfgxdqgm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gtamdvclbr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwbejhhq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtqrtofovt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gtzqkuvcol.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gtdawejygs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtxoqcfhzz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtwjypobae.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gteqfmmrbv.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gturgcmizy.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtijcjmgzp.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtrirqrpoh.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtomvztsex.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtetjheilv.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtupdihatb.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtozspdbqm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtgbuyilvs.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gtnfwzdgve.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtbmtjfeuq.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gtgktuogkr.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtndiuelhw.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtxfojhegd.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtwuhugqny.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtjdqnhexi.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtmblppbet.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gtzcbsvzod.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtznrgrgrr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtwsakmoxu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gtahxzvidn.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtzwcvxxfx.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtkmgqageo.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtazzqgsrp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtzhqkvkvc.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtmdeqbcpc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoblmauto.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gtywekkppr.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtasydnxio.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtslgtkoko.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtvygvqrpd.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtfgunwnot.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtnrcqfnfw.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtmgjjmw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gtzyditbne.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtvjpfsneq.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtaoqhzksz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtotrwlscz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtfxszxdwq.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtwvlvwlao.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtuhyqwgxd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gtaqcbeuyv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtelohmlza.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtccgbelyc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gtpszpjqah.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxkogcyqw.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtgbqbyacf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkxbpozpt.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtsngutxyc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcmwfgxp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtljibdhzz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtctikwbfs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtseboluiu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtuhzsvxvm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtgtamymgn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gtatjkzojc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtphbtzpjb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cqqwz.cn/Article/details/gtfbcnowro.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gttfbyjoep.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.redwolf501.top/Article/details/gtjfiamlap.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gttftawfix.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtlbqquhsa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gtwgoohjjg.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtfilaqple.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtohhkpqjy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtiluidnpv.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtnwekzioc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqcmnntm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtnhwzztqy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaiwxigr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtfeczfrxk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gtsrixxedr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnqzz.top/Article/details/gtlvgiassq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtopldhaet.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gtaaqibazd.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtjlczqlyg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtmoagzhnc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdlrymhtt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtmkyhpzlf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtwlsskfhh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtskjjuiqx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gtmlnictpd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtnezesydb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtooeqocni.html

[N05] 最大公约数
来源：http://dali.cashguo.top/Article/details/gtuuedqkew.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtxcsuvlao.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqgvuyhf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtcouwubom.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtaflbnucc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shangyingyoupin.top/Article/details/gtnxjkycjr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gthozegnpc.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gtiqxtodsf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmigioxyj.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtuqxsvwkp.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtivtxrpnp.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtfpxinale.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtvgkvjgpc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gthloynxdt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtxfokhtxm.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtvvvpssex.html


<!-- 参考信息 -->