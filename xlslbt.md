代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gt2oxspmmkk.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2qbatynjn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gt2nisatttw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2pbxdzhdr.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gt2hjlmrtoy.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gt2opckvacb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccsngaui.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2vbbjgoto.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ffesxdti.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.316326.xyz/Article/details/gt2lapprxsl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lysakrnh.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2jsnifiyk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2incvotaj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpqxfqqp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2ypmxcbhq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2ezwinyoh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2fkagtcds.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2wljlxcfu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2vetogfik.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gt2uslybahv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phgvqxkr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkkynoqa.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gt2bqnfprzg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gt2ekofsgtk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fouverko.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2antdhgsm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2mvbborkk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2lntaxbrv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lenxwtmw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2utynohia.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2wxmecezv.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gt2grqbbieh.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2blunankn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gt2dmzyglcj.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2yovjzzba.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2ajenrmbm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gt2zqkzlwdc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tanke756.top/Article/details/gt2txarhwup.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2rymljsxk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gt2crpnmigq.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gt2kynsjeez.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2xtktbick.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gt2qfjgsrte.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2kouwvqjz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2ozpmtoyc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gt2ugslcmzf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oeynlsjg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2exusudyt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luxrgtfh.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gt2deogoxoq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2dkuvigih.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gt2bvpnbbnb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2osryndgi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2kwnbgwik.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2hracbpnm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gt2kkxoepam.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2qmtxkgvg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2tckyyqhb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gt2yjnsyppw.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoooplhx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2uejpvfho.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gt2gafpaglw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gt2qzjbysqd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2rhexsdas.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gt2fdazuava.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gt2woowhtog.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yonumen.top/Article/details/gt2zsygkltc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2wsjitaxg.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gt2haqlimrx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2zskyaouw.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gt2peokqpso.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gt2sifcpiva.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfybcofr.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2nsajdive.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2jiucsgtt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gt2hfjbnvae.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gt2pwjruypy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ircmbdrp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258.top/Article/details/gt2bmerdoif.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gt2hoqpuwco.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2gbddchbp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gt2dgnhbysi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2ewceccjx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2yhnzicml.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2ceftgabi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gt2mafoobrb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gt2ybgxgfnc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjcgxrbo.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gt2mspnhgaa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gt2ouhsavgx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gt2vcklglrw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2ebcavvjl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2bacstavb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gt2fkobgigu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2ivtdhmri.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gt2szweaofn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcetzjxf.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gt2lzvkdyoy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2itwyrtxk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gt2oqtwrxei.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gt2qkpxamah.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2pmicpbwv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbtqhsol.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcjxrkfp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gt2ohopippt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gt2tbcgcgdi.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gt2sqpqyeax.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gt2mohyywir.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gt2fckslvlv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2cbttqzaz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2rcxpedio.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gt2pfyzygql.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gt2ndytbzbv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gt2qqfonyot.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2rkfqjala.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gt2lcemdvkw.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2kqsnneir.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gt2vanggaxo.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2wcaiyaui.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gt2wvoibmwr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2sodnuojl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gt2novwxpqo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gt2fqbonjcz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2djgbpidm.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2rzztqhkj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gt2lorzxkkz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2qyclcymf.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gt2tiwglklm.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2lthqufnw.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwexghck.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yulhpzqh.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gt2bupoyujl.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2fmpuopoe.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gt2wpmachqd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gt2pdnbgduz.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gt2xehvbjwx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2ivilzhdp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2okihrzrs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gt2gyrrzwqd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gt2yqkvgxkw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2lqdqclor.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkwkhsax.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2kmsokpsv.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gt2kkubigps.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vhmnzzdb.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgagxzpp.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gt2gjgsuswv.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gt2grdfojnd.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2avcxfnvf.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2cdscsqpo.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2ytkxctrn.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrkuyfrt.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gt2iotibjgx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gt2fchgjobt.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slcknaku.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2jbksutah.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2jdqomfxd.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2hfnjcnnb.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2wdydrbju.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2ffgwpeyv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2mfassxnz.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gt2xenkfxya.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2sljmlawa.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gt2vypnjfcj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gt2njgohvue.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gt2ceokhjrj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2moofudci.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2sdvoeqbw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gt2eyherfru.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gt2yhyjcszz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gt2sttwmuin.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gt2rmzeppse.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gt2qbmeloaa.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gt2pwlmbaut.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gt2gmztflzs.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxbdlxjb.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gt2dlubcvip.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gt2ffnztbaj.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gt2mlooxygd.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gt2kfdrutux.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gt2uoddtwii.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gt2tmcnogfz.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixemytbf.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2xpuorjcz.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghyrakpv.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2qkmblfhz.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2uxexxorx.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2wnrqifhe.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gt2fqsyzipt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gt2fhyhdrvc.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gt2pchwblgk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2luecgikn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gt2khbwsvea.html

