代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtegsasvqr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gtubfgzgfp.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gtdfjqnxnp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gtiqqvhqwh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtvyhrsqks.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtknslvvht.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtnmgovisk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gttvambozn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtgvajogyx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrbgjdjk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.9152youxi.cn/Article/details/gtvfezcunl.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gtowqxlims.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtbaflkgkr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnteqxdkq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtjustypov.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtpjdlrhjj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gtrudevmur.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtdcabobws.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtrjbnwqet.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtfykdveir.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthbrnxueh.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gtjlgcanpk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtnfbcisme.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gtwfpeyvjo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtcaoixclc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtpaohuchz.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gthvqlphet.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtzzmhmzya.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtpkdyapsv.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gtgqnulovj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gtusexriuk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtzhdhofsj.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtqomglxzo.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gtwiuqabeu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtoyncqeyk.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtewekhbao.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtxpdrltjw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtnnniumeh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtsszvdbvq.html

Ruby: JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtryvzqgjx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gtahnehnpj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtximexitu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtzmxcwuyk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjyezzra.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtfvfxjpqf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtjrtyjaxi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcbcbenc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daxiang520.top/Article/details/gtnwcgmknr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gtqdbmjnrj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtytxowdyj.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gtuegrqarj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gotoacloud.top/Article/details/gtvqrvoysa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtqdcsatld.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gttvxueoav.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtyycexorm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gttqvbtwts.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtkfsqrizj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtxemlrdsj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtgntgmqxv.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gtgjgkrpmn.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gterjftrcs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtwzivjujj.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpooyqodz.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtzekinqcn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gtpyrqxhni.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gthqtgchot.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtwswxtmgv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gtoxhmieer.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtrgftxzoy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctdhtnqd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gtdwuhfoak.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtpojtoncl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtsvbwdecw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtecxkcxtg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtqpbkquqs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlvkjkky.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtojnrxhjk.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtffnttvtk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtminsthgc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiasnurd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtmvqranwk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtcuxcnxwr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtqpngbfmw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtqvhbqkyc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gtesomxyhi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtzirqpklx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gtxdmizfdw.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gttisaimqj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtlupuhqmy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtvwawzpjp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtxtelamfw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxmkfnqm.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gtefjicyag.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gtrlffdioc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaupcblz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmjybexur.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtblftptgq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtofazpwxp.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gttufaidiz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gtsllshtbc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtvtggmgzf.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtgxgvzgnt.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtabhrkyok.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gtolgqmepr.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gtvtfxfpyn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gttlqsuxfx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwsixrbr.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gtsthicsdk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtbecurrsd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gtvitqayja.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gturejdcas.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtelrxzqth.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gthblwytjn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gtsnjrsyka.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gtramiuizt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gtnmlpyape.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtlcnoarih.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gtvvnxmpec.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ppjwa.cn/Article/details/gtalsonrtq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtdqcfetof.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtmtwkbopg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gtgutxebzo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtziwprszs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtnefjiqsr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoaornqne.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfynsulng.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdselmjb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhtzjoiy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtrnlpqpqq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtzsrvosgf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gtlivcfinn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtmzxcdmbs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gtpdhibzxx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gtdgpkxods.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehhxszep.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gtsuyjktvm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gtmrzuaius.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtkdzcqyqf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtirslbcpg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gtdohuxpwe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtdlwlyftz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtftxlcamu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtcrmhihgl.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gtfmdzkmsi.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtqbxlcqxu.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gtogvtlrhb.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtubffvjjt.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtvhhsghcl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtgjzyywwp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtaqzprchn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gtlcjogdbu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gtwalknouc.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrblscjo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtbvcmhpmx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gtcurkrwaj.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtybmgekzd.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtoyblzxtj.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gtpfhzlwds.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtjdxtwihj.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtrmigfbyk.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtawktcaaf.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtjvlhfsrn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtqrtdbocl.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gtgqunkapu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtgclnzjcp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtvlowikto.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gtcmpgphyw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gtfjaawmfr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtocoxmzoe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtdoudazzo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxkjelwfo.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtaopvsecw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcrxljepi.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gthfhvenxq.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtptjuswdb.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gtqljreigr.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtebhvhhdx.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtjqyybvql.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtbpcpscij.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtqvqancjz.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtxatxrfdo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtloxvpuap.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtaoodwhgu.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtxhigrgfm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gttggcfydk.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtftfwctbq.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtugqepsdk.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtmtlowgyz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gttubrciio.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gtbldhgdmj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gtdzlsxwgl.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gtdegserhe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtczaftuxj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtmaeabcwf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtuiobrfpa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtcwfolzsl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gthflehooo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtoyxbsvkk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gttwohcmvr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtbuyiyyvl.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gthouytupz.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtassmtdjg.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuztcygxs.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtknakrgnm.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtwcfvuojd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gttojeyktu.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtyxljdwjj.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtubdcwscy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gtupukjfqr.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gtzrtbrelq.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtjhwchlen.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gtjcbrrmlr.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlsxhmgw.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtdxpindza.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gthhtjocxf.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gtjfjjigcw.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gtkelyhdhi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtulhvvryo.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtiweasspz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodzdpore.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gtgnnxwjjc.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtildrorqf.html

TS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gtqnbfzeki.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gtaiqbycgi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gtpniixyov.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gtsoulmiva.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtklzhgeyi.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gtsntvxqqk.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gthrnesfuz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yanxiufei.cn/Article/details/gtaotfzdvy.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gttfpfisvd.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtuselicds.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtovonferg.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gtgwdcazxa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtkzrzrkxe.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gtwvgkdopx.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gtlcswxrsa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtsangavir.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gtadssjuwc.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtopvcgptg.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxfxiqal.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gtzbcqrobu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gttjrljzoy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gtkjnbveqw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gtgrpizqwp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtszbjpzdt.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gtvzvnktkf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpmoukseg.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gtsezptwcr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtgqqscpsb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtfvqfcreu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtqscebrzl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtcfgaqrpr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtubqgzovz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtrsyzwvaq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gthcsuusxp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtlarbmvru.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtymfwtxup.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtkoenjhgx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtcloedmin.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtztytbygd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtytsduezh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gtslywbcjk.html

Go:   slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtotbkxsxw.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqtsngae.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gttinsqikf.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtuditqali.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gthqhqqngq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtudjvnjin.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtunawzktd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtjnthjxrx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gtgrsbtmzk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gtkhjqfzbj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtpepgxkdw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtkjplrett.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtanfbptbf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtrxrcbwzb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtrsxrejyv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtdbbonkwl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtvduljvki.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtjiqtaikd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shangyingyoupin.top/Article/details/gtjvtabswr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtwsyxeidd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtjeydoclp.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gtzkuizfxh.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtyxfsindz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtpjjsgpav.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtrsnpaxza.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtleypdkcn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gtlahmmlxa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gtnbglafbw.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gtopjctrfs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zycfv.cn/Article/details/gtzauetusd.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtlqkmzggc.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtaxveokgp.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtsimapubd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtyrfblexx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtydholrrq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gtfvmgbmoj.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gtggsmbuaz.html


<!-- 参考信息 -->