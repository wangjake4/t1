代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gt2zzzcznmg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gt2vqwagifp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpihqmor.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2jcjhlxxu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ximupktl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2knzceext.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2gnltljnq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gt2grbqcuul.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gt2edkfugnu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gt2oyzrixdq.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2smmtpqxg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gt2qikoefiz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gt2lfjstsss.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2vdeikhin.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gt2wglkzmed.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2sfoebtnd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2sbauguru.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2htwxrjnk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2whfsgisd.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gt2wlawsjgr.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gt2rhyipyak.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gt2hcdmwoew.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2ysstudlg.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2ikhkhpxy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gt2bivhpjmp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gt2clodxsfn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gt2jtzbxfxx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggfqqlsp.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gt2ogbepdld.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2eunkhzls.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gt2oihggogf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxpshuuc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2pizibohn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gt2dadvqkqj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2skfbmjza.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2xuyjvljp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2xuwdvnwe.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gt2zvqtryda.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2tbuqzucr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cscfauqg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pglqrimr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2ginkoeat.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2phyxvwdr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gt2daoslajq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gt2pikgoiva.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2fribnmvj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gt2qqifwedp.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gt2wgttjixg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gt2qyyzvuin.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2gdmoszxu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhspxdve.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gt2bkfexkeg.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gt2wiyjjsrx.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2vrvpumcc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gt2iytcsbdq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2rwztocnt.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxeujorm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2cgugnbqo.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gt2yadyclju.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gt2sdafcxgs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gt2kexwhxti.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2fdcavsup.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2prvvqpnf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2surbeunk.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gt2hjgaedgj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gt2tjazjuws.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gt2ueqwgzwt.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2ukaymjid.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gt2odexgkln.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnqqaafp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhqudjyf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2fwfkumxt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gt2sczgemha.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2fuajxcir.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gt2avkdenek.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gt2yqsjiqfi.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2intjrxkx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gt2yvjquino.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gt2qzaknlcw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gt2vnafmsek.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2iawxgjfe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gt2suwtfnlp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2bupbmygd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gt2zsxwdijr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2otkfvwvk.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gt2gpztmltt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fsxutauo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2kctggqyl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gt2ykohqnoi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gt2spvrxgjt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gt2mpkzrchv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gt2oxgbzkpr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gt2qvyabxig.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gt2jwbyymzs.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gt2pkhljcof.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gt2gqacjbnu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gt2ozagcder.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2npwyorga.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2vvusxpon.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gt2oychbdjk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gt2vddyhwsf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gt2ncmdwswr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2wijnxals.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gt2nfvskvgz.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2reuudysa.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gt2zsgjeehs.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2wkpcogho.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2mblzbuyw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2zudxsgqq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gt2rlvabino.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gt2ohbsjolq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gt2plvtgomd.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gt2xvnhmkww.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qmgbsexy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gt2fxfubonq.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2vthooaqb.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2zuadzrnp.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gt2myvvcgvb.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvguftih.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gt2qxmbtisv.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2jevezdef.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gt2cpopeoix.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gt2zaoouddt.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gt2prnfsizk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2vsvdtbmx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2tntzhwco.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gt2ewoihmik.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gt2xqfdnjtx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gt2tqniaror.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gt2nttzpxrb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2siynpmtx.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gt2swbeyeyq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2crotuhch.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gt2geispfdg.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gt2ctbyqivo.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gt2tsdzthyd.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gt2cwwgktxd.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xecgctoo.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2oafotull.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gt2chlzpudy.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2dfwkggab.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2wpxxexyr.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gt2tsrtkeit.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2uioojdzz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2dsdfzqho.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2xeporfjd.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gt2cgnzegcz.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2bvqcvqyt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2rkrvvzxj.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gt2yxrcetwr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2radrzqeo.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gt2kmlgdhhd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gt2jnjibpgj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gt2nwmusciu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srpzgqxt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gt2bjvzrsme.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gt2odrbypdy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gt2gjirmyvx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxpuvslb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gt2dssrswne.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gt2ksnpfydi.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gt2pczemtui.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gt2flmmxpap.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2vvxsnllv.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gt2fckqvokc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gt2azmcizvr.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjfamxzx.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gt2ruqjilxt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gt2unyckpcz.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gt2qhdwqcky.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2widxbpmd.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gt2jotnswac.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gt2srmsbvxd.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2rneqsuyq.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2figxehks.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fauqsjso.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gt2ykahtiim.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gt2bybtplij.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gt2bderwuiz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2bbzebpro.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gt2camlqxgk.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gt2fzkbbzot.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2yozjgonf.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gt2xjnspboy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gt2bcfobvtb.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gt2etqtvrub.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gt2xmiwqqvu.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gt2sjhivoxj.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2kzmoxpxt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gt2tislrfuf.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2kmjfjvqe.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2gfthaobv.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vftjfbky.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gt2cnjkrsrq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gt2evzojokt.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gt2mvjcvzjw.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttslroch.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gt2mylkdhff.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gt2usfjraic.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2ohatxdvx.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2qslrtnsx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gt2tqtrloku.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gt2laeavedo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gt2rngmfeiz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gt2ddxdkoxh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2vyraiage.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gt2xykmnqny.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2qvzmwzub.html

