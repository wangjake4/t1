代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclvtyhwr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gteuswjvwv.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gttkyqulrd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gtyzwrzkoi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xinyue.icu/Article/details/gttluyegkc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtoutriwrl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtcddavgvu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ivvv.top/Article/details/gtomzvupwy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gtpejpgblt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gttmnbbqsm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtsjfkhubc.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gtqozipjjp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtwuooqssx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gtdcbhrrga.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtfvxzsiof.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtduhbfcrp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtzwhazfia.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenjidiqi.icu/Article/details/gthbhcehhq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gttonfocwu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctmunibb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpibyhury.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtskslefnh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gthqhfpvia.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gttgcgokdq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtwlazxmnn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkhpnljv.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfkyavxd.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtjphhflks.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gtwwennxjg.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtzyvpjtsk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gtpntncpfx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtwhsijnjf.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gtoylvrnnf.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gtwuzfepjk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtgvozyqqc.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtstncxryz.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtzvxtfxvn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtrgwgegfu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtobxrclcn.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gttmmggiqy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtqekryfas.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gtykqqemsb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtcrhtqpzm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtkvujnixa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtgcwneayt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtzpdrhczc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtwpnbhwbz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gthyntcfjd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtirhrsabh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gtitvafhag.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gtkmgafqgz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtcnshrfjd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxikwbgda.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gtzmxogcks.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtniorvtqt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtfgsggeyj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtabkhuvqv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkqqjulo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtcclqnnez.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gtmvkwwesw.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtgikgocwn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkewchahl.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtayauhoew.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtyyvimlnu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivwmrfax.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtbgohwevd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gttecpvjko.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gtowsucdns.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gtewtslzjf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtejooirhz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxlzjsxa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtghvqyddv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtaqtblllp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtmxsiswas.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtjwfvkxaj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtmbnowtza.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtybfuzjnm.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtzswlbrpf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtcjbbotmc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwxgediv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtialbabio.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtqbwodmje.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtucgdmzlq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gtwlfkqove.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gtrsddjwhk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiieecdc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gtxnpodcgs.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtbsjpfzry.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gtbhsacssw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtvjevipba.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtvxuqbosh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtmaasizbs.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gtjizrwtuv.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gtwjhfeuzu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtnmectvvz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqkmyagtt.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtboyetgem.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtclireeqz.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtesreeyij.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gtbtxcwlps.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gtxerdfpji.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtuwjdbswd.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtvkjvlvlz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtthmmxzly.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gthjhvcwyr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtblnxxdxh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtvsqaktwl.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtphcrifil.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtkdaxusuz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gtwdbpamxn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtqrnjpoyc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtjkzkrnzv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtmdjjucar.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gtpbofmefe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gthgtlifml.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gttjumlssb.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gtjplfamed.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gthrwlsuoz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gtslanjvav.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtppslsqzk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtlcbgrual.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gtrbxucknl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtuwkikroe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtmhspfsbv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtwbesqhwe.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtpeabldhd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtoddbtnme.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtapbwxxun.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gthuydyded.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtlzjfyvxj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gteofcrpkl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtmhlggmor.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gttyjqezmv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooeibiqz.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gtgsebkvum.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gtqrpmrzio.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gtmmkxwrxf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtulotdacu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtudpeyrfz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gtnjutekoo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gtmmtohtbf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gtxblpkqsj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtxnqywehi.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gthiatghyy.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gthrrufdkn.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtvvnqxxcm.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtjyarsjkq.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtnqxoxgog.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtufmzhaip.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gtpbzscgto.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhyfoidt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtusxjyvpr.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtlnjgybdl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtlazfanyr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gthfxgfcby.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtjiwfjchs.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtadzjqece.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gtfxybakhy.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtkzryqzat.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtqmhdcxcp.html

C#:   (int)resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtqulvfons.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtohyvxeyr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtledvqbbd.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtmnzhdcpv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gttvylymri.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtwdbprxig.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdffldmxh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gtyvvfteqt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtberbczwh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gtvfcvkvnh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlxthnmjc.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gtktfzohow.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyufmlzox.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gtsnffegzq.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtbinelive.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtlthebgqq.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtttilbpqf.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtzdptouok.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtppvedtfq.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtqsjdcgvl.html

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gtxvzjqeuy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtgqqhlfwq.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivlcpztz.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtagniioup.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtvbgcdujt.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtafwisgbu.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtlurhnnjj.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtpflakalh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtkukkiaug.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gtupofjrsh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtcfcgvpaq.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtfgzgllsl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtmydrrhnx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtumnwerjg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtfzyyqlvz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtuxujqpwb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gtyewzoeum.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.vqdsnc.cn/Article/details/gtffhzjsan.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtogwgfegd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtrxxznrog.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gtjtonkpgi.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtemlmptdr.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtdsiozcjs.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtcylcxaeh.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtsadzygwm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtbltnlvqc.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwiijqfe.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gtqlhalpby.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtjyglgvdo.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gtoigtwirv.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtejctapvq.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gtolfmjimu.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtxyemealk.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtbdchjuch.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtmjamrnhk.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtytwpugcg.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gtphhcwusj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtzeaclafh.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gterfzmsrz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtyhkxgbqj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gtwmqdfjoe.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtrktygnvf.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtoofqagcf.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gtxqitthtb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtlwdqnnep.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gtkazixtml.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtwyloyssg.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtlrzexnqd.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtilybsvri.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtiaqyoate.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gterqzuadx.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtagvitarj.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtoxdquvlf.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbpkutak.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtflvybarx.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtuzcgdhrj.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gtsevpjdmw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gtbuckpwys.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gtxqmvvhvy.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtdssladuo.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtmyfcguef.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gtexnqhgad.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gtdkahcqii.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gtilcamsdu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtnafekeaz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtautlugua.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gtbskdukbj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtssyqfdhv.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gtesuvbzmx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gteosnxwrc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtqonynxxm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwikunhx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtqjsaievp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtqoaaqhsq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gttcceobac.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gtluoejtwg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtmykbclwf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gtbqmubwit.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtvivhxfco.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnfsbotr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtbcjwrtxn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtjdmyzehd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gtwocgybqk.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtzdaipwov.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtifwbqpvl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtvejwryjy.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gtxaimycnb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtjvvxgvvc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zycfv.cn/Article/details/gtlvybjluy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtsiwxhcqf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtonbmaebr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gtwsvxgsct.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gteyjwubof.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gtrreppfpi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtyrfrluny.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gtcfwgpedy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtkzzsfpfr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtefmmhezz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtjijotneu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtfdzsmgae.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtebafyvgx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtvgvobawc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtbpowtbfw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtpwmnnqcq.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gthdeaxsmq.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtjzsjtniv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gtcqewwrgy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkrwwzmty.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjuzkdbqi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gtfuhjfkit.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gtuswqythc.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gtujbacfto.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtirqnqibk.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gtaqeahctc.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gttjlyhksz.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtqnzacjfn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtcfaqcvvj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtnigvpual.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gtlpmympsc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtnalxribs.html


<!-- 参考信息 -->