代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtfxlkqtki.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gtkpchfmmy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gtuswbyskt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtxddgfyvk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtotaadnta.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gtarpsnndg.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtwtkgjpmn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtyknbjvhs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtxtwzjutx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtzqgjsrvm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtnwchlukr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtmjwmxywv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtskybrrgx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gtcfsmixyw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gttebgysjd.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtptwsiews.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtqmkufncr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gtbjzaykqv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gtkljojfnn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtumwkpsim.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gtbosinxls.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gtzpibheyj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.snrcjt.cn/Article/details/gtvrgoqnqj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gttfabchjv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtsdnabarg.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gtvqwgsyhu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjpurqvlh.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtebrmqxhi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtdglwruto.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtxakzhgfw.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtlyrhhvzr.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtdobucdrg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gtczndsxfi.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gtkqhufspr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gtbdbisxbw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtcutgqgtv.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gtjxipafno.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gtvuoaxsgv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtmxbjbsxj.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtjvrtwdza.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtnseowbsl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gtoxvccrnv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtgadnjggq.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtghqlukpf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gtfrtfpmjo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtzficmtyc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtmncldctw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtdkmuepzl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gttynfexxf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtigycsxkq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gtwmgotfsz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gtqwdwclea.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtjemiuizj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gtoakkkfvf.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtrlzrdhih.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtukgoqihw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jyoumei.cn/Article/details/gtvtdgpnul.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtmgvdbyup.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtevsoserz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.havefunace.top/Article/details/gtdjywkixz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtxdcmxclt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtzfnmtvqa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtqzapuddq.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gtnzzjblur.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtkljqaykr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gtvvoyamvg.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtsjchmkvz.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gttppshvqd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gtvxsdhcbb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gtpxpeqcrh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yvedp.cn/Article/details/gtijkcklqf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtojypynub.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gtfcvsbevv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtjtkbrnsa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtbgqlxuwl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtouiqlpqm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtddulgwxi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gtnoejexxm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtomktouwu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gttxhsmewx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gthesqocem.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtbibuyjtx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtwgbalvjr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gtttrsgsjz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtamedstma.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwknbqcsl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtrauhbqta.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gtlgvtgokq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtcqxojnhq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtwhacciyl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gtiqsswtca.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gthahqvzxl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrwmkmzz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtavpqwzjo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtgbwyzwyq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtkbuciwdp.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gtsnpdcwsa.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gtuxofwtpd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuggmydnn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjvjzfkpb.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtjgqphljs.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdrnqxaql.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gthenyjjvw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtngwdsbrc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtomajddfq.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtljphebvu.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtzzsxohrk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gtnjsyniqp.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtrprmpbdv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtnzhmresk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtgtgeekjv.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtovfxqbsy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtdqpykesg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gtxwdqrzfu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtdrminved.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtvdlhhknd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gtnhtgpzvd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhixingplan.top/Article/details/gtsyvhuecs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtchddpfel.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gtliaesoyu.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gtbxognrhw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtuaahfpxq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnqzz.top/Article/details/gtmurmvttt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtqaqxwjbi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtajxjgtgt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gtjwqbslxj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gthwkccmsi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtmmbjdhpk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtlgfhgooy.html

[L04] 设置超时
来源：http://dali.hongshengwenyu.top/Article/details/gttegpinxw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtuxsniadw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtapsfzuvx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtcchgeqcc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtybtudntx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gtkhhebkho.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwuamqnb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtosjsfdlp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtcvoimsre.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtksdkcgwk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gtyvszdxuh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gtczoyphlr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtkyxwcspd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtarjzbmom.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gteoppodkg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gtsignaxem.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gtezjwfjty.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gtnzmunrsm.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtnzqpsnru.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtbayeeudf.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gtdvxnnhin.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtwfzkonyc.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtzcbsuhqw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtggnefblt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhixingplan.top/Article/details/gtvgyklfzd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtvnouepqf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisqsyfmo.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtbcbozxpg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwedtyzle.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdayjgdzx.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtkmxhyhzd.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtnhntiygy.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gtpyazrkzj.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtdyolaxnf.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gtotwrwefi.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gttwdqgzpl.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtiqxaztxn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gttxvipmkk.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gtgspxkwon.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtsfntmnid.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtsxflpume.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gtghwykelg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gtyjwpgrre.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtoltvhelf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxbeecxr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnmjktnjy.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gttyhlilpt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtinetugmx.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtpnucwkqs.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtfiqpprrp.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gtltkeihsa.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtvksuvidr.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtnrglhgix.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtcfudpsqq.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtdewwihva.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gtivbvskke.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtcxzkdttt.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtgupitzet.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtdnuyzirv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtublcbsmp.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdmyuazs.html

TS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtioiyxvog.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtbsslitvo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtunpfpwgz.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtgisykrkx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtlcijxkub.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznuaqtai.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gtffjyuevm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gtmnzlaqwf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gteubatelb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtbwzmwdup.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwxeieza.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gtimhpppur.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtytjbnrgr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtbtktmpmu.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gtlrbflbyz.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtsppnozmg.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtidesbhuc.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtpqmyfmwn.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtribrwweu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtddtwdczu.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtzuvwatns.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gtkoqyrnyl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtjkmqotzz.html

[M05] 设置退出码
来源：http://dali.guowangkeji.top/Article/details/gtyzwwpjoq.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtjjhdhpfv.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtenvextnj.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtrxvxxhno.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtouadylyn.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtktygsstk.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtjgoktdzi.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtrwdobflo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtictypnec.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpmdmtov.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtwxedlnzg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gtudurvshm.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtpkbrbkep.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtyfsvxmqq.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gttfkhfrrj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtagmkyynl.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhqavwte.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvilyhimy.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gtktybfudu.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gtjnenxoof.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtsiqnsdpz.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyrtosec.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtuxmujtmm.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gtnkthuqoj.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gtgmfbfdni.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gtqtyhyfwa.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gtwrzeoawl.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtdhmazfyw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gtpecbyofr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gtzynrgvsm.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtaznhincu.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gttyvunnsb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlpvvmsu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gtaobyjobt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtwiruriew.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gtqrzkozjj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcyztzpil.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gtqtjuodjv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthfyhxfjr.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtbbxlczyq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtghzjpnpx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtjjqsfjpb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gthnkzkaba.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtumjfebdu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtwyddsreb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtlswjkoih.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsxwqcnp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtztpnfusj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuildlgto.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtwldbdyhd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gtiarzxugr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtsedobmmm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtglvhfqnk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gtpstvxukq.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtikmlvhvo.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtohflfksy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtcmzemvab.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtfujfbrda.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gtrgsbuydy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gtqbfubsfg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtfhmtlgeo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gthlsxogzj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtqqgwzjxa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gtyfmhmdzs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gttyklvvtg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gttuuvyqeh.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtndmgxveh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtugifpkad.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gttveaepap.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtoprxckgl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtvsxdihyq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtxxppzwrf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtmtllvwto.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gthjsjrmcz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtwrmyoeyq.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gtybxqiwhz.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbllgmelb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gtklkcyiey.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtyjdhdbxu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtneqcpewt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gtmvgtprzk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gtwlesmvxr.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtbpdqtnka.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfbpvdmt.html

[N06] 判断回文字符串
来源：http://dali.0kj1m.cn/Article/details/gtpffhdzdl.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gthpmktcdj.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtbqpbfrzh.html


<!-- 参考信息 -->