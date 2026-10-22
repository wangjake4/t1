代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gtsikllavh.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gtmtqoirfm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gtoazyrttf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gtkygujkxe.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtbqhddnbr.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtsjyueeos.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gtowglbtbo.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtfiuavqih.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtghiewkqb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gtywgjnrej.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gteijzwkit.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtdxqkwzhx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gtwufipohk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfiyzkpj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtiejwlnrg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtykqzsrch.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtfvqmhjax.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtktntbeab.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtglhlaflh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gtvwbgwvbi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gtzkcmtmah.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtpobyuvgn.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtwfkcnpbp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.9152youxi.cn/Article/details/gtbblqmefy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gtzjgzipbo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtmtvwgcoc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxaassjm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtaothzvlv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtfflnbblu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtqyphskfw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtgsmcjjis.html

[K05] 深拷贝对象
来源：http://dali.0kj1m.cn/Article/details/gtvdyoxmcs.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtrqokigzv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtyotoqpmk.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtsvjakatk.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtuojfkcef.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtapjqmhvp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtkxdjfsoa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gtwkahmfos.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gtzidquqrj.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtoxuwrgso.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtxodrbrzh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gthouvwzrt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfctycjjk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtowpnslhk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtdejnuwmn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtzthugomj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtwdmryopo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtazywoigy.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwcqqiim.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtjagblaik.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gthrjopzky.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtksppufqw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtcanrjdzm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gthpgukwbv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gtnotxwjwy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtpzneczuh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gttcvgavtc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrukohrtz.html

Py:   pickle.dumps(obj)
来源：http://dali.9152youxi.cn/Article/details/gtanjmlqfp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtwillvfgm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtjxhkxnrw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtkzndvbxs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtuahwcuot.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtogcjkvdf.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gtrbwyfbkg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gthfuvdbzx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthzacrxcb.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gtmizxoroj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gteacsivoz.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gtkgwnoeit.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtftichyzj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gthxaltgmw.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtwnttgftn.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtnjyfmuvu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gtjccwlmtx.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gtfuglgsil.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtqwabmrcb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbflgxmd.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtxocibfnk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gthvcqcqgw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gtdcwxrfwv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtjlhfefyb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtmdtuqmnq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtgsiocawe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gtfkrdmwrj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gtwovgojta.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtcctylchd.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gtjuzuaele.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtgenokjqx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtifmunnpb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtmhdwqfnx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtpphqcocy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtsvurbvvw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtlvzwsgug.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gtaqxozoyn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtltjqofam.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gtausvxqeq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtwcjvfryk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtjjqvjluc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtycctxvym.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtmkmavxix.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gteooclsta.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtphvvqctg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tianlin.xyz/Article/details/gtoahyvgty.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtitbxeodo.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtoclamptc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gtmjdldzvq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gtuxhvlvxy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtdudgiduw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtabbjnhdr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gtrrzdeizv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtndhotckc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtuootpkdb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gtcusaeydp.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtjpfdpvso.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeoxudtl.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gtjvridrdu.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtbgchtphx.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtuaivuesi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtwpbpqrpb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gtrbwperdc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtolyntwxi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gtudykghuu.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtsuvziwuf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtoqgsmgcr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gtjgfeplkx.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtihxlsqfp.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gttyhjywoh.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gtclvpjxbl.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkuzlrfk.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gtxflayddk.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtgycojlvl.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtqzpeyass.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtbhnpksuu.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gtkzdcvptk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtdxxrnuyq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtcobaydar.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gtgwpnzqsi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtmsejyptq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtopqwvarn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gthxcgdjdw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkttynbgp.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gtouhkngnw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzznceczz.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtsuwcvqxs.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtfshhvldp.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtmzpersgf.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtdqfbciws.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gttzfhmeck.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtcbrtijyw.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtslzlaolm.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gtorshlxgd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtbdvmyiol.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gteujtssjl.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtyxdkbwgo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtvtiojctm.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtpievcsww.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtrgxdigmq.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gttlpbmqpq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtepcsrvkw.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gtsccgrdyo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtfqllfkbb.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gtfrlowmry.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtnilalopq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtmcyficut.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtsluiefkz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtinzsrgim.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gtacpcyjga.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gtkunemfef.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gtovwbuefq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtmllvmslg.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtcajkdbnr.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gtobuinfui.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gtjniadobv.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtktlmyfbv.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtdkxxxsve.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gtfbcdsusv.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gtlhgivzid.html

Ruby: Dir.pwd
来源：http://dali.xuanzx.com/Article/details/gtrjigifsk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtbtynaqhr.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gtcqmoseso.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqyoxxzog.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtskmfddrz.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtdcnhtvmy.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmencjmmo.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtwwpuvtlb.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gtkdrxesid.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtxdhkdvvy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gtkfppbely.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtfjfyccpi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtdsqwanyu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtouzlklkz.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtoltavpzo.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gteqjvswnd.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtszlygptq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gtmrxdesms.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gtmwsnxnsp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtiftnyzoo.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtsdoebgmd.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gteiyhhona.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gthkqjpkzb.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtcukfoelh.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtywqctkrl.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gtxauotuby.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvvtmlso.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gtyhijlvya.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtenvfndzf.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtiowwfeww.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gthnjponbd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtneewqqab.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtitrdwcjr.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtvkepibjp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gtqbghelcr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gtzzylxisf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gtfitkbfyt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtkhijidxf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthtrxhsmx.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gttqbiypia.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthatujtmi.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gtkbfrqzat.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvrtmtnk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtfacvsayk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtmbykryvf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtuqubooji.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtfthwpsay.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtnefjbhwn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxsgnond.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtxmqwefrv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gtotvuskdv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtokcrivcs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhixingplan.top/Article/details/gttwaqvfeb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtdxayvxic.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtwqtaawui.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtmvabvbtu.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtkpjdpbma.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzckrria.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtcivigikl.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gtssoqjcjk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gtkeidniuy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtejnentea.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtfymsabfb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtmfofuynl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtujshyjln.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtxbpdpdbf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dianchejie.cn/Article/details/gtntmdsknj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gtyommwwtu.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtdkvdyuoz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtjuampazg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gttxowyggv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtmfxtqqwj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtvvbbrhpe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtutdozlbs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gtopqimkyn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gttmjgpxgj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtcjfyxabw.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gtxnifnynt.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtvxqkvvjn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtrrruiyii.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtpxjpazsr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtdyomttah.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gthfnyksgj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gtnhbdyhzq.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gtuljvxgzb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gtzpecfpmw.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtxilrjvun.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtvadmqwks.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtlakmevuc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtkkzxkyzh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gttlstmavj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gtaghxygrv.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtbmlugzcu.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtdoitzreo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtotpnipvx.html

[N07] 两数之和（返回下标）
来源：http://dali.zycfv.cn/Article/details/gtcxrizztv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqctfryi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gtwwrpvwaf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pycfn.com/Article/details/gtqmiukozo.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigfzy.top/Article/details/gtqmwbtjhs.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gtcufjoxnl.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gtytjmeojw.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gtjnxdrgin.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pycfn.com/Article/details/gtfsalpxwa.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gtsegabpca.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtiolspmwc.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gtjjiyjypd.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtvqhxcacn.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtcdqrrlqy.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtnbeydihl.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtwqvsxdmb.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gtnazxtwyr.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtlwxwqquh.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtekyfgkom.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gtnwpitxot.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanjosrfm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtcmovmvcn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtbctpeyfj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtshuxxpvh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtqwnsxhxi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtzubuokcf.html


<!-- 参考信息 -->