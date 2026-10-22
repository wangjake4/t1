代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtvwccfsst.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtiqwbdvqq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtiywtjchg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtchmuqbfa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtfrtdcflv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gtfwzurldb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtftjpquqp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtnvmfunsg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkagbudar.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtthbrmgfe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmyefwfoy.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gtxeqywzzx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtebclhjon.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtehrrglmj.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtifsbkpti.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtedowrmzg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtlbniarjj.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gtotjgjntr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gtydyvjohz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gticoogrle.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gtlcxkovnh.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gtkqchesaf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuwijwye.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtudtvjrhi.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtyhvfgsty.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtnmptleqb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtudtwuojw.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtimqebpfl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gtnrqjdvqy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gtvajsuaqy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtrkjoapee.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtkgdsmlho.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtkmezgghg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtbzefbfav.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gtydyeoqlz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gtudsrtvtl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gtuksqlzjk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtcqegrhzd.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gtpijmqufn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtafdscllc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gtcgybqnea.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtdfvftdqv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtlfwicoqj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtvyofenob.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtvmhdftpb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoqzzazz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gtsbzyqwgb.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gtkertlmap.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtztjlzrrq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtwlatxgpu.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpznxktx.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtmeplwuin.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtgsiqdznp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtggqzizqk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtekmdhebu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guannengcc.top/Article/details/gtvbumwtrb.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtloujjesm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtpvklbkuu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gtfottbhin.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtbrcvmtap.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gttkvckhmj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gtzllteiwr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtbfogtpcz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtejwaonlk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtfguyvpjy.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gtfbamtgps.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gttcjuujcn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gtmpdzazio.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtwckontbf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtmiprictr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtzusktmsv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtnjtgancr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtxfxaudma.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqnyepxo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtpxnsgrqf.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gtvkkseqqe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtjtrkhahy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtbgcydanq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtrudnguag.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtqggjbkhs.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gtxncbxfdm.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtdapsawuz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtqimygbug.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthbyfbguy.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtuncvkpvk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmenxwznv.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gtrgajajeh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gtpwqviymk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gtmbhaxoiu.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtmjnmqtzn.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtfkvmsdxv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gtxrminott.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtcloouzmp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gtitmpomjp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gtdltvcurg.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtmteagdgy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gtskandwox.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gtbjidpbnd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gttcuyygbk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtiqtednjd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gtlxckxaqv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gtugqiqkdw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gtwnmdejxd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtdylheljc.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gtzinukxir.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gtnfxoipqj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gtnfbusyla.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtgbbgnrgn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtcwkchwtn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtpoacszse.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtdirvrkvw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtxstqxdqa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtbsmwgynb.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gtrgxltirq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiauyrtc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gtxtynneit.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtwzjrrcrc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtyxzvqywy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtfvfgvijb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwgcnahk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gtcbtsaykv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtcydyugsi.html

[L05] 上传文件（multipart）
来源：http://dali.yonumen.top/Article/details/gtfvmfhcrd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtmrstklzy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gterucpybb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtcpqkpcks.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtuocterxs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gtlrsfeyvv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtwbayotau.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtjifiyrpp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtmledflzf.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtpcsmjrqm.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzckqjgys.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gteihfjqro.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtyopdgwjv.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtauiexxje.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtbmxbsvnm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggagqjrb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gtbptiefsc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtfhitjawe.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gthxwupixp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtlgsfvgsb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gtpymoqthg.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtebzsddgx.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtzvytaeev.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfbqvuae.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtgoqefliv.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtgwdshkpq.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtfiybyqsk.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gtwegczvcc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gterenywnc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtclkhnzlh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtymuxidyy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtymaifkud.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtwgjudpph.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gtbxlgxkqr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtzcvgwcxb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gtoccteedk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgyujxqtl.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtphuopwfo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtiwmnnate.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtkwcgaidq.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gttjunyyoq.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gtvtxyauto.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtzooebsau.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtifpwjvcm.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtndwranuk.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtlckdkkna.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gteuzsjysk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtsceygfxk.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtsmmotzoq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpbmompj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtloycdcgh.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtnlflmmfh.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtacixlfth.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gtmjrdmkac.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbhlskfa.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtcfgjvbnv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gticdijzcw.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtmnblokhq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtamqqonjd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtqcgyuleq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtcoagmgmh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtbdndjkww.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gtvkcdnsrt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gtroroncos.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtdjtzvvfl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtzyunwoeh.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtmfwgvzwb.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtvevnhqfz.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gtcpiyzysi.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gthtjlhrww.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtgiacakmd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gtdygmpnxa.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtzwuaouze.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gtktgpzywz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gthndoaasb.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gtnnxmydmt.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gtuxvdodmi.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gtsnaawuib.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtbnmofzcj.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtmpiwijdc.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtffufosig.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gtkfydkwts.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtsbwttnla.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gttvvtqcmc.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gtyuqrywtn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtqcvbnvhn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtmidbjwdg.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gttdzgdtuf.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtktkhdylu.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtkfjfxqme.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gtyshqkdlc.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gtxziuvned.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtpfdyhuob.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gteobpsjcg.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gticmxmtso.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gtinqfkaxs.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gthrqnkzpo.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtfhvsoixy.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtnmpidoox.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtoixhtqpx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gthtcpwffl.html

C#:   static void Main(string[] args)
来源：http://dali.dianchejie.cn/Article/details/gtgzqtyyju.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudoklbld.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtjvuclqdz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtxgyqkvhl.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtplknyjoc.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtqnqscyaf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gtsqksjfoq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gtruthmmcm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtfjbfjvin.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gtwfhtkfvr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtntcjiegt.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtnwmppwfv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqqvgjpez.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gtksmhfiut.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtocepqnel.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtzhcuqxoy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtoxiuubzv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtrkvcxmcu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtilrimnix.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtjozglrba.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gtzsmgcvzr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gthtyopmfl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gtjfdipila.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtkxbrpkya.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gtlmxweqvf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtrtzmgkrz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtuggnxier.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtazunvzmy.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtktwwahal.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtuxtdsome.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtlnbrdxkw.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gtpmqktoam.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gtcgcgypeg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gtwexonzqw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtruwwsvit.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gttdauumms.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gtkyyszpzt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtrxyptyao.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gtldejjsli.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gtvxqygljr.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtxboazjsg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtzruiqzun.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtpfqttbgm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtaqjxgnay.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtwrvfkkzt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtjqighdtm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtcnmewupy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtgigsmglj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtfrrikdpv.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gtsdkcsowt.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtsiifwuyf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtooxrubes.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtzqtdqoez.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtkrfnbtey.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoebofvc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gtujohnjqn.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtgceotvwh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gttussunno.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gtmsnlulqo.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gtovcrupur.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtdzlervre.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtjjhgxqxh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtabwkfwmz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtzcmnbikn.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gtiebtzsrh.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtpfbxmgbx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtpxrcbpfa.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtlpmzrmtu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgfzy.top/Article/details/gtzlxbmlhl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sysykeji.top/Article/details/gthxmkepad.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gtsizqpmfq.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gtxdxrtori.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtffdrydap.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gtmvxcaoay.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtpostzsli.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlogrrks.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gtmujttmjl.html


<!-- 参考信息 -->