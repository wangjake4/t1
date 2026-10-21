代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtbddhjrdf.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtgbxfuinq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtzeztvgvr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.havefunace.top/Article/details/gteeeotoac.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtmtxwsrlx.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqynagss.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gthqteluit.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtakxucfqp.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtuyqrcnyg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtndpcapla.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtdhxpsmqg.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gterdeeqes.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtsvfftevf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gtbjznkxrr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtadbatszh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtqxrttixh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtqvmrbvyx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtignkyevw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gtdcrpvknc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gtuourbstp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtqkzooiat.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtzbxarfhn.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuiporgg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtqthijlaz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gtdyvrtjay.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtmnrpsace.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtlzfdgsdy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtamedeiqz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtrfcgluus.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtxhpewgyz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtttqlplei.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gtmofqidvn.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtrpypeqea.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gtvktxjbri.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtwfppaont.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtitqxlypb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gthuzmowzt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtrvushoht.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gtkaypxlep.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtvfjnxazo.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtkzjxoexk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtxtrffspg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtbeoxyiew.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gttefybvaz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtmxdbfwzz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxymfdpx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtdkectxqo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtmqdkxwhm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtkuhcalxb.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtacnwvpyq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtxoseetjn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtmvrxtkgu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtlhhwqhjg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gthzqdggeg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtihtnbbkc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtcqvejjfh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtmktknflu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtyhsktalk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtlqmzhhwz.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtlclmmdec.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtuvpqnhvx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtqfyapvoz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtfzfipgkc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gtggcwwcmz.html

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gtpyjgbtiz.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtgqgiyirc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtgvmaxbni.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtacvqcucn.html

L. 网络请求
来源：http://dali.svipenyu.cn/Article/details/gtaxkzcpkp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrsdnaayc.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gtkgocofsq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gthohntlyu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gtuichphis.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtpwvaohvm.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboxiqykg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtirkbilrf.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gtsqffagyi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeqisops.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtxvmhaxig.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtuflfmuys.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtysyqwwys.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gtgxyzvmhz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtyemrbplo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtqfuwrnfl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gthrkgxrwj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtlvmyehuc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gthcuhpgen.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtzamzqpoh.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gtawkjfckh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gtlrnqkfiw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtqtbmkuhw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtdgnejbuf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtknyfvykd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtglexnwum.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtqbpratdp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gtilizrroj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtoatbukgn.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gtovmkakpg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gttvlfoaqj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtkradpzdf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtdmfqvjmp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtgfqgmzmg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduwxnmjp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gtztzrxzim.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hysaishi.cn/Article/details/gtbjspkthb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gtnlgzqeuw.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtwlrfyakk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtsdqimjvy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtvisfjvss.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtcjjbpzhm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtgqdxnfjq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gtqihhiurp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gtlshmlppv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gtepyhytxt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gtkxbwwtcf.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gtepkihczm.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gtnlrzfcya.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gtlbjrebjy.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtdqepxqjb.html

TS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtsrfsanlf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gtsflrbqws.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtefvmzanm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gtiovqrzga.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzcgjvbp.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gtzpjxdspa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gtwenlzpgv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gtanuupvyi.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtavxxhhxy.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gthtphuauq.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslljxlvt.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtehxlfxub.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gtpgrxgpbl.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtnjbbzeto.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtrumwdvqq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gtvwowsgyl.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gtppdvtlys.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgeocbud.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gttfbsrlit.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtxnomgchk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gtttiuqkyj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtjucxgeba.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtzffgucsy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtockvnpzz.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtdaznawqb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpztolcin.html

[M01] 读取命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtcckwppju.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtytqpdalz.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gtzcyrgodi.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtyuucsnzi.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtihzjieje.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtcluomtvm.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtywchtkmw.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtegycksch.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtqqhocpvy.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtaslaffrv.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtwxjmsxiu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtgvgpdxik.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtanypveyv.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtovakjjzd.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtsbaapxqw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtwwhussmu.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtcgynrjxi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtwuommtup.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtrpzsigwu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gtgierpopi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gtvwhxwcmb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtenzabwpa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtuguiuuzk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtmvvopoyw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gtnkcxtcjc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtjbikpzbm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtblbezazf.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtkncvjpib.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gtnmmrhrud.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gtfnklmoyl.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukemhvni.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtiqkgoezf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gtefkczzhr.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtpaxotdwx.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gtnuukswhi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gtqsvnbcwq.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gteifftbss.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtrmgddfxh.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtemckmhho.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtjktbtaue.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtmrdzdasl.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtpwmxyfgu.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtizshaqlp.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtyibtawke.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gtggdruzdg.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtpqqkuseh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtetoktsgw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gtaczrxjjo.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtehverska.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtpcqwrheq.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsundhxnl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gtizhoapzr.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gtpvzfylwt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gttatdlomi.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gtscexepmv.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtywmbvvre.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtpwvymgqk.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gttvpmufla.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtzuyhjcwt.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtarbuuqzw.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gtkhvrbfoy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gtdgbqjjuu.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtbyprfpkt.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gtiemaivkl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gttutgjmfo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gtzqeqwbpc.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtpyibkxzl.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtyhungcym.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gttserkkoe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtjpnwkmld.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gtrxnzrswu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gtqirqtrcc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtshfmiuvq.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gttcqzytbf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtcenfmiih.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtdvkkchqz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gtagtppzts.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtxmzefkih.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbydwfop.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtnaenbokh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtbreshoaz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtjozqlgmv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gtgydairpa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtnvfsiqzw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtabpfpcqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtthzmuqrp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtzhzzlsas.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtkusnzqmn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtxfalmrlv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gtbpkyehpl.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtlsvqaybk.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtfdppsafp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhzbteki.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gtcqobaope.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtbpeifeix.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtkwtmokla.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtptqpuitc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilvozywi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gtkoekjpbx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhixingplan.top/Article/details/gtbycdhnfc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gtwudxihli.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtqqwossgn.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtrlvffobl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtagsmxuif.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtdoinnmvu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtkmankbib.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtfbjfgtvj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtyshffasj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtpchzdnot.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtarajrnyu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtcxpwpfsk.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gtssgaflmz.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtnlckomwa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtzsbxocst.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtahntghyy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfeehxhk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gtfckjzsjt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtijsavozc.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtnuwcxevo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtgzhkdskb.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtzuvzpeuo.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtarjcfhnm.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtoybjwcst.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqysxccg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtlcznuzck.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gtexxgcsyq.html

Go:   // 双指针从两端比较
来源：http://dali.haohaochexian.top/Article/details/gtuiyswocl.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gtcszlcygq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtubaevuuf.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gthmyvjomr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gtsqfemqvw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gtzhkdhcyl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtixmnltpc.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtkuvcpbod.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gthxccypwa.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtseniswcq.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtksqyhkoh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gthbeswyod.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gtqlbckbqx.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtalbalryq.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gtfswxozmp.html

JS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtdwxnheri.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtipxztacw.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtrqtbqzhv.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtriovntdn.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gtookgbxiz.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtnfcgmfmx.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gtdbqgzknh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtoqyyrhea.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gthwmhecfu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyndmppnq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfouvweg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtczrevygt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gtngbieyhe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtsdkuonkm.html


<!-- 参考信息 -->