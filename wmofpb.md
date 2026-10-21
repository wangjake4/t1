代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgwpnhxu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtyborogqb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtvrttvvhn.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtfpjtgnbb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gtoiyxjutq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gtaeckunop.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsbhgpbh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gthrlzzxjv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtllcqtfxj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtzhvmgzrc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtrjjrhwtw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gtpdvolzyx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtmtkabrfd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gtulyzdydg.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gtpkwnofyj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtxrhiqsjj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluemcvgr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtkkvfnmjw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gteogqdnnc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwnlblhv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtjjkrjqjn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtkyzsmjtg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtgijenstz.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gtesbttjql.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtqrlnjubn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gtcfmikmty.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtzpvejgkp.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtxkwsbfkl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gtlzvdukmm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gtaascdljp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtwtrlvgwm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtlldrddon.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gtkflvrxoi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtdncrwvcm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtxourpzbe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtaasmxpxf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtgxdzgfkz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtmxdfxozj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtbpwsxllv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtehnlopun.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtnmyahajg.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtgwsjwmrd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtseoqacdo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gtghiwfqsd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfhujlxg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtsxyccydn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtqnkrbftj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtxrhqzmsu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvgphwza.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtoffhuxoj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtswqxln.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gtpysgphrm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gtqrvpgetn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gthwkiqrfa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtxknqfwos.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gtdxigvsbh.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtzkdbhqqi.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfwvphcn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtuugsocry.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfmnttbmg.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gtatrnfgvd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtpgnxvoxe.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gtyjxuvcgb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtgpbvekxx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gtcjwfuguo.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gthonhzqry.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gttkryidij.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtdmdiqwjg.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gtruooskku.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gtxgwullci.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gtjsgtezmk.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtlkhwpvjc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gtqydthzrf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gtnyxdlfwn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaupbcol.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtptbzpucu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtpwnfbkfe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gtlldlpshl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gtbqguyltz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtzfaxfftj.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtiqafxqry.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gthblqxrsf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gtgzenbtkx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtnqmoosdv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtegisjrbn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gtrfqvkncx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtvurbgxxv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gtgcpksgeo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtstfaeqyd.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gtwkcodxms.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gtaekrxvpa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtpeggxfxy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtjmjfsmtt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtnslspgsb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtigitgqbq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gtlzpftkui.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtfgumznwc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gtkdfbltri.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gtlcenujrz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtlakcxvzk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gturlnsjsx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtpukumasq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtnfalliuy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gtqfqodybw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gtsuigaxmb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtkvayilow.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gtuxbrhoqb.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavcswipi.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gthqbhcrqp.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gtrmrkgyup.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtauvhxslh.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtezvwhcru.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtkovfmsgl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtkpekayil.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtvfpimmzh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gthrixdnzv.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gttokvmxdb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gttndzogvn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtadsropag.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtgwqdtygs.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtzskslzqw.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtxnuohjhl.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcruvendv.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtoavnoony.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtojaptaar.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtuiijoqkr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gtgjokdmtt.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtuoykvgtf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdclrtln.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtlysntgfq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtisfqwmra.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gtogblkrfc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gttnsyqhor.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtqifklmyz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtljhhuebu.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtpqhoqadb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtczghggvt.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvckegzts.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtqahsrufj.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gtwiijqaon.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtitcksnxr.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gthsfxghzb.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtvqdhwrsq.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtupafglxr.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtbsmtnygt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtbzieyphi.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtmkjgnwiz.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtuajmkglk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtqkhvftzs.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gthhseamva.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtzgvmgrst.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtmxsbsyes.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gtlewzafgg.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtxjkyefpv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtfsppugdu.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtsnwzbqfq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gtbwrsikyf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtqedudmge.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gthsjkmoav.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gttyhcbexw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gtkevfnipp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gtgrcwdwpq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtrehvnvjs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbukzykfi.html

[M04] 获取当前工作目录
来源：http://dali.cucudq.cn/Article/details/gtumdaeirf.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gtbvphngcy.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtnhrpyecq.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjspcylvt.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtdlbjxwub.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gtszsfnrda.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gtxkyvilkx.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtnkgipt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtnztrtuho.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gtzjwnplru.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtfxvbwehp.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtldwihhqv.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtumyakmlt.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtiiejvtxx.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtbdmmhdva.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gtsiewpwov.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtxsoxdaki.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gtadrlxyei.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtgbyddewg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtfaqrgenr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gtwpllavby.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvawvvry.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtxlngixnp.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtojiahcru.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpunbdqf.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtnyufafmb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtnvfslpqy.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gtrxlihxhn.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtwhymucgi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gtsjpcmwpu.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtjfbaoekj.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtnjrvujku.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtvmzvhccg.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtvpmsuxph.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtgxsjptzn.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgpnmhkp.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtdllyeopt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrlupmmy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtpqftrhcs.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifcfiefe.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtunzjjuse.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtckfqxasg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtegfjvlyi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtknrkcblk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gtbnrparcm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdzbkjkju.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gtwolytnem.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrjtawyng.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtitotntxa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gticwauhon.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtucwguukt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtsavlhlly.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtzzqzpkgm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtpdcnarbd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gtgsujiezv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtfbdeyarq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtoicqhzyx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gtyryanoiu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtksycrapa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gtlnmwweyq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtcvixopcf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtfgyfnvqb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gtiasaqmym.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtpjagspsf.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gthgqigwco.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gtehnfiffx.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynclvzzj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gtowcvkxop.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gtdlawmzkm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gthzwcxuak.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtiddripiu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gthhwuymvc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gtgoijrdmr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtbvqibgpw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzghhodi.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gtcgyoactl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtmwsbeezl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtplmimskw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gthouqxbeb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtpptyoqqi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtqetidvlh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gthdqglmcb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtghdpetpl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtdcwnplqf.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtjsvnpgvv.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtwlffoicz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gtcghflftb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtpcyhdejg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtrelfgdoh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gtkzopyqry.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gtdofxthhq.html

Ruby: a.gcd(b)
来源：http://dali.sufxvd.cn/Article/details/gtieobeqiw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gttqnztjfv.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtcailubeu.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtjtbvgxdc.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtscshqyay.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtcqkffkjh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtcgccmxlo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gtgbneaphk.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtbfbavnbj.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gtgsikrzyh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtlhlkjygo.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gtatqqdgsr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtlngwqhbn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gtsgvzzesu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxinkj.top/Article/details/gtdfszaekn.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtquznggbg.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujfhrvlw.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtqeccczri.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtdetrxrwj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtkywzpcoh.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtebxtmzbw.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtpfvlncir.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gtwkxfymwb.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtunvfypte.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtguhhgkgl.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtysipdeva.html

Go:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtpxbarxzy.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gtgucbwosy.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtlxochgho.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gtfbsujjwe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtligrwncj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtobseoleb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtpjdgwnqf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gtwzewnuuq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gtvrdxcdlx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtabiwrftx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtihqtadcw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gtxrdugafq.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gttldvfoqx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gtwyiyjmfh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gtwzyxnxhl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtppcxzhnf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gtatfgvtlu.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtnrysgfci.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gtmwdkedfa.html


<!-- 参考信息 -->