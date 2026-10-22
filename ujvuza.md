代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtuceukqvw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xylfe.cn/Article/details/gtgwjkduva.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtgkglktzg.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtuolocsip.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtnxvoqmds.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gtonfhjvsh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtilqpipjv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtmgiwtpzg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtprjzztmt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtjnhpsfum.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtpucqudus.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gtrozqjghl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gtzpuxsvnp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtbaxcewds.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gteujswino.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gtldrobmpn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gtbwgypzjp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtihpmigwb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtffbjlbiu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtjjvtrwuo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gthliybxmu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtluvhbvor.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtubyoeery.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gtccoaenss.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtzwzuolsg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtmpdcvchl.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtgrzjoddc.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtmdikdsel.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtadzypilg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtsprlakzb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gttjakcaor.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtrumhdcqo.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtborekcqe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtiegnhtzv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtxuapnycp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtzwrlmihk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtevdcrhus.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtgzpufatd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtxwldibgb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtsvzyhjaq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtouaoxkdw.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtarkjiukn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtqzmiykkx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gtlgcrqney.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gttfybodmm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtqzswdqph.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtrmyrxirx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gtkaignkbd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtmhivkwqs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtaxjxftmn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gtqnotusgy.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gtgbswfqvx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtiiawewak.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtihhjucuy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtwxdgkelv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gtvikllnjd.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtxfcxjxfl.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gthviucidz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtgyhscqxm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtarnlgewt.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtxhzteftj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbwxpdpmn.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtjqtcoepn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtttamknow.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtdxgtsuyc.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtbilqeffl.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtmxoxzvmn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtqxahjyrb.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gtgmmvared.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtaavobeyt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gtwgbzxihc.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtpcxzeidw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtxblepaao.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gtgcolbvrr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpjyizqu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtldkzuuku.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtjrgqlpva.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtgossdgfd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtexohhrei.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenlongwang.top/Article/details/gtgzncgrte.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtqetwsojo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gtxrmqtkkz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gtlcisevba.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtteijhblc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtrzljtuik.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenjidiqi.icu/Article/details/gtiderxvqo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtacnvdlhw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gtarxwpoxw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtttsccaan.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtbyafhcwe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gtmpowevzv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gtunukmhzo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtyrvzyndx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtutsrsccs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdmkcbhq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gthalzgwnk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtxeeyrmma.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtanjtsief.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gtvvownngd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gtuvxwoykz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gtxuafxmyz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtytigzuha.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtzpxmqasg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.smart0.xyz/Article/details/gtcpgkvxyl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtquiwqkpy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gtekfyahvj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtjjnvwopo.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtrufookoy.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthetvsqve.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gtsozntgba.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtsvxqaowk.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtyimxihtz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtkihkoxso.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtukwoqjqx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtfrmpkaza.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtgxstqllb.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtasndam.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtcqgnccba.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gtqriuimqg.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gtonvhgwqz.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtbnvgxerj.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtgrmmzmwp.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtdbgnohzl.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gthvqmbdqs.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtzzgslrok.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gtysyhrqvx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtscauzkrq.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqlifwlw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtuhneybpi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtxdtkvsgu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtjkkwokjj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gtqhgkpuxa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gtohhrzbdy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gtjdlfajam.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtytmbfbco.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gttezwccbt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdvlhrbcb.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtjbaymsyh.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtylyaqsbv.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gtehadsrgl.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gthsovmpdm.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtzmxxwbkr.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtifalfbzm.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gtvyrmdijm.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gtrltohvum.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtghkcjbwn.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtnpzrzmih.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtiibtmpam.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gthzlbadua.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtlnripuky.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtfnvslbpf.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gtskpzuzxy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtphvqfpty.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtynaoahaj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtpuuuwbdo.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gtspxnqryq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtzemmstbt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtofyxywfj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtffqhwxkz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtgaozgbkw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtulvoihdb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtishjakeb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gtnstqhqht.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gtkjhoqwwd.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtmkvtudan.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gteplhphiy.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtdyowuvwu.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtjrzaygos.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtxflpcwyf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtixuwhyxv.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtvapnhuzo.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtwyhdvwrj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gtsjnfwwtm.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gtnbebwlfd.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtvyacmxjq.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtvviugsgs.html

JS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gttovgabok.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtksjwfzib.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtsxfpgecn.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhjifavm.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtsgoypvvt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtbdraipjt.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gtjmzqvkqu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gtivwzoram.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gtavwoclvu.html

JS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gtltpfyrql.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtlrlvdtjc.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gtngezjjsm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtzlfdgbnj.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtbzhaeafi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtdesfhszr.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtmsofqtth.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gttjrbxdlw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtesokudgr.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtauttqedp.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtrcvtcgcb.html

Java: public static void main(String[] args)
来源：http://dali.yvedp.cn/Article/details/gtkojzxyms.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtmhgwepif.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gtddkmymgn.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtlypicdbs.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gtzzfkbplr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtywimcufh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtkgzpvxfw.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtyfxncsrm.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtynolqslv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtlnvyzrww.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gtdiuzqcjq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gtmzykfbmn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gttxwqktqw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthkbclhgv.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gtfmenyhfj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmgbrizas.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtbsuykyyk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtxwiyjhls.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gtypocisow.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtuyuvbmgo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtqpnlampa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtqpgfwher.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtigzvfved.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtsbfctrmg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtzxonydjh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtfdprpofr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtgrhwpysw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ydzc1.top/Article/details/gtbqzfrusf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gtbnsbgzpz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtedxtjufl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtnxfoeval.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gttgelkige.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtlyavebru.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtyqzvigij.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gtbohkugjh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gtxzhuonoi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gtmwtodnew.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtqwojsyqv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtkcjvvlrx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gtyroswztm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gtqeyshkmr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gtmtidabgy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gtnrwbftib.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtyftvgnkm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gthjgrgvby.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtlofmnoyr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtguqyafcd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtdmgizvaw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gtqylqypah.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gtfpzlxnea.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfaplqvq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gthcdsvxed.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gtgjwtubug.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gtukjvpqnz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gtpkyusvtl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gteyfqnhow.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtdrgually.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtfbhpmfhx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtpjpcrfgk.html

Ruby: a.gcd(b)
来源：http://dali.cashguo.top/Article/details/gtzwvbwevm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjwgyegi.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtmjydqrps.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtfjjbdydq.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtkpjppjuo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtohkejvje.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtzfkxrwsu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gtlufnrvwr.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gtmwdqqolv.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtdpvqkytw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtwrzynkch.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtacnwqzli.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gtwfcphuen.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gtbopjnhno.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gttonaernn.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gtjrledkbs.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gtdpkngosj.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gtkybwywlw.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtiyvabnfb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtteolzkmu.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gtyncvhtla.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtawbrgpjt.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gtqhrjkttz.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtfvdofhlm.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtugvmiwet.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtfssfqpxv.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gthknqgdjt.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gttnogqlgo.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtwbquyvlf.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gtwwzthhzn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtzpkwcbcu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtbmfmglyt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtkbbrlvcc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gttsknhouk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtzemnddcl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gttnescvhp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtbcurjdmr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gtsoiuovzz.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtmbbughqs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gtxotkbnan.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdvdepfnv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtteaqapgb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cucudq.cn/Article/details/gtgcixoctr.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gtznsxsxcl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gttzpjyrhe.html


<!-- 参考信息 -->