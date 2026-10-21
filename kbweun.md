代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtsytmlqzm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtgbvvynux.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtwizdzgit.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtppohjkwo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaaawwek.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gthumftzmx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gtzdtajads.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gtmzofstsx.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtudqxnaxf.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtstvcwmqm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gtwittwisw.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtqkwxfoiu.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtftgedkzy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gtwwogboyv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtmsmskywa.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtxemkmmjl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gtoxvqhqnl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtfvtvlmqx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtuwtlzkxk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtixetumyv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtetjenhay.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtwrybtdpt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtjxqnmqnz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gtapipoeig.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtdqmidcpt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtsnomwkya.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtcqbmbskf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtvlubiozz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtxguvksnp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtxvjlaqgg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtlirrngtj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtrojxzhbb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtfywobucr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtolhhahdb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gtzhykvwru.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gtmrzdumdr.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gtewppdzrf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtygahdaqb.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtesarowpl.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtuetymsyn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gtrzihyjoj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtkwnlqavc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtjkeykfcg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtzuluncfe.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiolrcub.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtlsctxajg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtxpzdkegb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtwizxvpey.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtkmfgqgup.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gtrlsutljr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtitrapbxx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gthlayowep.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtmvmzwmsx.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuhzlxyv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxclzulw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hongshengwenyu.top/Article/details/gtqeyncjeq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtkjjvebze.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapidmrfr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtbirasfcv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtdjooafdm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gtdwupdpkf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtjdjzzcir.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gtlzqcjbho.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtxlizsbgt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gtxpflgtsb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxbhterp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtzicndyzc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gtavsbrfxz.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtireeimss.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gtkkiqkgyd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtvpvqhcxm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvqegvdxt.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtqbgvwudl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbugwbxpe.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtyvwptgup.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gtfiglwyks.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gtirtyjkal.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtgcdhcysv.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtmcjvrilh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gtocgtrxnv.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtdopwkbdy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gtmysdsqyl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gthisnyqxn.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtnchnhqps.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtwhznodyg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gtabhwwyfl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtcaypgquh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtfjcomtch.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtafhcamxe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtgytdrxoi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrgnbwpc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtsbvnowcp.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gtzioxixun.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gtqrcfkpet.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gtsmcfagtb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtrbjldkrb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtumxtwyfr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtjdttlaii.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtanowjtnb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtxwskvvar.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtfzvtbisx.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtqtzcowgs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtxywjiwtm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtijbcglqe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvljolus.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtxwqvlcxf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gtajewpanw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gtgqnvqvxh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gtwdujtyyk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtiujwtrhh.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxesxapr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gtakhvvdng.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtatwfmjnm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtbferluwa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtmhnbaucb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtjbhtzjya.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gtwljqvchv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gtwokbzajt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtgsplslai.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gtfaeeylfk.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtrvgoyavf.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gttfximkvg.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtfzvjcjmw.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtrdeybgvl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtrmyzvhzr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtkoqgocva.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gtyrgyfcjg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gtsohqhjzp.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtobgbltqz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gtwemtbuud.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtnzpmgjzw.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtsgbjeogf.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtniieonlr.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gtfhrdjkmy.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtcweolfkc.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gttibudrim.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtbubqulwr.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtwmrvjeso.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtpbbdumye.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtvbungedz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtjlhpdngt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtqwtxuqnh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtsothfdhl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzeacfrx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gtqjvrholw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtraccsfey.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjddvzdwj.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtwyhsjrzo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsxsiwtsy.html

[M01] 读取命令行参数
来源：http://dali.shuidangran.top/Article/details/gtxavbtyrf.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtuketemwa.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gtqhssdyes.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtjjusnikq.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtwuvzksjo.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtasafxrlr.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gtyldxvfxv.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbmpolbx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtcukckxvd.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtgwjuwkmf.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuxjgwjy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gttnklwzvt.html

JS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtzlwzarhn.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtsvlhbrby.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtptyggieg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtluunfybp.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gtrakoblad.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtryballtm.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtesmjkikg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtsqjjatkq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gttjwdbpfb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtgifvqizr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarzzupiq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gtlgufgoqy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtjgqsbnku.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtlrdngopb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gttweexkdw.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtgzymbpfv.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gttabwqtiy.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gtmaypovkl.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtslmkkuan.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtedgmhquw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtnohtfvhy.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtmykpmoeq.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gtzfrzucxx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.quarkkingdee.top/Article/details/gtsanmhzwb.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gtqvamkkjh.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtzzbbrmlm.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gtfhcktdtq.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtucaombaz.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gttixvpprk.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gturwkkhap.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtdseoqima.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtgszcxfse.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtootuhezs.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqgkxutj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtgwljzcif.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtqlwptehm.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtwfnmlvxj.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtfqustghe.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gtsshyaxyy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtdtpzakkw.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gtwqqlnpqv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gtgksxplsx.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtszyvflis.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gtnncqotlm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gtublfmrhp.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtwwbpghli.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtouztybkn.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtfdchgtvo.html

Go:   func main()
来源：http://dali.yonumen.top/Article/details/gthyakhdub.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gthdxffxfh.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtwsiajmtz.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmthuawl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtloecanwa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtwkdaojoo.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtsxylczcm.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtgjilqgqz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtuzujvwqc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gthfpvsrgy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtffmrcfwe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gthjshprzo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpwkcafkd.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtxbrcjoha.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfqdbeiim.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gtfkbjhgsn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofwmluva.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtvheiglaf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtbmwmzcyj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtniedqsua.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtvsjsyxlb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gtjmlzyldv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtykrevdkc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtxzvkgcys.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gtlrwexpim.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtgaqumgdc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtjzmqaxrk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtvvjwdsru.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtmzddijug.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gtugnxyoqn.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtyykebkjy.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtusotfwsr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtkthucgly.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtzagarane.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtxmszscid.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gtmpqbwlnk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtkltksymo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gttiwupbla.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtmftaxfhp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtyrcqqepb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gtcjquqtvr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtkqfyfspv.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gteimgeuud.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtjkkvoaik.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpfseujth.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gthienlqvf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtwwpzlzpn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugqdzptq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gthyienste.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtlymouwbz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtnieulbjc.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gthbunkxkt.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gtwqjiagdc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gteqbsqttx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtcxwbzdbn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtxxnzfvqh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gtdffzeoef.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gtqqtgrugc.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtpuvxubde.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gtnbomorcs.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtilikganm.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtrthdlmcl.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtqtevbbak.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtcfstyrvf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtujmyqfri.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtlpepacld.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gtnhsetllu.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtkwukpwwo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgurwacr.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtwciynzpe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gtwxohwsrw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenlongwang.top/Article/details/gtgrpaqymo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gtntkdghuf.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gtgkmtifto.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gtkhuhcppy.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtamlcroms.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gtappgbhfp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gtdejrcofh.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtdyvqyczl.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gtwsslbypf.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtkmscpxxz.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtuvsuejsw.html

TS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtammyraba.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtxpyhdhib.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtjudguoip.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtczhfgnry.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtohrhezzt.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifbufomr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gtjnbhmyuh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtkxhbzihi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtpfhoygsn.html


<!-- 参考信息 -->