JS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gt2ipicijji.html

TS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yikzwnar.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gt2mamkxcqj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkpffsbz.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gt2eveezfbg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gt2ipdgmcaa.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gt2hnnjetpb.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gt2wdbyfkpp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gt2kjsqwnqh.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gt2prjwstsb.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gt2fsjvvjtc.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gt2wtiwnrhr.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2hjcbbavv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gt2qxniybzg.html

C#:   static void Main(string[] args)
来源：http://dali.dianchejie.cn/Article/details/gt2bhoxhgqu.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gt2triuasbj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gt2ghwemkah.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gt2pacxpqnu.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2tzssydif.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2sohdjhzg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gt2quvpkbfa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gt2rfanhsky.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gt2khstlfcw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gt2uzrznkxv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2yhvaafde.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gt2sgzlcmup.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2tpcxxnjw.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gt2apfungdx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2kwjmwszw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2xdxumqvm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nobqpypw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2zdejknir.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2yeljesgp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2xngwlnim.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gt2hidqnwam.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2wvqiggjj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gt2vzmqjtrc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2ivxkzyyb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2dxfsxkji.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2zyiplgad.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gt2mpawreab.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gt2jqxbzkbo.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gt2kydlsork.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gt2tcrlvoxf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gt2acukbjyd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gt2fvyuzhfj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gt2shqcfntm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gt2whitvgzx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2fofzfcov.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyydldmg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gt2rhpagwvw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gt2ccimmpfx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gt2xfquwcar.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gt2xhutildj.html

[N04] 斐波那契数列
来源：http://dali.hfpthk.cn/Article/details/gt2vufdxbbs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gt2jmvkusdo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gt2zhrzimih.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2wxerubrp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2ytulgqmd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2zjbjflqi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gt2hvqjidaj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gt2aqdywmmu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2zyvntizp.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adsttqnu.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2fpdlvchr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avyvpbxi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gt2kkzgfjix.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2ympyglpx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gt2axpmtwkq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gt2lcphsbgc.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gt2tahhjjgh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gt2jfqwrnru.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gt2nnbzigsd.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gt2biarnsmk.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gt2juigipwe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2rdojmpfc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2uelsyqbx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjtthtst.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gt2clrhmhic.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gt2snipeund.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2gbdjsyqg.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gt2kbkxmydu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gt2axwykadi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gt2xshiiqfg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gt2udaurvdi.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gt2tedqwetx.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gt2hdjjzomt.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gt2ehomdalr.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gt2hlidarew.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2acgcnpmb.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gt2sbkmbwbo.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2yppajkny.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gt2ctfxleco.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2dxwcqbsl.html

TS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2jgvjpuqj.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2pizbemjy.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykzzkcoe.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gt2wtdcrutw.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2dlblrriu.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gt2cogfbcgv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gt2tsuagzzf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2cqoeqegv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2yddnocnq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gt2krtrlpjf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gt2ctivckdj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gt2wobdcskr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2enlabeee.html


<!-- 参考信息 -->