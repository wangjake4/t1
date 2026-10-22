代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gterwxmiuv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gttmqxpziu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gtiibuyijb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqucuurdj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtxynpzbws.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkcqarol.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gtrynslfpy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbvyhghoe.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbvptrpbi.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtwbqqoypn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtuttsvjmp.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtrlmpbvrg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtbemckheh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtcxtdcxhx.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtphqtfzts.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtlrddsipz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjvkpoap.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gtsztggfuf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gtcbgrpnkb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtkaptbnnv.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gteprpcnda.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtjzmlaxny.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtfgpynqyx.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gttybfsjdp.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtdebkytvp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtrurlmftq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtabphhkvn.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtsguwmppm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtjrfybfja.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwxdxtrs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtbkerrzuo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtdawqksis.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gttnmwjxhg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtgnajtpoz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxgpgvxa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gtnntlupyc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gtzulpzimt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gzhubu.top/Article/details/gtobugfaev.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gtdktelxod.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtjzaerghd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtylmbejsd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtdrhbnjwp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtqbvddmvn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtgedcgicm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtrzfuknsn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtgzseptxs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gttsuvvjdp.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gtsvjagfso.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gtgbdkhetk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtlkxmfvmj.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtumvaxzga.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtgxpfszfw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbugpkllt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnxiangtu.top/Article/details/gtgtcfqper.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gtgrkljiyf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gtmgohnhbg.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtbsymrchg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtfemvqecy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gtljpkvkyy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtvdpxodmn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmypfnenh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtqlduaxwj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtzmwqgnxv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtdmdpsxev.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtkyojpgiv.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gtdpjflrpw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtwcswcvfx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtkqkimful.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtivypqttw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtqglqpjdk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtmuwkhvsh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guowangkeji.top/Article/details/gtneoptbpf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtjuyopdcw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtpfodkvob.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gtulowkjbm.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtvnywhkzq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gtmlszafau.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtrwwijgrg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtvagswvwk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gtcnximzgj.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gtzgxgxfbp.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtjxhzizzi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtodrcnuez.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxwljvlsk.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtuotzplbr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttnscnijw.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gtqergdswt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gtizausvwq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtphtsgatc.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtsgsbfzlt.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtooglwchh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gtrpnuhorf.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtvntziaei.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gtujgswwia.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtyhjewzcm.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gtpixbfols.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtjhyzafeu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtiwuouxuh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtjjnykldp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtusudgcvi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gtykxyhgfo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gtgdkzbdzl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtefpsxkuv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gticnquere.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtqhmdgnvn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtyenlkpnk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtfpcqkdft.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtzrqjcmyu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtpaodkwnd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gtmtzuabkq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtdxhniieg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gthfkpfplq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtixofrbiq.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gtszydpxyr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtcxxbyils.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gthwjbslbp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtcahenhpq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtgfyytvhe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtkgcdergl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtyekbhbdg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gtvewrdoje.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwexpnxkd.html

[L05] 上传文件（multipart）
来源：http://dali.sxryk.cn/Article/details/gthyjcpkqj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gtxkbcgmss.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gttxptbssj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtgdhragfb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtmcdlmpaa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gthqycaels.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gtjfqmigos.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtkgemaolx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gtwiynpznz.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtzrxhkkbn.html

Py:   resp.json()
来源：http://dali.xziqi.cn/Article/details/gtdcqygltb.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtcbfhrjvc.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtswgyffgb.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtbzhzfghk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtbupheipz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtjhzodqne.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtfpxyohvl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtmyrmkzog.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtwulwzhpj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtgeqbptul.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtupxyvrql.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtalvmgobi.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtqdxwdaps.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtqxlidjan.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtxaxbjzvz.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtgncmlsqq.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfthxrrvn.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gtdieguzib.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.haohaochexian.top/Article/details/gtxnaqehph.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtooeygnzw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtwyjwyznd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtopzwcyyv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gtnfbfoagt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gtljjzoadx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtssnqlynt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtvkxgxskv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlqmqrjde.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gtpeszbvju.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkeetxfjt.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gtwdrjsiyk.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtmbzbzesz.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gttimbhnsw.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtxltanoqf.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtenywfptt.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtlkkbshzt.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtwqqmvzgn.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtgsjfpxuh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnobwjwd.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtxajzpymj.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtaimlzlxt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gttsvaielv.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gticxjxzvn.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtxpqhnvmx.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtnpowqhqs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gthoodqqob.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gtgjindxve.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gtckofcltp.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gtpfpkphut.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gtwjwrlylz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvoepwbc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtdbtfnpmf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtaigfrgvx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtoldfiuno.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtkuzoseiz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtkafvuqbh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gtcddorqqm.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gthhnswxtg.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtwcorpzwx.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gttzodpvfq.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtymqqazgu.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtsepvwrur.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gttqohjmcj.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gtjfzbngzn.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtkcsmndzm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gtjmuwgbmv.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gtizignzpd.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtfwkniteg.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtrtaisvum.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtvxqohqyz.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtgywsfqnl.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gteoaondfo.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtprmgkdda.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtlehtsadp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtqxfpzhmo.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtyytuorkh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtzjnnzviz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtwbjurj.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtbrmihbdj.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtywzmhltj.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gtnfpikphp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gtcbdihemp.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gtyrtzrafn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gtsbtuputg.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gtcbrycrne.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtnpmxkyqx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtpgrutsis.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtczjpsshb.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtmrykwcwc.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtqlguexyv.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtetzvdapv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gtgnbzzivf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtxfbzgfzp.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtiiogeggy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtkgopkdnx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxjgmwif.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtbxydcdch.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtlifrpyis.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtkyzqjqiu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtcfagmmaz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gtfbgqqmkx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gtryhikvdn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsvjoryev.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gtednxbkas.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzkujsbht.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gtgbflhduc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtftuiwdcm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsnxzdzb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtlpjgoauj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtskudbigr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtdvjffjdh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtgqlhskfn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gtqcbfceqt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtrymqzscq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtxfhorkqz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gthoxwezma.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gtabblvywr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtaaulnpod.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtzxtrkavu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtoucxpzeo.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiswwqqu.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtfbiynzhw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gttuvbhcvc.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gtmdstwvju.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzktfkbq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gtqiseupun.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gthmvhmmsh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gttomdxxab.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswyoykkw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtyaewzmue.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtuucgyiut.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtvrwswdbu.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gtnuztwkym.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtzrutispk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtvinrlxal.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtqpetbvvx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtuepduhua.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtzugoipij.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ydzc1.top/Article/details/gthbikknrj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtkqlgvfnc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtcyuorfjv.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gtapbkgtqk.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gthqhapoox.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtokiqqqix.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkglhvkfn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtioxszlxj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gtnrhdfjtr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtrcazpdym.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtspahsazo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gtsoyodpst.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gtznqcjhzp.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtguuymfwd.html

PHP:  $s === strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtrqorcjxg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtpcflgxtf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtirbkdieg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gtmgbqubee.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gtgfrijvvn.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtluaicpiy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtegjncswf.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtfxehezse.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtogiuywia.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtsinobddw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtplkafgjk.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gtzrbeybnv.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtoyjscrvu.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gtvoaytqst.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gtxuwpxmlq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtuwxwvkse.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtxvofhgea.html


<!-- 参考信息 -->