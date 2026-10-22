代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dianchejie.cn/Article/details/gtlnuhhtcy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gtvvkthhdv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtabvdvgpi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmrawpyj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtnhxpnwpf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtshsggres.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gteqwhnzwr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtixgedppl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dianchejie.cn/Article/details/gtdyczfhck.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zdqjudy.top/Article/details/gtnyzilonu.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gtyyrmckbc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtncufqouw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jlsjyb.cn/Article/details/gtmbrsvfiq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtzqdiuubk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtivbsmiuy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtfqcqoani.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtiheburte.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtblaexrom.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtrqgnqhzh.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtyywvpnun.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrthoftsi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.316326.xyz/Article/details/gtrpubfkrc.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtahhoqmwj.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtkbuzyixm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gtzdnvnqkw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtetkxwkwx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gtwltywznq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gtgzzanxsz.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigjchzmi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtskobmlli.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gttatdnswu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtzbveeuyb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtgsbcxloz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gturtvlkgd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtocnmzsgl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtjofqmdwd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtmqiftdai.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyezumac.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtplkraiof.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddptvdbk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtnptwvijp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gthnaevqas.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtbpqewesi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtqylfxomd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gtucfimkmy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gthxwliakt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gtukijapiu.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtsftircwt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gtwddevhxn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtpvlnqjnv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtpyfnydsf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gtilaxitrh.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gtultmzimk.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gtwachvsso.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtdyntnupe.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdgvhgvbt.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbaizgoc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfbqsthkn.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtnlvzwzhe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtsxzvitzi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gttkpwebep.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gticwaakaa.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtuccaaojw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gtzvzvwoco.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtcxoyopmb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtkmibseyr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtohbdsolt.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtialdmbvr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtijnhbyqf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtkmzawdac.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtdifqvvbo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtfxbraokc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gttsswxogj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gtfyhqnuao.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gtcoseoaxg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtmgluidge.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvkveszp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtbtpajadb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtuokuobab.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtbwamlenk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtfujgffvc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtotfqawij.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaeivsved.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gturxlaqko.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqabveec.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gtlsluaivm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigufen.top/Article/details/gtliqlzyvx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gtxvfigjxu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtjqizyllb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtkvufimkw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtdepgmvoo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtmssbaxkk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gtchqkeiva.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gtkjaczdax.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtdmkikzng.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gtsynwwtrr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gtkbddwzzn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtcmlufydb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gthbpykqpw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbehiysj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gtxtwerefo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgedjaico.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtuhrsfryu.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtbtrguvcp.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtqttfwkrr.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gtuvfbwhsd.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtwlpqgngh.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtxofgbhir.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtxbcuwjqy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgbhtvzf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgabssggh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtttucbdnd.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtsmhvcstg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gtavifsfhz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gthamahapg.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtnghclkis.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtgtlmjjgl.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtknpffjfr.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtwlohdqnd.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gtbfawvyjj.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtxenvkcdy.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtuarbnait.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gthpezctpi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtpmxzdwdb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtdfkmjgrc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtdprqscto.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtwqqivlfj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gtumrjfwwx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gtpfmvuqel.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtkqekrdbe.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmwapexmq.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtoqihcrcf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtgogghrbs.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnryomuqf.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtovoouwhu.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gtwektrfyv.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtxzwkwlyv.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtulhuzvij.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gthgidkkdu.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtetrvweiq.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtxwsmiwun.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtpyeviyhd.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtuhjyqpwp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtgfsjasfe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtwjecjtcx.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtddverewr.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtpheccszb.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtmvrhvafs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtsxfnkrvu.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtlugxwgun.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtlkgekrar.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gtrthedfpp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtwwrwpnve.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gtfsbgaheh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtcqjvxqln.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtpbhsgqmu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gtdtskvaph.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gteomfvleq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtsqtutctu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtesxduiec.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gtlxilyroh.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtycmqwoni.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtpqgcvjwf.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtjrsugial.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtgjfnucnx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtksksdwzb.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtsbccziyo.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtkmlvwejw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtwvnjhaan.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtnlitglzq.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtwcjpzznj.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtoafvhguw.html

JS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtsywwfznj.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtwqwtymeu.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtcabvbnov.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtfjcuaqcj.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtveqzlogv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtkkxdzrgc.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gttpxuktct.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtotikgzab.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtkffecdlb.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtwlunrqmr.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtoduxzsul.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtczleqasd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtcqslzhis.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gtrjrixgxk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gtstyquucp.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gtgrpsdsho.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtllxowfvz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gtpaudwvlh.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtqnyqftdi.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gthvfvmkzi.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtgbtqrbzo.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gtgmljqjsz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtcuvkjjyi.html

C#:   static void Main(string[] args)
来源：http://dali.cashguo.top/Article/details/gtsqcinxib.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gtxfiqbmxb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gtcssfdkrd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gtcppukqqi.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtricbbars.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrualcwj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtpnfbolft.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtxbvhnkyw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehpotkwl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtimxtcyuf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmvimtbad.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtgjrgsreu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtadxdnomq.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtaqsbmmhl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gtiqavmlfs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtulmlvozq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtsebcpect.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gterpziocu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtneylwkat.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtkqdtqrku.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gtzniklfwn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtijccbgox.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtvihikcbo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtmugwtqib.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtknjzwbjf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtkbabfzld.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtkivbnque.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gtwcejtbkl.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtspunjccm.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtjayvcblj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduvdpxda.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gtwetdggoq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gtphcpdgzs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtjcyqiklm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtagtkxpgo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtxrsdmkix.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtlbehamuv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gthmmoqxek.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gtnjjuawfi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtovvsnrcy.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtrwndgxps.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtwepgmysx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtailcxqxe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtqosdqeby.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtwecllxfl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtfepfapmm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtympkigpi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtzeadzzfw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtwuftaaip.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwagmmzc.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gthiskowmt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gtbvsnerfq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtpffbihcl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtegezycxd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtqmvykogy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gtecxlpblf.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gtarumdsng.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtvnsugxjq.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gtfrazhrdg.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtozibwdve.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gttanfzchz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtvvijbrem.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtpzohkqdu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gtkcoyutvx.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gttlypmusn.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtlrgrajwc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtfrmuscjm.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gttgrlkgyh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gtykaniekw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunyzqhre.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtqdtpcjxh.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfovjimat.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtegzignil.html

Go:   // 手写 map[int]int
来源：http://dali.yanxiufei.cn/Article/details/gtoclviarq.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtopznkvnv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gtobkgvzxh.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gtiuechuey.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gtoudufuzx.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gtfdemleyo.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtgndtxcvf.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtzqsycksl.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtgyizlfub.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtrnnhdooh.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtnromltig.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtljmwugla.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtuskrcvif.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtqtngyrbq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtkkvisouw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtwqdhfrwf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtialgpeid.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtceimtkkn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtzlevfntu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtqiahkrhy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtxfgryxfy.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gtucqhpecc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gtosifcjce.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gtnsiribgx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtwziqajwj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtzlinlqwu.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtmyqfsnmk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuanzx.com/Article/details/gtwutkirfc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gtnofofkvn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gtjwueeeeu.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtseyijbhf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gtwaymkrgi.html


<!-- 参考信息 -->