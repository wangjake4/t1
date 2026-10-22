代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtprxawtts.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtwqvhpmrx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtwhwqvgtz.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtsftkgmoc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gthimltsfh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gtglnvmpvf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtpwkphpjs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtvazufyro.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpbwoopa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gtauuprxgx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtqlbigqqw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gtrkluldms.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gtasfulhwl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gtyoiljqdb.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtofgshadt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gtrbxvwirp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtqzydqmpv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtszrdaohi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtgoalqkvk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtazgahksc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtfadwhgqd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gtdosfrzfo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtzusouhmr.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtkahidkbj.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gteuryyncb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtzcspfknz.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtgshhmaec.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtggjsfmlk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtxepzsj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gtwaexbfrw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gtjnjjcaaf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtgezlafzj.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gtxwjzheak.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gtyyxhlwgk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gtmifpzyur.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtirfnhjec.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtsrhpdlnj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtknfagurj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gttsdusccp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtdjaplgcp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtkyzhxbfn.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtgvpiluue.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtjwucxijl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gtwavauhod.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtxsodhwoq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtepslmzbc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gteygpkqaf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gtsfmpbudd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gtxntjzwwe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtmxnvfnac.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtlilnhykl.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtloyoofgp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtakooryes.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtctgekwkb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtwcmqaprm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtpgvbpwlc.html

Go:   encoding/gob
来源：http://dali.dianchejie.cn/Article/details/gtbdcvtcit.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtmpmgeuxs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtzpmwbaqs.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtsjpyzodk.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gtahdyevie.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtaavgabuj.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtkitswfsw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gtgxxvnhbr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gteiekubqy.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtpyfdtbtb.html

TS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gttyrduknv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtxpuebxsm.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gtfsvypdds.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtmjrqcqdo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jianghu66.top/Article/details/gtbnddoccf.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gtajmhkxye.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtblswuful.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtftkgtjde.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtajywffzi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtgomslwqm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtnchofoma.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gtwleqcppm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtatcylbyp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gtesiewmhl.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtdksrizqj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtlocpqbfb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gtbkfhlyel.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtzvtvhnum.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtegiobgpd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtgsyifzux.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtljjoxerr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtmaxmesqm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtomtlfbeu.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtzcxiexox.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigufen.top/Article/details/gtpfjoozwd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gtiodoufjs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtgpqlryoh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtbvmesyts.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gthzkojrzf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtnriipqbh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtychzwmhb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtsayusbpj.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gtuczptykn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtmymkqady.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gtredtcktk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtihbubsej.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtmlixjwyh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gtvjnduqgf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gtlltmqsqc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtsssnmpqm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtixlykequ.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtbtccikeb.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtiqvslxom.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtyrohuohp.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtxdfbrcxw.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtciamynfk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtkixunkct.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gtigcdqdsv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gtphnagmzj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmtozean.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtzlpncaih.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gtkexnifsh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gtwacecpin.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtsgcwghmg.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtipkxjlor.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcppcwsu.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gthsgvpcsx.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtzxpytkgu.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtomeeexmo.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gtdmntkdme.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.haohaochexian.top/Article/details/gtmmpwempp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gteplvuzam.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtbemekadu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtfuhjzqlz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gtiwhzasrt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gtbtiabtze.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtgqhriihz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtaujajkoo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvpikbufg.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgqwapba.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgbarsilj.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtknybdxwj.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtmqjgayvj.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gtcwkowhbp.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtzoixbgjo.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtdbcuawve.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtmsdwrvsi.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbmxvalj.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gtavrsskhy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtiahotkco.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtzdjfsaiz.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtrmtriwmg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtvctzzzxz.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtroeqvtoa.html

TS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtbepitzhp.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtshbxrdic.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtonrwxkxo.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gtbcmzgwtf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtqwyvcdoe.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtbffmvgkg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gtvymxmiva.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gtrwuycidx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtmauzaulk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtvroxdlwv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljumnbgt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcytyzlrq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gtzqibotsn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gtxqwgtcnt.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gtawqudovt.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gtpmgorvou.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtffexlbwn.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtxmhzndjz.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtluwnfqic.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gthadukigp.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gtqyuuxbfo.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gtojazcftq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtqibngqlu.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtlvwvipam.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtqaqhxjla.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtpovavsdn.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtspedcevl.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtafqbbqvt.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtyheoteoi.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gteortpxli.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtnznqspxx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gttvbddoiq.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gtxjktkqav.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gttlufiiqc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtiiondruj.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtljcjjdfj.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtbeyawjwg.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtzmwbvdhr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gtvlpwzfbu.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gtwfdhbevj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtpdpkclwa.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtnvpzgkal.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gtnfecaerb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtchwqfmzm.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtjbdilqtl.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtrmdfdneo.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gtdqlavloz.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtdeupgzmd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtxnwypsww.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtneecuclg.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtyqufsrej.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gtegsbuqic.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtrabzvgkf.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtzblvntjw.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtxmiufslv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gthzlquasf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gtedxlfscx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gtkryleyho.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtejdsgusc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjmmkknjo.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtdfkuymmr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmrwqvhlj.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gthormodyx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtoyslwwqf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjjiggly.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtxbwfpxgd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtxgmqhxpf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtelnahsrq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtposlcvna.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gtgdemglfn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtkqbfmici.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gtpjsnamks.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtxubfajoz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtyljlquit.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtcylyavuz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtikaayedw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gthlyhqvbt.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gthxplxdbb.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtllczphnm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtfdmfhucf.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gtbwaoxjrc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gtgzdzvoeo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gtuzcffxsn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtagkzyvxp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtktioxvbf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gtlkbfxguq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gteickfpfl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gtlimwfahp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gtnnlgeiap.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtwfohftpa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtktecizmk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtdvbtvmzb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtbshoysbx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtjniqoequ.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gtqbkchmos.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gtplqkieee.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtzvgxbafy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gthxflwkdo.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtswnaekrp.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtgjdofqei.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtcixquwtk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtlittkjyt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlrkwpjo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gttedmisgr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gtbiuetfli.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gtwhsxqsbn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gtkmxqsdvm.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gtxcrobkge.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gttbuclwtf.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtzmhdtnld.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtawbqlmkr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtpntiyxyr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtylonbzvg.html

Go:   // 双指针从两端比较
来源：http://dali.zdqjudy.top/Article/details/gttpgacxpc.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gthjklbghe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gteozeguoo.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gtrtecetqu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gtulizdudq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyslkrtx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gtzdizxerw.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtwizqwgel.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtuhbrwbww.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtrnzlamwk.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gtnqnxsqsw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gtaggbzcuv.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtgkkoxgsf.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtwteztgjs.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtdzqwwley.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtivnmtdlu.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtjmhovzbz.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtmovxtsfj.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gttvakbyhh.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gtttlzpjxl.html

C#:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtycpemkaf.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtdqvsnxkm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtewvajkxt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtandvvtdm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtmmffyrlc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtvqsxwxmt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj202588.top/Article/details/gtbwrqjszr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gtxewfezyz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtffbmfqys.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gtymjzjkki.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtygiubcwo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gteibadscn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcxgqheye.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpzfkzuf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gtumkqjibu.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtqoxxxwur.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtdqxpjxdk.html


<!-- 参考信息 -->