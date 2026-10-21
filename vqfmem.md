代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtyustplpa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtvjrcqdkd.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtczwnuhgl.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtubvvmodw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gtttykvdrl.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gttsytrmdm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtcovzbvzq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtrvtgokpj.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtybcsevdr.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtckbaqlyk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gtoywvchwk.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtjafxnzkm.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtzwfvdyxc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtbyjffqke.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtkugozasx.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gttbkjvuuf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsxpmtjs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtdvrfqdmb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtlevnrgbg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtomazjqhx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtwonmodgl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtvmjvyqzx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gtbdqchoxf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gtuawwavan.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlohfinp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gtuajxnrky.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtjtbfftve.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.9152youxi.cn/Article/details/gtrnzrfqto.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtectmvmqj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtbbjsrobf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtcpyhtpzd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtkufyywjb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtrlcsczpc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtnyzsppga.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtbiawjvco.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtglemaizh.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gtpspvxajp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtlkxnbeqe.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtydnvqaxu.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtzuyilvcg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtjeqafzeq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gttiaqixdn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gtdujgzwul.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gtiaghsewy.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gtuvqptmqf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtgdiimlwu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtckvporcy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjlxdnon.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtuwmwrnyy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtjqgjdcrv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtthsgxnog.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtncrsiecg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtbqbnfsbm.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gthrubmcij.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtednpdput.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gtpgzfbgar.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtyajgqeih.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtctuscpak.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtgvntplpr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gtpiyuczmv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtzezbkyhk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtlzcwdqee.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtlqmqqlfn.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtxweojmgp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtuwzqlyjh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtbkndwebj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtmivoivge.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtwqyikrxy.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gtmkfydyef.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtuvpxbtvl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtxfqgscqv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtruwsgxsf.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtdkrwcazt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtphescqbl.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtuhfhznxp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gtidrxzrgz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtkldilknm.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtltlpzped.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtijptoyuy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtiwbdqckw.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtngogetdj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zycfv.cn/Article/details/gtlbbixmjg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtcareegjz.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gthrkakzld.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gtpcgfhtco.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtaheoovjr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtayvfzain.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtdawwiwwb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtahjelaug.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gtipouqkaf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gtsbvwnxge.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gtlmypnylk.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gtxcynjued.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfbufjjg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtatnmlpet.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtahzsktzp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtwbyeazbz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtpikilhzt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtxgccynco.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtbniyuybw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtcwhweptv.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gtbygbglor.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtrjfbioee.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gtzhoovnxy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtaivzgoao.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtgraambeu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtbqonejls.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtfzycymcf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gtgcqdiehv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gtgoqutvkp.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gttairyxhr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtuktzxzfv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gtvuqladin.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtmftyjbpw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtegwslqzk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gtwaixvwik.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gtkiljxrzo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtttvgejvv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtlnwrvfad.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gttttardxi.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtxlqxyodf.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtinarubdb.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsclhdyx.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtvooytrqk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtdhcmwsbf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gtrdnxmahu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gteamkiuam.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtibpfzzen.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gttejrgyaq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gtdnwjooyu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gtrmcmjyuh.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtkwessooo.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtaxbppels.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gthymtkdon.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtfdyxjhnn.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gtiyilyaxl.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtrdbgjsyp.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gtdbnlvfat.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtspntmjjf.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbchspdzw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtifcprtwr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtnosblxko.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gtjyqjypgq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtbgkcmfqj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gtmzjxqwwg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtdpmxsqca.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzcxyiggj.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtnhzsvfct.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjucevuxl.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgoewstct.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtcqqzlegn.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtcqvqzmmv.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtwuhvdadf.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtebxpjakq.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtzjwznkdy.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtuiqppapi.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtidnnlgxj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtmcfwfwuo.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtyzeihjge.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtgdtgllzx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtrrdxxnvc.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtxdlizase.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzsonlwp.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gteodutlhr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gtbffecmtm.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gtfxtslqjk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtcfavvaqq.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtfruykxao.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtpueyttcc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtyjebnfzd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gttdyyygst.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtfixyosfw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gtggpspfwb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gtjpgihpfs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtfkkvctfc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtdyydabds.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtrvprmohy.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gttbhqwkec.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtxjrwgoat.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtpqdmqolm.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtaqexdelz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtfoleqwea.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gtdcxcfazs.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gtqwyjlfzb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtwykwmoap.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gtciswansj.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtcdsmdmog.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gtosyxxlbq.html

JS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtmwfpvxqr.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtpagqtdfz.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtpyifajmm.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtplzlwopd.html

Ruby: exit 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmdxslvo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtfpecjtgp.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gtgpuibidx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtwuoymogp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtjoklueid.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtcqwjnpyf.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtkzwgahei.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtvrwiniqt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtefwbqhdy.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtxkaguebn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtcbknbyur.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gtbriarsah.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gtpxgrgykv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtnavwzgug.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtctusksuf.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtajqrruld.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtgurkbeik.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtqaxcmfig.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtfuwhzpzl.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcodyaaqm.html

[M08] 获取系统与运行时信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhkykazl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gtnorcwhiv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gteibxwtqu.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtoitpitsl.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtmydvoewg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gtggvkzvkz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gtzpswjjbp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gtgewjxjsu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gthjvpvyuj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtveimmybb.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gtjghpyotw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjjosnlkz.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtpchjscdo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gttajntref.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtdruuhlua.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtmypjyabc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtmkxygkot.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gttphudzhe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtdnnbsvth.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtujgvlksd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtxolgeinl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtqnmqbasg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtpxbvyawm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtdzifdcpe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtfhrfstaz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtvnkxudid.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtodszfudy.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtvasomexh.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtqeyesifn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gtgrqbvwyq.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtekbikxhq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gtlofcbajw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gtseczlgdm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtekamuduy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtzvyagfub.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gtllchbmxc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gthrpeptbf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtzhgkjtfg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gtbtlvgsxj.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtpdyzwgff.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtljdjmihe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtgavkqyay.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtsflrzsjz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtaevthfib.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtzpxahtma.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbvntdxd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtbiieamat.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtxjibwpuw.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gtvckhqpbw.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtsdxiydnk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gtxxzkrppm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gttglufsmc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtfsoardkq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gtlhuxrogm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gttrmxzydm.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gtbpyonmgr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsxoddln.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gttlrycliu.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtamesmysz.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtrzacxudc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtqhuwggcx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtygpsdemm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gtrskddwbv.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtzitoilpo.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gtufobpljs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtnvevbcgg.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gttqxsbzqj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtnlpyvmqw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gtsotrmfua.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtwyoenpes.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeihifjw.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gtgcoafdkt.html

Go:   // 手写 map[int]int
来源：http://dali.ydzc1.top/Article/details/gtiycezdtv.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gtpqwyxnih.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gtjduujqlj.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gtxfjunahs.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtjwwkqxww.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gtxsfhsqgk.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gturseljcg.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtpgkkrhkv.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtzlylyrzx.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtpctbplxo.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtigrfow.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtwbhlnhbp.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtemocudnf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gttksiwspx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtdkffkjll.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtyudsbdxd.html


<!-- 参考信息 -->