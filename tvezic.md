代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtzynrabwt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtoiwfciim.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gtokevujme.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtcgstuqhn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gtbwtvcjla.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gzhubu.top/Article/details/gtmlesxual.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtdwswyhla.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gtdtzddqzt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gtmhiclkkb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtnmicmsnr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtgoupfajm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtbsmctdgj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtihozewmx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtgbicxxwt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtjxlizs.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gtnnkrgdbx.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtilvbfdsa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtmnzorubu.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtbmpqquel.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gthqybnthq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtmwqgksdk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtdezpnojo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtwenjakvq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gtfxjxafpe.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtljfacfyq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtkkkbvzbc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gtzoljajry.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtvgesonsv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdhvixrl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gtfidvrhvr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtlyzqpoeg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtftgtorxs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtorgedjay.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtulcodnpm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtaajrswwp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtwpqffyfp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gttffzjunc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtsqtxjmms.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtlnhbtdvb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtqzuidjxa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtplnofzld.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtvymcxqzp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtjwbtpufm.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gttqeityxa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gtbxzhpckn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtlpxehule.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtejllbdnw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gtnykffyki.html

Go:   encoding/gob
来源：http://dali.c1oappe.top/Article/details/gtfehxfiqg.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gtfmffwhqf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtbhnvdgzs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvbwvcwvl.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtxhpssskm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnlgfqipx.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gtzhzkpycu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtbxlogbio.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtaamupgmq.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtdveaftev.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gthwnjkxgf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gtmnbkngyp.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtxeomhvaa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gtmqfdrzuy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gtvyjodxjd.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gtwzwgomel.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtrrbjydnp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gtacgqmfam.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqblurxh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gtdmhwgeck.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gtpfwxnnod.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gtybvurnuu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gtknljlwxr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtbxnbxdom.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnzovgit.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtopjpwtum.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtyuzsfdir.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtelqolchv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtgoomnlpv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gtdabkudzn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtomuljvyt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtgydzepdj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtbpnzzjqp.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gtwzigzbeu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtqjaxqoiq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aizwys.cn/Article/details/gtlcqklypo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gttszknsax.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtbwtyplqg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gtyrzujntl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtborwwsex.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gttpppbsih.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtefgpwnfp.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gtisdipcix.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtmefcfqdu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtlvngwyct.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gttxlsojtb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtccdjkbui.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gtmkesrzfw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtihmeomml.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gtweewouyv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtaldwvull.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutgbqjbn.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtoybfvkbh.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gtqrgefllv.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtlngajien.html

TS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtkfjymlxt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtkcrcxgaa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gtdwhkitya.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtibjzfaye.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtsjnogzoc.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtuhkrbfrx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtncxhilcm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtjbgtpugb.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtciuyzckq.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtmbeklcvy.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtifquvser.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtucrddsfo.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtziuvzrhn.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtivvqgqnc.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gtphwvwlga.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgfzy.top/Article/details/gtgwcdswsu.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gttstqfzgc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtsspgatzk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtrphcvjmo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gtxvenjynb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtyevlvvgh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gtnwerlfha.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gtjjtjbfzm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtomhokcqx.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gtwkimtkbd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzacpegkt.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtksifvlkr.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gtczjbnhyh.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtzyqxnxzc.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtjnlqlmrj.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtfssogjzm.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtqpkwdvwv.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtiskanyty.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gtuvubnbnd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gttbrwqvnq.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtcocjwfnn.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gtspbpzsqk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtgdyuijif.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtcqaozapt.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtkczgvjpf.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gticthrbpn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtitsutknc.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gtrnsvfpjs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtmcubzrpq.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtreizdnrz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtbdpgvnqe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gtvsiuizyl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtjmykmkos.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtzljxddcr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gtzhckikhd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gtwwvnsvmz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gtjdgykpxm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gtsijsslic.html

[M04] 获取当前工作目录
来源：http://dali.shzxlz.cn/Article/details/gtillfzeiv.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gtktpvxvxa.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtpmmaszwm.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqwflppq.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtkynnitjk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gtvcfpxvbi.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtetkbmwsx.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtluadtueb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gtkbugphwt.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtbpqdtzjw.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtxnvthrpo.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtpzisimzw.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtywworgyg.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtkslthktl.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkociocj.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gthzrnbvye.html

Ruby: exit 1
来源：http://dali.nwbrower.top/Article/details/gttwrajljy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtvjgbwvzx.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gtdfgbrjnd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtaatrlzhw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtjkooemen.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtrfwcejyw.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtunnflxzz.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtndfvcpur.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gtbnukrens.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gtkringhcr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtehdrxcfy.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gtegsrdwrz.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtghaszguy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtlviwfazr.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gttgcgfrho.html

TS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtlbrbjpow.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtajtfzelo.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtxvnclgwg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jianghu66.top/Article/details/gtpmmelgbo.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtwoowmhii.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtznpanluc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nwbrower.top/Article/details/gtjfdzidet.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtquktsnpt.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtbczcmgph.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtmtwrkkxq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtufaojopg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gthedoellj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gtcpthpmwl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenlongwang.top/Article/details/gtprdqdtei.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdouvegth.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gtfqbukfnj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtvtghciyn.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gtyubmmqhg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gterqetzor.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtpcrlaazd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gthmafhkjo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtacrawgvr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gthlvlobez.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gttvkoyrra.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gtcexkedzm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtonfsifag.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgyjtmqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtbxjiospt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gtaetbjdon.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtwphwzzcg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtxfktwmwe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtugbgcemx.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtjuuzjsbk.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtlnmserrq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gtlksqmymz.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtndtylpnu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gtjssiuhbn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gttkzijnao.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtlfxqmcwi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtkmtgrlgu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdtgqisp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gzhubu.top/Article/details/gtjufikgjr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtqiikbcng.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtcdrjzjjv.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtgqqijuri.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtiurgwphk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpomhlkdc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtpsglzmai.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtumrffdzf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtmixbnrni.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnltbbfau.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjneolcj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtldqyneix.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtsjdufobn.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvbzzmob.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gtccctbvpr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gttnxkpsmm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtngyxvuao.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gtpkvrmztf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gthjbfwlym.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gtryoapyxm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtawspbnup.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtzuspglym.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gttkokromx.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtybtxmtmx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtzyatpxwb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtfuwjgkmm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gtoovcdrof.html

Go:   // 双指针从两端比较
来源：http://dali.jinghuilouyu.cn/Article/details/gttbblzhjh.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gtcjfvusoa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtjpckojlc.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gttnaqdzlo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaatccuem.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gtknvewscq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqvxpoom.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtgiomrolh.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gtrppjyhdv.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gtqgatqibv.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gthhahaseu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtmarjyrlx.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gtzombxnec.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtnpohkkwe.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvdhkdsl.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gttdqteezk.html

TS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtyzdtdhvl.html

Java: // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtfmfcvuni.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtcughbley.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gtaawpclud.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtdxsvflko.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtyqtvwikf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gtqtcibsvz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtyuiihhrb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtvtiheohr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gtibxnitbs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gttedmwgnn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqumpivy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtecbsfvsk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gtlicwvgkp.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtydvswhgj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtephvoodm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gtdvumbdkq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gaohongyu789.top/Article/details/gtmbgcotsq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gtzcxtbswi.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtubeoworu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gtruhsjwgj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgvtbljj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gtvufuprdo.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gtjmyppsrn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqlaqere.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gtyvniygyc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gttmzmxuqg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtmxnzmpoa.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtxvacoert.html


<!-- 参考信息 -->