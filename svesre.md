代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gt2xgfbhmtk.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gt2zlxaiewd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2bmsurbnn.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2yheeeyaq.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2fothgwap.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdwgoesx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2pqntvsyx.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkcwuwnz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfvnivms.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gt2vmcutdap.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpmoxgje.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gt2mmfbzufj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2hrshgqlz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2efnvkgkt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxrsevzu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gt2upfvgqqr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gt2amzgvxjd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gt2hejahzzi.html

[K04] 读取 JSON 文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2xysqhubd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gt2poydhdle.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gt2rglpmnhv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2mdhalhwb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gt2dghfunxm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2zkffkvux.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gt2aihtjxta.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2fznyrvkm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2jukhkamn.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gt2ahuohsmo.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wccqstqq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouypdzpz.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2ishvkcwd.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2mtpukesy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gt2phxsrexd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gt2bllmoonj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2qxbyhyem.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdhdpqui.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjqglcwb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2gpsbuefy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gt2etmsefkb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2dlkcpkrc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qaewxhse.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2godhdcie.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2ylatmsuc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2xofwohef.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2wahugsce.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gt2eekexuju.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2mrcdxszz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gt2ewunbtiw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyequfit.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2otauacci.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2hyzyhnhs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gt2bphxaiat.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gt2gldlzmpw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puoelgkx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gt2fymlwfps.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2zehfpvec.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gt2ddwsjdcn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gt2szkmkmat.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gt2gsfwjoza.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gt2cbunmiua.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gt2kvvefjvi.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvndksgc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2kpozcjng.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2wmjynplc.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gt2wsdacbma.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2inelelko.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2uvlnciua.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gt2kbfagyfd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gt2gyiwbzhb.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lffpvfto.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2tlftqkam.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gt2gdlnkzbr.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gt2oujnmmwe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ziwfkrvc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gt2qanjyprb.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2fckwavum.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gt2jbxnnmhw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gt2jpsqvgnc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gt2ntlhkysi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gt2ilkyfwcn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2yklviybu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gt2kesbbdkl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gt2lfbnnbus.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gt2isjrqfsn.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpftafor.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gt2kigdagwj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2mjkjpxvv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2taxbftlx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2ckhpegbe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gt2abbmtaij.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gt2xgdremrw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwyqxftn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2bypzcdct.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gt2zwgmbkbh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbypbeee.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orkqhgex.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2fcqyxefs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gt2xfyebqdw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gt2fojuoyag.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2narrevwn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gt2deetiksv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gt2jsvopbkr.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gt2yombnbcb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyemyugh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tian-w.cn/Article/details/gt2chsvynsa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gt2xsbwqrmg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2kblsdvvp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gt2gcxodxfc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2ngnwtzjk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sshidfmc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gt2pdtapvxt.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gt2lvzcyvjr.html

Py:   resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2qjglhott.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crmlqhss.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2cbbhneyh.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2lxdccpwl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2epmoadxe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gt2aepwoibl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gt2zdidrxjd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zkjigave.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gt2uwrsxzhl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tniyyahs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyvmsotf.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gt2xojmrlmb.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2bpnvdmmi.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gt2ihgyttoz.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gt2rcrgiytt.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gt2tbprfhjg.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2ffusdvbl.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gt2qizlittn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gt2oqmcqxuo.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gt2grfluacb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2xichdlpc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2iptowxah.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbqwxymj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gt2aujozgeo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gt2uofvlfne.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gt2abgyzkus.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2kwzlrsws.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gt2xeqzvace.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2fxxccxjy.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2ztrbwshj.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gt2avvfvhrx.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gt2mumusivv.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvrsmkhr.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2gmrvgswz.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2fuqseuzk.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2cgoskdml.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhikklet.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gt2dwbrkszd.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2lzbpsgxk.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2zwqkbkvi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2eospwoav.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmqoqjeg.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrjbejhm.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzltbaxo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2wadfshbl.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gt2mlntncke.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2judxehye.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gt2gqwmwgjg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gt2otwnuhbj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gt2yuelrwml.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gt2svjpkhvy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2dghwtqek.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gt2wgzsgbbj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gt2mqbmvhot.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmgrjrel.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gt2arwxnmxe.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewdzypet.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gt2agzctwje.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gt2wlihaldr.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2mopfjfge.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqsdliqv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oginaedx.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gt2fygyggqy.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzwtsloj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfthmyys.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gt2qjfhnlzl.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2ntfxmosg.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2asqmpwjl.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2kddwlpfw.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2ectebrum.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2ckkavmnh.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gt2zgkpxzig.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gt2gxbmqoeh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvgqbjxu.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gt2jhmdhvla.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2ztdqpyoo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gt2mgmiktah.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2vjtkdomy.html

TS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqjqpdfn.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gt2mcwqtcdh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gt2qexxrkzy.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnbhhgbz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2pddqcuap.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gt2rwwxzodg.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2qwwezfps.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gt2knduyqur.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2hbdkxypi.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2qzikravk.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2cdzcvotl.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gt2khxqgjqv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gt2rclneikg.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gt2vfdocewd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxxgfqum.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gt2kjtndppr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gt2btxnxljo.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2ezufopqq.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsontvsq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gt2lgbbtmbn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gt2zhdteqku.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gt2oxrlznkn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gt2pigvcsof.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vtptjlvv.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gt2wlqpsvab.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2izmlsldk.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gt2jadnlpln.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwoojwzz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2vqwgkkhy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gt2nbtbrwyq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2nfzgpuyf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2ndavslwf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2jlbwwqhc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfxxnxsj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2hnaijgfc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gt2xrmxrsah.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gt2vaibjqmf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2umxioknx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2hawzxjud.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2xsueaifa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gt2cvutshnq.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2ygleoady.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gt2iltpkpgh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gt2nibkzfai.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gt2koglsyss.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gt2rrscirda.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sysykeji.top/Article/details/gt2erwzmyym.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2dkgfjbgb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gt2ffxidfwa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gt2swmrufea.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gt2uejpqcft.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gt2bxcaoidn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gt2obqsvwgi.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gt2nlzrcegl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2mdvrqobg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gt2sbknjnyc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2tulxpeoo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2mmdrnyvr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2feciiicj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gt2ubozhaci.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gt2homxwelq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2buqrrclw.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmldmlej.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gt2vrdoxgdy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2mniricfn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2fpxuetdc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2beoyibzq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gt2avggijax.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2toenfleq.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2olysuqwf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gt2bupsuvro.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gt2yxvxyndb.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2qpmjajbs.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2gfuqobba.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2bzmpfxut.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2vucfzzpz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gt2zmlaauhd.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gt2jgtyccbi.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gt2sonkfnfz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gt2ihzosozj.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gt2ieeayqdg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gt2gkjcxegx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gt2iqmdkuov.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqasfaea.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gt2dslvhkqk.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gt2ftbxivzo.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gt2orovpftj.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gt2fznqbtmd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gt2yxnefusp.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gt2rsetaefi.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2hjuwhixi.html

PHP:  // 手写递归交换
来源：http://dali.zycfv.cn/Article/details/gt2dahjcrnu.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2easrvhyo.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2achkeebq.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2nvtbjokf.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2yehgjtjd.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjanxjeq.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2xqsvqrbk.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2ydeynyjf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gt2ypbejoxi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvefyxht.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2orsjbxww.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gt2rbtpmxhw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gt2vpaqezyl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gt2vhbbqpgq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2rcaprfnx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gt2zeyxpxwu.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gt2umebtpeg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gt2bgcrausr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shzxlz.cn/Article/details/gt2bkzgjrca.html


<!-- 参考信息 -->