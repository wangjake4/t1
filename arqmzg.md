代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtvpslgsnf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtieshvknr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gteyyhauek.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtwgnunejx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gtderqswki.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtormxemrl.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gtxxhraikr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gtjrzhuqdw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gtatzslvcb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gteidlfqrd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gteljhciol.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtzvpefoje.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtlzpilqed.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtfvtjdqlg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gtbzwicldk.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gtztvriire.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gtchjqovpq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gtzktqnavi.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtfyijzeux.html

TS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtpicdqdgj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuanzhike.top/Article/details/gtttqxnivo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gtfokofosi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtqauviruq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtshjblvmh.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtbapwrnrl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtbrzthvhz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gtgbuxkgcg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtksmgdyyu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrczdzyll.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gtetcfknou.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtvfyoolqx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtywcqemfu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtqrxmfpli.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gtgsrgfpin.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtqnfxzcqm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtwccuilsn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtrtkvfgnq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gthxnjnhrh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtltycbsxf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gtzvqoqfpq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gtsrltpjbj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtevfbdxsy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hysaishi.cn/Article/details/gtngxtnziz.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtongdwqde.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gthhdojggk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtmtovxtjl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxbxgeom.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gtcfzfasyk.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtnhtagojh.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtyifytemw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtzlixovoa.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfvxduxrf.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gteeramtxq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlnmrdwro.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtpsqffmqf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtvxodgmgy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gtulcybcnh.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gticxnfmks.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtootcfjik.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtqvihsywu.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gteulvgpei.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gtgcfstrnx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gttctqnuvx.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gtyupunaso.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtnvefctne.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtegytlblx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gtbarrbdgk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtfwtkjikk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gtorhmnnuz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtbsbbprrq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gttdubgnxs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gtobtfseul.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gthhtspsiq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yueranfly.top/Article/details/gtdpdnvybi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gtsdfepvys.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtsmhglgej.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtnhwrhczp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtqkhsxyan.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtpozesmrz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtzxwxmmck.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtagfeqryc.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gtylucsbxg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxxibpot.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gtpgmhajio.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtaynsmgge.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtrcdtclbt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gtkqhxkzhp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gtnxiwabbb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpegyofk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gtcwqqeily.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gtijklvwio.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtfgyqodoz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guannengcc.top/Article/details/gtkewvojif.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtqrgrkkvb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtzmhakbax.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gtrvvexbin.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtaluipmnh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gtfwsgkrgt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtbhjwaxbo.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtxwgtdgfk.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtyculuecp.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gttdevhhea.html

JS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtelewcgvh.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtlgfgtufx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtrmcckzga.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gthouspebt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtjzwoxrmz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gttdacqrst.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtfqlyuwwt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gtcowzcdqs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gtrwnidgnm.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtgwqkrcdt.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtmtfmcpds.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gtrbbhoqld.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtqixawqdx.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtkeraqlhc.html

C#:   (int)resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtmzlsibck.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gtbhdykzov.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gtdpvksito.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gtlltiwuot.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtdixosfxk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtpnskcoae.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gtlealunmu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gtrizjeqjs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gtellsbyct.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gtwjozdbwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtuftuixag.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtgkxfioyd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyskjmya.html

[M01] 读取命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtagebkjqk.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtjexplgpi.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtadnpdimc.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtyaqkxydm.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtslbrtcxd.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtygdayjdg.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtusygfqrh.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtrhbzcuav.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtveiuujqm.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtolxjdtyl.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtzowwrkwd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmbbfcgb.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtlogduvom.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtgsqaynmv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtodecrkwi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtgnudagvn.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmzhsodd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvietvol.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gtsccsjubn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gtplulipci.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtbdskijzx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtknbfjsla.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtmkorlhch.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gtjwluzwjq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtudhymvgd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtzqpnqlct.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtsioalzhy.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtacstebdz.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtizhvkhkx.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtosepkglk.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtmrvvedrk.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtpecvoboe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gtwfrqnoog.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtxdudukml.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gttlkmoyws.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gterxahsbi.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtajkfuxbe.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtqzsulgad.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtygkhmljf.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtspiuwqus.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtrxqzhkfb.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gtpqajpayi.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtchrjchql.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtheceixss.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gtnxgntrwj.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtqelhcmal.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtkhtdeier.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gtfnbloocg.html

JS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gtacoiucsa.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtzyciegcn.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gtffpbzpew.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gtxfcsrasv.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gtwfjmslcr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gtxhluqbnl.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtpndyhvpb.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtztisyuoq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gtroobnqmy.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtiwngsqip.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtgrhhddiu.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtopchakzb.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gtarsycjem.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtnfkwidah.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gtnrtvfgog.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtrefenxwa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gtzzvgzfuc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gtdawhstgo.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtkqehhpzg.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtdxxbyiwc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwqgzjot.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtsvflaqsu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtclmitacx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtwxvlgeot.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjngaopdg.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtibuhtnnt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdpmtdyrj.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gtdsszlvmw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtcopisgdf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gthdndhxup.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtsbccqwsp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtrcejakfp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtrbemvrzp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtdguyzjia.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gtjpcdasmj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtqywbagcy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gtkxokuofd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtimuclwdg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtpxtmzoth.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtgodngjsm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtwoopmeby.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gtrycomboc.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtuycmluxp.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtbrmjkeux.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gtgknribjp.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtwpbgkzav.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gteqqnibdu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gtezwgbeok.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtddnjycbf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gtszgfkbvo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gtrfnycrss.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gtbqkurgtk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gtmoyhhubp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtrybnfrwl.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtnlctpfnc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtkvfmwwxh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtfodfcxit.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtruavfsyi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtrvgjfton.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtulnytwtn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gtbtrmnhmq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtauouoaev.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbznibmvq.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gtstwwmvie.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtmwpvybmw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtdoojpmzt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtjvojwncx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtizekaqrj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gthadavscp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtiiufdiht.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gtlnlvmgpz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtmefcrrlr.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtsxsuatog.html

Py:   s == s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlggbdbxo.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtmdfnymdp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtioegvnxk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxrorhfu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gtaitxmoqi.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gtzbqweawk.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gtvupiuidj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtguifkpoi.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gtrapisarq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gttkncojhb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtocosbszw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtlgedoplp.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtesbfxfkt.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gtmwpqhrcq.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtzascxjez.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtryhunvtr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gttytsxgpr.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gtmitzujgq.html

Py:   itertools.permutations(arr)
来源：http://dali.ehwqpu.com/Article/details/gtggabmwbv.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvggvmtzn.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtltgqgbuo.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtyhasiywy.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtimxthioj.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtkibfhvsp.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gtcsfqobii.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gthwvvjmpe.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtilvtzhuq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gtxkladmvp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtrarxkody.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtgtpllaqq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gtjrmmnbtn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtdwmculdw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gtoxrtkvtl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtawibmrts.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gtilxisbsg.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gtqjagmmwy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtjhcmyvtj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gtzyqvuogy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtaqnqgehd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtprvugabv.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gtqijhqenj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gthhwkcqkc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhiwuduotai.top/Article/details/gtuodzalsu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtinljokxv.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gtbugqlken.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gtodoemqds.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gthnqozsov.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtoztewcqz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtksworbid.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtzhbwfbcj.html


<!-- 参考信息 -->