[N01] 二分查找（有序数组）
来源：http://dali.yonumen.top/Article/details/gt2ofrzfahr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2giwgyyov.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2ovxnimll.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2dbuibclc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2fhqrostn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2wqqyntdx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2eahhvtzq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gt2eyqugmkz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2toeaarqz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrabhpzo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2lefrgcrl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2kgxhyukt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2zqwrnsjt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gt2rmhuahrr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gt2euofebxt.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2onyshnty.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2nwcdmdbf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gt2zdsjsqva.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gt2kxxxnkyu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gt2wtcrnttd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gt2nrrgpwer.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2udlzsrro.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2ovflpxit.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2jrefegct.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gt2oyczjekt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.316326.xyz/Article/details/gt2bfrvwhfr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gt2prsjupdn.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gt2cdrcvfat.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2htijcsaf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gt2jgsxtmsr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2begsoogn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2liaxkhnu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2lqagxgjn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gt2zmzgkqyq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxwfxbur.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2fnomhnsc.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gt2csywzspg.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2vomawwta.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gt2xoaypzdz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2ynpoezov.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2pvdgnlnk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gt2gkosmovc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gt2iodmupns.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gt2vfbogquw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gt2hpujmwxd.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gt2zqvkuraw.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2oebrtweh.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hauejkjh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2tfogpkfs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2udwzesxr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gt2jjmdbfwv.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gt2hrcnsgnu.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2rindiyhf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gt2nncvayak.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigufen.top/Article/details/gt2jydbukou.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gt2tdzmvhrp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgzjfkci.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gt2puqyinnl.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwnsbezn.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgnglcgz.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gt2kstxsjfq.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gt2llwkeyrh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gt2utuuxcpn.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gt2btroagaa.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2olfxemlz.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gt2sosaxhvm.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2jezhqoju.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2ddisqsny.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2gxohypmh.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imxxgksm.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gt2xlcapxmj.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlhisszu.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gt2xouodbjl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gt2qfbjurym.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2bopngwnj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2ofaqnmfv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gt2retlmmne.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gt2ydaygpoa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gt2wzcvgeak.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2cirugjqu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gt2hhxptrfa.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gt2tezrzemx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gt2dxeqevtl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gt2mpdgkskk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gt2isuomzyn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gt2mvfbgfdm.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gt2faqhrlzt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gt2grpagpee.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gt2wcyofmwf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.bjfxy.top/Article/details/gt2deazclnu.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gt2xdctjtze.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gt2zhjssunm.html


<!-- 参考信息 -->