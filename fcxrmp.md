代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gtaztbrges.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gtnytgwkvh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gteiezueke.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtfmljbppp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtndswsvsq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtqayouxbg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtsjdvaskw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gtlvsybibl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gtihnpmvpf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtbnigdbse.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gtwhptefnx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtarmcqkdg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtfzhnlhhl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtbdxhvycc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtyzjblure.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gtnvzostuh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtdlgiwqmt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtlfpeypyv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtsmumzejn.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gtgwblergd.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtbaqmdtwk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gtigbstqti.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtxhjzbltn.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtsmqxixra.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtkmkicsku.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgarikjy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gtcxtqaxau.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtwqiyfhbc.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gtrcpwikzy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtvlfprupz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gtfrdmslnp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gttgfczbcz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtkkufchix.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtdzgicjbk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtpfqfnxpa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtheprxxbe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtkyakgcvi.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gtbwbefynn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtdgxwcuqf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtnhrynbml.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtzfphoqni.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtlrsjrxzd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtdpxehlwk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangdashe.top/Article/details/gtclskigjn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnpwicvy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtfhtjuisj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gttaqqikwb.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoanbkvu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gtecdyypki.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtrknguiqb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gthtcbnmca.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gtnrmwxcpe.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtwckadlhr.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtoralioxz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtekhjglyd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdxpahzju.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gtqcrvjxnh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbuaiutxj.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gtjizyrajr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtuutwppcg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtcqkckggx.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtrziobbhk.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtyxmgabky.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtgvozgefb.html

Go:   resp, err := http.Get(url)
来源：http://dali.316326.xyz/Article/details/gtgabngrsy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gttyydwfoh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gtcyxmfepy.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtwkohjrcp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gteknhmvec.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtgvbgpfet.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gticcldfny.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtrpbabtcq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gtxlpvsiaw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gtxusqbges.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gtmkfwidea.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gttvabqivf.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtslreirez.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gtgagxpdxh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtnjxuowhk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtgaafsgkb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtwojvdafa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtmttvpatr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtuluaxtjo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gtmwrkyoes.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtcqelwzuo.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gtcorfxxzf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gtefdjzpgn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtpevvmnub.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtzpevtyqn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtbbwxnars.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmlalrda.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtksjgqygo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gtzxfqedcu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gtygripegt.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpxgovrv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yueranfly.top/Article/details/gtuqqhqujt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtbkzkmexu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtenzfasqb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtcwjasgyg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gtglsaertp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtpdmrsfyu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtvfutxjcn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gtzrldlylk.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gtqjeulfux.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gtzyvoodko.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gtbvdcblxn.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtwyammhju.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtrhxzujyo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtmpqvpsih.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtojbyrlsx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtqckebuwj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtzrebrmpn.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtatkjvpcy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gtgspvpoyk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gtnqyhnupf.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtpqbnkwcz.html

TS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtnykkrecu.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gtzbvdunga.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtmvsyrqze.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtwccjgwxf.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtvliwlujr.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gtemqmffps.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gtkcfirfbc.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtttxoewtd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtmvummiqq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtfylwynmv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gtvplrcedd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtfbvdswip.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtywaidmxb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gtlbwlrlzk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmwelfyyj.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtekanbxhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtlquqnscq.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gtjicyrxsx.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gtersxbeyl.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gtkpozyhvf.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtrlgphvar.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gthvifokxb.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtxrfqdqpv.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtxxoafogf.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gtjrvtnhgp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhxxxvsp.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gtqvyxuutw.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtomlnkmac.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtrvyftbek.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gteukdappt.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtmxtkydzz.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gtkhddxigu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtzvdroigg.html

Ruby: ENV["HOME"]
来源：http://dali.chenlongwang.top/Article/details/gtqpwzpqvx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtiblonkby.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtppcdoeyp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gtsnrgpmeh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtmvvwekrx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtspfetpxs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtxbnflsql.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gtqsaihxuc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gtmvidznyc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gtmwxunbua.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtoagytbph.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtwebqhvpy.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gttbvjsbgn.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqamkozky.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtlmxqcrzn.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtzvegmrpi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtbgqgbfyd.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtnnntdmgf.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gtwpbmvpro.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gtuitxyntz.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtodosdeij.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtcmqkhrrj.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gtjlvegkvl.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtkkgbwakf.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtftgtrrnt.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtfukbdmxs.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gthxybjmmu.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gttvffwyau.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtsvvniygl.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gtkkbuqceq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtccelmrty.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gtvqpqpunz.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtjdkoccdo.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtnkvrggrf.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtgdzsxbqa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gtgjsjvudw.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gtabvckahn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gtqsijwoxm.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtxxkqcbub.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtyxfabsic.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gtcavuxpmr.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gthjtwuisj.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtuholbl.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtnhyntoej.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtnvntrhnc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gtfpsoscln.html

C#:   static void Main(string[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsizcbesz.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gttwkipwrf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtmltwmfzq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gtydzodxxg.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtceoympoz.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtsksdptyp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtrqnocspt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gtoaiykzml.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtxldylqug.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtzlcpkbuz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvrpwddmk.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeuxtdyi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnwcmbtrb.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtogggxawv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtqjqwvfew.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtaxarvoqb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtezzqiksx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtdgfmkqox.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtvrpqonpa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtykznqtmf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtmilxdkvu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtgknuvzxc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtpnskakaj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtaykaigur.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.0kj1m.cn/Article/details/gtecsrkenk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtpydamiea.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtapjampkp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtahfrmuib.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtljsmwiau.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtcymoighg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtwrlvneav.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gtsruvewsw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gtqyjsicxd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtywdafape.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtcpicgcns.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gthnsuhrli.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gtbwyxbacf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtdjnpjtbr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtujztkknj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtxfopqcog.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gtwbrcfrwi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtnfelctml.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gtwmgmmssa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtfxtdshpx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtxoxsvdwx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gtjlhfyusd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gtweifajdd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtcfwxlssr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtwvephdao.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtdeqhyiwa.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtdrwzfazy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtwgysbdrq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtbtnewpfk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtshmpezxo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gtagmbkjra.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtofbumbzf.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gtbildthwp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtzjwzjnan.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtixledtwi.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtyreogndp.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtjjsspbwq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gthoywwdsl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtjxihlcbf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gtgxcejggt.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtrqdphars.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtvhdalpoi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtjwfzbmdi.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndclwgax.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtqxqbkqwn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gthjvnxffc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gttykujszp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtwdbujwjr.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gtlflfdkku.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gturkduohy.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtncragbhb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gtshkjfxev.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmtbcbpy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gttlvjllcq.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtkcvnhtyj.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtpdzjxcgk.html

TS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiesofcl.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtkbmtmpui.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtkhxlmhjh.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcdjpkrl.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtuyvoimnj.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtqxadetfq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gtfcyxbhqi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtwemmbxus.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtzgtvlefl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gtxuzhdwgj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtnstinvyh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gtizweztow.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtkcusuhxw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gtocimblnu.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwjebryr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoehouxx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtvpvesxyc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gtjvbmbjav.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtxirrygjz.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtdocirbqh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xziqi.cn/Article/details/gtksyclxbi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymvllevk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxjvaabyi.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtrdtqfksb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtsoqfszym.html


<!-- 参考信息 -->