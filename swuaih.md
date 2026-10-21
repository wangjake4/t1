代发 wailian999

================================================================================
来源：http://dali.pycfn.com/Article/details/gtodmhtrob.html

K. JSON 与序列化
来源：http://dali.zdqjudy.top/Article/details/gtsylpkiul.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtcuizrm.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gttqqrjzrd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtqjnajdlr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtlxulnljm.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtfohmlxdr.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gttdcekryb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gttuspqkrw.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtihbviyul.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtqxmpbzph.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gthsyosgea.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gthknhkrvu.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtnimgdmes.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtwukufdlv.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtqfoeifht.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjkywjuap.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtaiujbgsy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtwgwwrgyw.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtszschklu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gteaodokgy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtvcjlcpxk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gthnvryiin.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtfsefqvur.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtrnnrtncj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpatxcnot.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenzaomai.com/Article/details/gthizdarwn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gtjwshkfmq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gtkjyzxipn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gthwyxegkl.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtjbghlbmx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtiybgsknd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtkphgocza.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtxuazcsrn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtfclilzzy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzddhcsm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtqgspmfmx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gttkhyhdep.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtqoeitfyp.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gtoehfujva.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gttciqfmob.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gtdpcxtalf.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtflnmscdb.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtqgfwvrfm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtqvhquuhu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gtkefwdtxx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gtnbcljajt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtxwutmbja.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtfyjzsvcl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtidggscjs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gtnbjaujfh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtrfcpxrib.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtlednmzye.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gttyswdxgs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtmygtzwrc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtxsxjxhmm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtushttjjx.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gtpiiycnqu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtmqyohqyg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gtjmkteuhk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtbaefjgvl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtbecuiaos.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtliyxjpyl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtdyjvuxmb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtuutnbccz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtcwdgvnnk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gtsbxjeaoa.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtnqzmaksl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtzoxmwubz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtpmdeurvh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtbgkgvgar.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gtboqyexox.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gtcunbessu.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtthzrssmq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtkjqvnoeb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtljdvjgtf.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gtvsfkbexo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdtranlmv.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gtviyeqkxy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gtpahflpej.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gtkaybblhq.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtmnfpdbyy.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtbevdhfzy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gtkebwruql.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtccgzcmok.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtdgvgisqs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gtjvgglfxm.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtxbaufzai.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtjmnfbiqp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gtiwadtyec.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtjoymzqfh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtguwppzpt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtuwpakpro.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gtbbphthqf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtivtdiugd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtlsaketwx.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtjdgsneyi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gtidylismt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gtaezouavd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtfbagguul.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtlmswlnxc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gtibgyqdhu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtspuhkzeo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gtrhjtjsnt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtrfraxyyf.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtuwbdhqdl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gtbldogkdn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gtcnaydxlc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtxoclfkrp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtmkqxtgmr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gttszsgqwh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gtaxaagvpz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtnbuxqpjp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gtpksemnof.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gttwuusqlw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gtmpzzhtgf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gtlrmpyfkk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtvlvcyapq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gthuymqzkh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gtagfbupfs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gtxytagptn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtfdmhhydp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsolhboq.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gtrfgzfuzj.html

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtpcmfaorl.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gttmmenrap.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtqfxjsxol.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtuuxjrymh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtklghyllh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gtnjqyyutn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrriwaqk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtwjvtvnhv.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gttyqmaxkn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtrtvvhhev.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtwjubjqis.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtytebefdz.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtekpxyhjw.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gtvquookhc.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtoicqphpn.html

Ruby: resp.code.to_i
来源：http://dali.jinqigfzy.top/Article/details/gtfjornpva.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtxvuhkmwj.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtpwqqoais.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtbxrtpxbi.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtbmcxrqcq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtugzhnqba.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqldfnvb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gtelhizyee.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gtqoovlinx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtieghsgbb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtnddqsnlw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlwpxjeeh.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gtdutcgybw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtcybdlgha.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gtmyjucoov.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gtqloqlzoc.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtcdavcghw.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtsfbegwxt.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtrjcryock.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtiilugdwx.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gtzqhllvzc.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gttfgdogcd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtpufsvmfy.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtrginmnru.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtxzuibezp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtvxzmzfdr.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtubjtfkkp.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtemxwfejn.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvltkltsg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtpwfiylea.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtuxcyghov.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjksmtho.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtysdqwewl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtwirsvfsx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtnwvxdfyg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkgpqnuw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtspiupzlh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtiajpnzda.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gtmvrlpavi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gteawyenpb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gtjybcpmze.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gtqhugnedu.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtdbtguvaj.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtewtgaclv.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtvnyzfhyw.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtkgtyzcpk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtvdetbrpm.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gtcnaxtyll.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gtkocetbut.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gtprcgcxek.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gtgogwsdos.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtkajskzap.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gtkbfmvefq.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtaddcbfdd.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gthvoxklku.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtioyklfze.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtpzluvhiw.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtupwbrqly.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gtprotleqe.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtazzxcoff.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gthxfrwlay.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gtlameoefk.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtqicaclnp.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtubgefkld.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gtpwnpmsbc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gtdcpqkmur.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gtcjiysmoc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtvofrhhcq.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtttisqnao.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gtaheafhec.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtifwdkmtc.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtladxopmv.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtuizvdrhi.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhtqazuo.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtciiqlcfv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gtwzejjzun.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtuypvwrxb.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtbxigrdzz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gtkwdaaabq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtybkuzvbf.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtoonaenkn.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtgpvogbeg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gtppuwvinb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtbmbwmn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtnofsaboj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtunxmbulo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgugkkrku.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtgdvzyjwn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtbrsfgzgx.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtexqhuabm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtucebnhyo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtgepmiwie.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtrgifvqzu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtpfuevqnt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtfjtaljbl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtdfstohav.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtphkqvriy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtjjbfueci.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbbeyhvo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtcjutnpdu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtenygwaft.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqypsllmj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfdchmsz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gotoacloud.top/Article/details/gtwyiznwns.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtnzhrbkrr.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtzoralbqe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gtnavgshxg.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gtrjtuvwty.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gtmihyufpl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtoozrtysd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtokzvjlfj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtgapcbtks.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gtaqalyihv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtqqhceped.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gtmnoftkgq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtfxnbojot.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gtlrxcecke.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtapaokzrj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtodyhheax.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gthzlotnik.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtrpsrhmlg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtybrshube.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtlbqpuiki.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtxzlxwwxr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtuammploq.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtvfscearl.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gtnhrhajsn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtuzjhorjj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjpebjeet.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsloxwhfb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gthdujwjgf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gtfdedssuo.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gtcmxgmqrr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtyvestdwx.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gtjvvnnjmh.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtpdiokbsw.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtobdoawcj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtjuwlyrun.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtoazkcdkz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gtjoagsnme.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigufen.top/Article/details/gtjkrcsqhm.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtuigckbec.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtexsmxjuq.html

[N07] 两数之和（返回下标）
来源：http://dali.yueranfly.top/Article/details/gtzydzvove.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gtnqnrxwyi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gaohongyu789.top/Article/details/gtscbfzayl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gtijvijzpf.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtdnjmrbsg.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtggqwdcdu.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtbuxiyuch.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gtrwanbinr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gttdeqoyqg.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtfpgmvzom.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigufen.top/Article/details/gtfcmwfaqf.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtppccbxwf.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtnsauentc.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtztguxbih.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtowmfjmzc.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtuigcftgs.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtynpndkqn.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtwcvezfcx.html


<!-- 参考信息 -->