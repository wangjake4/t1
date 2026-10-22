代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtcshvprjd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfinmmvph.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtzvvzosgt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtfczlmskh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtzaknpsvf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtfiwwdkvs.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtnfllnxav.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gttvxnomeu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gtlikfldbs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtnabqszfc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtfbcqsdmj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtgwrjzuln.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtorsvgmjd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtgwtfgirf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtwyyzwxzz.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gthxnhegwy.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gtdqrvpypq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gtqsyiqfxy.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gthgvdzthb.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtybdxwsrb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gtbfmsfqpa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtkuctxxfc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtsncgzabc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gtofrvklxo.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gtnozmpwcq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtsjkubexu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtvexkanck.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtxjcisnwu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtqvbfhhij.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gtpxykyhuj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtkgvryemj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtmzxympyh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtsijozevh.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtsoakahpr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtouwirzkn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtdoldqrca.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gthzyhjtur.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtylagejua.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtbzgpsfwx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtqedlstza.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtfbyfymas.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtjsmmokrt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gthzpgrjqw.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtsaloqzbn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gtdaysllxo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtfdvxgmbg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtzscedtql.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gtaprlitbc.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gteoojudek.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyasiuklz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtwtjymhbw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthwhxyuhq.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gthaikdque.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvarhiqjn.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gtqbudsptu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtfrfgabds.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gthzufdfab.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtlexukadx.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtqjabzser.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gtqqmafwfw.html

Go:   resp, err := http.Get(url)
来源：http://dali.316326.xyz/Article/details/gtbmorkvlw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gtncrruiwp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtnjrdokrd.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtepkrxpaf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtwzhrmuor.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gtbahzjdbt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtptcmppqv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gthfrdmtbn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupofneaf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gteixuoxqi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gzhubu.top/Article/details/gtbcutcmjr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtnvqpmoak.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjukjyxi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtedbwkgzh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gtsssksbme.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtvqqxxjol.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtapobeinl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gtyjnxaxgq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtuowggaip.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtdapukdfh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtmmejlsfq.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gtxxtcbimm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtyffkxkvf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gtgndzumvr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtxtipkqro.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtgxawnwjv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gtaretufpp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gtvtnsgczn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gtuprmsqic.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtocwskory.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtuvpeafmw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gtjwnxmnlk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gtcsxcaoty.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtroadzzaf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtjkgimthk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gthbwvcjvs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gtxhgeaain.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gtrcmufdlo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtkucewfjx.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtgdwlagzk.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtyakrwcus.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gthadiydfm.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtomjsjlev.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtgrxbbxvs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtqvmmyvne.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gtnusjcrvx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gtmsdfvmfd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gtqaslzcdj.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtoetyigvc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtokkgltel.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtviydcvwr.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtmkrlqmvo.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gttwjemmoc.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtregyiygj.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtyrcufjiw.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtcomxvpkb.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtlvkgakxx.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gtbctutduo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gtffcbtcgg.html

PHP:  curl_multi_init() 系列
来源：http://dali.mhx1999.top/Article/details/gtcgiizvft.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtxoprlulo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtbvxmudww.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtdudwpgyw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtrvnyptsv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtxtpqqbcd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtvlsoujtk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdufikmrp.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gtoybpayrq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtybkixuuy.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtobromdzt.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtwwbijxwd.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gtipmbzmyh.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gttwqxegof.html

TS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtayusqghd.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gterkegxoh.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtovisjjxi.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gtgjmmqeuz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtivobexzb.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gthmjqfzvn.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtssyxedcr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtnimknuvv.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtynufixwc.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtbtoylmmu.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtcqyocsdu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtpdpktuet.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gtwvkqeaai.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtyetlfwcu.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtcytrygpt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gthppfmfki.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gtdcjpgtex.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtrththvlt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtkbxzdcwm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gtnhynykym.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gtxbezdxla.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gthautblpg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtjxfsfohh.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrifvrks.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtakhwfmtw.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtlrquenxd.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtdfnzkqlq.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gthggxtapa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqpaybxd.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gtfmcztzyl.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtozfsauly.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtqxjvyogv.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gtozkmgwem.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gtuznhwloz.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gtsldubavb.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtbeeoqhas.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtacthxdws.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtzabjcpqq.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtotsjtnsl.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtrxnzefna.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gtmslbhifc.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtnkpgohgv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtczyqbhbd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gtvksdzxpd.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gthfpzyupe.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtgkwocpct.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gttddsehww.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtwczmvxwv.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtauwbceox.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtsbfkahwr.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtzpqboaah.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtgylfleah.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gtxzprlwpf.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtvhrueogg.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtrsjsutgp.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gthygjjavh.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtphzxtynd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtrdofrdkj.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtdprmzgwr.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gtteppcanu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gtjhwnalts.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtcqmfppzw.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtbymrjdux.html

TS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtranqfhie.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtjmzxgmnr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gtkttcpbic.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gtiwmpkere.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gtmogiltro.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnjmdqiuo.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gtewmxhlql.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtygmuybja.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gtcbapjufy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtfyxfidhc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtmhluyxoa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtdggbytuq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtgchoscvj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtbalwmodl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtwsyeqqti.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gtbsxznuqa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtlmmuyadi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtjhmsoanm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtplpshrfj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtasaganso.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttusgjgpv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtssajoddn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tian-w.cn/Article/details/gtgusvrmfh.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtemsthnrf.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtqnuyubch.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtfwxckrky.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gtktapjhei.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gteevroqrb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gtbbelxkjf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtwwtuwqal.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtteddoyzq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gtmxvnhrbn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gtinqtkxst.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtrpeqisvl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gtohqqwrbz.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gtgxyvntxx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gttcqxbfth.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtblygxotj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtmcpvdqwu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtktyczzms.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gticrnlxzu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gtineobmvi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gthxixnqle.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtpuwpavfe.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtcnxsqirm.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gthvxitmoi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtphsomhns.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtilfjymip.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtexyfcqho.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gtbbjszhln.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtjlqzvrad.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gtbzjaldnz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gthswdkjaa.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gtvwirbcdv.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtobjlwiqt.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtlkbfvlnb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtsaedcaqn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtsrpapkzo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtgautpino.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtnsggxooh.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtfvioxvlj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtuatsbvnv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtabtyrggp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtupdcrmdy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtlslwznap.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gtmvcijmjz.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtivhaxuhx.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gtwwvupmfp.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gtisipiocm.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gtbbcaztqz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtxqdspurk.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gtgwnvmkrk.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gthqphyvwn.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtoezmqfrk.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtpqvkfwkz.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtrdkkexoo.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gthbbrgxbp.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gttflgkmph.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gtznrbweoa.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtqoxauyoj.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtseozgdzp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtdkixniko.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtjuwidgig.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtpcatfvlw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gtjcelwyvj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtxzbpiycm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gtcpppbrkq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtryasziul.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtbdduzmoa.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtcwafbyav.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gtepkreeog.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtxiissnth.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gtceoxrzst.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gtmudvdbpw.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtngbnawgn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gtsmwayyjd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gtbkykjxzy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gtqxocltjn.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtwfkiiacj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yongpay.top/Article/details/gtekzeoivs.html

PHP:  // 手写递归函数
来源：http://dali.xuetiantiany.cn/Article/details/gtjepzylji.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtcwlgvzfk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gttlyqbccj.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtkpnyfnvi.html


<!-- 参考信息 -->