代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gt2eqjzitvg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gt2msninefc.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gt2cbxlkqcx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gt2wrsccjgw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gt2ijvfrave.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2lsgeodkn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2cvplocis.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gt2vldbtcus.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gt2ohysjigv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gt2xwymrhhi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gt2ilcolnug.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gt2ictuiiwx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gt2mdmxcwfd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gt2uwouzpvx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gt2hcmkrrsg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gt2ockjiudc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gt2ytrfceii.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gt2gjqvlgrj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gt2zccdetwe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gt2nzxtcljt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2wsgycayq.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gt2gcuyntbn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qncwmiga.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gt2waswwwpy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gt2jfxsazkc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2czrtqnsm.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gt2wjibpdon.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rohiajty.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gt2ffdowwgw.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2giwgkabn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2peereefe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2ftlhvlyg.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gt2edkpnhqp.html

Py:   json.loads(s)
来源：http://dali.smart0.xyz/Article/details/gt2jymxxthl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gt2jfdqxdrl.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2sxizbkkl.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2raacefha.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2bowfiuvc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gt2tskgktds.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2byjzcszf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gt2hyrthprm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gt2tljrhnbt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gt2mfmafpqv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gt2jnomumqo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gt2zjwnyhze.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2wzjewuug.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gt2recvmgxc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gt2uvoiozkl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gt2sazbjiqd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cucudq.cn/Article/details/gt2ojrccgqi.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gt2cdbhodbg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2slaqiagz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gt2wocuppuo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gt2hhsczmkb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gt2kzlythrk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2koeouwep.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2zxtxocbx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2wxqljeva.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2klnifplh.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gt2pagbdvhv.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwexqlvj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gt2sfpkjueu.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2tsbuuksv.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezwcwwhy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsirhbho.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gt2aqpzsjyx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sweek.top/Article/details/gt2vbobeepf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gt2ghsamhfv.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2nezghdsm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2nduhemid.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gt2titiswyn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gt2koipbsrg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2mblljgwk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqhbtwnv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2cdklabgy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2tsuyfxpo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lubwxism.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gt2ilvjjeor.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lsoihmum.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gt2iwzlnmyh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2zxbstmzp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2oabmvnij.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omblyzbo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gt2hcqkeqqh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2upusfzzy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2mmrsqeqv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gt2yzxthmau.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2mytpgwcu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gt2urjnzhtj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2enpyonoj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2zxfpakpo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gt2svveepjo.html

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gt2oynzdeiv.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2exwuzcjm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2vofaebdt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2izcacjdp.html

L. 网络请求
来源：http://dali.smart0.xyz/Article/details/gt2pfhzopje.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zoettdpo.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gt2buxpgirb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gt2ydwkqunt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gt2lptzxeeq.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2ezwxoojx.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnoeuzbx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gt2vtahzkdi.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gt2qqpiwqpx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gt2bhxmhsuk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2omcprgok.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gt2yjpyhoqd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2jwhpddqa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpbtyjcc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2htxaohud.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2eniomqes.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gt2wzvqabun.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gt2owxnycep.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gt2ofjcsvpd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gt2buygokcq.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gt2ihultufc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gt2syxvefoi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2yyfqvbmx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2uneglhbm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2belzrjuo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gt2dwdlyypq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gt2qwawfydi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gt2ibhmmpsx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2tkyyizyc.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mumfrmdv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gt2kmagbmax.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2duhsntxq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gt2xwoluidn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gt2wwgteydr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gt2itmlywuj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gt2duzhepdy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gt2ymxljhpw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gt2dnshfzuy.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gt2fqflfhbu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gt2uxcyghgl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gt2bxmqseng.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gt2emneokkh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2ttrcojof.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gt2zljvudnb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gt2iykuglgb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gt2uhzwrplj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2vvwlqyru.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2fctoqfct.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gt2mnthouwy.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gt2pzermbvr.html

