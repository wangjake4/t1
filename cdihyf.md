代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gtsbtkcykc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gtgerwucyb.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtqtqmhjvj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtrwxvtbna.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gtpvwiaxyf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtvatzmmsg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtrhblxuub.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtrcrqzkde.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gtcdfepwoa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gtzkedjqgo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtiohptwmp.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gtvencevuo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gtbdkytoll.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gtyfbvnngv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gthqnowywj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.smart0.xyz/Article/details/gtekkwmgva.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtreohzybj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtlxmbpvil.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtbvtsucdq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gtnabmdnbj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthumzpons.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtjkzxddag.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuyhoqnho.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gtqlcpfiaw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtlguwppic.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtloyuhvpi.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtbswwrwif.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtxucoocha.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtaaqtuutk.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtaftaubby.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtdvaahdlm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtxljjljbn.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtaucgqeoh.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtybsqnlwa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtdaebjrdq.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtjelkqsbw.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gttovyimlz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtoljxhuyf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtadsepken.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtsyuhjfra.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gtxxvhdtez.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtyblgnkbk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtblobxtys.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtdtumzjqx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gteybosvwb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtztetlglh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gtvjenbbmm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtibxfplsh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gtosubvwic.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gtglbzejyw.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtjhgdfbsv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gthhhttvhi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gtybhobqvq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtczllkcir.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gteackbkus.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gthdfbykrv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtivyxuauw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtezglcflg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtnxjypgib.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtdspltyhn.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtxztkquxx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gtmpxnwrxg.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtyhijfzad.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtfgcqtoxp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzlbqgru.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwkqawxm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gtkvdsgfpo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gtzvpnqvpl.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gtodwjkmld.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtunqdlqia.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gthsiyrytk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtzjtpznxf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtbngolvqf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gtcfccczcf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtslsedddd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtpbjmktzs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtowcvcxub.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gtkitexgka.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtslnonaoh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gtoeqiyibk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbasngkj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtwrsvkesa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gthwyegkyl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtkhtxbbes.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gtvzqqxxsn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gteqttlkwt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnspxrdv.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtknmswbqj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gtmkzeotyq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtpbzmygpd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtmasqbdvv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gttdmrzpjd.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtobiztwqr.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtudikfpam.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtiaxfvifh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtscnmpoun.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtbwttwjst.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtazqqpqan.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gthphijxur.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gtqifydtxy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtrycecizh.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtoprbpdxb.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtxobeyesr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsusrbdj.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxregscs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ydzc1.top/Article/details/gtksuuerwe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gtlshbclaf.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtyuigbxjx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtcaanennk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gtxkzgoglo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtpdrrivux.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtdlqvlfls.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtxjkbpyel.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gtqvpxducu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gtgdzhkzkn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gtevvkdrfs.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gtydfekbst.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtwxuxxnny.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gtofbsutzv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtjiodvrdg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gttoqqhhhk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gtssfvgnve.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtgyexywzc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.316326.xyz/Article/details/gtojszbzfe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtaffejahw.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtfoakxtsm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtntyzeydp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gtwpdthtju.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtppnoeirr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtagefwcki.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvivkckfk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gtwkefufcj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtiwmraoxv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gtpejywekg.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gtfukrnohn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtdexkodhq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gtswnbrvfm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtrrbatllj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtylybbtoi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gtzzoafqwx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtkqnxlkkp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gttrcsamlw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmydgazkm.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gtaguwzmbi.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtgrpzoyyg.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtaxqmxofz.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gttqtfdkvl.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtdfecssdd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtksyfupmx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gtyohunqbj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gtgqbtxcmt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pycfn.com/Article/details/gtwgdwiuxb.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtbutqrfud.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gtcxrppquw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gtgoldsrdb.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahrixzpp.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtgtolryio.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gtfhkwfrle.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtaepdgpas.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gthfendxmx.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gthagkxoxz.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gthtfxqrpc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtfukmxikj.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsqhoggc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtsjlmjuyu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtnafstxgs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gtxjnqhiuu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gtlvgplxnw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtnunnsjsl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gtyfyiioul.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtznjrbwzi.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtojmlycmm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtuudgyquk.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gtnuwnyesw.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtjkotgzfx.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtzsahzgrt.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtyjxkepja.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtfsuqchwd.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtcquuwqor.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtmgdkprtx.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gttedslcpm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtvesflpps.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtojloxjgv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtgqjyhhjz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtirhhtmiu.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtvhrvsbok.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtziajixla.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gttwggkqcf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtbmtcoipz.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gtuhxssnek.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gtlwdbcwti.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkllhnbq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtsgxvktrl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtovjwdyuv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtgsietafz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtmabzqhgm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gtrnprekch.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gtgkympjya.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gtdwawbnyf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gtkgitchla.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtjbykqxnc.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gttgwzvpih.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gtcoekkhat.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtmeoziqod.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtypymoeun.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtiaedlwzq.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gttcdhdjph.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gtlenrntop.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtultmybbo.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtaetgwgjp.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gttoqtybps.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gtdmthahtl.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtbywjutkc.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtzabvkpyt.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnflqmamj.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gtlihkwpfl.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gtdfdsckfs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gtberzwgkw.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtpmvcijyp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtykeigskk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gtxuhwmifm.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoulumvmo.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtwgxttmbm.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzphqliaq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gtyrgnjlnw.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtkdgtxuan.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gtpqycevvw.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gtbqgiqwnu.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtvzzgbnhf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtladskibh.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtgaqxbhcs.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtufbvpxhv.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtgenquddb.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtpimvpbzg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gtxlfkslhp.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gtqogorhpj.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtzsxszrmo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gtyueawmic.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtbqpnkevf.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtscuguioh.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtxqwgvwby.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gttrgkvnhy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gtqcbhwihb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtqanrzaqb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gtvampanch.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtkbqdkdiz.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gtivobfzrx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtryovluex.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gtfngqnnld.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtnutbylyy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtwpkxvjgg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gttdemyzbs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtxdkvdcfv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtowotauuz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtrupgtrmo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gtuqkjasom.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtnufrwhad.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtkhqsdydf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gtvcwidwug.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gtunruwojy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtyewxqslr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtbdnjtgmp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtvmcrvbjt.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtyobjxjvj.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gttsadgznz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvztsdrw.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gtxaefnwdo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtdxoyzgfw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gtmzktxwpp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gteqakspvq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gttwkycido.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gtpsrvwzlq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtgisgvrzy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtjochfhae.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gtegmzuyjc.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtqeeakgaw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtitsxlocv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtcmahrhqp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtmdwxyyzg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcaksfzsi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtinovoivz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlujkpet.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdrummeh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtdqhobtqn.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtfupenlhh.html

Py:   math.gcd(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtwqwpedga.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gtpiytllbu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtnlsnleqz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiuzztca.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gtwdqsoqcy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cdnleiting.top/Article/details/gtludavspe.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtawabpkrl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtxkmkclav.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gtvtlgdovf.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtzyrcquzo.html

PHP:  $s === strrev($s);
来源：http://dali.yonumen.top/Article/details/gtbphorlqt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtwrjiwdtk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gthicaxbcm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtlmpvrmxc.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnxdtnvs.html


<!-- 参考信息 -->