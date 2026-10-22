代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gtbbywcgld.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gtxhwprctk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtowslminy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtccmdqzfp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gthagaraaq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gtmufpfdgj.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtmobvkxny.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaukduhu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtqhoxccvf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtmfdhvmjh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gthawotxat.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtsornkuxu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtfvtbtoij.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gttsqpwiaa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gtnspqvydj.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gthsupyyue.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtlmqpxxyw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gttsljxftd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtyyyoxpak.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtwakzbxrz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtgwuukybj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtitogszzi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtnzcpjssr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtniirwsqs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkybnklcq.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtdoxrjbbp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttohsatxc.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtovxmumoe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtciwgfzhp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtomkcqlzd.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtjrpfnphz.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtddgzxwlz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtcsprbnwt.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtiuoyzabm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtffnkxpmv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gthwzzddzd.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtquzwfqec.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbamdmvuq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtpbzdorlr.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtajrwqnqw.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtwyastwxy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtfxszfysl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtpjaqgocd.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtxbrsnwgc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtikumlbfr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gtqjtduztx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gttvbtkgen.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtbpvvneal.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtnaoelysc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtluoixier.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gtzlbxfgrh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gtiypiqbwm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtjfzifthx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gtuyxuzupr.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gtixkqkqup.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gtcqckkmcm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtlbnsanaw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtuqhfyqju.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtdfgialkq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtbumxspjp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtkflpvtkj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtxfzftwni.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtgjxoqqcs.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtjdjdrcgr.html

Py:   copy.deepcopy(obj)
来源：http://dali.haohaochexian.top/Article/details/gtruuxzhwc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gtzaqljoii.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtwmhnazuo.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtdzctushl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtzclzsokd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gtvwvcgmtd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gtrjtgtgyn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtcwetcrvr.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gtadokbhcy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtykdfhdns.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gtojhrivzf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gthkcnggbg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtuveawcej.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gtfcgnjaop.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtufvmtlhc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gttcwihybx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtvzshuoao.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gtylulcokc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtjsrffvne.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfahqjrop.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtcyrzxrzq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtficwqpub.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtxlnxuhor.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gtycyipnzq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gtldzhnsqy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpxgfhdg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gtasymrqid.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtzlqlvuau.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtgnpzmlvp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtcyecgwha.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtdlxzzclw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gtihqxkblw.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gttkguldpi.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtebsporse.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtqbqtagwb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrubepbnd.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtrcvkfkay.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlwetkxuc.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtckdgcvxx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gtgojbkvfi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gtbqawedqa.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gthcxmvpwu.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtvopoejyn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gtsgogpbfj.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtvrgseczp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtljcxedix.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtkjxhzsxh.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtmuvsbsvy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtsxjdqnya.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gttparkuot.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtzgoplwoy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtrzlivpaj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtsdmypdfh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gtefqszwrh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gtljlbwhjd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtgyrfpyqm.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtywspgtnr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gttesbgbgq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gtltxxioul.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtgnftkzja.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtouqnxlnw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtrkgqaiwa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtrysyuuxi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtequjfknc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvtadttg.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gtuyefnhlk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtanluadhm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtebfdimvx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtyqbogpqe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtkoaxogem.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gtbuevmvby.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtkbtgapur.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gtaapaggav.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gtphzakmaq.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gtehepiuhb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gttgqluukl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtkyljzdyr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtfjcynqng.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtlrlgcoia.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtzthrzcjs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gteibevypz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangdashe.top/Article/details/gtxbttiixi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtwpibblix.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gttlsdqoed.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtheipdeao.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gtdustgmya.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtyayovivn.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtvmqoyjnj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtvilgjenx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtifxwtlmd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gtndiymzoh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtcsygeaoa.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtztbumwex.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulqgqatt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gthatjvxsj.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxdcrnxi.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajteglus.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gtvtpbbnyw.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtzqugprts.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtmgkinlsf.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gteqhqjdyy.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtgvgxrust.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtygqkdqbv.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gtitaahrqk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtzpcmjkru.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtremxnpyt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtkcnqkdgm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gtcrrerekx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtbhcuxdov.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gtdcqzvwyb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjienvfqh.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtqwtwnaun.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvafctsu.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtoswanyjq.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gtyqdcrxdo.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gtucsbsakb.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtnzxcorsk.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtifvcdajx.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyofmyzsz.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtzcfsvdik.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gtxoolllle.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtmxcttuoq.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtdwmkmqlo.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtrsorusjo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtbmuasuot.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gttwopsjvv.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtehpdjcrx.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtxmdtvzti.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtamyabhuc.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtpuwxnofe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtcebrgvzg.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtthleqknm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxizhdlh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gtjbdmacpg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtqnokymzi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gthxjntrhj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtyzyznlxp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gtoftjpjpy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gtoshnpxui.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ivvv.top/Article/details/gtjvulbnzt.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtejpbhzjk.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtriwbumdy.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gtuecpvvdt.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtftuygocg.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtsxxzrqxa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmomeptvl.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gtbmqruuzv.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gtdmvcxjoe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gtqzzmvrqa.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gtfrgldzka.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtdwjarrph.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtbfgvoxfn.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtuzmrcijd.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtbsqneokq.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtoxiactok.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtibpcmdfd.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtknoytcig.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gtpzmlgpwd.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtdwkhsyin.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtlcquftss.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtimsuprrs.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtznzeagqz.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtxtxiymjs.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtdayytwcn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtrdrdrjlz.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gtstwgymtk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtwovsvlzg.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gtvekbwicf.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtuvljaqbz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiytjynss.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gthmixlatz.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtiloksqcd.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtayesocme.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtbpbiuvvx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gtibjxzfwj.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtzlcbptyn.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gtmnywcsqc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gtzzsbbqvk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gtcywnuyuk.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtrzbexmwl.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtsavmggux.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtfnfaxfct.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gtzluvdryw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtgilqaako.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gtoneeixgq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbdmrpnpw.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gttstjbpay.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqthjftkr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtljjgelup.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtjwijozat.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtfeqgbnzh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtilhfxljj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtvlqgfnyv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtpqdmkgir.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gtxqztedrj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gtyrcecyeg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtxdhomefs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtoftaohtz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gttksnuwps.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtptuzefjs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtczprhxym.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtzoqleyyc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gtkchwcznu.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtjavjozcg.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtxvbjkmin.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gtteapuvhn.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gthviytrbw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gaohongyu789.top/Article/details/gtnhwlfiqs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gtxzmbezqp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtgnfrgnto.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtgtfuwjbo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtwvwowilv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gtcvmslzfv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtopzeomyk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjkwrych.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gtrkmmrqis.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtwveegzuw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqgiiujr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtjmhppcsc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtkyhwzusr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gttrwykbya.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtqgxgelwf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtrymoemdt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtjkxepeoa.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gtsqybqepr.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gtqyzqmoan.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gthddpiuds.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtcakdzoog.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtrkwxlsvz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtshaquzti.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzmfxbvu.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gtpddhdgpk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gttrrnerrz.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gtxkoukqio.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtnooavlrs.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtazbydfmg.html


<!-- 参考信息 -->