JS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2tqpakxfq.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2nuzjvzap.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2ozxzxsxm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gt2idwuymhs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gt2bqviawds.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gt2llxqlkps.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2qxkuxxsw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uakcgnkr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gt2nfrfyugs.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gt2wlelfkrq.html

TS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpnobiqw.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2ywdmgjiy.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2bsqpygvy.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gt2uzlavoxs.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gt2gmjysdke.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gt2mkjrozml.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gt2kczrhnay.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gt2bgeybfno.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2clwomjpk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2qfxootcf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eelnbzya.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gt2ckqtjkhm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2locxxyvb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2poydvwhg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktvgmpnj.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gt2ulscsauk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2inyqvvno.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gt2gfvtrvax.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gt2kzwhzfpr.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gt2rrljtlui.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bydpisob.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ertczxol.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2uzuotnqx.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gt2uqebhlwa.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gt2ohgbndtw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2islftezq.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2ichrhhyi.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2pmcdsnjy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2ltqjcidt.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2qgqinigl.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2jlzacupx.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2qfvhzbkw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2flnxrkci.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2zqglmjyj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gt2ewyycjzk.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gt2yicnqkef.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gt2aazmkzep.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gt2wrubmahm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvaxxgmx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2haavqepj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gt2lkzdqjry.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gt2durhfaqv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gt2pfhlpnra.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gt2swfsbmxh.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gt2gefcyqpn.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gt2lhpeinos.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gt2gpksghhz.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2sfvpcdie.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gt2glwjdumf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gt2rvbiludp.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gt2goutrxpm.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gt2xfevjyxt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2xlzmfmop.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gt2mmekqseg.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2llhqaoyz.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gt2ekmapkes.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2wzaaugzf.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2fexsobra.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2cqqheyna.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2dpxainmc.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gt2dargpmjj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gt2lddtsgeo.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gt2cfcyfbvd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gt2ubxopsng.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gt2fknfolot.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2fzytxkan.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2xfbqszlv.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gt2gdciehoj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gt2yehnoxsb.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gt2kzisoooq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gt2dzccpvic.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gt2kcgrtlmi.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gt2yahcopja.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gt2atewmljv.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2qgsmmwcf.html

TS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gt2mpjjscpg.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqxiihsj.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2drvvjjrp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gt2repbwhkw.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gt2weavipet.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gt2kgqgnnrv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gt2gvjhesvv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gt2mjncztsn.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2xyxvaefq.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2jwyfshqi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gt2dbruvtns.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gt2etzaceyx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gt2wwwiwcgd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gt2sogjqtgz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2xkiaqdsn.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gt2hgfklebd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2vsiujeeg.html

[N01] 二分查找（有序数组）
来源：http://dali.hywenlv.cn/Article/details/gt2ngmkntlj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2foxlguoc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2dooksdlh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2amtsacbf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2zxjgblyl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2pjbausdh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2xoywouqc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gt2xmxrfsfq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2wcxbfpbj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgvtjpue.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2lgltvxrm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2fqqosalg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2cqxovief.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2laglvahg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gt2qwgmeige.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gt2qjcmnflo.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2lwbnjhlj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gt2zrjjssya.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gt2ffifcfuh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gt2ojxdpczj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gt2ensuwtpa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2yhdwvghm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykphmlom.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2iwraxaat.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsgyoagn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghxdmsap.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gt2gmmbniao.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gt2wlxajhyq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2brvixmpk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gt2mwqgtvey.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2vegsdhef.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2xwtjisnz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gt2yvsgkfbr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gt2fzpismnp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gt2etgqqfrq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2iioivkzl.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gt2hwcxaeqw.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2cxenpkaw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gt2pzvstbqg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2oejedwhe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vfytjsyr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgufenzy.top/Article/details/gt2mieinuqb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdjqwhos.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gt2lbcviczo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gt2vdkphwod.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gt2ebrdkykt.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2wijekpxw.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gt2ygkwkwfj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymlvhycn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2lrsunyga.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtiosesb.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gt2vkuhmxao.html


<!-- 参考信息 -->