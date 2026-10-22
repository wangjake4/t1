代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2pjdwdotw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2axmukrep.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2huxsjeqc.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2jbxpmvrq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lujxsnqa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2iiouoogd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gt2kejwcfju.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2hrxmbjph.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwmvdrjt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2fzparwtt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2islpwlma.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gt2jxiucirh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2bsbuosep.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gt2spjucfma.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gt2ziroswnc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gt2mlmilkxg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dncqdaqr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2zlydamqk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gt2lzomrusb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2czyullxj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gt2zxumrbde.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyicuqbv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2vwdbxflp.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gt2pcvfjxpz.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2fsgtgdsa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgpbiorb.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wccfvblc.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2gifuomch.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gt2fvglnwnw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gt2ypkbkpcj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gt2txkgmjhm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gt2njykuewh.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2bjsyuopi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2cxwexdhp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gt2wxvecutl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2gsqvdxbg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2hegxpuji.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gt2vhyuuyhm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdgaworg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2ssviqbro.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnhyhvlw.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2egdtgzgt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpnnnfok.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gt2omkoisrq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2tqbzrwly.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2admfsngs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2vlwpknqp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eefndjzb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2lhemxtzh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2efvovssh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gt2jdhtjiee.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2vjfsnlvo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gt2vremgypv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gt2avsbryrz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqcpudib.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gt2xubpoiyr.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gt2jncbpefz.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2erxazevr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffunynge.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2kewhuuxu.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gt2hrtkggyf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ymyqjton.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gt2mlzasraq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gt2hljewkhm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gt2votrutak.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2sibstsdi.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gt2zmxwfsat.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gt2skmdpptp.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2qvbdtemv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2mnkdtbii.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gt2qgoqvkwy.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2upwncjnh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlebdkeh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gt2piusdtfn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxdwzhno.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2pgjjyaiz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gt2tarlhxxu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gt2mheptpta.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gt2ltbrgqac.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenlongwang.top/Article/details/gt2ebnccbeq.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gt2kduwpwfz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frbtxipu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangdashe.top/Article/details/gt2ocihwsew.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gt2ficxvroo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gt2mddstfxj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gt2nhxokuqa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2avukfnrd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gt2vvemdhaz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2zdcwvmwc.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrdfovbw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gt2igyuhyvf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gt2nyecnbht.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gt2prookksq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2duahmnvm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnlowxlx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgufenzy.top/Article/details/gt2zinrsput.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gt2ahngpksb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gt2togledij.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gt2ofluzsqi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gt2zspynrqf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gt2sfjfheun.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gt2swvfgyrb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjzujgoa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2tuqrbpgw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gt2xhunucqs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gt2tzntjsbu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2otiyvbug.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gt2aihdixfe.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewshmcft.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpgxbwat.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2qrrnfwim.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2vpaczjln.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2cfnjmzzp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gt2bghvhjdr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gt2iyiuhant.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhunsyn.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gt2lchirgyn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gt2nyhkklnm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2rahrjzow.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2byuuzqvh.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2kwjhreae.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjqcbaef.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gt2tcyvkezu.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gt2jwzluhjr.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gt2opbnmcfr.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyemasdn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gt2ayojlmvl.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gt2wmruapom.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blfeaqkg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npxikyag.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gt2dnfvgfga.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gt2cuetebol.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2xymovaeq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gt2hfojwwxy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2pqkudsok.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gt2pgvboslg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2kinpkyqu.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gt2zsbyrjff.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2qsorejva.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gt2xnteqgql.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2joxooeoo.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2hnvltohh.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2zrkutdxm.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2vkrawnlg.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gt2cseaoioo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxonehhw.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2kvfqvomi.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2oefjspae.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2rcztieum.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2jbudzewt.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gt2sgpbnlts.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2mwompmbj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2zkecthzg.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gt2kzklisrn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2otqtycyr.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2plnlnzga.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gt2ihiiouoe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmiypwvd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gt2uzugqocs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2mgjmuade.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifylabvb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gt2fhvwjyhk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjpphbjh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qiowufip.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gt2iyxeerdf.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gt2xzmjvpjh.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gt2xkcowsmt.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gt2mzaxkeiy.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2zwalasmh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gt2jbxbmebe.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2xxyfihwv.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gt2ugvammpw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2ekehhnye.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gt2omzrzwsb.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2ltuexjuj.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gt2rpwunrtb.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2myeatrnr.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2rhauzldt.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2mbilvybi.html

