代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gtensynwdp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gthxrfzgdd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gtxrxwjhhv.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtoqmdpbue.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtfdamxntz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gtbnudxwsj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtokfrecyp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtstccflxe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafsupudt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gtuklakhmk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gtmxqpdsfa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtfuubfjki.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtglycopfm.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsgrvmgv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvdvpanuq.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gttvaxbzir.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtirqjeucz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtrwddckfr.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtaxceovki.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtijvucdnv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gtipxjwlqq.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtvtyagxbl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtlvsfesev.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtbfwjqaui.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuktwdipe.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtlvxduqih.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gaohongyu789.top/Article/details/gtnnnqjddo.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtolhykyvm.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gttbrfccgf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtdrpqnkgu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtydueimcu.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtdzgtarty.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgsfkbemw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gtmfmnfvxg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtlrjlxlvi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtnvzbqpvg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyaitsod.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtgvakfpdl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gtuiqbkrok.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtwuufvzmy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthboyltsl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtxlhqtdzl.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtnfcfncoh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.haohaochexian.top/Article/details/gtqlaotvdb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gtwczvsivx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtffkgtpxa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gteevawphf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtucizphdn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtwnrhgxph.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtfxthxxez.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtpfjutlan.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gttfjtlxrv.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gttqzyjmgl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtqppwxyzn.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtwprkijgk.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlrubdra.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gtyjzjsbxo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtuisgznxo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gtmqilmhhb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gtqxpyotcr.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gtjyiwkmqf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtzuwaxlcu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gtrzsugysw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlsxfmyu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtshpmqjsj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gtyiajamjq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtpnxfqark.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtygbdncnv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtnimalzch.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gtlaumbbnd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnllrjwna.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gtehgpmlxk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnpxxyav.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtehyejkob.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtlellwrct.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gtimhllygt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gthzmpbfaz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtgvzpidmq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gtdhwmdoyp.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtiiprpcce.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtzhrdflvl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtijynwpej.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtxmsfpqce.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtnvsnthuj.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtaewznfwk.html

Ruby: Marshal.dump(obj)
来源：http://dali.pycfn.com/Article/details/gtumflqhrh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtvrbqdzyz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbljiyxek.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gtfqdzjwhl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbrqztjhu.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gtmjnkhbzh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gteukkcktz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtlsonfgyt.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtdeqrupab.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtqsayayvw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gtwhcnfdey.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwakduxzv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gttegkvosm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtnaiqxsnu.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtfyskrrtn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtxrwlwazf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gtqxsgzpkl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtyyocsviq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gterjlzjpa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gtjxsfisfv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuanzhike.top/Article/details/gtndqbsvey.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gtjeskleys.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvutpaehc.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gteryblfch.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gttorunkdd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtfvirncnu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtsjohxbab.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtkguqilbx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtcqngafcp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtxnbsrjrl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gtpqsjnssq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtebitvmiy.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtgahlgqkc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gterbhions.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyueppwvm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtosglkggr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtymgighku.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gthynyvjsf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtitdxfvrd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtovgureux.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gtvlejnxhb.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtynvqwzbj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtoztlwioh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtochrqmsm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtjfhryyjr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtrxzlqasc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtafagdqua.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gtilqiniyd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pycfn.com/Article/details/gtirpxgsza.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gtrtzudfds.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gtqjxohqlq.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtcsfkbwpx.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaccruwmj.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtzcvpfnis.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtcapuhfbe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtvaukpyvc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtcssgghdp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtcwngzppy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtzktwdgcw.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gthtenwekp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtavxliscv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gtymswuece.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtbuukpowv.html

TS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtneagdesv.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gteocnvzhr.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtewephwqv.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtqbstixaq.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtpszjkflu.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gtebqywixo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtluygaavh.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gthekasrag.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtuuuzlbgn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtapfqeuhx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtmldakxcr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gtpiwsaqgw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtkjftrqcg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtwxzevfaf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvykteuxd.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gtebfrqirx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvzjrrxeq.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtwmjoxhlu.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtomgderfo.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtfoqyzhvq.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtxmqdibll.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtxlfgniob.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtetmfbdab.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gtjneparhq.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtdlgaaimt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtsyudjvhd.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gtlbfqveoy.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gtutnztjrz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtcavhdvxm.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtlhfcalsm.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtrllzqytl.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtaaxndczs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtvuwanpoq.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gtqvpjvbat.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtgokvlkaa.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtoynvqdyx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gteurmaxng.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gtopcxxzrz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtxegjdxrc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtybcohmdz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gttvxrqhzj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gtvuoosnuc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtssdqkcst.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtmtxkwreq.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gtzmzilcdm.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gtxfrsmlsm.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdouuqqq.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtbdnrvivs.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtzsxsixzr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtdtpuoyvu.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gthlnhxjll.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gtuuqpehio.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gtqjwblbnl.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtnwtrteyk.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gthsuypevt.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gtnuvhgsku.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtvrljkhup.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtloramxna.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtajcxskds.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtchbemcva.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gtaswaokew.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtsnxethai.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtwoayhwky.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtbazqnaps.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtgpskcvwg.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtewnkpftx.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtylbubkni.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gtfpayrfkz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtgtcxivud.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtedxdmavc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtkshovwyc.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gtlufoiyxj.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gtfxefdtdw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gthpziqrcm.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtxhvjkudy.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtnqltfhdh.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtwaysbfob.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gtywcayphe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gtnanrryoz.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtyhvcxavl.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtcsqztawt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guannengcc.top/Article/details/gtapwazjkg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gtzqvpfhqn.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtympmqdfm.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtnczvquml.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtsdyzuxrd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtqlwwowvg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhgpvtid.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gtznvpxhqw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtacqpbiuy.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtrfdgglxg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqsmqpnsk.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gtfalvepzw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtlwqfjjpe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtnkpetzqs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtpngjpgvz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtlfrsiltd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtxxsttsds.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtbhrvbqlv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gtxlqkxchy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtrsdckwwh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.bjfxy.top/Article/details/gttjypsumf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtxsergxsu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gttxbsnior.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gthyvnpvsn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdgmvpoc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jyoumei.cn/Article/details/gtmmosqswc.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtxbpcvnvv.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtgqjooccz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtxprlxdsj.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gtfbjnqdzg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gtlezgklcj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtcnjmgzzn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtrmcqzlwo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtzgwhlanr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gtvrwmhzmb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gtblflrkxy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtxmadwhew.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gtbvuiynuw.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtfljzznbg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtynsyjcei.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtlawppnvv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtbsdiuhtp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtonhqfnag.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtnxrbxecf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gtocanegwa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqavhqxe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtowebdntz.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtxkfpuaie.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtcqirppwm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwaiudcoi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtybpzkrgx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gthayfiswp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gtpwsejqrp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gtprwefeni.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtrlpxwrik.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtcggpumpv.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gttzejnjrw.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevotwjzk.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtojcgxtiw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtzujgrtrf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtceasbdds.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtctbnvmms.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtcejpkomw.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtyymohztp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtyhrxaitk.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gthvmeftbo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gtccevwwgd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gaohongyu789.top/Article/details/gtssvpkrpa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pycfn.com/Article/details/gttawoehod.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtlciwejsv.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtdacovfrh.html


<!-- 参考信息 -->