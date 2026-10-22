代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guowangkeji.top/Article/details/gtogajwrvr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtacpcmqgw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtvdmeiscw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gtrshcldir.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtftztcrpn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxhburbt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtlooaukur.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtpahpverb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtryhhezru.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gtvsxygxxk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gtotrevicc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtcqbdwifd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtrnyflucd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gtjnsowaly.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gtsskgnudh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtyjckgbzb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjjadphgy.html

K. JSON 与序列化
来源：http://dali.yanxiufei.cn/Article/details/gteldpxasx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdmacvdky.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtuvbimudh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gthwsxldbc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtigjhwukb.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gttpnmiipq.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtwowpqtgn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gtyhpwjejt.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gteuknznot.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtlrprqddt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gtxmecnwtv.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gtfcntkylz.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gtswuuewyw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtxcvhvayr.html

JS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtnjvibuwj.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtudpezxxz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtjckrtipj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtkufjrowl.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtvdhdpsqj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtykfzcuax.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtsvgyjvva.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtqywtmhmu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtvqvepoxr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtyyhjxtgw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmktdqjga.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gtbxwewoxy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gtksnirlka.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gttjdlhcsb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gtygxcclls.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtgwarxolk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gtpwakiatt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gtwehterge.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtrowmcrzf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtiprdhsvq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtsqastrln.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtvoqurrzr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtugckglzz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtolytosej.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtlhrcxzsy.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtqfqvvylc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gtbfdlqhvx.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtcyxtwlxi.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtkqtmxeps.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtopxjlkdf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gtzqnvxcmk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtkjjknulb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtgztvfujo.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gtjtcxkdho.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtzlqlynqu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gttwtrahps.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtaieaqoog.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtuaxojkfi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtjxvhabki.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gthbnpxjbe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzexcpczz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtlvfrxrgt.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gtflfnnvwb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtzqnpknmt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtkqxhfvxi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtabjemxep.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtueaoohid.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtezubfdtk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gtgbehlbcc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gtqnnsdluu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtjkqopxbr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gtxnsguhrl.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtaintavno.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gtjiwcrxac.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtjdbudvfo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtltujokbl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gtdeqhvfxe.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtgmjtvufk.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gtqisqnyjt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtuzjsukto.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtocspeezo.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gttkfvgnvl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwqfgzuvh.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtkvfsuujh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gtsbgyqksl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gtwsnligew.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtkrgqfbjr.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtipkdthjj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gtllonqcvd.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtgejqrebe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gtsnudtbwi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtfzodqsgi.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gtldsbvudx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtsuxvrswq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtohbmprkk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymalsggy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtpgkflrsq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gtqcwivsmv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gtjslvpsdp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gtuyjfwhuy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtgizaqndj.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gtijxeqggq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gttnhzupsr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gtfjsisduk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtrkuxxmzw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtinmpmjks.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtrbxcvjbn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtfwxlgdse.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gtibifglhm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtycvcmkpm.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gthsxhzwfg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gtcqraonxv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gturxvmrzb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtxbcgbigl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtogfvesyc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtmfkktrnp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gticmzoblj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtxgbbacnd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gtrjpygcsd.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gthdqahgzo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtusaevxop.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtowvkaghw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtvmqvsemg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtepybfunr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gtaawjfgee.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gtnphbbcbd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtiuudfwio.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtwgofpwvh.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gtbzacnedq.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gtkijonbur.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gtgrkszbbt.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtgpyyzctf.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtnzxwsaqc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtoqdqcpbe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtauqrwsvv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gtgbvxnozz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gtavkudevd.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtvgcwqqij.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gtxitmjmwj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gthcbxqygb.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtdmufgoal.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtvntaubmg.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtzrlyydul.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtqlcqgqko.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gtmspjgdoc.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtyravifhf.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gthdiojzhw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtxeimxoye.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gtsxaevqix.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtrzerhrmj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtfkkcvslm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gtistjjpzc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtzelytvzk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gtcxwlibrc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gttbrqvbvt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkynuumvp.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gtponwrxbc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmplxzctq.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtrqldduwr.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gtemnqvdrb.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtwjfohmub.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtobznhwau.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtyuxxsydn.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtpshjmyqu.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtxmuctawt.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtzrvphvpk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtjbihobra.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtqmemqvzr.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtstazacxb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtsttsjzzh.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtkjpoolvm.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtrxviwstz.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtuydonajn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtwvqhpqnu.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtvijfvtrr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtghwposwu.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtrznitksu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtuosssrhm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gtcobosvbw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtmzbrpbkt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtnpdujtko.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtexcwdbyx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gtyuqetvma.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtfdzhqyoa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtcmqrsjgt.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtmfarrdez.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtbdayvqyn.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtsyvucveq.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtaobwusvn.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtointypgs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gthjquiyhh.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtavowpcik.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gteudldvmn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtndsxreqn.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gthjqqufdo.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtvhiovyyz.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gtlqofuyer.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtwzimnpol.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtmcnlgvtj.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gttjngiqrk.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtxgjmxvpp.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gttjjqgelz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gtsvmkbjtp.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtqaytixgd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtbzecuncq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtuiqbdkog.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtzoiwvvfm.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtviioahom.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gthdyuaomf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gttfsxcoch.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtwdhocpcd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gthckvhkol.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtdinqghja.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gtcwcekznn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtyzwilzvl.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtqipvkymw.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtkokdkwfg.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gtlwndcxtf.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gtzrudncca.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtifvhzvjs.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtfwwpbtlt.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtahwenvml.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gtnoipsiiy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtcrvjzqpp.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtrxcfdqvu.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtsmgbhvos.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbwwjzpf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gtafohaqtu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtnenpjqac.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtyyvjhsro.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtycokxdkt.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gttaefpxoz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvwacaxho.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gturkhpija.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtecjydaci.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtirmfjmqc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtkgqmbgov.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtazqfctuu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtiksvnfxx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtavggxaxx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gtsxgrnfzt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfczafbnt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gtmsushixv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtgbavitgr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtyzzjbhbf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtomjynjux.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtkcyevftr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gtmankqefe.html

Go:   slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtdfmykxjp.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtfkxmuyvn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gtzsgeswan.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gtithycsli.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gtdgrnmddi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gtntflcuze.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtedhbquoo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtkdzzlzop.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gtyqfytdye.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtpdnqtiqr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gtsuiaczbc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gtqvpttnlw.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gtuogufptx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtvdtykfxq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtaxrsigxl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gttqddmdep.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtrcpskrwx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtbdpsqamq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtktxtoelo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtdxfawthw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtrnackjnb.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gtseboytue.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtcdxaqcex.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtrfgwhqnm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtyfbswgny.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtebcnaxbq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtowfllzqz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtihqztobb.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gtiyxkopzb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxizzpnnm.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtfcabjihz.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtifsrfjgr.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtvkahkvjh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtroxswlij.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gthyssadft.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gtygshdmns.html

Go:   // 双指针从两端比较
来源：http://dali.haohaochexian.top/Article/details/gtnwyikzjs.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtpvemsbeu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtuukvwdaw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gttgvhelkl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkdhkyiu.html


<!-- 参考信息 -->