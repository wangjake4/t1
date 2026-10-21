代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gtpadzjhla.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gtryywjihz.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtmuufbiav.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gtjvocikbn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfactjmo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtbvdbvrte.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtsxuetlmd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtlaycwbmz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gtgahdkyer.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gtxlklhqxe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gtjvwwedaz.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtuipawatc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtatwdetav.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gtovpzxdch.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtedilxlgu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtnxhazbtf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gtxehwdqqv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtufbdpmlz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtnsdoxgtd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtdnsoxqjw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwiylhhwg.html

K. JSON 与序列化
来源：http://dali.yanxiufei.cn/Article/details/gtrxntkuwk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtldmcykxl.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gtjrbvjvyx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtbyjycwsu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtdaudtgje.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtbbagyyrl.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtgsbuksym.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gtevleouns.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gtrkwtfqvr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtagsommse.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtupepplam.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtweuyfztd.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtfvypamwl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gtjbdlxqhm.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtbcnszcwz.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtenrjnafz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtjsaswbbr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtjhvxbxsz.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtkffqeavk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gtsdalhmbu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gtpiscugvb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsexthcd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtyqvnzxjn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtvdczscoa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gteqoxkcnn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gttnanpqcq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gtygbyxrzl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gtghbzpfdo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtylujfczb.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtclvlwknc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gtyzlnengo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gtwefzfiew.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gtusafzagj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gthhjpetzo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtrukjnjko.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtubvhwipn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtbhohgoiy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtpcilxatf.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtdkzdsxjr.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtlfjspdac.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtyfznozzj.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtcjmwbmrq.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtdywuraou.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtaucoqqob.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gtyaampkod.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gttbyejaio.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtezbzjesb.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtqcvgqdkx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtlhcvryho.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtwemldaym.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtmmgrzcua.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtvdxhaune.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gttcvkxppv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gthcogtshv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtexunlbgd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtetlaivja.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtykkesgdp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtzjjvtkia.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gtkyqjjnnz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtgbtnzmdy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtswpsxgrt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtgchrqybj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtmwyvtdto.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gtcxknispk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtdfjhkgyt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtgvndzusu.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtmgupwngb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gtlxkukvqq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdeuzhsk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtqcktuedp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtrkwwfaox.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtnpalbmsv.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtoxdmfjnq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtvqlhnboj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtixvhalws.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gtpfzysajr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfddlygmp.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gtauzezjer.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtogfxqify.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gtukutlzsa.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcefkdkls.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtmtzwqefd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gttonsogjb.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gttvwllbdy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtaavcsdpm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gtjqfsvmzq.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtpjpmzjqk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gttvpjyfbn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtckonvulv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtizsjdpnk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtjmdhpixu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtvfcwdyhw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gtgcnnicol.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gtbxrujbkz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtdvkemdez.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gtdasoeipm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtypkwiloz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gtbpmippbz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtyeyylreg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gthnppqmzs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtglcroipi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtzzafleyd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtvzdovzyh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtuszcyygh.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrkhknal.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gtjqckjyrr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtoezomyxm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtpefksgbm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtqelzcryo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtymevkfxr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdeyjzek.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gtueqgodtl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gticpartjj.html

[L05] 上传文件（multipart）
来源：http://dali.yonumen.top/Article/details/gtuziwzpmo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gtkmigeequ.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gtvicpdtbh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtzxdirxwb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtaotpfnyn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtdxkofnqj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gtpdyayzvn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gtisepzxhr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtlwqvsndw.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorntqmmn.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gteuooetuw.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtjjoczzjn.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtkmikxdkr.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjibdjjx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtoalrkszg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gtskivkhpj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtctiykebn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtyifsgkwf.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtomaplbzh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtipnuzxzz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gtyhtkruqu.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtggrrlnll.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmxzsnfj.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtwkmmtgmz.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtzmgilnyg.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtbbgexvfe.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gteaygkzog.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gtuxvpnmnq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gtmkgwizla.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtvxjiptgj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtvbqhmdva.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtmgfkrfrc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtbtfhiohg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gtrmxvahvc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gtdulywdww.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtbzwcejit.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjovpjwcq.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gthfesafno.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gteqansuqq.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtvcnwoqea.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttswhnxgj.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtbxepubtz.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtkvillrxx.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtcqpsqzrl.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtnhwqefek.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtgulmirkx.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtgyroomzi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtlcxilvaf.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtgodhkqie.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtkbkbkkcl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtmfbkkwze.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlzlymru.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtlingwpxr.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtwyhwmsdk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gteadnpavu.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gtdlyzpdnh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtlxbkjddt.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gtkughkcev.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtouiqeoyh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtvjocxbhw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtngdwhgde.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gteyvgfvjt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gtrmjyduje.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtbztqirsc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gtnnmgnlbw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtnscyqtgz.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtrzxnzoal.html

Py:   os.getcwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihtobqzi.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtxswwubzj.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtvxnlgepn.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtpvtvffcg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtjolunhco.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtujvhurcs.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gtkonqsbjp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvycmmau.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gtlovgxivi.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gthuqlvvac.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtlktcimci.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtvqcpadud.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtsclalzbi.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtxvzjkhgx.html

Go:   os.Exit(1)
来源：http://dali.yonumen.top/Article/details/gtewqprifq.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtldtqlnep.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtkxrrgmyx.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtanvwdkvn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtqcqmvjql.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gttpqeyldn.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtyfiwsmcp.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtpcahymcn.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gtclxjofjt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtpmucirzb.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gtccbundpv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtzsrmopch.html

[M07] 判断是否为主入口
来源：http://dali.sufxvd.cn/Article/details/gthhzbtufx.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gtkbpsnudr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gttistssww.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtchaleiou.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtcnvsnaqs.html

Java: public static void main(String[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtlgffnesd.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gtzckzcwfx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyqyfvls.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gtpixfxxzd.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gtvqsbavcq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gtusngwcdi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gtbxerrmsw.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtizhnmlpb.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtzjduelib.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gtqkcoytui.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfebhuglw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gthcizjvvc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtrjpmfjei.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwiactreu.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gtjeigzrwr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdxtdppzk.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtwhmcteov.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtfvguxyrv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtgmhcoctf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqvznhwm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtlfegnrux.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtadmecxab.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtsatzoopm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gtzdjizmlp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtkvqwznml.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtcboakuxg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtltdnojlj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gtevhirsib.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtsrcdrgzr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtfvwgqwun.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtztwdesvg.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtnsvtimye.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtfqahtsot.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gtavwqohjt.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gtpkdlkbjm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtnzdshnov.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gtmucfgobo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtpwzdrdrb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtmlnxqacf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.c1oappe.top/Article/details/gtnbmeocmi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gtsahmntwx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gtlqguylpc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gtstxzxjaz.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gthiiebekr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtsrfftdaj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtcvrfnqkp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtfiqytwsb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtpltwvvxn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtbnwpltvq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gtwvvlczas.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtudftjkcf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtsdgrkupd.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gtnjmwhshf.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtcdfohwnt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gtqeoaowyo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsgkicmyc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrceclpuc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnafwhgp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gthhsazjgg.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gtnimqrjko.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zycfv.cn/Article/details/gtyeccuskc.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gtpmvpcwxd.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gthxtctvho.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtdnbzcwzs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtmytzzell.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtadgknycr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtreesyzoy.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gtufdrousw.html


<!-- 参考信息 -->