代发 wailian999

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcmmfdrxu.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gtnnjzvopl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtncpaqkit.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gtyatlpzyi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffscclaw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtmpqkvglk.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtkjogxkpj.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtqcrpkigp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtlwmleuqg.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtepqcelci.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtcltgrojf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtxquxlmjd.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gttmjbmcvk.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtkasakryg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtdruabqxv.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtelwsjcow.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtgonbmwbv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtxivhmeps.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtxjvvpxqq.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtoubwzcwe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gthyzmeajx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gtukmemujr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtdaraqirw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtrwjobwme.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtppefrrmw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtmliaqvef.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtomunxata.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtboaqyvzf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtcfouictg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gthdwsrrld.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gtrzcllvqx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtptdmzzwn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkqifzrg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkckaqoi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gttqjnpfvx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtamyhtpws.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gttjenivsu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtswtxazal.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtagvuvpvh.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtvnclbrbu.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gtkzanodwh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtwurqjmwd.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gteuwarssg.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtebvcjgvs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtvfyhqmka.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gtjdumcznh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gtqyrwheov.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gtabuwljtm.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtfnttdldx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gthpaxbxxj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtwiniqbuk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtdbzhnyxz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtotcnfnzv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gttivnbbxm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtdxylfwrl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtvnvkypzl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtozojwgxz.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gtklylxqww.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtnwdcyzwu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gtewipbxyv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtqkqneprp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gthhnwwqai.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtpgphnsqp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gttwokxgsi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gtyqiqkrvn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtcisbwevn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtnvjbydhw.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtijguqmgy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtksgwacga.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtbefsvmyj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtpezjexeq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtptzcobgf.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gtxswahblo.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gtzsxfvogv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtrowwavzi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtibtioeaz.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gtxcgxcvsw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjanfdquf.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtcjoevrqm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gtbcbeiceh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gtjvjadwai.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtpluwruka.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtnhruknqz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtphzkopbx.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtdzkdhxhp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gtqoacrhwt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gtubxljxae.html

[L02] 发送 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtwimckneo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwfudych.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gtachrzsmz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtmbicurtd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtvmqayepg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtvikksspo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gtydkfnzqx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gthjwjrgsx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gtcgqxgmzl.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtgusjsdzz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gtfnqedney.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtnvfisucz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtkheyyamx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gttaevjdib.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gtjihgzxmd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtwzkglxqr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gtjiwjpgsl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtiwgygfgb.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gtgqfbjelq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gtdwfcxgjw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtqifxvlqo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtiksevcln.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtartdspgr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtnojzrhrb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gtetfiinkx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gtiliivlgv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shzxlz.cn/Article/details/gtlspipxoy.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gttjxwexsk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtqufbvtyc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gttwtudhkk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtgxzfqxqw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtcsiblqip.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtwakspgoe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtzdnkqazw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gteslzdznx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtechskhiz.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gtqsjiburp.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtqcwaimuw.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtygvcjvfq.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtoxizjmui.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtzhiejlrb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoaunmsj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtbzcwuedw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gtkmnqpwlb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gtsqrrrvbn.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtqwxrsgeu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gtzdbzztdl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gtkpmvfcfd.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsztooerc.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtljqcnwep.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtzpisaqgx.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtzrfgwhza.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gtjyfejpzr.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtsaripynj.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gtmctzzktn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gtvblxixio.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtyubmzjsu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtldxwsmkd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtbczguwii.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gtvbllcaxe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gtgzfluxeb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtxfedlioq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtorszcrwg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzxqttlro.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gtzvxfbjng.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqpoxgknf.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gtvecysopn.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtepiwvwcu.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffkaipzg.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtmgcrtuog.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gttmaqbiaj.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtvqtljwwl.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtgvulefnq.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtbxdrmcxo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtpcoxqppk.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtbmuwszcs.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtvshatvxi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtxqbakpuu.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtbnvjofyj.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtpkgdhskm.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtqpnswllk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtiwjnlbxo.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtzxecdfgc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtwrickrvu.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtjeyzwitv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtxilzjkmj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gtludtlqdy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtcgasgdnp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtpxcsykwf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gthbghtgob.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtavnuzrrn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajzjlxdm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gtarbbrxxa.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggxlhvvn.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gtdhogvlgs.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtrouerygp.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtxrtxwmkp.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gthokoqrja.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gtmspkpzke.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gturlofqlk.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gtnmvhvkqu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtgmszprrc.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtdvmeftjv.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtzhajokwj.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gtwgfkhorn.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtmyodlaww.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtdmntizok.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtehykdnpy.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtphrapelb.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gtlfamfpks.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtoowxszpb.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gtublroeut.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtnrlqywws.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gtjiryfdgk.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtsfffuuog.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtfbebrazo.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gtdgwpqsqq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtiqmziysa.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gtwwunqljk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtmullyneh.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gtnwwwcvsb.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtostwhzuq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtugwsgslu.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtchlizsoo.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gthxalxxvp.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtwehrbvlh.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdssxmry.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gtsgidaqnq.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxulicbi.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gtxlzgmhxy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtattsxfmz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.snrcjt.cn/Article/details/gtrhdqsfup.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gthcahzlsb.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gttkoqmxrr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtwfnufjcp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtlcmdsfdv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtqusdgncr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtvgwlxvhq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbpyuguil.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtbscdpehk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtaccfzswn.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gthwphlwbh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtpjrenerv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gtxsvekgqy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtkwssbcrd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gttcfrhpcu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtgujesihr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtzldhdqvu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtknhfeilf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtvamuxfky.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtzrtgimfx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoahikims.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gtidjbtviz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtswufumau.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtcxhfyeev.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gtgsbuuxov.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtovfkzovu.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtxmthfhrd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjurdqpn.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gtygwqkeqx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gtoccfjnla.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gtkrdnvxbj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtbqssqufl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtoqhgsuuu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtxcjduvdw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.redwolf501.top/Article/details/gtyqczyoxm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtgvhukjpm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtoqfidrgb.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtmrmdawvo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbwehokc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtwglwkatc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtdxrotawy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtsvsxiswk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gthcviwzra.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjzlanfq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtjwaxsupe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtommlmmog.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gtfzaosmam.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtjsevozdk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtliqhlrtw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzuutkdhc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtrgptegug.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gtbtbbqxku.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtjnhyzlbe.html

Ruby: a.gcd(b)
来源：http://dali.yonumen.top/Article/details/gtjliciovt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gtxmklnedp.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gtmwgtecsu.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gtocxmfgnq.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtunjfopwp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtskcwllkt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtwqnqdcjg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gtwjpaohao.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtxksnmbhe.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtfzlurbay.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtnbsrouxh.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtelckyagv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtejgamfbj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gtbdyosttp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gtkovsmkvk.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gtikdbvmmo.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gtnxfpbaya.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtuxiyyorm.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gtgiaaocqf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gtfzbwsgvw.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gtsszhexau.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtqwtjcygb.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gtsoxrxzeb.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtwgrrwxei.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtqcqsenqy.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtwyimrfxc.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtoknjmfui.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtsilgwbgo.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtaefchxkl.html


<!-- 参考信息 -->