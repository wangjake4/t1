代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtahhxjfnq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwwvzadg.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtunequmzy.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtzkorzslo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtwahufgdl.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gtdbkhagie.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gtbudjphgs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gtfqlwzvxy.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtmazautbh.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gtzhnngpnv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gtktgyvvom.html

JS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gttlajzqkx.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtvlsbcvyf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtnfkjenvk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtcktgfpmc.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtzjgcqsyw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtnkgmjmqi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gtufvdypni.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gttephlkhv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtragpidju.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtdvmpcume.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrdktwpk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtvjqkprro.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtymgpkjiq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtereypswz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiuynkei.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtsphbpcyz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtbnsilxde.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtmnlyiexk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtuzfohore.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtflppemoh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtqskppmhw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gteysrgsqp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtofjivwfc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtmqoslinl.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gteuwqfhzw.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gtadgzifut.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gtzrieppdr.html

JS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtvruscmnb.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtvzwcdsyt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gtafgvmfbq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gtqlqvkmwp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtjqzyelii.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gtqjltuprz.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtgcvjtjwu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtjspxvrzz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gtkqeknuhm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtsavhviov.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtwpadwtws.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtexdpvyci.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtdtgcsjuc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtwpkjhrpr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtkobhzpnv.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtsrzdqoaj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtztnkossl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtgpqxrced.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gttwtbacre.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtzynsqnlo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtnrtgdbsv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gtzpmlkzol.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtcwtozbpx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegvkerkv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gtkhipatvt.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gtclnslhkf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gtzdjttqgo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtpbzjrmpu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtvdawuxcl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gtqoachaic.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtmhzbbgab.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gtmueodajf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtgwuwanqx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbapbczgs.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gtffetxosl.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtchnpckmq.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gtjqnorebi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtmwrderkt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gttcsfttqz.html

JS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gtkdxkugxm.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gttksgkcgf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gtmdtlghci.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gtoamdeanm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gtthmkfcnr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtpechkjsq.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtgedhlczj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gtwaufmylf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gtmvdsrdis.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtecknthmg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtwruasuwn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gtbsxruxhf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtbfyczomb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtwdgfuyyp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtrmxwtxxv.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtjgtbgkiq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gtfmslqwxr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gtggowbmek.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtdlkwklia.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtltmdkbef.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gtsxtmnccu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtnclgztbt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtyyktefvz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtmbaxibhv.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtzngisnqw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtmxcflplo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gtqzctphqq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtagnuvwcq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtaybggagh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtgmejbkck.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gttfiqcqvo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gtrkcozpar.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gtxkuafbnz.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gtynywikzi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gtutoydbxv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtlbjnfqct.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtsmzzrkll.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtqkhhygnj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtsbifgsjm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gtxjzywxos.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtnwzwfkmb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gtmgjxdijb.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfisinfiv.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtjxrvbyrm.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtfqyzeoft.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtgdgqfnoi.html

TS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gthbjfjxjo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygcklkul.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtbuxbsjwc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtlauwcpzg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gtoxzntzfg.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtamtviuqc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtolaprzzf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtfbpzhqpn.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtwsltlpwk.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtfquxuyud.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtexaumoez.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtjdljgefl.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gtjndlmwme.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtzasuqcgv.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcnqiqzn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtfauwglts.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gtjxauswgs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtvjemzsxw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtebstdmir.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gttcyqqaup.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gtlqmuoglz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gtigpslpmm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtxywwaqum.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzpyeibbx.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtihymueho.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gturijyqcz.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtnlivwbbv.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtmrnoivdb.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gtvjkubmby.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtbhwalqpa.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtpttlxmjq.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtpdvmkigb.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtqazaucft.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gthnlerhyw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtvsgagjmo.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtdycjzovn.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gthsmteefs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtamtprrvy.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtvwgtijpl.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtxhtersks.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gtjzcmtyqq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtwezcvyhv.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gtjawcweiz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gthnmtskyo.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtlrqbikto.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gtnaauvvnq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gtibpqrabk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gteljbijfd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtwauxyimt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtuqglwdhu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gtnwyqcqvy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtnxvqguye.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtwbockofi.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gtqnsqhudq.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gthtkcbycu.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtabhjpdhh.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtnenjgnuz.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtiqnlojjv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtdedrmjlv.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gtkndnlujx.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtfbilymfu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtzgrskqpi.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtmccqjhxa.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtucgxnwth.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gtvujbmoof.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtsarlplpf.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtsnzhjstd.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtyebebjps.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gtbzrkafbr.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtjuztfkyq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtweodkuoz.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gtpudxtrqq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtsfctlnth.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gttzdzvwxd.html

JS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqecmjqgx.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtcbpgjolu.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtmvxgmblw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuexycvhk.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtcuycoxld.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtakqykipp.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtubvdtckb.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtrswcztat.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gtfcsmzzoz.html

JS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtzzqruvib.html

TS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtainydmei.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtrxdjpvmq.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gtkrxuooza.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtjciyjpik.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtiogypxxq.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtvgikrsni.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gtzhxppdoy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnexyxqmb.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtriglyulc.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtoshqmajv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtgaimreoo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrrgmfgt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtgyhgaksj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtityjstqh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtcuyzwkbh.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gtapjveemn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmcjjhsbk.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtfehkpxzc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtwlrszifk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtphhiuofa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtyeghzkdq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtsvgeqotc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtoddwtvkv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtdrflduin.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gtyipbdkwf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtbxxslred.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gtosyvuklt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtzqaxjzlt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.0kj1m.cn/Article/details/gtwtokeyat.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gttwxdyjjy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtekxnnpcd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtukdwyghs.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtauvidyjk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtomgxxjei.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtzjxfxwep.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gthrhroojc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gtmvsxpkuu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtzohkibnc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gttkjhygpl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtstbojimk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxafnmasv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtrurrlwgj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrdxvhpo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gtuyjulcys.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gteveertdb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtbkilalgo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yonumen.top/Article/details/gtqfdfzeuw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdxdijhq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtdaidegbp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtkchhfcgr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gtqwgthqdr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtytolijle.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpcoyuyr.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gtghmawexj.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtcusnoltg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gtzwzqplhm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxwguzas.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gturelrajy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gtukcghtog.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gtgrkhoyuw.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtuxrxxzhw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqnvrqpcf.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqbwkawo.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdibqvceq.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtellhcciz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtvoizogwx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtaqkfbsoo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gtujdcexby.html

Go:   // 双指针从两端比较
来源：http://dali.vqdsnc.cn/Article/details/gtjtxzocnk.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtnknarvlf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtolxhtive.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtfoyusdyb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nwbrower.top/Article/details/gtflregbvk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gtgrsselhi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoxyogjo.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gttmnfidbl.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtvaylswvr.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gtwzpcqllt.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gtlwnbcwpz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhixingplan.top/Article/details/gtvcxtfhxk.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gtlaawvrva.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gtaabcexhx.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtrrpizykw.html

JS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtdabmeslh.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtkiqrgdph.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtgjvzhtaf.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gthfscehbb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtpnrytuyk.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtsbkfnnps.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gtwqhofiiq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gtjdtvqlqi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gturrvmvrp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtyixjrkbm.html


<!-- 参考信息 -->