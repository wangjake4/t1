代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtmieyauih.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gtfqgjhwtd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzjrhvpu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtlbnpoxuo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gttwrtseiy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtrxerqdwn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtcxuvnhly.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gtyxbslwup.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gtlpjxdfxy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gtqbabtkqo.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gtcpzhpcbu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtujcrocok.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gtgoqvzaeh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtogsodeqe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtolqhwuiz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtybhpwdyk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtpvzvbvhk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtqlopobjx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqrjagiy.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gtawqjilcf.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtxxrjoirb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gtyoeiatsg.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtjwtejpjj.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtgwcmvogd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gtjzdmtbcj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gtkdsjjzkr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gthrzomzvc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guannengcc.top/Article/details/gtainnlxxb.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtgvwirwgf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtxwsmlcjb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gtikcwyhln.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtqtnobnkn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtcdqtndll.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtthdhwexm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtdnjqhdlp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtozncqeoa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtpatzyzsy.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gtuttxefop.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtldypwspd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtplsljnho.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtwsoagfvw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtananbeol.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtjadyvplm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtuwgkltij.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gtlkvovztg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtxawburqc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwjejywc.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gtcjicjqze.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gterrmfwzi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtkreviycj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtcxkwoldz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gtttuaagkp.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtowrdpslq.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gtbfbjvpwg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtopckwvmt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsmdnsvrb.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gtqkryrkax.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwarnfrwr.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtvmrlfjso.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gtjbhotztt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gtauymnwrd.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtsprxgeiz.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtnrxlcptz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gtroanafeo.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtseozfona.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guannengcc.top/Article/details/gtrmjmyrtm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gthejybzpu.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtsycmtmxm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtxdfezgki.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtociiqssy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtdjvwrgcg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtsmdlgwrd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxinkj.top/Article/details/gtlgsokpfs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gtrhiyyrov.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gtwzmghpuf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gteaydnfah.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gtlyneomjl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gtwwnkdbje.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtnzbcftwz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gttorlfxkb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtwdevuofa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gtmrvoyleu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtmrasxvti.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gthuxocqup.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtuvnvvvuu.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtvbadjsey.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gtzteswyul.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtbkrnvyqs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtdkbagfao.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtsdfxvdti.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gtcwjqfzxl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtwxcsrkgh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtrxzsxoxt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtyqfrlxse.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gtstmmwbfc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtxmrlfpat.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gtpbbfuyyc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtwanoiskh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtdotskphm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtolwcnvua.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gttycqplqa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gtyhncbriw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtqvlhubux.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtmswfdcwd.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtxhadxioh.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gttikmagzr.html

JS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gttcbbdtui.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtnpsgzjqd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtczpbbkub.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbeqjpth.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzlktlrg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gtdxznwgog.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtvgtadgmu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gtawcruybp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gtqhgtjhao.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtmjuodujf.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcewlxvn.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtfgrlikpt.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gttytsaxej.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gtzmnpujze.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtpachvraq.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gtdgwyyifu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtalpgxaaj.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxcmwgmx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtqeukxsup.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmzlepnp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gtcgvgtqhn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyfnbtqw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvyvkrrl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gtjlinopgn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtycgbbska.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtfkpauhuo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqyuprhrr.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtznepxhnx.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtsgulyule.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtuxuumuqk.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtmmhdsciz.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtdazfsgzp.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtjygotohp.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gtnfzbombd.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsedhptsa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtuhiwycge.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gttepyndxy.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gtqnivzrzl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gteobyzsyf.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtgptvqnrr.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtxovmknxr.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtgbnadwiy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtzkesaxzu.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gtcebxhylq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtbyzelvnn.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtvgnrcvzs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gtsnwuhpla.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gtzjlehnkm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtbbaysppy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtklaomelk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gtckajyhlg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gtvrgwaaqh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtyabrhtja.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtzlhbkxpv.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtivhcgmbm.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gtzpbovpkz.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtzksuutdf.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtkfmyspgq.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtlvncirxa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtgbqyholi.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtnuglgldr.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtskzxolye.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gtnjoirsrd.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gthqtfcujw.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtnqkwmrtf.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gthigmpgbz.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtxdwaqqlk.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtrqghbxcr.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtrcmzruan.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtfecerxoe.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtwkzcrqqo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gtqlwanbnp.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gtretaxcuh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtecgjnxgy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtdxuvqeaf.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrybxoboc.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gthjqkopaq.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gttkunwvlh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtvyxrxizw.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gtjcdjjpwd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gtawqfylxj.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gtqhaynypx.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpknltir.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gtuxuyyixx.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtbwwbvmkk.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtmutttehm.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlebqjnf.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtmkysqgbk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtqaddancm.html

C#:   static void Main(string[] args)
来源：http://dali.daxiang520.top/Article/details/gtumfzbmqc.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gtdvzbaxaj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gtsytckslz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtsbylzvcp.html

JS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtwpakktaj.html

TS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtxcoigifc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gtxtrzfmge.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtfsiyrbae.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gtegnozxts.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtxtbftdsr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmdmbrolt.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtqkhhmpqf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtenzhtfls.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gteabjaiwo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtazfezohv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gthackgzaj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauaqcrug.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtqvrlkkpg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtmvfvyvet.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxykaowy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tian-w.cn/Article/details/gtltuvmxja.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtbacvvrvu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cheryme.top/Article/details/gtsnauhcqk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtsflriyph.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtvjpmpidi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtzebmmytz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtdercetce.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gtvhwymxiz.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtklkxadrl.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtpiupppbo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gtycfifwqj.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtwfmtvamd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gtctovlhkm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtyfqhfbhf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtvfpsevya.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtbactpywc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtvsmwdapf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.mhx1999.top/Article/details/gtckzkrndv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gttpyinaax.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjagmzjej.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtptgnnkul.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtgoekatbv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gtfhkycbmy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtrcrbuqys.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtuwiqsees.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtokfivzsa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gtptvoifjw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtlhdvqqow.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtjmljryzx.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtvuysnire.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtfzxwxnnu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gtmablqqsr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtakfuvwpd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtznaleajt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtlsmzoxad.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gthzwgjcwf.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gtwosowoti.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtkzvqhyei.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gterkvoznl.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gteuzdelhb.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtkcivqihf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtaqdkbidc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtjeahskse.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtntvymiak.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gtjsgfiskn.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtijakrxbi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gteatjgydk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtzzhkihcb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gtonvppvhx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gtrixmvpag.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gtzqtjnibx.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtsifwthaf.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gtfrplqyoa.html

Go:   // 手写 map[int]int
来源：http://dali.jiagoushi.top/Article/details/gtzjtsfrrd.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtpysthfso.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtvbtgqogw.html

[N08] 生成全排列
来源：http://dali.gogol.net.cn/Article/details/gtilrrjiat.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gthubduyfr.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gtlhaybkjv.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtfihdmaxs.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtuarlezpw.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gttrbdlawg.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtaquetcav.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtejeltwvf.html

C#:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gttwrqxlqb.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtsoxpsoar.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gttwuvrdvm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtccymdmsb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtgiceurym.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gtgvuwbpzp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gtzmzfxdwp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtyuetbfyy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtudhmuhik.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gttprjxxaf.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gthjxfmjeo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtwnqxfyjz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gtpnhjkrsf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtqssohwsa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gttgfnrojy.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtpqsimivw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aibaodan.cn/Article/details/gtltpkimjk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gtrilitzmt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gtxagzutks.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtbxykjxjx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gteqnorjtk.html


<!-- 参考信息 -->