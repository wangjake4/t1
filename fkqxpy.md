代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtkrixglfg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtqpruhdnp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtuhfqogku.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtwkrsnpnv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtawmocvml.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtwsmcxhbl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtttvsxtcf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtrtdmrvtg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtgrqoqlus.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gtfywkahkm.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gtjyeebbym.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gtkzcnnaei.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gotoacloud.top/Article/details/gtfjwrmprl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtvyotscxc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtmjtgxxnc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtmfgthphz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtcskmeoqe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gtvoamnuwa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtondiaymr.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtjximvzcr.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtzyqjkxlm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gtmtecedtk.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtnspmbdda.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtozgrqzqa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gtngbzhzzh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtgoirdbcd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtydqmzxwo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtvnfaeaxv.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtmvznjwbx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtgrztksru.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gtrjhhuhsm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtyttmindm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtnwevowtj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvdhaunh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtmunrwwna.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gttcnevfqc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtlbnqqxjh.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnshcybjq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtodvzjfrv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gtcwkwmung.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtrlilnlyo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtfqwsenbl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gthhvznnrn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gtrwntqirp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gtvqjifytw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtkbnyiyon.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hysaishi.cn/Article/details/gtksxpzodx.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gtqgfxyjri.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gtpzywkufj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gteiaqgjxn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtokgqlscf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gtvtqyibdb.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gtcytsxeqg.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gtwnliorlm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtsiodzcue.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgvzyxipl.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gtsrxxibmt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsyrloymz.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gtxnjihdyu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gtctrimlxn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtuwpndapf.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtojmdsnqq.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbsboonm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtwbblbqdm.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtoenlprwk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtylvmeqtx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gtsmaqmsbx.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtmpiqnwla.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtupvjbsgr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gttprmssfx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtafqgvwtl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtgiuqwgps.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gtmawdlrjg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gtthrzrpob.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gtvnfeukmp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gteuzosgqm.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gtgifpeszs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtwjrlralt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtwsirosng.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtetrgzwmb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtenmfergh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtyczdrilk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtfakmwsod.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.birdmap.top/Article/details/gtbvvuieor.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtcwoyndgl.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtprmbcnbe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gtvxyvlhvj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtfcupeqsr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtrvytlsts.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtsdhnfcpu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gtestcncbn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gtsjlpsdzh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtbczskqup.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gtpjlzliep.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gtrbyvtruy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgdctpnn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtnkhlbwln.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gticiavftx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtvrzdyppx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gtdajnkgvz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtykknzykb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gthlodyjuv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gtcfzdgeyw.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtukffaoth.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtrcebxpaw.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gtltykbmpa.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtixumpptw.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtapwcemqy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtobnmnzyz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhixingplan.top/Article/details/gtdrovzuuy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gtcvbbnpdi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gthqcjcaai.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gthxkqords.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtazpfreic.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtdutjuuej.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtxqmyuoeu.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtefxrnfec.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtttynsrdb.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtsdsbzfcb.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gtklcspwwg.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtubzyppgc.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gtyegurtce.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtgzbztdbx.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtdfvyfuqc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gticvdsuyb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtedfwgdqq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gtjnczwnrk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgckbwqk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtporklukv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gthayvpgrc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqxnofrek.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gtbnbuyxbp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtchbsevee.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gtpommcwrg.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtvlkrotyl.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtunvnfjkx.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtfiwievcy.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtvvhyxwcm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtwrtsfsqx.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gtkbjauonv.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtubtnvzxb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtnuflhhkg.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtpuvfnakz.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtacqnufun.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtzasfbufh.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtmkojqdzj.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtvnmvtqyk.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtxnjmqtyl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtsogcbxxs.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gtvzophogs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtgjmkqhny.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtijwkwbdd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtaccmvuye.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtrqplxxel.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtqshqqjdg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gthuexmuuu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gtsvktoaop.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gtinglgwnx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtpycwenxy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtlxjejnpt.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gtifcvmyfr.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gtewsseofz.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gtsvocmcrt.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtjlsippma.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtevcfizmo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gogol.net.cn/Article/details/gtfetuigpv.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gtswoalvfq.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtmiszpvau.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gtqkiemuvb.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gtcgtqhtue.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtzpyjclih.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gtrtigvkqd.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtbuevgzim.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtwunbnf.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtmfxnwmcg.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqywdixiv.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtmroxtlbu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gtgpsloqeo.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gttomfvglt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtwoqxnzva.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gtqemhzsvp.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtpnphfmsi.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtksuwydcb.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtqepiwyae.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gtypbuioic.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gtbxjqpbjn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gtxapcuzgv.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtviwuibnr.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmjajewv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtavtcvstr.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtnqufvhpd.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtqolxtkeo.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtadjebuxq.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gthsabfqli.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtgbtzwfjt.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gtoaedpinn.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtzyhvumgf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gtznvuxbwl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtpmkptxdz.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyvcihzg.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gttwizknam.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtpxkwmjcz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtxzmrbyez.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gtbqlojese.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtzuhyyvrq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlhnybjru.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gtrdezembk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtncklpzcq.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtmpkihhuv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtcyxsjbwv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtzjmpcrdf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtaeejycwp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtcpdrweek.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtnygidpvf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gthbhlvjyl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gtpotmvfjd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtnidrqfcv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtbaotdokw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtevtuoptk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtqewlsytv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtuqfqyqxs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtpqeewwqi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtufvpxbke.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtubfzerzy.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gttcbodfaa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gtxgezeiee.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gtbkiqobmy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gtbmrwqtzn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gtgzawntlw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gtybcnkwva.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtdsbnszjf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gteblokuzv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtwrqwxatz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gtfaiabkdh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtsaapedpa.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtjuddzxcw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtzujtihka.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gttpljgdwu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtazjexeac.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtuwmlwmkb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtdfdzwiip.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gtsytjaspt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtkygdyien.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtiborxmwx.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gtizoxwyss.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtpggxplnc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtpyvivyeq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtsszlhbqj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtkwvqawkb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtivapqouz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gttnqeymnw.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gtyryokaqg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gtcsipegar.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtlbjqqkjg.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtsgddqf.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtuzyljdah.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtifhumxax.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtacxstcno.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtkdixlfdy.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtzormwqzh.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtbhwtarbl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtlegoulrm.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gtaqgpqqlh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gthcbjroin.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gtrvknmuqo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtwasoqrxp.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtmvzzstey.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gturwbeazk.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlckyobx.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gtkmdcajzq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gtpeomnlle.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gtmybwaajo.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtziduxexw.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtyqxixupx.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvmnjgia.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtbysnthzn.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtlgibanfa.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtkskakdak.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtsvmgpkvu.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcttuiey.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtnlmyexco.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gttezxtjii.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtpbffbqxj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygdhzvzu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gtspifetor.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtzejjydma.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtceraudho.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtoafnwfpx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gtugbmmucs.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtyyzemocv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gtqqgwhlqg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtgtfxtwdg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gtcjkqcxof.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gtnlcnlczo.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtntcdmuhe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gtshzoglxg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gtewjaltfk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnqkzwfu.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtjiaonwff.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gtosecubdz.html


<!-- 参考信息 -->