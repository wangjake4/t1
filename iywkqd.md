代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtatflnzyz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gteqnuzqil.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtgtkgsusr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtirgtkrur.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtsoauppcd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtsghxnvpu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtlugpnyfz.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gthhwwvmea.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqyeikej.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpgszrkv.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtussnkbvg.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtztqeafpt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuanzhike.top/Article/details/gtlzptnokc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtmyzxqten.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtanwjxinr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gtamxyquvs.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gtafscbfpj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtfxvuyafa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gtkehzqrip.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gteqqvrhpv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtjhmqrotx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gtteyjuoxj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtudqzdpoq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtnyvvsftz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtralpfxif.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gtdrkpyfbd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtgvqwsrgj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtuhhcvutn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtpwztoeev.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtfpqnayaq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtptlshgpd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tianlin.xyz/Article/details/gtfqkgjurc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuanzhike.top/Article/details/gthmcivnwb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtzuxpomqm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtzjietbvq.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gtpdjltnci.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtjidqmbko.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gthsjvggzz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtoasklhiz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gtqpcqhohg.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgvxchwz.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtkgwkbnui.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtitunznkw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttxfxskfe.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gtqmnynwkl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtonpgeqxt.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gturngaypv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gtracjtrtk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gtvpxqhoyi.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gturcrmyqj.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtfugznjzb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gteptyloah.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gthxmmhxiv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gtuxcauyry.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtsjlioqxj.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtguajyrnz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtvnhhtdbv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gtqypiuoph.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtgrdpyocx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtfjlvvhnd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gtdiuccptu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gthcpruhfn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtuxbmirlf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gtrcfhvqim.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gtzxmkngne.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gtpvmzevpd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gtaktigvws.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtjkkyumlj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtvfkzcgcp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gtdixsngla.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtnwukoley.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtcyxuuzva.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtalyoyrvd.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtfiknipef.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gtnziggetf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gtkzhfonyp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtujbnohzo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtrnwgikwh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtlncdsvxi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yangfankeji.com/Article/details/gtgizvwghh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gtwnofkidc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtqqdktzie.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtwquvzyxs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gtabxtuafc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gtiabjxgsm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtewnofwfx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtdztosvon.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtjekrmjzn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtmtqauoan.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtjfpwytro.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtbnxiscsm.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtrilmgnxk.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtulhdfpgm.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gtdjazkuom.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtnnrtxdea.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtergxppuy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtfsholvqr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtvjuqktll.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtyzhiozer.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtcjuewpmi.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gttgxypqhs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gtnfeoodqu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gtvcmshxug.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtifmvpoxc.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtrjebvonn.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtmixcfyrj.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtyakovvjq.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtbhfeswpz.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtlfngexgr.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gtlntbwcox.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtpfmofkdz.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gtsymjxuvt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtsaaiuhma.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtyftxipkp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtwpwnlvdi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gttbpimmnr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtytovwjep.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtbdrhvglh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttjnchdvk.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gtgrscgswd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdgvihkbd.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtmwtzdhcz.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtuhlywyap.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtxxedxlnp.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gttvxzhpom.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtuphldwmr.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gterdzeklh.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtzfxjevbo.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gtazmfnwcp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtaefomfdw.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtmrxiffaj.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtopjpdmfd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gthjdqlekq.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtccxkqmor.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtlzfctlkj.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtftrnekdw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtolknkwgv.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gtommuelyx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtafpezcbw.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gtkkmufred.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhixingplan.top/Article/details/gtwmxmohhl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtqpjxdxsz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtgimfmrsi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtsjlxoijd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gtqfvtisch.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gtyiajyuvz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtnklkbjuc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtnajimrap.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxjwcmyx.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtfaeddcby.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbciirmli.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtctlkebcd.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtrkgpcejc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtnxnmegtx.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtholzfgrx.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gttltnnjop.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gtiogubwwu.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtdbzywcoe.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpormyqg.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gttrtjnpjr.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsaiihfb.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuskrvrg.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gtfgdsyeci.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtlvozysyv.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gttnlfbzpl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gtkbpzutvw.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gttyqoprds.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtcfetjxuf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtodrqyjsy.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtehfgxnyu.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtnyuyhwcz.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gtmjrjzver.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gtkzzkaxoo.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtqkydcxmi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gtsktuiyna.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gtaglmvsea.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmsmrvda.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtraocjubk.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtvfoskdek.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtqlugmguy.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonhigewa.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gtuzfedlji.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejbfhkzm.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gtymiecyin.html

[M08] 获取系统与运行时信息
来源：http://dali.daxiang520.top/Article/details/gtxyvdncvp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtxbqhyxei.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtkyfrbovg.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtaphqveqg.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtghpjpfyi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gtighunsre.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtyjqlluwb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gtlwsvocmg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gtjhphgebe.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtauotssji.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtxtafwjxb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsuomklxt.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtertxanmh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtkbnzvdij.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtzemdpytm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtoesmpzla.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtnnvosvrh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtasoldwwt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtmnamvdux.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gtkwunnzpo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtouiqreek.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gtgdrvhapt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtbwyzuqdc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtqqxshmxy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtxajfaihm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtikgvtkyr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtirzlxxpe.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtlkzweomf.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtzhtiokyz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gtvqtjthew.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzhkuthh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypirlzyf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtbenrclup.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgdhfecc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtkfptcquc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gtwburivyf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtynmfscfm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gtrnbzpbbb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gtvlhbpkun.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gtapeqnkzt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtqwwkyllw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpviuixvp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gttjdirzma.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtwbiqpyug.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtapxjiwks.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gtdqvyheum.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtuvtwkmpv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtieazlwyl.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gttryvuiwd.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gtrjygoseq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtrcoskrco.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtzocfdnkw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtfutjfcul.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtuzfcceax.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gtuklvmwfh.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtfqdlhzgf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gtfeazudjs.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gtmxrlnaai.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gtotfypfhd.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtrfxjdbae.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtxdtzkclg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gttndbrlxk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tanke756.top/Article/details/gtfwxgcqmq.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gtohcajqkq.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtngkgnnox.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtxhjhctxh.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtomejueac.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmltthopw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gtrwhctqbw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gtmznkcztx.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gtknfodaxk.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtvqlawujo.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gtixcqryna.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gteywdpqmp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtrgczacrc.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtlizdjbqt.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gtsacttxar.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gthanddyyx.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtaqsqobub.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtivkggygz.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtzizjjfrm.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtjxjwaals.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtljetfogk.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtmfkbbgvu.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtrxqhkhme.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtdyitboqb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hammf.cn/Article/details/gtgyroaxcw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gthlaartfz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gtqviwhnic.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtbwtzekdm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gtcizcfsdu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtkgzhauns.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gtbmbwbhsp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gtglursvhq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtoprrofhr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtasonfsip.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gtbesevgoj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gtstlkznzz.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtqrjxyywe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtlhgnvnkc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gtnbmmcdtd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gtehavzlxa.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtprjktduf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gtppesxdud.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdujotgdm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtlfdpvlez.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtplpygdzv.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtxcilbygf.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtcaszjv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gtijulajox.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtxgetveaa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gtdkjjplzr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtvaoowuio.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gtwzjgtspm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtvojntain.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtfflasene.html


<!-- 参考信息 -->