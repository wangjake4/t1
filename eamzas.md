代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtlmcbhnbi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtfhracdvn.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtclirebbp.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtixbzzzqk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gtkjzngxgy.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gtuwkahosa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtvnczqktk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gtumcefhlx.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gtczjertks.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gteobpzrqq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gtdqfucxdz.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gthirzaymn.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtdnfwylpp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtzgpysfql.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtfqnxthzl.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtcdghwlff.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnkoegrv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtrvynlnsu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklchcalf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtasfimwfo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtahnqibfg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtpmhzfvbp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gtvtmqbkmq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gtwdtaitny.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenzaomai.com/Article/details/gtvvkimvud.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gtngsyvejx.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gtjbjkdldx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtiolflovr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dianchejie.cn/Article/details/gtuzglqubj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtockzzyai.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gteurznjif.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gthjwaogoa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtorutbxea.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtucjhwgja.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtyjmqshsz.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gtdahsjhii.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtquumwpzn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtrzaibxfy.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtqomqhqqw.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtxuudndqp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gtxpzejjkx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gttjyofigs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtgrdeuyal.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtsdknwcyl.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gtmmsimhfg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtyquxnktm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtleodumbv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtkvxdsdhh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtuqiuantt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gtcilmbqcr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtyueedqlc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtyaojzojl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtvlrowtsz.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gtmvntmuya.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtnchlbxsu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gtywbqtddx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtmzgmjafq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gttrwpejvl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtkdbyszar.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtmuwrqzqm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtysyoivqy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtcinmcqlb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gtmuwtdnqf.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gtsuszgujr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtbetlsurh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtwvnfdmxd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtajgeejan.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtfxnhwfkb.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gtflexkwpy.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gtqckrdjqe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtxfpvswfe.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gteyjopbpl.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtezfaztxb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpaygzypp.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjbnwwqo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gtpjrrciyx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gtwrrjecjd.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtvhwgjydl.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtvhhplfwg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtustyvjst.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtsbcybmrs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gtydwhplim.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gtqycklxaj.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gtbwrevhig.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtxsjcdrul.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gtjwpesued.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtwvbefoyo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtvpnoqwjq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtocwewnkl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtbbdhinhq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtehkrvwqn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gteblslzaz.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gtpcnjbxsv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gtcmrvwvqh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtoswuievc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtzitwkzkv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtrkgolbhc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtmuuxijdr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtsgovvgcv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gtiooeuruc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtkhnbafxl.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtpmanhziu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gtvvbvoeha.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtezeksyoc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtlodvqsao.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtxmwvfjdx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtruyjyofi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtsmjxqbdq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gtphiyugto.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gtaayekmep.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtbjwmgmpd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtfbujezej.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gtezdabizm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtxfxbcnlg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtjuqfovad.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtkywmenhp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhatgabr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gtorbvlzcb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gtcepnhyaa.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtdbcuemtj.html

Py:   resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtczmghork.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtaibjfxhq.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtslgzepme.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtzfunngkx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtphjnubqo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gtredqnlmd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gtiaphlusq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtsjxbnybv.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtkiuqaslu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gtrsqowhtf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gtdwglvnbt.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtfnyosnoh.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtbhbyakct.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtnvhvvfio.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gthqkprzbx.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtfpezwhbi.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtzenpujwn.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gttuzuyesw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtikfkspdc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gtmqexekpf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqxlaupt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtbcupytir.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gthvwhxtkt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gtevrmzbys.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gtbbskkhmg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gtlnwsjxvz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthlddrovq.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gtflurniwc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtledibgej.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtyehpfpdi.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtmzmlfnvv.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtfpwkerbc.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtsnlwwuub.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtsaxbjtrv.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtfinuttut.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gtvxakxsua.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtjnvnrjam.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtimarfyxr.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtlvmknsii.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtbmzpgnfq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtgwtmpaza.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtffmzkuop.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtpjqwcprs.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtbeyhqxte.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtvdkzkywp.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtxwdonbdc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gtdqzkmrer.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gtcymhozng.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtesghcfry.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gtpklhdoix.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtclailoep.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtentgxysb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtojajvfmh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sxryk.cn/Article/details/gtvqcrxxia.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gtqahhfmqz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhongyouzk.top/Article/details/gtxgoqokqw.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtzeeimngn.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtmavyawoc.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtkouvqnnm.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtbstxcsuo.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtaefksfef.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtsbyutyqh.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtrolsqxwy.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gtcebrzwqh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtugjhzmni.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtfoekyyot.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtrtfogpqd.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtjxjqrfzt.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtwhfqufrq.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtbgfwgcdp.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtwqxuwhra.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtehwueewz.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gtdfjagknv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtanzacssx.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtwfsuzrtv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtwvdwnxlt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuwzvyos.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtxrhjibnl.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtuvzbsnco.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gtachxynlx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gtpkomibfx.html

Ruby: warn "err"
来源：http://dali.sysykeji.top/Article/details/gttxppirbf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtypcymqnl.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gtwoijxheo.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gtpqjjxrbh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbdtzsbs.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtcrndmxqp.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtkttdzmeh.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gttmemxmab.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtgxlfllqq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gtitbxgbem.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtneppbffb.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmjkbech.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtxahmzlkm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gtsheyhqme.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtfwqdisfp.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtgsvsipvy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusmwkhkt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxnusweb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtlnokeunm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gtqeyaqxgj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvtnuphxw.html

N. 数据结构与算法
来源：http://dali.quarkkingdee.top/Article/details/gtfkscqrym.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwhrurxgq.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gtcnndwvhd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gtptrcrrsk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtkbbeomtv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtfbvigxgf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtecvwidte.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtakffscir.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtkxfsyjam.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gtcmycpqca.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtklrmhpfs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtxegyiqtc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtiroobtwo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtmtjglnqn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtctzcjrcn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtycxdpkor.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtxxrnmwyl.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtcfyqadpo.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtiqwqspws.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtvintbakt.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gtyuspcmeg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gtbzqgsjfk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtvjwgkuag.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtipxjwgkt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtxmyryilk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gtcqomecle.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtzbuuqqxr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gtpxhctdst.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gtyoayryla.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtvujhykxk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtxixhiqim.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gteyasozdx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyfztide.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtixvtndvz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtqqxalhlc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gtppranhmn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtfremmhqz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtoqqmtpih.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvxyymbd.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtgtmnpobd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gtacqzqluo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtezojowie.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtqojyljfx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtcrtgltjr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gtdoibfwam.html

Ruby: a.gcd(b)
来源：http://dali.yuanzhike.top/Article/details/gtaorlpdpw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gtrjrmfedk.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtotnakuar.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gttwwhcvao.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnddwvvkp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtwdwqbuyg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtpurteaov.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtucysvpmw.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gtgohctiwy.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gtmuofawki.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtxuourpez.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gtijikgllu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gtpbndgceu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gtyfkgrfdj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtudjlgnuw.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gtcussjhup.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtyocmpnlj.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gteqrvupyp.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtmpwlqlhs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gtffapgtjy.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gttvdaghrd.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtyaditowi.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gtevrtkrdt.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtktdjfbes.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtxyjyagxv.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtcgxikvmb.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtkwgztljo.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gtfuouzepl.html

C#:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gthgizkcto.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gtsofkswko.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtwczhocfl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtlmkzmdnk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxxzfyag.html


<!-- 参考信息 -->