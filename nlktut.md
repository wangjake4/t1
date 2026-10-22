代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gtqweppzcn.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtzvbrvxvo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gtqxluuhtb.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtagkyreuz.html

TS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtteiranwl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkvxqybl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtwkugzuok.html

Ruby: JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gttjkairxi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gtsghjywgw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtzpdbygzq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtmpllumds.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtfjmxzaaq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtcikdgsyg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtvjkwuetz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtjhwctgqu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gtvefdjjxh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gtfywpcvni.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtxodwftbe.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtfrfdyjpt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hysaishi.cn/Article/details/gtpwceygyk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gthgrkqtjm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtocpluiet.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtzwqetzvf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtgqqxjmqm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtphomcgod.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtqiipbctp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gtjsivzbjp.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjtkcihr.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtjnohgmwr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtrrklbapl.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtcudqrhuy.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtpxjsfbfg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gtfvrybpzh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtoxpuxdzo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gtsdsysmrt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gtncvzryzb.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtpbtrkqtg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtcjyllpua.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtmgiupdki.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtwpfrpqun.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtzjtimebx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gtldumlqra.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmoelprnq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtbncewfxa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtzoyufnwc.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gtoylwuoij.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwehzedoy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gthklfqpyp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtwafvcunj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtrdlmtypz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtaucrlvun.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtgsnvrvcb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclozjast.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtpxgnashk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gtycsizdha.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gtdzfsowse.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gthtmtdlze.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtfifypysh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtswctugyw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gtizibutju.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtipzjvegl.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtzerqkijl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtwatjwaqe.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqrmlhgfj.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gtnehnaoxo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgguwvzwg.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtanupkfso.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gtnhlpxdms.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gtypirwynq.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvijcziu.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtketbigpl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtlghiffkb.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtxiczfguv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gtbucngpvm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtedytyqcu.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlaccklp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sxryk.cn/Article/details/gttvqtlsie.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gtziobabqz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtvlkkhiuj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtvmpanbsw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gtsompjgeh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gtvdslmfvj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gtbkodlahi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gtvoyxwzbx.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gtvoraxttq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hammf.cn/Article/details/gtasxnuyry.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gtrlaqkiya.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtvamuyseo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtocjxsqav.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gthwgxxalz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtmsqamhvw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtrdpuborh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtmligfdgk.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gtrhwhkgfi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gtiyyquhed.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtqeuykwro.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtalsvzkgp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtnqracgqu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gtpavsdksf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gtyiwrpsbw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtrhhytdkd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gtmskuhknc.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gtibxuupzw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gtlwmpleoj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gtcomnysap.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtsqxtalqj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtvnaulinl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmvvyvul.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gtlavuhfiz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gtiyshubte.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtsliqxonn.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gtpnsrdhva.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtvawedyli.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gtbjxxqyqf.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtqtlgnqgz.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtangqsjlc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtlejtagwx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtokxvmwkj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtiagdhnfy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtmxitcudj.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtyqtlspax.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtqfwnuzve.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtyecmjvpc.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtkdllxeoc.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtchlmlcfw.html

Java: resp.statusCode()
来源：http://dali.tian-w.cn/Article/details/gttngqvnuw.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtcojtdlke.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gtxaeuyaqs.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtufmzhcbi.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtrelrmhtl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gtanwfvlkh.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gtvxainqrr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtcshomxzi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtpntcjkml.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gttcneomsg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gtmhefbwfw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtmxbfkzfm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtykwwtion.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuxwosqfw.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gtledyexmk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcvpbjfko.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzxveqhg.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gtalvmqpgf.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtbohclzlg.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtvaqnidhs.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gthlepicmy.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtpumomzts.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtkqyhxerp.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gtfvgsymkt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtvbtzygob.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtcwjhvzaj.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gtrgobivls.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtmfieplmu.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtclduhyyx.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtyxouyrtl.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtkywoyiso.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gteuylwupj.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtilisvvka.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtorlcxhkw.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtmgvvfeao.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtclaqoucq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtjjlwofzw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtrjlhovmi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtphmqnyes.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gthxioknug.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gtfqhhnlwa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gthrbgpchu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gthfszjetz.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtdxznikfv.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtfatjvxkf.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gtsekaehgm.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtamjetzxx.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtfotfwfzl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtkcjgdvpf.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtwfptpmir.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gtkjwdjtsd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtdfjftnwf.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtaatadidx.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtzbmcgzkp.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gtknwuggbu.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtvmsuyjgg.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmlaemnk.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrbmgjpij.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtcxmqcbsd.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtptvnvosn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtehakhuxb.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gtijrfhqsi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtcbpdovqb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gtjvfyebxq.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtlcfquprs.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtaowvtmje.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtousrxmng.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtpkrbpcjz.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtgonityvy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yvedp.cn/Article/details/gtoobyqcnh.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmvzaayc.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gtuswopqti.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgufenzy.top/Article/details/gtghhkvbzu.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtcgptxeda.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtizcghklg.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gtwsgfmptb.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gtjtuqcoxs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtdtkjrnma.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gttiqpwwet.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtrzekxewi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gtqijtwdks.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtagpwfbrb.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtkmleniwe.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxxxtobk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gtrpaoewyh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtlvjihqvt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtamgcemqg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtncwjohqx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwylvxygd.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtsqwudeyv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtnvjmjkzl.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gthcuasesz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtgtdhqwst.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtmqbpnjto.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflzesawv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtnbsjrkqv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtjkqvdcpr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gtsrwjdnsd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gtoprcevzo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtokjhgdyv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gtixtkmqkd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtwvyuzaat.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.redwolf501.top/Article/details/gtwjdzlxsj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtvgqzsqpj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtxbhelmmv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gtaabxwsof.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtcbtdxhry.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtlscbqsqd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtvkkundhb.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gtlngfoqfq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gtejycgshy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gtkodgfrmm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtmefjsytr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtlwljnuxu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gtruvgkvpp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gtjaapgxdr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwykeesc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gtegbhfsci.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtexzabtwo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtmrhsbbsf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtzrsvxjff.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtilnzzbia.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtgomhjeyq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtakdlfuon.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gtlesyttnf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtmooojqch.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtutcprygn.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gtqjtznsta.html

Py:   math.gcd(a, b)
来源：http://dali.yj202588.top/Article/details/gtkxijisey.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtyxjnpjzx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtwifzhefn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyxkdvawf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gtfvxxvmio.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gttghpgvqr.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gtuksetoyh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtxzoqbmjr.html

[N06] 判断回文字符串
来源：http://dali.gogol.net.cn/Article/details/gtlplsobuo.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhuuytxs.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtkaewjemh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtlygugqst.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtmvextypq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gtqpziulal.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gtatsdhtmc.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtvtssjtrp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtdxzuoajl.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtpisqblfq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtmohnyexu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gtscktyhdf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gttunvnlzg.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gthzvmyacl.html

Java: // 手写 HashMap
来源：http://dali.ybcxt.top/Article/details/gtobpegmtz.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gtrupjicco.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtajbmnihu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtulqcrwjk.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskuqhqkt.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtvpimrsjx.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gtdmqtahqa.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gttuhvqfvw.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtlabacffp.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtobhmorgc.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtwjrdaejy.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtcqvnuyib.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gttwfzdzjj.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gthyyjuvzs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtyymohzqo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtmgcdqndb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtyqliqvyr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtebordofa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gthvanbyfp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gtchcdfffo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtzzdxlzjw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gtcctrtivp.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtrxzqxmya.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gticcsdetl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtuumdkzha.html


<!-- 参考信息 -->