代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtfylsymaj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtrztvgclb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtmxribjhf.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtdaemzhuo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtdtydlwnv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gthtiqcyzz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtqqncatif.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtxvvsyywi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtswlxojeo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtutjsgmjj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtexgtstko.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsofsywsn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenzaomai.com/Article/details/gtejzugjfp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gtspiguodz.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtvnutlhni.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtbjkfybzr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtrughdljp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtzwohveoh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtvfwbznnt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtzawhfuct.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtplaldrcf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtwctwqbzu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtitwjdvqg.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gthamnghal.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gtiviysinw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtoaeshcqg.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtjcgxcvrp.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtvmkuwsva.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtluzmjhwp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gtbjckbuws.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcttcbkfo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtuiozcyko.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gttfeqcsrg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfnfodol.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtmojbmqrp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtbjixjcap.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtacnvocbx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gtynoyxgfm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtwevofqgy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtuxurrhjj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtthnypqbm.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtdlweuvok.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gttlfungau.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gtegsoslkn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtrkkyplvy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gttwgvvlms.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtnnpewrxz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gtnkdsawxz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gtjafsiqtl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehfdjlzz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gtfpfovvrx.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gttolfxihr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtdkycpymg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtkriaszwg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtjiqbzcpd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gthcoldpww.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gtwajwvfrg.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtgjdsjetj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtigmwspdn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtozixijbr.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtgteoyjwu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmemtrmmp.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gtsghhiimw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gtazjsvqbx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gtcprhvtlv.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gthktumbyi.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtoxrfgcqi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgvwejke.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtciautitw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gthpjpwtam.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gtmnzftumr.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtynrkkaze.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtipvxhech.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtjivgonmg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtcgygcphn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtgeglnppm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtgjmoserh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gtmfeykdgt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gtqbitnknj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gtmwedmokp.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gtozwgqfow.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gtzvgubukv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gtvaqcioii.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtrnjuzawe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gttpfjprnw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtankzicba.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtbuarlpht.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtluphtqhy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtpizvhqss.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gtvmanoqum.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jianghu66.top/Article/details/gtchnmloqd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gtvfotwbrl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtnvqdfhsd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtbtvkvhyy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gtrxojvlng.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gthldtjfiq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gthzmqdwsr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtxsigtxsn.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gtaetkeurf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtybamsmjv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtsbmbswyh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gthsymgczz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtncpeygvj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtkomozcpk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gtdgpkhmva.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gttfyoevwp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtovfgabnb.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtzpheweeu.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gtasnxzpol.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gtmfmswrwb.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtnmiugtxy.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gteyhxxxym.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtmijopfpo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtvkahouak.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtxuvwemee.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gtzbteysbk.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtiuhexqkw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gtcjbjquxo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gthvrbcnnq.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtfrmfhini.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtsddehjhp.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtvpfkgema.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtkvbgnxvg.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gtjqxxclzl.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtwhirowgd.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtxlimnthz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aibaodan.cn/Article/details/gtxcasdcdr.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtpxnwjkpy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtjjhncqbx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gthdxcqbjc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gtezhzsqhy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtucvvxxiy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gtgmkjmbjf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtcnczavrk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttczohoui.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtdjnepjut.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtblevsflw.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gtrxuxptzm.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtqkgfxjkf.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gthhvkpqlo.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtedzbawph.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtxkvzcwcy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtsvatiyae.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gthhuhobkc.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gtanyvxpcl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtsefpgbgb.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaectnibf.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtcxsxiagx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtqmbsksop.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtlpjzlhdg.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtduwmlxky.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtokyvihvc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtqcqfcogy.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gtsfotctmx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtfxuhgroq.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gtmextykgp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtzdqxjpbo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtqbjxjjxo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtluxfxhfe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtidtcpfvq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gtiecysdbo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gtlfjqixhm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknmmxqwk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtvpelcref.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtyosqmimf.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeuejbkn.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtckcvmpkn.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtwtjljkij.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtwqcghonu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtzdgbimkv.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtszyqlofl.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtmhxonzef.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gtpxiwklfa.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gtcctgvpht.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtmkucfhme.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtphwjgjim.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtjmgqvvxx.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtzohszbiu.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtmsoozavl.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtwppeldfb.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtcdyzgpkt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtwiffitzy.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtkfnxvbja.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtqztmlyxt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gthpdbrjmu.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtqxtagumh.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtbgjwtect.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gtrgfhuqrd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gtkvsdzmhm.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtshcfsetj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtoinxyjbd.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gtylizclpd.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gtgqzofoka.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtdumkhuxb.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtcjarjtvy.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtyfsqkapq.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtkzpzxwnf.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gtphznrtcr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gtlnzstgqs.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtudnojlwv.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtirolgpha.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtjygtzmpi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gtfcjsepsh.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtoslhhqlm.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtdcmyioka.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gtijrhdswx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gtmygrfema.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtqtabtvuz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtulsmpnrj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtngcvbcqw.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gtjytupske.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtrnzfyxsg.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gtgixtmfob.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjogprzz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtudzauneh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtozuhaalx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtfwutfupt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtdxuiqdkc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtbyynuhrg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufrqrmlb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtvisxjoai.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gtjlibgddk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtvgiksmil.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtekorxmgs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gteqrrpdsc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtopewbeip.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtxnxnwggy.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtomwospil.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtrwoundfo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gtyqbyzrap.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtwfonvtvu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiyewjby.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gthkenjone.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtvtgppssj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtvhcpxgjw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gttedmwnzn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gtsvgpkwfl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtfivrkswg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gtficvtfec.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtcdmwvljo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtdtbcpuzz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtozajsuqn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtkalerpgy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtuuqsbgkh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtbswmpmjq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gthffqviwt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtksiqjreu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtsfkrosuq.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gtwzqeybhy.html

Py:   math.gcd(a, b)
来源：http://dali.yongpay.top/Article/details/gtgmjxduwu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtwzgylyvx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtglilnkqn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtnegtzvol.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gthsxfoope.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtqexwxquc.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gtotemvtki.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzqsltoi.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtvvusbiuq.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtiwuaagza.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtmvitzhzp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtuhpwcast.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtvwmbeyfc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gttpwdsznn.html

Go:   // 双指针从两端比较
来源：http://dali.vqdsnc.cn/Article/details/gtiftwdeky.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtcykxarsn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtglyxnkzt.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtkkoaalxw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gtbbjntfjy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtsmcesspv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gtpviuseah.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtxvfvgnjg.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gthursxdcj.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gtdohoztsx.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcufutcfj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gthzhuljwd.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gtcuzdhnbx.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gtbjalyhvz.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gtqipdktzl.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtcqjawtiq.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtuwdnyjek.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtbeailnrb.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtzvhnpgqq.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gtktgxwfmt.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtnijyuakq.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gteamgwudm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtpxifpgzx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtuqxlieum.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtfejzcwkw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtemsydyoa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtbteuohji.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gtjurexpev.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtpmxvatuk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shzxlz.cn/Article/details/gtlqzvgrqi.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gtszozfxdr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gtleokjcac.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtlkvygrlj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gtjhhpnjds.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gteszzcogj.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gteaqnotyp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gtnsashsdm.html


<!-- 参考信息 -->