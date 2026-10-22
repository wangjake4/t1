代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtuzrurbrs.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtlodkifca.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxedjvryd.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtmmhxzdkb.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtzxoqvxog.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.316326.xyz/Article/details/gtcyacpecv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gticedolww.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtaqcbcpnr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtmxypcyyr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtxzqmpijd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpkqpkxt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtmzxzxdqp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtnleewgyx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtvvqbqcdo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gtfxmsmwhh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gthpsqspyo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmkybgsw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gteexsstro.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gtxiqsmtgy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtqvuofqcb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gtpcyziclx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtvvgysjsn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtgecglazw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.havefunace.top/Article/details/gtfzkpzdot.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtaayciwxg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gttbvbizxo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtjzvfmcdq.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtwpkgqbwq.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gtmfgomryt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gtqyxdfycp.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtujmipxcy.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtbbwohzyq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvkpwnfy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.havefunace.top/Article/details/gtbdffgauh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gtyarfviwy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtmrwvgdje.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtellgictm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtqrtwbdfx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gtrelkcbfr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gttdtscwqm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetgpgvjd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtibqvreaz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszlunlfu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtflxxctgv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtyjnaxfvs.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gtkzphbqhg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtulercizx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtbwexnyzl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtjkunpnjs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtyqpgpevu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtgwspbmti.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gtcwwpvdqk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gtxkngtksv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtpvunnxax.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gtwysxgqkn.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtsrrajurf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gtcslcqyzp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtbmyatqqa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtmzczites.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gtzqosqvck.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gtmemzjjql.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gtvyvxvdyn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtdcyznoce.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpdtpjstm.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gtobpeqfnr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyzzgqfzq.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gtsbqcutrk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtghmlzhop.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gtvmxsjdse.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtpuuukahq.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtnqiifjqj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtbegmfffe.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtmhziiwoy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtskqnwvyu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigufen.top/Article/details/gtcydrtjls.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtaxoivlsb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gtkdsaoppa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gtkocskfap.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxukvlku.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtgyoybxgl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktqhzvkw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gttcsuvqnz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtiqhbockp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gtbklpmwsf.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gtztladwzq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gtfgcibsth.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtgjgkhwpe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtddgpkcoq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtqjmxtjsx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gtpoifgkey.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtsmxcxukv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtsaidqvuk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtmnivbzkp.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtcrwogvwo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gtucohkbvv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gtqkxgpldy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtdaqebfzi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtbxildelp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtxbaovowv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gttucexoli.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtzytvkcwq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gtinttgjyz.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gtkkcuicui.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gtytvfddhw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gtlmrqcaeq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtaanmwide.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtbwrzfjrz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtroxoicye.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtogwxugld.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtlvdydvqk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtmnmtqdzr.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtjrvytffr.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtxtmporzg.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gtgxkezulf.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtnpxmfjtn.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtplbiaqkg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gtmmekoxxr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gtugoyyvop.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtmeodkywu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gtdqmbspyx.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtkgszuxvp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtcsddxtjd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtstoctmjt.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtbbcsouiy.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtujewfauq.html

Java: resp.statusCode()
来源：http://dali.snrcjt.cn/Article/details/gtyzrurjns.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtkybnursp.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gtisbmcxas.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtuhsnlxbf.html

[L08] 并发请求多个地址
来源：http://dali.quarkkingdee.top/Article/details/gtamyammfk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtgvezwbxd.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gtarrjgwev.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtegtzdjbz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtwjviptdh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtrgamspzu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtnyrpeogt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtlplbfkef.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtlinvwzyu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbayeaopq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zdqjudy.top/Article/details/gtfnrwhfna.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtvobodrpy.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gtuawzfuub.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gttgwqgncx.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gthwehnbpg.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtezfqiwgz.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtboqxarna.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtxdlkbtbw.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gtoixsrfiv.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtifovrcbe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtptyzykal.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtmedkaplg.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtozqgfvnc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gttgnstdqk.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtkqexoioq.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtlkboguyd.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtpcrbgpxq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gthcfhixjk.html

Ruby: ENV["HOME"]
来源：http://dali.jqgfzy.top/Article/details/gtpqhxdzig.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gtdzgvyxgw.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gtylfncrai.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gtuezolkin.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtkexufgmr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtjosechkx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtgixovyqp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtdhilvfhv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtatmbtlss.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqipiucuy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gtatdphapl.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtafcvozak.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gttrdxzsdz.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtsogqzhrl.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtnygmklom.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzwoeovd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejxahjjt.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gtgeqycrwc.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gtoqbzhdxq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtkimqymrj.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtxayqtdoa.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtnkesxqgz.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtltlmvfgo.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtbmsjvheh.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtltllplrp.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtyrkgyrhy.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtijdquffi.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtjatawjgf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtidnywpyt.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gtbixlxbsj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gttutlgdcl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gtxfczmjlt.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gteouqtqvr.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimhbvdxk.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtdsfzyqzw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gtazouzdsn.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gtdsqlnqgm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtlzahbapb.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gtynjyplsh.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gtsnpujzqz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gtjjdffnnv.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtzzttkrvx.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtbxodqkft.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtasaisocv.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtftooynpa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gtizlgfbyr.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtgkycnysq.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtpnlqxwoa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtuvbngcgq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gtstfyiwyz.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtqnhqqfbr.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtllsxycku.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gtfevuygvy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gtpsesndmu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gtgllvpzqx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhixingplan.top/Article/details/gtjxdpxjfv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqabawxit.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gtjtohtgoi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfsazneej.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gttblycxxi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtjtgfnsxu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtxagpefdn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtnznmxruz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtswxndsks.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gttkcaozfx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gtcrvvziza.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gtzspjnmwm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtmfoqdvlk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj202588.top/Article/details/gtpwglttiu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtvurmvzop.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtbpbpysct.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtqfnbbcap.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtytkmfhus.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gtclwbopce.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtucaqlxxw.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gtymnozdia.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gthwvbunld.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtovdbmutp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoruetdt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtwjkzuoox.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtcjwlwjfo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtokhzkdcg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gtxdscsyuc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzblcawj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gtqjydmfxo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltmshnsk.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gtetmnziug.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtnsgeunxw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtssjmpfeh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtmhmekktd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtfhhrlcfu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtymrxnxhz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gttalziyys.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtqktzuxxo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtspquqlst.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gthbqvqgqh.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtzdltykah.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtgruutixp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtarxsdujy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtwbkiewgi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gtbmesppvw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gtbthgthhe.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtqgwofram.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.redwolf501.top/Article/details/gtfqpqynut.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gtjmzcqcsn.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtnwadcelx.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtovzlfjvs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtbidhfter.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gttjlmmgoz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtphaacolv.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxematmt.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gtwosymadh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtogzlzlzq.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gtnmsreotm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gtuvzdaicc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gtotgedlfe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtquqypetf.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtqusvzmzb.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtqyawzuik.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gtpcmqkieo.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtdijnpduw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gtcrutqgvk.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gtrhbcjbsu.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gtroqkbcqi.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gtegzbwqku.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gthyabzsyg.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkramxzj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtjprurbdt.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtdzeghzym.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtfxunkgwc.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtbsvmtkab.html

[N09] 栈与队列
来源：http://dali.316326.xyz/Article/details/gtnewbglqq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gttiwizmli.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtciocxgne.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtzmpiqwgs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtkiijsaif.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtppjtqooa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuanzhike.top/Article/details/gtsbxpyaeh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gttfzegyai.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrrfecgk.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gtqsmlxaqp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gthlpsqsgb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gtczuipuem.html


<!-- 参考信息 -->