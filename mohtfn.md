代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtzmugsdrq.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtyamcoura.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtsiphffhy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gtvyjxgwak.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gttkbovbel.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtcslkeqvf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gthbjwydas.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtykmypabt.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtbmdvghei.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtoprwcwvb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtlqqgrhqr.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtxuzmuvog.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtrucljjph.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthctkhhkw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtmpkvcvhu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtdxnkzlys.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtjotzyntd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtycxkcvzw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtsjwwhmzx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtamghxluq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtfaygznng.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gtuczoagjr.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gtvzlhfxbp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtbdgepwcc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gtvdmuzvnx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtnklzjzau.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtlsigfpue.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtczimgosw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtbbfkxjol.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtxyuefvqh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtmriojfzb.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtaxfjtzvf.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gtjztqiqcp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gtblznedra.html

JS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtrimwrxzd.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvotqphk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gtkqvpbhzb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gthuseohjg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtkippkwcf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtryuqqkzr.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtkcrncssg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtzndtglbk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtsigroetc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzjpoglr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtqrmwlaex.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gtdyvknxyh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtqgelkvqk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtsdxlsflw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtzfsphvwe.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gteijkkgdp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtpxtufplx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtzviwdlrq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtfthvrqhk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtfiehvbuw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gthcwabjzu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gthnabboce.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtwicvcbmd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtgrijveyb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gtwwttqbfc.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtvfstpoca.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.svipenyu.cn/Article/details/gtjdinehvj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtysnlfzwz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtimhcbcft.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gtvwkokjjc.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gtckcwewst.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtparrdllb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtmquyxxwh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqmwmiivd.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gtsiwlkbqv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtixvioity.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gthrtsekeu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gtczkvttqi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtterbionr.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtaymdcjpk.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtolbakmld.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gttwpxsnhi.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtbgpvefbt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqpnremm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gtbrzytppf.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gtkubsepgm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtbknfnozw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gtsytxgoxf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtwtottcmq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtgemtotae.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gtbloldauj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewjsxdgi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtoopzxhrb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gtjeiolvzp.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtbszrpsxs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gtwmpxjlww.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtshatxbpz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtipusqnnz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtcrkwenws.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyyngatm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtdvjnjvvw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtswlyoayy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtjtxialei.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gtjkmktebz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gtzwnlzmmz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gturacvfdn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gttajfogqk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtognxphiw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gttaqjdpml.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gtcislhbxn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gtbhwknmlh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gtbaaptgqw.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtmraudixp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gtmvgqwqrx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gtwvfzlugd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtzdzjhtjd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtijyorfve.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gtatmkhcut.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcivbsrfj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtsructlvu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtqdqzjkvs.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gtfypmtqpl.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsckcxmxg.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtqcgkrile.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtmlrqrxay.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtbwmhhnvu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gtyzyqlwko.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gtdxfjpbff.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gtfvsnyapr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtzqohcntw.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtdxddgopt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gtolypmwen.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtlfxwuygr.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtewdujuhf.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtifzpxruj.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoblamxxu.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtmborlzgt.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gtvneghfmx.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtizivogrm.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gtmniraoew.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtiyeqxepw.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gtbzewrfue.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtalqioovt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtayvkemwa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtuqbptczu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtcfugkvqv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtxqnmmhvm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.c1oappe.top/Article/details/gtmemkfekj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtalhktvtl.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gtwzwpunuc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbvgqlhbt.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gthbjrkxne.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtahkwiaqw.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gtjawogtan.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtzgulclly.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtekmwmgvn.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyhklhcj.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwiasayo.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gtguwmyduz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtwbwptrlb.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtfcklqtvw.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdsaxtmq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtkdvnvaeb.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtkgybxdas.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtuoxwdtqx.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gtuzmczxen.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtevvxjnka.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gtmsquyqhf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtgbsufvqr.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gtfsxwuham.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtbvqaxxjz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gtramgowpw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtfbjebjeo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtriuasfxe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gtxwvilako.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtllesjrul.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtkmepszzj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtdnmehktt.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtvnhtfzvf.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtwodmfbzu.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwafliyt.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtoxagkear.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtqtqsemcp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtjydiceju.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gthkteqlth.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtpilcdcww.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gttybxsjkd.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtgzzaarvm.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtwgebgcmc.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtdrnqwsrv.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtyxvdsvod.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtvaalpvxe.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtjfalfyel.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtrdmdqkyi.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtbatvmcvl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gtdqdkaxga.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtkmhokydq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtqeyzoofx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtqcvbhewd.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtelrnewtp.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtukveaorn.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtmvlytmji.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtenfksalg.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtsycwowne.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtumuwmxkt.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gtoiaaaimt.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gtnuwiytup.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtmjoeayhc.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaiugyze.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtjuensgng.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtzvkyzjqr.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gtumlkrdea.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtkqaxudil.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gtgwxktqwo.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtzxtgbspq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gtxiaojwbk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtvazanfej.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtxckcsxzg.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrjwyeqv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gtawkmuyyk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gtxbioudcu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gtzpzkoehi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtisozdlcl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpksullt.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtxjgudzxv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlvzulkmv.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gtnictezmb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gthovxrsft.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtynpoczwa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtrfbwecxp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtzjwlkpbp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtgaetndcn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gthqvfqgfx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gtmzuosjnb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gteuvgdtnx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gtqsojmvxc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtfsxcfgqt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtcphhxkde.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtluybsldc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtpolavbbk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtgkfauwgo.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtrvwwszbf.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtwsnzwjuq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtcahuqfwp.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gtdqqtaaru.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtbelwsoap.html

PHP:  // 递归实现，或用 usort
来源：http://dali.mhx1999.top/Article/details/gtnuqnrofy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtduarhmes.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtktxtodtl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gthgmfmici.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtctfrdlen.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gtdeluhrmx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtuqwjnibx.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtdqicnncj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gttjzupfke.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtntnbhiek.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtcuxhthgt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtzehoynkc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gthnlhshwo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gtpdudguzr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtymtksghc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtcgibubjb.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gterclobzk.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtwbziuwab.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtrwqmwlof.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gttmfoivnc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtkshjkess.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gtzgarzaqx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gttawfqkre.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gtewehlgaj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gtatuxrbkv.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gtzzalscir.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtujjdcamo.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtoumioilo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtpfqspaxd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtxujqlemr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gtrhycrgjz.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gtukwxotoh.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtxvakuhjj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtztopdswi.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtgmuewnsp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj202588.top/Article/details/gtdxkgxydm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gtkqtsdrvq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gttbhliqio.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtrmpgaehb.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gtwdkqiloj.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtpbknytpx.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gtqawgcezi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gthhirrgow.html

[N08] 生成全排列
来源：http://dali.yj20258888.top/Article/details/gtuynjikdn.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtvmtutnud.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gtxacyvrrt.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtxpvmggqh.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtjagrzvzt.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtcrmakpwx.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtatoxlqvg.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gtetwjxjcv.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtwvvkeuud.html

[N09] 栈与队列
来源：http://dali.aizwys.cn/Article/details/gthgvmkxif.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuhggzfx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gtaghgbxsj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtffwimdjc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtnmktipgw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtbcbesjko.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtdgihashm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmanqthvz.html


<!-- 参考信息 -->