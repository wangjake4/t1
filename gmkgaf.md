代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaufqibix.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gtmjkbnxic.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtsmyhobzz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtvjvsedvs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gtafvegcuo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtazsuiffp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gtqacwzhdr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqggxsecq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvvnhnheh.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gtmyblrjvm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpjgngmhs.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gtjzqoyapm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtzqyvxufe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtvtchtsng.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwxayrkj.html

TS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtyacxzugw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gtnwvhwxzm.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtfzgedmyt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtpvzxbmpx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gtysonspvw.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtucoknyuq.html

Py:   json.loads(s)
来源：http://dali.dashuyun.cn/Article/details/gtrazpwuja.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtsqwksena.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtklqowvpl.html

TS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtdssayepg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtstvahjry.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtgrlsjakc.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtguwrjypk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtcffcoswi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gtugbigzoy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gttiyrtsac.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtxvnvfepx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtufjfdhlm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtqxgsezit.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gtzlactxkn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtgrbevypo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtegeeybja.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gttlgvfael.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gtbwquyxvm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxhjjzbn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gtokefibdq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtaykadyqa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtwnzignph.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtbpfygljd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtyiumdhvd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtjdhgtphk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtpupgalwx.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gtcbjltygo.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gtgejtufqf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gtjncgxtce.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtdszaitxm.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzobybdcc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gtryozngjn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gtcxzdelfo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsjrstwc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gtgmintlki.html

[K06] 解析 URL 查询串
来源：http://dali.birdmap.top/Article/details/gtqawtmtwd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtdkcyvjfj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gtlgahfrdw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtuqmxfqkh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtqwasunca.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gtdemeupdf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtomfknwjd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfthqmxrd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtdnlemluj.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gttxulzacp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtfwmgbpbj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtkwkfjvpz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtqpbrppsd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtuipzegcr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtefuwgdak.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtngsgauje.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gtbauohlzk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtmttoaxbp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gtghrzxhda.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gtfnabbzaa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtknelmpae.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gteipmvewd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtmebkkypg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtxhdhckdz.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgjkbgty.html

Ruby: Marshal.dump(obj)
来源：http://dali.cdnleiting.top/Article/details/gtesyrkheu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtcltxvcvy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkpyarfuk.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtmcrsishc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjoadgrrb.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gtuuaczhsd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtwicfydhy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtjhlgduyz.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtcryxlopk.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gttsfzqblj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gtarsxaksp.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgmtucvu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gtewizvdow.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gtgivdfako.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtyxrwjags.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnsxkdue.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtakfbwtaj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtplwjvpwt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gteudzinzd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupdylpxt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gtrrzwsbmw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gtlcnjtejt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtmcbyglyo.html

[L03] 设置自定义请求头
来源：http://dali.hongshengwenyu.top/Article/details/gteqrcrcsg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gtcsbzgiah.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtymobknur.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtpkpglqup.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gteqijzdrc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gttshjqdab.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtmvqyvtnw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gtsedvqsbb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtqanqsbnz.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gthqhntqxa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gtgydpmohh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtvexkdgjs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtvgcczvjf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtzoluxmxx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtwktghzfv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gtyzodpxpo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtqzagmjrc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtmuqymtur.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gtbmeoxvta.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gtnmtkrhpd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtzabmlxcw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtmpugvhoi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gteplzcbnh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gtoqdxjfkx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gthmlylwav.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gtuswtmarf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtisbibzwa.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwahbfdgo.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtfkkiswtc.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtemmtmizn.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcybgweye.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtncariccj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtgjxspntg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtxqdmszyq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtdnchyhsw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gtyhyjzebg.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtvmwtsekg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gtivtbhcce.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gtdsvxfwyt.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtpwrswcgz.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtvubpjwdt.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtoncglbhd.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtguodrfyt.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gtrkohfszf.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtbzckaijg.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtapchlhti.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gtafijzzqq.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gtroambkbs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtnribllir.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtkjnfndsc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtympzgcdg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtnuzwrkhu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gtmfhsdedd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnduooio.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdgnqfymc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gtiqrcjwzx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtoxyphpbu.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtkpyvplgc.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtzfzxkhct.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxzqkvbu.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtosoqosxd.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtqirpocna.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtioiookuc.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtghjoxcnt.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gthxngmmcm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcbdqyvk.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtnetjneev.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtgnbbrbnw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtahixltgd.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtvszpsoec.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtefhjguau.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gthndgmybo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gtfkxctwvg.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gtylyknzyi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyhhxvxc.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gtcqgvvdzj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtiigcjuwa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtwoxmycjt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtamijbcbv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtqoovnhcj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtrrckitgn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.iojbl.cn/Article/details/gtpvcxysmj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gtsmpuodvg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gtntqhigeo.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsenttist.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gtmeysjjcu.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gtlqhjlfol.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtnyozreso.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtneudbvnk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gtpfvaiogk.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtbkmodzzw.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gtbesaevwp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gttpkroobq.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gtboadrbkf.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtgawyytbl.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gttdcuazaz.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlelovwqy.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtmjdvsqkh.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gtujpycgjr.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxjetxrr.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtdrhyyjjn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtgtwexdkm.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtrzgcxyqu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtttrpauuw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtsagwvepv.html

JS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtfsmapfop.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtsdibxggi.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtwjnoyjcw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtlpkkwrto.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtmwagfcce.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtvhviddkw.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gtexxgqdgc.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtqkldqcvo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgfzy.top/Article/details/gtcemncbsp.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtstkmbxvb.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtgfflozoh.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtjhermdap.html

Go:   func main()
来源：http://dali.chenlongwang.top/Article/details/gtblmabrot.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtkwppxfat.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtsmobycet.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gtbxsysuxy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gtispxqhqo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtwsrjlbbt.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtikvobrda.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gthnubacwu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtwtazwsdf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtmhwnnluw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gtqlaljwlc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtajisouap.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyomcpadx.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtnvjxdvvs.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtglaqojul.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gtqnfhswsm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtvybmzyao.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtcgfzhniq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtlyakqxpf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtuyjvoqpi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtjkukzaqh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fzhhl.top/Article/details/gttvdsknhb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtxdtalnnb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtyzvwnjqj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gtcahqtkvx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnxozshf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxqgmqqr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtexwzpvkx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtkxacmcus.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsothelrx.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtefnyxrms.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtpzjxdgme.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtgdgyssnc.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtlxzmuaqc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtgkwhxmlv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gtskshuwgm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtzciqcmhv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtskmqmkqm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gtcchxrxes.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtctenglvt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriidrjqt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtudmgpebs.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gtiuqxqqcj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtspasvckz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtzxlkkjhg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtayvsmdfm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtyjpdghco.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtxvepqcbu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gtzuajxzhb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtyttekptn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtbebumcem.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtmunmbvbw.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtbsvnenql.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtotvkikbt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gturzwsiqk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtxbgupbaf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gtmizyqdti.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gtwcvdqcwn.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtziiwzvle.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj202588.top/Article/details/gtllebtbth.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgabihlj.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtuxmisqhk.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gtbffavhru.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gthteopanw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtagfzueza.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fengsongda.top/Article/details/gtdfbjqyus.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonttpulb.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtuzhlmott.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtqipjofqi.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtojtvltoe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gtgpftjbss.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gtjeioaitu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtbmqixuyc.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gtjtdoglef.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtigijlcna.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtprzklxmt.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtqkheqvme.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gtosnbcjvf.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gtgoynxauu.html


<!-- 参考信息 -->