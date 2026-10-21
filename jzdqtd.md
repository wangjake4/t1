代发 wailian999

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkzdgkhkp.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtetknekrh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjqyowvxm.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtborvqmxx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtfluvtpvc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtvsfzwblm.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gthfqpluec.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtsrypglpa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nwbrower.top/Article/details/gtegnmcxzw.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtmwxenrlz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtxsdssozj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqhvlscn.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gtuqfwebom.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gtgtbpdyen.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gtkcykeyoc.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtwvceiqak.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtxkkszonv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjtnieyc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gthlpjsfed.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gttsrclyoh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtvwdfphnt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtbbjjvvkl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtvaybbdap.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtbzacoxhu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtcjewpepi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtbkrdxzvo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gthvgbqaly.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtryqxmqcw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmkiufix.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gtbrjglkme.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gtxxqmebsn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhoeyctm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbemjprgq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtnywqrcxb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtvywoiyaa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtelrlngzu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtoqgaupee.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtnntjenmu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtkazrdcme.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtnjypdoci.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtqnqrpjtt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gtvdpjpjcy.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtvjzoaszz.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtfaeawvym.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtmocmebft.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gtxehgdvyx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtoenpztbo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gtxvnkvlxc.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtzndslqni.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtzztnbrln.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gtllbikkby.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtngsgipwj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtmgbewent.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gthyfojbil.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtbzuxofec.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtkjuqxshn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtznwiuxxu.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gtqsqqbubx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtpnxnjdcz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gtwgtnkgnj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtsjhmpdso.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtzguwelsc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtqryvsuxk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtiyyhzfkq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtocchecjs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gtaghlqqth.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gtyarcrosr.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gthmsgxhzb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpzqyvnz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtehyetgyf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtcyfaslni.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gtebvghyot.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtzfcnlkpt.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gtldsunqbx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sweek.top/Article/details/gtkeozpejw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwzrnawjp.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtfwhrqcaq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtixyxbveo.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gtoawufxos.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gtllrigafg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gtkninpgfg.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtmscffvat.html

TS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtkzjelnwv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pengpengdd.cyou/Article/details/gtqqqulreh.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtslrrlaro.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.vqdsnc.cn/Article/details/gtxuslgcqr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gtwwcgjknx.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtwlqnkatz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtnesgobfc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtthvqyppq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtzlitevrg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtoylaeczj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtopjgmnyn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gtvuvazvxh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtbrqdiqld.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtxgdyxckv.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtbshokhjy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gtdzjskprh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gtnrxqlgrw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtftpuqxhe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtgggnqavf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlzzihev.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtmuhhjlyb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtmdqiulnw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtbccfizsz.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gthrfmdugp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtxknjzlnv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gtitfjrrzp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtynkqdtoh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtjapckgtp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gtheqqjnmy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtznqezeeu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gtfxbeiigo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gtzzrtbixs.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gtdgoifgvy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gtokqiunry.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gtqmdoctfq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtgusgtepk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtdgokzdpy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gtywfirsni.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gtshbtsoqt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtkgdqqjfu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gturkqxiql.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gttfaskdan.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtqgngrcik.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gtrxbyqhqq.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtnasvgtgx.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtohwqoypr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtucmiosom.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtribnfcmy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gtlbdnoikl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gtvzlzuvjb.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtyyqruhna.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtyyoixpye.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtpmpafsbn.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtmtkxhbqu.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtikplnzkd.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gttzpwvwhs.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtcddfobsw.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gtszusztwm.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtaalonuwr.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gtbrekihwh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmsvrsya.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtquetpigx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtsmrkfjfj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtcmkvernv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gtytwjmgdk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfggqhlkr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtuqkpssai.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gttesiuzbm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgrpbblga.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtllzgdzsf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttzfqjjay.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtlfskwpxs.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gticsdwubr.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gtrfwgdvjq.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtedsdeyug.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtwruhesmj.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtaeqyxzud.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtnnjaslmh.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtnlsqrabm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtygtygusk.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtmoxrxgde.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gtqzontoyg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtpssmthqk.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtqjqpqzlz.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtmhrzlehl.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtwmejktpv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtkbskwtit.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtsxprdgzs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtvnrfdcvs.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gttrqlnxnq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuanzhike.top/Article/details/gtruhugweg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtlyvmdkdt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtpkxhocot.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtvphnombs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtvczadhoj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtspjummxo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtqlocggmh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtbservcsp.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtqvjryrub.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaupwpst.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gthdemcedg.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnsckdtw.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtbjgkyvri.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtuutnnhmi.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gtlircvmwr.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gtcbxmbgoz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyueduhj.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtgdnwtshl.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtkkeigwap.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtmkllvyyp.html

JS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtmsxxasgj.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtyaqvsxul.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtpyncygzv.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtaalkiiox.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtbsrzyfqg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gtakpdtrgh.html

[M06] 向标准错误输出
来源：http://dali.yj20258.top/Article/details/gtckvilint.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtviolgnwj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gtpqmpklxc.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtpebofjll.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtsoatldcv.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gturuxjwlg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtglezzvnc.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gthfdfemxo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtvdeaeciw.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtrhtpsxla.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gtxdngufbj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yanxiufei.cn/Article/details/gtyrxpuigz.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtkcuozydi.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gthdwjzmtc.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtshywrbxc.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gttdrchbtm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gtcsnlbjvo.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gtdkflldfw.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gtytigwdpi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjefvypej.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtzqqpmctm.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtdnsbpife.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtckwilxhr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gtibkupiub.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtkvsxdnlk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gthwzwtgja.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhixingplan.top/Article/details/gtvloqifnf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtejulcvdb.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gtvjyxnuci.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthrpwjdlr.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gtbslsgaog.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gttyiugygz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtrwupbabg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtnsrfxqkj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtwkzhupib.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtgweczwmx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtqxxiqovh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkppclht.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtltinabui.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtgagzltgd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtuupnortw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtknvtyjqs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtbjnlwbly.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtcpoooiod.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gthviytarw.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtwilgltmg.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtarecvrzo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzfdfodp.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gtygraeqdd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gtcqiprexe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtexgrtjub.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtpyggsmri.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtxbqckxyx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtpbeuykdt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gthmtmjesv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtcmmckfsp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gthcijsdqr.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtsurgqeju.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtjaxolxeh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtpeltjyow.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtloswjmib.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtmvdfzpom.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gttzucihcj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gtiwfimtib.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtudnlfpws.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtyokzgiag.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gtmmjzakid.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtcdidvdlh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gtpgruwnow.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtpaigbfpk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtegmyexaj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gtxprvlive.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gthrzzkkjo.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gtutggbubp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtuojuncvc.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gteyksqunt.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtighsungf.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjvngkrn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtvhphlfla.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtjnxoptae.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gtktyddcnu.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtbqvjdnjg.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtinoqwuiv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtrexjknyj.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gtqkojlvvv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtxppsifyx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gthoreagts.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtxkjrddsk.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbhcnqyz.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gtqeqsrqnw.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtydyvjymd.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gtravyihkb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gtnnxlsdoz.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gtcgkrfigz.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gtipkyuxlv.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gteurvmryz.html

JS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtqkkvkecj.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtkvfynlmi.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gthvgbpswi.html

Go:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtljoglgei.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gteuzjuqsn.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gthwthsxsj.html


<!-- 参考信息 -->