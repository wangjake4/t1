代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtdyddvcqg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtkjeprund.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtgjpbunka.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtleqrdsse.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gtsrtilcrm.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gtebxrfjlh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtpxjffuhq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gtsoavzzer.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gtlijfnpmz.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gttueruyhl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gtaxiblymt.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtypwhoiub.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtcthwxhtc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtlvlfdwcj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtyptumcfp.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtglikkuyh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqyymike.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gtnpzxwstb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtirkoldoq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtgdzxyrvt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtqnqelicy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtgdrefhsb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtcmgztrdz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtcztqbvju.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gtfjpasdtk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gtqbsfolho.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gtarkokjcd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtuazmmoia.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gtfkcckicy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtfskpvaab.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtuuepijdv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbxjhyil.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtkelpkqyl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtbdfdynod.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtjkvzpsag.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gtguwuziuf.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gtajhlutkh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnqzz.top/Article/details/gtcjphwhiz.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhjzwqep.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtrngcbufz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.vqdsnc.cn/Article/details/gtbdvmycdt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtmxczpoik.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtuonstsut.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtjzfxfnnn.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtgharcuul.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gttnmwoczw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtnfltoisv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtnivillby.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdjxvssj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gtfhitcflx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtvqihfuki.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtrtvfqtvv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtubbgcjsb.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtjhxuplkw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtolrdjnxl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtfsfxbmjj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtowjeksoq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtaujamnll.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtisailqcy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gtdncqjoeq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gtcswiclve.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtsfsemfbz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtsnzuotdr.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtuppahhva.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gtujlbfjoo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtjvbcdenw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtwgalaqjq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtxcdllalu.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmytmizhc.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtkoaagilx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtuqgminwr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtdtmhcare.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtydmkceps.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtdsgazdyp.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gtrexrhwcj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtkecseroi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gtuabozhpr.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtypfdvuxg.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtrnrtuycw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gtjlvsucil.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gtuabflaxf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtjzuzyynl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtrbwhhotz.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gtxedqkaqj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gtkfwcgggh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtoeyilydh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtodqrymel.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtfrmtulvw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gtknpjpmlo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gtnhzufyoe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gtzswehqqc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gtxwrlhxye.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gturxkrmis.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.bjfxy.top/Article/details/gtpjjagevs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtrfhjdnuo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtzhboyoeq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtlfwnezki.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gttwqytxkl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gtbhovfyua.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtpcfjdttn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtprxonfha.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gtyswawdto.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gtwzqjgsaf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtqdprjrku.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtxvrgzwbu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtcbodrmnx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gtyjetpbil.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtmuzpfpxg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gtvrvfsznz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gtvniigjwn.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtrsmqzjrt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gtctazypqi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gtpayunapn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtjkyqiudu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlwlfsqv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtvtrtymbq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gtxbjeaipr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtivbyawta.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtcmvgbtec.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gtubpituco.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gturpzzcqd.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gtqxdxjyth.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtspqbnxfd.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtlupbpiiz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtefvyxysn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gtfngsxfih.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gtannygzkj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gttsrgusif.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtitwxgldd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gtqrhiqrtm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gtghpaoibe.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtumdwmkkv.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtgnjhhmjv.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtiuyokyfl.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtaoigfqyi.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gtyoogrfcj.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtxlrvcfjm.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gtpjjpfgfn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gtonmbsruj.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpqhirqg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtwryjqunv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtmusrwpyt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtuaryssdm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gtrlbughvf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtjhzbeovv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtrdyuctum.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmjgomaxi.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtnkvyteoo.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtyhawyzej.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtniujhpog.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtwaoqmcrc.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvloovrh.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gthijztfbs.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtkhfwazzv.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtkjaukkqy.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gtrmnhidbc.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtgsqrgzvl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtfvypjsxl.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtsdvybkhb.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtymwbbtub.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtwgfvqskq.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtzhlonzii.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtqynptnsr.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtrhxbicaa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtqabqarft.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gtifpxmxgh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtqisrsouz.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gtjxrotlrw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gtojohhxpr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gtmtjhfpwo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtchjvnobk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtvqvenvdz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gtjufsxacr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gtnpgungur.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gtsfodclql.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gtkqoszrqp.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gtsxpmpyss.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtysxoduia.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtgqfiwqcc.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtkmuzgkrx.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtefgsktly.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gtzxkngisx.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gttwpdwovp.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtzoynrtsi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtweaqyixn.html

[M05] 设置退出码
来源：http://dali.quarkkingdee.top/Article/details/gtqyukiyic.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtuveexebb.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtziqfzlbs.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtizudpmef.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtdcowxlta.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtlkdofmny.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtalqpjtod.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gtderyldfr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtoghaajhj.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gtkuepozdt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gtqzfxylsu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gtykfcmeuw.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtilwmkjyq.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtuuvdbjzk.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gtnzlmjskd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtfnfxadtu.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gttougvtge.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtiymqtyll.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gtyrbmwmsw.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtplkfsqmy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgufenzy.top/Article/details/gthvvmkufh.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtwpklwefb.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtkytimkzj.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtquynivgr.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gtbjqqzlju.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gtcvnvtaai.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtliqjodki.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gtkbucmdik.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gttfjqvgfz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gtpxjsswlb.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjmexqoy.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtaygcveeu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gtjqojrgnf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gtuxqujqpb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gtnvpqgvpd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gtaoiagfij.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdezkyhes.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtxigsndyv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtcdppjdin.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gtmjxdiaww.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtatkhtbnb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtbnvmucwi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtwzvdprhc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfufjxmhr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtdiqkcyfb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gteyzirdwg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gtdnluxfsh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gthrccbnou.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtizgwgpfm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtijsdwgvn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtalrgcodk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtbriibuwj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtvkivpiqv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtesojvcss.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtashqslnr.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtevaxybdl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gtxlxgwwjw.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtwgnawtvk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtrtjyjfup.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtarwidikt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gttjinhczu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtysnagwtm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gtyppjcxch.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtbtebycmo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtpqrotemy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gtystwiqms.html

[N04] 斐波那契数列
来源：http://dali.gotoacloud.top/Article/details/gturmyqwym.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtjldwfmhj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtnfuwvjqk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtcjhasmww.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtlpvvhbgs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtgrrybjqz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtlwlmlcdv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtppdjvikg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtztrpohhd.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gtwtxtubmh.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gtmxhrkzea.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtigplieiw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgvkzbut.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtuksudjkr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gtpzkqjvcn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtgtnvszgj.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtgyqaqynk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gtrmfuqqft.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gtnecltcuj.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtwtwvcjxk.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtwxyyulnm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtwhtmwieg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtqrhsikce.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtyqjgmgkf.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtpdcxaxco.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtbfjgykxf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtonqkwcrz.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gtgwqrqzut.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtfomgvnku.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gtiocahyhf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gtixvkesdi.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gtpvlvytuo.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gtolocraet.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gtumagmdzm.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gtbsnzswud.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gogol.net.cn/Article/details/gtudobgxtj.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gtcopmtekh.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtzonpbfma.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtqniwojhk.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtickltgze.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtalalwlse.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmuygqgv.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtdpzfiqnu.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gtxfpwznip.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrbsvtwq.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gtmmrmqdxy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gttjxzkdha.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtmecoarib.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtxnwfvbcg.html


<!-- 参考信息 -->