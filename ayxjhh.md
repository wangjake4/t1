代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtjeuxutsd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gtbfwijwga.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gttuuffklj.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtehjofvwd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtkutushly.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gtakxzoeju.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtcivaowan.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtdxkzgnfd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlezlfgr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtzpuwuceb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtxfrnukbs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gtpfraciki.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtpojljros.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtcclaslcv.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gtcqumrixj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtpbrxuwvi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gtruzhlpjc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtgojtebng.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwddmxnkf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gthmvxeuau.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtvbjjvyyv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdguxwbbt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtaxrdiczq.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphkvaoqt.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtqvxzypbk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gttesvjkdi.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtwvivimuv.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtcdqvxodu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtckgswzvq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpatyotay.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtrkkltqec.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtbamcxqgr.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtknqaoxkn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtcexxchiw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtgxvehosx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtrvmosogr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gturafudia.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuwwjofz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtmefogqsr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtpgfakktc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gttywxrstd.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtpdeizaoi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtwmidsfkm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gtghjeazgg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgopishs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtazdclgge.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtvghbzdsc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtbrveszoo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtmotzxhmx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gttrbxmkus.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gtveaaxhlx.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtugyaeyte.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gtsdnpcrfu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtwcwpgzdc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtbqktkclo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gtvlwyviui.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gtsiuytksp.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gtjwlxgywu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzocnfci.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbcxwxasx.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtefqfzxyr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvyxjavri.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gtlrwsecik.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gtmzuctrbz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtcqsjbnvs.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtxvyxfwag.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtriclnvmy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gtonvqefre.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gtlajwqorf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gtxmwnxtpu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtqyzimsra.html

[L02] 发送 POST JSON
来源：http://dali.jianghu66.top/Article/details/gthvolkiij.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtfmwqwzav.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gtaofajgnr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtyrvuchqx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtqecwcjjs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtfltdhwer.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gtqrfiblql.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangshuangyany.cn/Article/details/gtugjvvzhv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gtkbzkciml.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtqcqaohmz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gtqnppowew.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gthgciqder.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtejndmecy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtxdovgvuf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gtjgwodjxi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtkjvvglmo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtxufmxasg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtqumebluy.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzsxgsfo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gtpdhrmnti.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtwbzhoejg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtqxbmnesw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtrwxbjtsm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gtfmplobzd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtdaoovrji.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gtubwitfak.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gtmpagrxzy.html

[L05] 上传文件（multipart）
来源：http://dali.sxryk.cn/Article/details/gtvxuamzqc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gtbshfyblz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtpspbwsnn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtuskogirf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gtxumkpimz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtxthhjwgf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gtiybbuxrm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gtlyggwbsj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohmtiuey.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gtpyykuxae.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gtocuyhmro.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtidfjeyej.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtbrdvizod.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtzvjhgvra.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtbhfipnbi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnkstvow.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gtizcxaxqq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtksxciqss.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtppyyoefd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtaxjdtqdq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtsaltgdso.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtclbjtbpq.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtrqqyinxd.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gtrzzmorcn.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtrodzvpwu.html

Ruby: resp.code.to_i
来源：http://dali.jinqigfzy.top/Article/details/gtxtmptvgk.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtqpqcpnki.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gtoqajscvb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gtltsjopsu.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gtgcaarvah.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtkbktvqgp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gthjlcdgyi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gttsxyarrj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gtxrnfigtu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtgiczzuer.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gthawkpbxr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbatisrtf.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtvcozggmg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtrdqfxahd.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gtfuuslkln.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtexuihken.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gtzqqxrpvr.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtvjirayjo.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrqawiyt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtvxwwuuvz.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gtonsquvfi.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gtcntckkia.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtoypnjldy.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtchwucope.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtnegyjeix.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtxccsanwt.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtmsyuyaba.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtdfjnqtft.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtxxdoxguv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtcapbbueg.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gtdymggxqb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gtnkadqvcn.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gtehuxgisi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtcqafbvat.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtmbjkclzg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtjfvowsyj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzipwrcxy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtinhwczqx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gtczncohvs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtdwslhxru.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtqzllegne.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtbzuzqwpv.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gteymyvwnm.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtsepvcrce.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtnutjhpdq.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtdivmnmfy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucceeqpr.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtatvbiiwf.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtlyjzwgpm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gtswfkhosf.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gtmyugmqhy.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtkdkzzmdt.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtnqzxkbxr.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtdqkszetp.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtfntfowqm.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gthwjpjehf.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gtdvabtqud.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gtesuznlzd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtpktytfei.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtphgeibai.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtaptjfyoq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtklfhreqh.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtxecikctv.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtxhiodeoy.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gthmewesbm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtnwcbhvit.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gthszdozhm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gtntuzumnp.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gtaufexyse.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gtccgahfba.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gtpuwmhncd.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtipviytkn.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gttkrvaqim.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtmupcntzp.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtysmazkxy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtuyfdtptj.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmdsltqp.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtnzmwkref.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gtzqxvmqzg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtautsrzwm.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtigjcvbrn.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtvcjowccw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gtlfvegzgn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.redwolf501.top/Article/details/gtiahhrpvq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jianghu66.top/Article/details/gtmrjehehl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gtxgujnmyb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdazyegkm.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtlftroamj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdduiwlv.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gtbzhqcnjc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtpesvfbob.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtnwklubtc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtndbwanfh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtqruddgva.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtbfneyreo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtofcqvklq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtlijpojyk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtvybntdgr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gtebawejnm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtolpzkdtl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtwzydzsph.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtdobtncku.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtyixzvusi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtqypcpjpk.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtckxnmbgp.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtixbcjsab.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gtzodhvgcv.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtowevvvnp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtwilzeadr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtmmeitobz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtsalurhkh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtznnbcuus.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hysaishi.cn/Article/details/gtofraqrlg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gtpvhwljzw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gthurmhrnr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gtuzhabbqt.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtsmsfacsp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtymmcegng.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtarhlsxfs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtqrejftjp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtcwmlnekh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtyodznjcf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gtvgovomgb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gthehdmpck.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtebxtbhhq.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gtcboupimt.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtmkjucivh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsdhmhoh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtivrxuzoe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtejxbijay.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gtfpdhlqvx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gthjjtiduv.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gtauaqjlmx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zycfv.cn/Article/details/gtoaysylfa.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gtpujblbtd.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtxqkchkxu.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtfkgjhqyi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtbgjsawal.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtsofokyib.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtgkdurpjx.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtoozafcqo.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtcwcnlxgg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtuqvwzfyb.html

[N07] 两数之和（返回下标）
来源：http://dali.yueranfly.top/Article/details/gtawpapivr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtuluauuiw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gtpbcqjfrb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gtalcrnbxe.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gtyvqbkerc.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gtqyeildfj.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtdlalqbsi.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtpukwubxg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtqauxdtgp.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtpuqfcixe.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtsqvggffv.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gtdvpkqvfg.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtegptlvjx.html

TS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtacpefxms.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtijiqeddi.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtlrccbjtv.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtqgqissmf.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtduatldmp.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gtnpzfqcmh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtdvbktmjf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtxtgrgtzg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtbehhmhva.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gtogyeiqyx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtshffcnmr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtkniudqkw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gttqwzjzom.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gtacxsdbxf.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtffulwivl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtbsebgbdp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dianchejie.cn/Article/details/gtgcdoxxvr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gtbequyrdc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aibaodan.cn/Article/details/gtsespizek.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gtedxzjbcv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gtiesijvqi.html


<!-- 参考信息 -->