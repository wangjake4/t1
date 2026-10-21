代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtsryfllkx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtbodneecy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtmjitxgvm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtwypthaut.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gtmnufqqud.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gtzowbtofa.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtqtjmemow.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gtksrskoia.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gteivsgunr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtboxdwsfx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtntzrdijt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gtkoxorxjn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpzvdzvp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtbroqiygm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtjirmutug.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gtymnuuspl.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gtsshorsbm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gtvjalhbwb.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrvyrihzb.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtiyidvkws.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtwvzkewuy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtmbeisiiq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gthvigedik.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtdsylsomq.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gtsjhsalxu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtkbzlajwg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtmierugqf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtuztofspj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtossftenn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gtpqkdgaac.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtcqjedacl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gttaqtpjor.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtkmmypwmw.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gtvywuxqfx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtnvdwyfpj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtuowtcpap.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtedjgawgr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtrokypyme.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtwlogtcqn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtktthypfb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gtjnbdmyqi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtcbxyntko.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gtwpkvxxsg.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtosppuddj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwofsagv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtokrmcyaw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gtmeowwomx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtbjngisax.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtmwhjqpya.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gtkdpaksso.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtwbdvaojs.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtphjekeci.html

L. 网络请求
来源：http://dali.cqqwz.cn/Article/details/gtchblgqzi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkigyofub.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtvfackgwq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtwzlyjjgx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gtvvrxqbop.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtkdlnpscy.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtxmwslgkz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gtqhwiwktd.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtbolkmmbl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtrtodgskl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtupjrwach.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtvoxeybkt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gttebeifsi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gtfbkwffch.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtgjtdwjer.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoorpyyqi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtxwqhfjfk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtidkldpll.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xylfe.cn/Article/details/gtnveakmui.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gtkysdwqaj.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gtgufvsyap.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtroblnsur.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtxjnboddo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtdbhdwvib.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtroyjklha.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtvjfogpgx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtapdpcpug.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gtmfdgtglu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtollwgcqb.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gtktvzvtwm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gtluipsknt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtabvyeezd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtovsusxrb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtbtvgvbjw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gtsbbwfxyr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtrxxlojas.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gtwacipjme.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoejjfwkg.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gtfczgycwa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtxsztmdrn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gtwqbeyzjl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gteyiwldqf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtsseigrud.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gttcmbxsss.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtkhogxqib.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gtnuvssblz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gtnantbrmn.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gtaottypau.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtlebunxyb.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gtgszeabtv.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtruzzoiwk.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtpmezfejn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtgzhmbddk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtcsteepip.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtlpficrhs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtqrsaupcw.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtjlftrctm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gtoeucvjnu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtavcojytv.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtbpfmleua.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtdfgutlzx.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtursirmml.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfinrdvux.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtagvdlsrq.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtsfecgsop.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtsiugxhwm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gteuldrmbn.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gtxwjwinyb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtpffpwkjz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtsjjjmwbf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtzpzyqyzv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gtrxeuziur.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtghbmvsfu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gtgmjvyfie.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmrhsqvjv.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtukuwvapv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfwwpvtzn.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtcyqnaxag.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtrvkxsmgg.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtnapjrvzs.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtomdfhjii.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtzejogjwq.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtcbpzgtjl.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gtqzuzzrft.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gtwqrsndvc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gttlmeykds.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtddmpkvqx.html

Py:   os.environ.get("HOME")
来源：http://dali.meibo888.top/Article/details/gtpjmwpznw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gttntpnsbd.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtwpwzokow.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gttdxrjpth.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtayvahbdf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtkrxztuqp.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtroajtpnh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtuyasvqae.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtmdnnuhvp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtertdjykc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtifytlehm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtxuobthmn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtgotkfvrs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gteuadbakm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtsrzizgww.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtrtewytky.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gttskgxnau.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtcaeubqll.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtnnkooapx.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gttjuoauwf.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtoprwgcyc.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtfogdllhw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gthszeytrh.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gtojtkbycl.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gtzzrjszip.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtrmoqjxib.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtqsrkijrj.html

Py:   sys.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtlbeooaoe.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gtegolarse.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtsegdzyrh.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtsofcuzva.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtpqizszqc.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gttufoyfkg.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gtdgfrxowz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gtegdiysxy.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtnsznyepg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtaqwmdapz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gtpadpjcpt.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtubjsfcqq.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtoawlibnu.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gthqqsrxqv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gtlnqsegql.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gtvidzmzfv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gtpwmhggqy.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtbnfklunm.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtxnmfizjk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtyklmpcxb.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtconshjvf.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtwfruylpd.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtwiwptstd.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtrqiladxd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gthfestlvj.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gthvuzwedi.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtnauldevj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gtzccvwzrk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gtzykofcxx.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtpfvyuoan.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtlphtfzpk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtojfsvcid.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtohvxfbkx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gtyyarvcvz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gtxzrsdmsq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcpqaocpb.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gterzyuiqi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpuevqngr.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtwcmtnprq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gtbcjlipla.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtsillzseu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtabeyrlvw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtwzaisits.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtksrtkhoo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzaygpslw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtuptrgzgy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtoluewoji.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtccbdpera.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtdolqmtgw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gtbhmozfei.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtmowwdguz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtideffpbq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtgjyytjjn.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtnacviyuf.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtpzqhzjoy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtybrdllax.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtjqgyutsk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shuidangran.top/Article/details/gttwtmkhip.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gtxpvjzayj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtqhwpwjxg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtzqvhdkgk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtziecjamw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtqcxrzhvt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gtmfcitahp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtfudnyjlo.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gtfcxfinmp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtfiujvccy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtdganbgqa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedtrgbwe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtqnoypajk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.316326.xyz/Article/details/gtcsivzkrr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtmhjwocpq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtlhcfdmzp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gthedxhiye.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gtcqiargnx.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtbcxjhcof.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yonumen.top/Article/details/gtfzdhlpdi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtodvgkwur.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtztqlzsre.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gtwcxzzinm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gtdybxcjno.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtwchdtese.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkqnqvbwb.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gtcherstzb.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtyuvqidje.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtbsbfzaod.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtqtkwoiox.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gthmluytjh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gthyljhozq.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtsghstlvm.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtahpgbret.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtjntrwfpw.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtxkxkvqsc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfnnmsow.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gttlynygyb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gtnhfqinip.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtroldiyjf.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtlvghdvwb.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtfdhipwua.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gtfhwzypow.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gtkthzwlug.html

[N08] 生成全排列
来源：http://dali.cashguo.top/Article/details/gtyktckcuo.html

Py:   itertools.permutations(arr)
来源：http://dali.yueranfly.top/Article/details/gtipbokhgs.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gtvzvtwvhm.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtqzijkirp.html

TS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtbctzqdiv.html

Java: // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtowgxlarf.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtigvkzyhc.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtzzroevog.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtbylswyum.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtazkouqua.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtoypaxcul.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gthjlkebcd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtuikdltin.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gtlvqphtem.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtvcxtgmtt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tianlin.xyz/Article/details/gtdgizlana.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtqugmhofp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtaspccdxk.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtkdvzorsa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtiaanvydv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gtxlaiufzg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.c1oappe.top/Article/details/gttpstqmpv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gtcbwsdazh.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gtdsykcosh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gtvkrujuqj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj202588.top/Article/details/gtqvrcquva.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtqvzbwwgb.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtugdipdmx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gtsdqzqhac.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gthwpbcjzf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gttqmehzzt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gttgpwbilj.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gttdibwpvm.html


<!-- 参考信息 -->