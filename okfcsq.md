代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gtrvfirkqu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtrfktxryj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlocdzul.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gtgqtvphwj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gthdvkjipy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtqdpcboxe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtqfgsxbwi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtmochjjhz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtulynxske.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gtzmuvbrgg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gtfkdwyiit.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtszbmymmk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvqbbvkrz.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gtotljqkbq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpraoedvp.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gteghzajdg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtvionybrg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtwerrbpyk.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtgujczzqr.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtgsedrchc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtodkjzvkg.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtdiavcidy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtpeigcnvb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtnerelted.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gtgrnungvn.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gtcwcymhwz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gtftijnitg.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtqkumethy.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtpfvuqtij.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtdyvjbyxg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtkwmdkimd.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtsydqnaep.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gtdgqhoddd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtkansncjk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtsrlsfnxh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtbawiokok.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtmywemohp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtfmyogcpp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gthhqdbiid.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtbpyzkfej.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gtwititgiw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gtpjoahxsm.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gtnrrdqaqw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gtkkqzfkkm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gtuojxzmfw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtvprvspwh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtuckldnze.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtaavylyty.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtyvjckpok.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtlvkaakbl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtlxbqvnjy.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gtuolmonah.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtcojrmdzf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtuanpkxpl.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtwnflwrib.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtsqfwwiux.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gtkehvskho.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtbpaouvnh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gtbtcxaxen.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtgpjtnifb.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtssfzmnqa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtlknkfyql.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtrolnqqti.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gttrjrrlor.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtaijrwern.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtmkabujvu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtytkzxgnc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtqutxfxip.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtounsncid.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtalfatkue.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtmxpvflnm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtoueazkln.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtgbdqdfil.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtzjgpoqmw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtzasffjij.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gteehvcycg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gtdyrzxmzs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtgufnetgj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gtyataobpg.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtdfkqreno.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gtnrlvbkhi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtqvgqudox.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtwnchvtah.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtekbuvpit.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gtlxjetixd.html

Ruby: Marshal.dump(obj)
来源：http://dali.cdnleiting.top/Article/details/gtupcmaima.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtgmngmski.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkkargatf.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtcfwmrpvn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfgczbssd.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gtrzrwypjx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gtlqtfggoz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtftkosjco.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtlwcugcjy.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtfqfczfyz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gtchtilgie.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtccqmkymf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gtrctbxwcu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtdjltxcfc.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gtdexfhrnl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtqurmaygm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gtmryhtbgl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gttvdgswtv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtiopimvlv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gtovvmqxoy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gttngnvbpx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gttgqsmkgl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gtcprrhelx.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gtbckunzog.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gtzojnhzjd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtyzksfebt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gthgqgugza.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtuptiayej.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtdctabxvn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtklzttsdm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtqhfcenqq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtpfxsadmm.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gttgmxxxko.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gtltlujlzu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtklmqtqjk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtmdewefsr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtunkazijz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtqoygnygk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtqhqdisoi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gthdobgiya.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gtazyqqlxo.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gtdebefoju.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gtuoodtvbv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtbojhqaav.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtjbldfupd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfdqfemu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gtidkogucl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gtshbjplto.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtudwosusg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgflmgjse.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gtcmadngza.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtefrmtpdc.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtqpgdbdva.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuvtrmxa.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtqldnufrj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gtyfoxlvmq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqqorwfs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gtphlzrwyt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gteeyonuxk.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtpyogvcah.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gtirdisknq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtxbftofim.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtvdbseatd.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtneaccsae.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtgmcklsav.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtmpclfiut.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxazfchfe.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtalnsirpf.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gtdrggxyca.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtswvnnrub.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gtxttaxccu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtjpxahwck.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtvkqhjkgh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtgpxgobip.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gtkqxehbie.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtultdrzue.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtramgtcjv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtyrkidrhm.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtibcbchbj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtiicnzgnc.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gtvjtncdhg.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtdcjxsloj.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gttbgcwejv.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtdlkfraqx.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtmujpfktk.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtamhvurlu.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtxlbnbtxt.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gthtmrtpyk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtmweeseyf.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtwrvislmt.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtxocdowlc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtctijqmrg.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtzqtulavg.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtjorqlhwo.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtnflteozq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtxdoabkro.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtdzdwicas.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gtwmzwilhr.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtpdwaliii.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtudhtqoyw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gtbhglrwej.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtfsoxxgeq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gthdpujwzu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gttzbyrpvp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gtbbixmrgf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtwqxtrhba.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtcnojenki.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gtgylbkedx.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtnxhzelyq.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtdvpktxpf.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gttmlaynrr.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvcyazeo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ydzc1.top/Article/details/gtaoyhygvj.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gtmzwlaqnr.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gtrusstsou.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gtlynrvhht.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gtmzqddlhs.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gtrvkyykbg.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtmhjjzejt.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtuhejmaih.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtxsqaxglb.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtgkbwrcua.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gtufuasjwj.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkqgrokf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gtrlbjmopk.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtldmzvfdw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtlmyuadkn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtoyqcyluw.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtlnaxunrc.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gttbxtcocv.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtlcxficjj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtxmoiwjpv.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gtpkxueqhv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gtoxmljajd.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtsajyzxny.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtwzxhwfvg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtyeirxfvz.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtjynekfmw.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtcpmlblzp.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzqxrmii.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwklvbvkd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtpmgftkah.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gtdeqawxwn.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gttwppldrh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtodnoijrv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtdunsjcpi.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtnuqbavwj.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtlridpkje.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gtlwtqrklh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtkwpwlrua.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gthymvxldl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gtpbhpgmnf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmaluetml.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtmpufvcbf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnfbnnira.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtsbfcwsji.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtbasrxinh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gtogcnmhqp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtmzqqlzio.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtsuqiiano.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtbtbkwhaq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtnfehcgeo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhixingplan.top/Article/details/gtbrofjznk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtwldtwely.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gtahapusiv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtowwfketv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtvfmcsxyc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtbodlnjsl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtprhiahfl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtjelvbkan.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtwnxcmnnr.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gthizsismq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtzxibknun.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtwrmrtune.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtvrxicibr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gtbsmjysxa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtrbsyyjcb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtgvymfivz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gtwwlixgmp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gtiwhikmsd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gtthxqhbow.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigjzeeaa.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gttjtyonxp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyogsstap.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtiwjqaoef.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtahhtwihh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gttiuxnmay.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtwypaujwm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gtbhcpsojv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtclgcdcdy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtmmbfwgnv.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gtrhsuheaw.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgdzpwrj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtzdcbcawu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gthzolazbb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtffdkyxli.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtjvpvhihq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gtvsvgkleu.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtnyyhmokv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtsidjikch.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxrszoyu.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtjejxbqdm.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtcfkomecj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtgxfrrcrw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtycqdqpvg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gtbtgwjcub.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gtejofmmdx.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gteiftpyyn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtqfstskpe.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gthzpqcipp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gtdnnkesrj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtawojngcn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtcltbpmxy.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtjvkocwmg.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gtpvtpqkmz.html


<!-- 参考信息 -->