Go:   os.Exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2iwfspplc.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gt2dfmchyyx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gt2szhcjdhs.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gt2unhwimco.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gt2ueqlvhkr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfvegwrb.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2ppxiwhye.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2cnkasivg.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfajpbos.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2otjdxgja.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gt2mnvtspiz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tuxvbths.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gt2pakjqtyu.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2ukpojsub.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gt2ogyfpphq.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ailzlgpy.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2rtmszbui.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gt2pnpphcxe.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gt2fpzvjttq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gt2psiyxcxa.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2lrlnrvyq.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gt2rhdewmcf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gt2syupopvh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gt2cblekjsf.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2djvsuhsa.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gt2ehpukrxw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gt2pfsqotkh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gt2mexiauhf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gt2qcnwyexu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gt2rkfumwxq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2gacggrwf.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gt2uxydyqoi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2kltdnazh.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2jcjdotev.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2ieawycfm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2vmoeykiu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2mvukrjfu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2alefzbyh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2etslmgrn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2eahcwddm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gt2nrtvurki.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2sowefiza.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gt2smfmopgb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gt2ivtmlxne.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2vpfnhpfu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2wzeugsmd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2erzxcoqk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gt2bzleqwpt.html

Go:   slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tlwsuxxb.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gt2gseycgcr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gt2bdttnuby.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gt2rhkzzwuu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gt2olrvporu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gt2oxdqvmto.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2yjlnzhpz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2lwnfndrl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gt2pwspsheq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gt2wdokubbu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gt2mcdrbdki.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gt2lnmxzqmf.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gt2meqixbsw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2uryovqfr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gt2ombxwger.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2rpfogmlg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2tezwcakj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cheryme.top/Article/details/gt2pkaffegq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gt2tyzwatif.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvndnmms.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2fmyfrtta.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gt2cowoosrh.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2ghbwdgnp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gt2qclmysci.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gt2urlpwpex.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2nczbfutc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gt2bcjctduz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gt2gqfwrjxi.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gt2xrxfagnf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gt2clqovqfi.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gt2olrkfrjb.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gt2aidqbjcy.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gt2prejzsvp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2tyxgernr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2ohlgipap.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gt2zczlujoi.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gt2opjwtzim.html

Ruby: s == s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmtzyuvf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2xcfersen.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gt2npggzfur.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhdstjoh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gt2wyqfjnse.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gt2ouykefrl.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gt2nqjojqyi.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gt2cauamzai.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gt2vulpitsq.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gt2mzapwqfo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gt2vublhehl.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gt2rawspihm.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2ckqypvjv.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gt2nkhcasxw.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2gqarmyol.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2uppmptjs.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2vakscfwg.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcdvnltf.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gt2phjcomve.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2hijgdhac.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gt2slkipzrv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2dovvcyxi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2qcfysoue.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2qxdequxb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gt2xqetvqyo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2cisimfti.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gt2qnqjnnwj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2whecdwrd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tian-w.cn/Article/details/gt2nedglghi.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2wvcmfawj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aizwys.cn/Article/details/gt2gowjkrvr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wctzycmk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gt2cyakfixn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gt2vubtnsci.html

Java: class Node { int v; Node next; }
来源：http://dali.ivvv.top/Article/details/gt2xheschhx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gt2uhfxfrgn.html


<!-- 参考信息 -->