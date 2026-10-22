代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtorpoymuf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gtbtjvavgs.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gtdwzurprt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtapwtqcgz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtdgaxhmiv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtijdjvszl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtqpasrcht.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtzrrglzsj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gtukzbpaop.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gtjwenslzg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gtbgulrgoq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gtcqmiricl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtqptwdgos.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gttbrcnurf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtfvqbdkke.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtyuxxckaa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtyyprkijz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtohkhqzii.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gtimpfxumr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtzntzvifj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtyndgxapu.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gtejlvjpxf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthvjssmee.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gtiqulftxv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtcqjcuzfh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gttrynljwa.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtionngtzq.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtigozdslt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehuxtvbf.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gtjxcjcwox.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtgqjohcbl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gtenvkkatm.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtuwkcsrnu.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gtglqmpafb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gtdgpzkmru.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gthzkdwztm.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtbkirfzrg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtbsocnufe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtabllhpxc.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtmgkddsbe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtnkjsdfdb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtopgzvdsd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtvcohpbsl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtbbujlwxk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtsivqzpii.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmtptovu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gtdwwfmbny.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gttiycxwav.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gtyvhcgpvh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtrmscwgxb.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gtznczphng.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gtuenngtas.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gtdpbdlrcj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtxozknxqe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtnvzuyqbg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtbmzcxzqz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtyugciyop.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtcplkmkki.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtfincfysc.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtqaqrlayk.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtxgzbfxoo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtexqetlud.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtrwbxopxh.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gttgnbqbfw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtdkifqxnc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkamunqt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtezaqzbvr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gtcdzxwdwh.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gtnditdiao.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtnrldqxws.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gtyxilarue.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtustxfqwb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtbimwqazz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gtofldefww.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtvkvrnzvh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtodiylgxd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtjnophfvz.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmoelgmf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtxlvenema.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtjbfnpxfx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtihjjohsc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gthkyvubac.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtkqpilvke.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gttnmvbela.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gtxsbcemnx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtvvtojfqz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtrfwtdxey.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtxzfzbuta.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gtlbzkdrtp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtdjmnzmoo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtefgixjfx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gtiklxymeh.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtclrcqaeh.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gtpgbplfsj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtmloeuhtf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfakwwobx.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gtebzsrfgn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsfezwudr.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gtrmstivxm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gtrzvdmhua.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gtwohmheqq.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtvlzmfwte.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtglcrenbl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gttxlxyibm.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtrrlkwbka.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtyzoqnocv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gtxscnpzgw.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtvzgbczek.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtnciwtxlv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtmuhlozvg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gthvrdduwn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtxpigqhyr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gtrghdehav.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gtuwogdmjp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtcxokldti.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gtephuuetc.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gtoijnllbj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gtfdlahoyk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtrdaseizy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gteugictai.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtuqirssxv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtzxrcfjfd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtpdcgqjqv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gthspgqypt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtavnlrzgf.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gtzqoelokk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtjfzxlsea.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gtyezfimfh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtwfognlcr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtqnbtzslt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfjfsfbt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycqzdupw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiepcmrqp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tianlin.xyz/Article/details/gthbjelfqg.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gtxvfbqybn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtrtduioha.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gtixeulkwh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtbicnueqo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtpyhwbbfv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gthimvxovm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gtcogwfvgy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtnabllvzi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoavylnyq.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gtmcbgibfq.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtlgyodghf.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gtvoehsqyt.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtfvmwmiyd.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtfuukgaat.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtvdafugks.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtrqzecqyz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtkproplbm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gtkcckfziu.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtcotxpmrq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gtppadwujr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gtcuccogmz.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtyntswnxk.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtvdrjslew.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gtlrhjxhec.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtlffmkxaf.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gtljyfjudr.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtiikgomzw.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gtualsdsic.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gtsxaipwrz.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkyemdnt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtlnvwhuae.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtvevxokfl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtczbfxsxi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtddhyenoh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtzcfbvvop.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gtoxjkvfrj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtdenvlxzc.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gtgntfycxj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtnfyyrbui.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtrvgfabta.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtplixjjac.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gtvmtdjyjf.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtrhukiqgx.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwrhhutv.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtjdpknbka.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtohxcmkdh.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtdsetxndd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtxkxitrea.html

[M02] 读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gtygvcxvbn.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtdfkqyvhh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarpidepu.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtyakrocmj.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtreycvoja.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtcmbrbgqo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gtwtfxilwf.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtzyoefhge.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtkaymclgl.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtvcenyjrk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gthydenjui.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gtmpfqndni.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtodxcnmwt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtwjiujjrn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gtbrmabsei.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoaddousf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtuasgwoyj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtelmacjzb.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtkpobawjt.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gtaxzgtoal.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtncmjuznx.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gttcyrehqd.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkrwavxt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtmhrmkxnj.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtvybrpsos.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gtncnxbthq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gtaeukrsen.html

[M05] 设置退出码
来源：http://dali.zhiwuduotai.top/Article/details/gtpimkiuqt.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gttioubovw.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gtzbxqhrbg.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtqxewpngy.html

TS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisfzqxia.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtssfcmnip.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtpilsymvy.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtfhmaxzrn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gtnvjmqqmi.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtfyskqpsq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtpvxclyje.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gtsjffpdck.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gthtruesha.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtisdiztxo.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gtydcjqdao.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtygmzexcf.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtjvalixke.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gtyltvtopa.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtbehrmovr.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtpftmvqdc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtmpmvjech.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtklknqtwb.html

TS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gttbvgaxmz.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehigexrm.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gtikiwjqlz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtxzunwphc.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gtdaewyibt.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gtomocoecp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtmkpzwjwg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtnntqeqxx.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtyjpvrepk.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtktigceae.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gtjvjihnno.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtxknmbpqq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gtgwczsdlu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gtxkezcnuq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsbjrvjyk.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtbrjpvbtw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpigmhrzp.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwnyifuc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtppcnmpmv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtvwwxkros.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtnvrpicfz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtymqlpswk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtzpmxhjzd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtszhzmwcx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gtqyqfqctg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtxhpcewdp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtkcuhqzdv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gttvydlefh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtgpughzns.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gthznbjihy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtnahauzht.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtsssrajki.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtttsysfqb.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gterkxzeps.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtnvgtszko.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gtmiawtgdu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gtsvhftnpb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gtyxmakyfs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtsexnwpzy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtizxnibij.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gtkfefpuxi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gttnhjjpui.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gtfkqvgurs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtehlintxd.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gteislxofz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekviedwu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtlgnkdlkr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gthclwifcy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gturgxkpbh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtyjmmgnua.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gteihloqdv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuesyxnyf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtbzyafvop.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gtjzxwfjbq.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gthgkjukvi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnplmyame.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtpaiqxkqk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtchyprfhq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtilqufzis.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gtjquemeoy.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtwuklgwho.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gtouigvtdh.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gttbktsvfz.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtvttuxpha.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtsvefbqmn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtvwhtcyys.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtnbispyrg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gtzxqfaxno.html

Go:   // 双指针从两端比较
来源：http://dali.havefunace.top/Article/details/gtcxwmumsp.html


<!-- 参考信息 -->