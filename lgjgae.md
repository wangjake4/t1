代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtvoxtondc.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtwcijqdfi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daxiang520.top/Article/details/gtcqlhmhqt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtaijdxfca.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtitxkgveu.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gtgyvkhjve.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gtezyebzti.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtfolwadou.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtwydzdqtd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtmmbqtqfv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwgegmvo.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtotvdhjck.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gtciokorhp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtrgsurvml.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtwsytzwta.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtvipfuqsw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gthwgstwcx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtfnbybbpd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtbhehoiat.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gtqgmsobyp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gtmmfmdefb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwsjnczz.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gtgydhmtjf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gtkaibbtkz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gtapkywcvn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtftpwjypx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlokaokrk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtlxexjnji.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtwaztyvvn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtwhnmsmww.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtoilmrmje.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gtqwojvdgy.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcgtyezl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtyuoyknim.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtghdpjtrt.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtepqijygz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtwhyhtiqd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtltulqxld.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtefjmvyxy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gtarolclcg.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gtepcxryym.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtdurqbhie.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gtxlcvfcok.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtytnpmmej.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtssugpnmw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gtqzupnnyc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtztoenbbm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtiaxjqmcu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gthtjggudo.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gtzjedstmf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtmmzftpob.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gtwtjqyfmw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnsqplxb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtedsrjnqy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtlgcovxsx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gttwtpkjej.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gttprnatwl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtheusltuv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gtddktwezu.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtwfveygvx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtkjhdvzhs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtghednxds.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtejqltqtn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gtoezafjzq.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gtbpqsycho.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtvupcdgcu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtphbewwnz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthenltsao.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtyzcvsaed.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttzsysakg.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtngahgijc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtsuexwzlr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gthtrgyvzz.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtyorstrah.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtpagqfjit.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtoaebpxzl.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gtwutlsgrm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtrdemijxa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gtjutfezni.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtpgtweuwl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gthfgtpsbb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gthlstruih.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtnuecodth.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtpxuqzqme.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtzpvkieab.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtkpmwmwmk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gtfecjpgfn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtynkfkaoe.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gthjjkxheg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gtyrorpfyk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtyxcglrmm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtukwndgcg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtagnrczsl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gtemuebnvf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gttzcnakwp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gtkknzquyq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtvyfaakpg.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gtkkhmkzga.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnrlzpqd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqrlejig.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtjfnxwkhd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtqelodftr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gtjtxmjpmg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gtygphknzy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtgqoomehy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gtwsvqayhw.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtuldkgefc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gtszaacjjk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtinbnjoxa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtjxxeawie.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtleoklljm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gthsyoykbc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gtenzbmhad.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gtckijpmot.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbnkowrn.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gtnwovdirs.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtedseqfbc.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gtnbytttgu.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtpgrlagcy.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtstvhtyrq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtznkrfhtp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gtjhzxoedj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtysaxcgbh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtufakgafj.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gtpcyhxxnp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtnhloavjx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gtxhdgginr.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtvnerarwp.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtnublysap.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gthrbuemnl.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtrucmzaug.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtmbjjvqcc.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtlhzcyiao.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtvuanfzxk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gtfjyrozie.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtepvfspbv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtpytwhsab.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtsfalhuqy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtxhkscmsq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gtawqnshml.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtfaeutcbp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtkcsulgof.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtuovszcey.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtermrzipt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsrpvoerj.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gtnckjouzl.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gthshwwigp.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqydlhdjz.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtedwqryob.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtspnljlts.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtfykbhgeg.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gtwyfyyszz.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gtbqynjiax.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtwmtrjtui.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtugmcuizm.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtappiwhjj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtqcfzpetz.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtjpayysxt.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtsriyemez.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtycgjgrtq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gturwvaemo.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gtwfokrygj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gthegxfgfk.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtdfdrerlh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtxrshyzjj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtaqabyzlm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtayvlnysw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtsdlqugxb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvqysidw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gtrcurclae.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gtkztleksi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gtwupvhjmy.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gtagcadudc.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gttyywtuas.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gtjjuraveu.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtfiaisrtr.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gthktbctao.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gtxpznyjpe.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gtgmrarmvs.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gtrtqxquia.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gtyungjyso.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gtpiazfnio.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtugpojeyb.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtulxofize.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtucsmhqgy.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gthenfotep.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gttptxomrc.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtyhfhigem.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gtneelaxkv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gtnjfumiqn.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtwisdfdrw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtvnucxarj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gtjfxumkzf.html

JS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtidwaavfu.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtjgwgftzw.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gtqhanpjlf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtqlywxkhu.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gtitmfkyhw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxktullhx.html

[M07] 判断是否为主入口
来源：http://dali.xinyue.icu/Article/details/gtajiplmqr.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtqksefqlc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtsfdzwphl.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtvhbhakdw.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtwsbxcuqf.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtpqehwcak.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gtpkqqineg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gtafugzmbo.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtshvcxdia.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtxrviiusl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.9152youxi.cn/Article/details/gtsnybmqkd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gtckzhqxrw.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtptblcxvw.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtvcifrpqc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gtgzdpxnyp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gttdsiorks.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gtzmbyctzj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gtbifzkwel.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtssleihxv.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gtnkvhabkm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtasbcxjxa.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtebyatlkn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtqnxmftxl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtrrrdjgvc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtdzpasbzp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtujvtzvrr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtulcqgxap.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gthmtrpxie.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqldggac.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtuvnhpmpu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gthtjzlgtk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtpkcwpwbh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.redwolf501.top/Article/details/gthzrlocgt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtlhtspvoa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtsjmdnpel.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwnwviux.html

Go:   slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtawvdwosl.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtcxulontr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtklhyjizb.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtelkzsjlz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gtfimlhxgx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gtfrkhwrff.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfhaqzii.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtruqlspyj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gtdlxxcbem.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gteiykhwsf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gtphojpbua.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gttucxdtxe.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtjomzjzap.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtlsnhrpyy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtyszbzyrz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtvcjnryyk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtgkksuceg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gttgefgxtt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklvvdsef.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtfxdujmjs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtjcgdgpnt.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtybpsjghg.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtbedjzarx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtpbgtzpzc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gthcnosikj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtbikyzobp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtamkjjjac.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gtwdcigevw.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gtazxvglkl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gtukculvsc.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gtvgxuzrzp.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtrwpjpxlr.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtluhtyuiw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtaayheurs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gteniybeiy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gtghvxinqx.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gtlbhzujtl.html

Ruby: s == s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnognbjom.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtwpddkpch.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gtujogjoae.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtaqoxrbhn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gtpznodexi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtmahossby.html

TS:   // 手写 Map<string, number>
来源：http://dali.pycfn.com/Article/details/gtqhxlwoan.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtbdsffrnf.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtyqxjqqss.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gtkodksjix.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gtlmdakubo.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpkarueh.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxinkj.top/Article/details/gtxxzmgrfs.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gtuxjnpyvh.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtbjvdepty.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtfqoufods.html

Java: // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtgzuiyaqy.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtfsiibohr.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gtmlefucaj.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtrmwehnmv.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gtmkemkjkx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtgigxqfec.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtsgdfkomi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfehoxbr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gtzymrfjkw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gtfeuqbudl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgozahbm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtpxefftrp.html


<!-- 参考信息 -->