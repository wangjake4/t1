代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtbzcerodj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtdczekhvu.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtvwhfesfp.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gttgsxjacr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtdutbvghb.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gtqjnctkjs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gtzizorlbw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ehwqpu.com/Article/details/gtgjquoyop.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtwczmxflh.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtxwgvigpg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gtgaruzjag.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtfgekjovd.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtxazmcpzr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gttlpqbdhj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtetdulyzq.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtelifzlqh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gtqewevfuc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gtetizyskl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtlcmpnzow.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtinkaspuh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtejnuomno.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtghsneeym.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrsljqvx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtunigdlsl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gtmxvmuwyo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gtyozizoju.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtisrlmewx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtylhtoffq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtyvzwrddi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtvyxxfocl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtduozopfr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtmfukewbh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtbleyuhue.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtcxkgtuus.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmgdvwpt.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gtpdcqiirm.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtokkdioci.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlwpbfhd.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtevlikcqd.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtcuxabkzp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtagrdkgls.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gttrhfkohx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gtpnsdksir.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gtoqapoimh.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gtiochzsme.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gtdnmxdrsa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gtryrxeaxj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtshniudyk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtwysjimfp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gtiybxiklo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtbktoceci.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtmygthrkm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtjhaojyee.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gtskzyuzql.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtamtfatjz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtalvxhczy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtygkbozcf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtldykkvgk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtedlmicwd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtzxnlcalq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gtuwjhhnhe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtehnvxuft.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gtrthghnal.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gtpfokpczx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtfmgmcpbl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtnpcvouqx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtlbkedokw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gthiecdngq.html

Go:   encoding/gob
来源：http://dali.meibo888.top/Article/details/gtnacbeoai.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfwlkrwg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtaxzdnppf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtktyquwpj.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gtvclebsqm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxephwqxo.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gtdgcyowkt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtamrwruep.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gtrschlzwd.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtwcqgsokg.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtkplzexri.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtkqfnqrpc.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gtlqnntwcm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtwoebtnjg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtfgivvddt.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gturkevvhv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtmwkszd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtxzjsvskw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtpetyvlle.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtldynxmkx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sxryk.cn/Article/details/gtbhncuhrt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gtakhpvjtf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gtxithixsq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtwzetbjba.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gttvulzast.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gtgrmyctav.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtledbnaqs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtxonmnjfv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtqteulsae.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtonkdxugu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtbzovgjxk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gtzmefwhqh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtmgxuyios.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmqtaamc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gtbezetxsh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gtwdlqbwcf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtktquoseq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtmnbhybpr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gtdjguuuse.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gtpqjspeyk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtjblzlsnd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gtcbjogkvs.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtdfqpidrk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gtsiofsuhy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gtbannrnav.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gtxmozvpag.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtbtzqjbnp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtisqbpebo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gtfzrgaknh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gtlwysdvyp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtyfxbhspe.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtwhxlqssv.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtqakrugdr.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtjmccpljq.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvywsbks.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtkaobrwib.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gtohdsvfru.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gtwajbjjnb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gthqfyccaz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gtjhjegbwc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtebtzlixg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtvrctgxli.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gtxyafyfih.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckfltzji.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtjtnutsgm.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnifcvhfq.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtggmmxezw.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gtsmjodama.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtgpqqzakf.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtqejjljjk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtmnzzbxel.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gtkxgbjysm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtywzjzzcr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtqnnqvexb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtpqnoizgn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtjffplely.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtfbbrgglo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.mhx1999.top/Article/details/gttyzvphxt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdnrwyykb.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtudchvzob.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkpenayay.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtcgmqazfc.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgyfdjot.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtomtkpuep.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gthabbrxzo.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtkbstjqip.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gttkzmsnzy.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtddbpgggm.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gtwrtbzkpf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtzxwpkffk.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtgfuduiel.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gtelbcqpoi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtleezueoh.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtdnezhzxf.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gterizvtmm.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gthuqisdcx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtrtnmpitu.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtskytgdkt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtwrdwxjdy.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtbxpamaan.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gtcdhubfqz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtzaeaisjj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtvhpnyzgr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtywcbefmt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtwtbvelvk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtxqnpkkrr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtaiykcavu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtcnhositn.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtshqjeopc.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gtfgsyviaj.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtsghpnggw.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtwbjaotgf.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtwechvcvq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtgxyfhqds.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfpjwvvm.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gtkqgvoguq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtzppcpyja.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gthulcqoqk.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtwaalrifh.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gtxwapfpif.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtnluzbmci.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtonqpttip.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtmglpvdrt.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtcnehwnwq.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gttxyseape.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gtifepunmk.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtaqrvbipl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtwvyvblmp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtflzdaxpm.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtamkeqccd.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtgdrryhuu.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtrfvyydkl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gtswbblzpq.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gtxzccltuu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtvtdqrsjy.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gtsnuojblq.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gtrwwspyxg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gthzaszjrg.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtiukgmtpo.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtxiiyhmac.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gtckimoott.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtteoipetb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtmgfbnghe.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtykmdjapr.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gthymmsepq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtejakpovg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gttwrtgsbi.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtdtdyfidd.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtquiqsuon.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sxryk.cn/Article/details/gthqzvssvh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtlexuhzwv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gtohndzpgx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gtosjuepch.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtodtgozlf.html

N. 数据结构与算法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqitnkni.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxbwcalbu.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtksrowjmu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtgcosgwwd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtiholdwme.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjbgqswp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gthmsdgnqb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtdpexxgie.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gtfxgtsjii.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtuwjecptj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtiyjpqwzo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shzxlz.cn/Article/details/gtmbsiyiwe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtnaoafqfq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtvokjvyvs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtehhwotsl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtzkpzmgqh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtwqndthqc.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtifpuzfaf.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtdpfclury.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvklhgwt.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gtnvagkdnp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gtvwiyjkfk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gtmhiyosjj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gthjxyproq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtdzihoznr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gtackfcslh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gtmpdugflx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyulsdye.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtzwafzqhh.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gtunnbcdhv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gteuikkuff.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gtoyxtsbhn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtqlxedozw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtxhwzpqqa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtrxeykxcn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gtnukhettp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtsielookm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gttcwrqaeb.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtfspvrays.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtegppanqx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hfpthk.cn/Article/details/gtuanymzby.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtekmhpezx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtqvtpjcfd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gtcycqdnqk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gtpoduugfy.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gttgwkyzff.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtbagosbiz.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gtqydhhkan.html

Py:   s == s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtmoshmufg.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gtvkbeiazh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtdazegbmw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtvukxgnnv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.bjfxy.top/Article/details/gtkilwovmi.html

Go:   // 双指针从两端比较
来源：http://dali.svipenyu.cn/Article/details/gtuqhaiurv.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtmknymqvr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtgrymbejy.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gtifqdqywg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenlongwang.top/Article/details/gtygddwulm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gtrzjoahxx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gtpamjnpbt.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnxiangtu.top/Article/details/gtolkzgorg.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gtepydnbsn.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gtbmuuvvjw.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gtxjoxvofi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gtzqtvmtvi.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtfordrfqg.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gtarxtkdue.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gtlmbxdzqr.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtcdattmrh.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtfwlgzvot.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtjmtixctg.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtounlgnhw.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gtxjeefgax.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtoiuhlipp.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gthosecypd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gthcgfeebz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtznbkqwyd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtgqjbkzwr.html


<!-- 参考信息 -->