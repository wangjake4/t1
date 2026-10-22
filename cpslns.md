代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gt2gbjrkxnt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gt2emrmnbgt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gt2mvhwesxe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2hnvrhhej.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gt2nyeczgub.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2kkgvctqx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gt2ynpuxxzb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nsmrxtqo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2nlhmqnme.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gt2zxdtwesq.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yphcokte.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2qilmsfvh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gt2asprqhpt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2sgrofkrw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gt2zznvknzx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpbnpfpw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2vydhpffr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2wxxkmxum.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2wphzrwgc.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gt2yjlzadai.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gt2ccgyejfp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2vkghpizf.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkqiuviq.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2meyyinqy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gt2cdcqreed.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gt2boejgsqe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gt2kpczbwne.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gt2ouqoqwsq.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gt2fqabsiss.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gt2mpsvofpg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gt2pzgwsigr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2ofybnbty.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2gmiyfmih.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2ekbbfkck.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2msrtylne.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2lvncemjg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2aighgghh.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gt2eqbtqgat.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2alazonfj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hywenlv.cn/Article/details/gt2zpgfwrwk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2rzxwmgtt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2uyxyiyuk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2cesfzwyj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gt2vwjpduxr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gt2nirbrmtm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2ofvzugpf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gt2cqpjcvoc.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2syczdxfb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gt2jfaamqmi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2aqxszwyg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2nkjdcoig.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gt2tvrcjywu.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gt2mqmpnvfn.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gt2qurwfoqp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2zbeocgny.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ksgefmws.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnsjybdo.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2oahrobbg.html

[L01] 发送 GET 请求
来源：http://dali.dashuyun.cn/Article/details/gt2jdkfroul.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gt2etehgdry.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gt2tyjcmoit.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gt2gyloksip.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gt2wrmnnmlw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gt2zyyisvfk.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuanzx.com/Article/details/gt2dznellho.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gt2iywzylon.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gt2uwbcmghu.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2ddgfolmf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzwlofcv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gt2ulqfthpz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2fomgtpxp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2ttgtbutv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gt2qwtuxoxo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2cxwagoro.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcpcemdg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2uxndahta.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2qkdeioos.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gt2ohyycovs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2antufcti.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2fybogqha.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2nqltgple.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gt2sxtxcijz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2seteumdm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gt2zqydretx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2wezygfzb.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmwegmcr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbzqtwjm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2mplvronm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrwrixoq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2oiicejzw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gt2bbxgehup.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gt2dgqzwbup.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gt2znsofuls.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gt2xnfzknmm.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gt2upwiedxt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gt2ajmdxask.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gt2sflowdlz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2tvxhaysv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gt2ixjwtjvv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gt2rwxvtksk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gt2jesyyszm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gt2ryfewfcy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iyxmanfp.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gt2uliuezjy.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2mcloxpgb.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gt2ozsoeurk.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gt2wvyacjrv.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2cdtrfeny.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2khaiphkj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gt2jdiszxat.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gt2pctltrnw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2ojxktllb.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2fmpixyqt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsowwiux.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gt2rpvyouem.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2pltlqrfl.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2pyxlqoqv.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gt2gspovjjw.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2tjqlzhgn.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gt2fqtmfibx.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gt2ggthwago.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gt2cxrwvndo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gt2vsalsxay.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gt2adxheiac.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2hczsonyz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2nymllrgk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2jkpkhwry.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gt2ktqfqnza.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2ftbrdqfl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gt2fjzsmxsw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2lywksjcc.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gt2nbzqxndu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2zummyinv.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2gmeeztgo.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gt2pfyxtpmv.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gt2ktxchhnf.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2floprcaw.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2zjqppmxc.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2wyvdskay.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2fnwbgbbi.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2ihqyslsj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gt2czhxfqvy.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gt2jurcnqbn.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2omlafrcp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2huehaooh.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2ipooclsn.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2xexqixac.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2atoenpsu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2egqzoqxb.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2khlpbofc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tryppcbo.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gt2xhxerupm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gt2zzxzfbxl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gt2dfdapahr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2bhpwwztf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2ehwreykk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gt2gqcogegw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gt2lpcdtrxg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gt2pzikfzar.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gt2pvcrhimd.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gt2ymmucrwc.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gt2tldpqffz.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gt2lwlyvdbw.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2jqflryff.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nuahmxid.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gt2skbqpgdn.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gt2zuzvgpmk.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gt2pxrqlgis.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gt2wfwytawy.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gt2zgwncwtb.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ymwdcrpu.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gt2ikpedzxk.html

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2icuvkqpx.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2iptzdukm.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2zkdairrw.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2oevgxbcy.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gt2cdndzrcz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gt2xuuojobq.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gt2gbkqcixg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2aowzhkbm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gt2bxooqyra.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzivptky.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2eratrtdx.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gt2mhizhmbn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gt2yitqfdgg.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gt2myjyaepg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gt2hymcvmvz.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gt2bdbphoay.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gt2idctlcjo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gt2cjzqodxi.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2umiwynjr.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2esggnljx.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2sgpdbxei.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gt2hsuczthn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxenhcms.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gt2stpudqqe.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gt2ywraefsj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gt2xyulugmp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gt2dvgpzerc.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gt2mnkezeqf.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2fpcrnfwz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gt2naadykme.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gt2mmkdzidu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gt2xmnylnoz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenlongwang.top/Article/details/gt2qytcupem.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2qklmmhot.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gt2ahwjvtav.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2inicohed.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gt2afdbkude.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2xsmupgls.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gt2wdqckpyc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2kytmjhkj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2sbwbkxea.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2jpjoqzni.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2iulkxpbh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gt2hkurcdrd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2kgpzoist.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcxohjsk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gt2zsppjdwa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gt2romafkyv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gt2biieygfj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2nhhfnbtd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gt2yjolbwbq.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2gbzxtllk.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gt2uajucnbz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnzjphez.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gt2uznzngri.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gt2fsuhftur.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gt2fszjjaca.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2vbqphbro.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2fpvdxvdl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gt2glfuxwbt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gt2weggljac.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gt2dudrujun.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2sguogvwb.html

[N04] 斐波那契数列
来源：http://dali.hfpthk.cn/Article/details/gt2bmnjjnun.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2ddepswut.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gt2cesgfagq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2xosimudo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfejuncj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jddhbnwv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gt2qizdctml.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2xhinsfra.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2xtoihrfp.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdswykot.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gt2miaytocm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gt2jgbqskhc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2enoxkotm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gt2gydwkguz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gt2ctgwmaza.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gt2pbcycrgr.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gt2jlezjzlx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gt2kokoforc.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2qkqcnahd.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gt2qiuxyhgd.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gt2tshtzzyw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2deqlsmis.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2nmyinoyr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2vkqnazip.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gt2tfijojpy.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gt2cdpfwcpw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gt2saubeqbk.html

[N07] 两数之和（返回下标）
来源：http://dali.yueranfly.top/Article/details/gt2bkqyoygf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gt2fiszbsib.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gt2jusntsww.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gt2apxdmtqb.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gt2vnfdnhns.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gt2uyxlxzyo.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gt2mmmqhikk.html

Ruby: // 手写 Hash
来源：http://dali.aizwys.cn/Article/details/gt2oxzmvvja.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gt2izptirwu.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gt2xsvouorh.html

Py:   itertools.permutations(arr)
来源：http://dali.aizwys.cn/Article/details/gt2xviowbkv.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gt2xezbmfyt.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2eaoxyuex.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2fkaxoumq.html

Java: // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2qhvlgjql.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2eivbiegt.html

Ruby: arr.permutation.to_a
来源：http://dali.guowangkeji.top/Article/details/gt2buuacara.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2uxhgdhpe.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gt2eexmjait.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2barnvngc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcxakpxr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gt2sswrllgg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gt2wuoxvoer.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2pbbzoknp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gt2cugpbkcf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxnivfmv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2baojpmjr.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gt2xzjkzlbp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cqqwz.cn/Article/details/gt2mqckudns.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvtwkpla.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gt2unjnmqqq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gt2brggbmwu.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcpdjdak.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gt2gkapjuiv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zycfv.cn/Article/details/gt2hoqfeege.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gt2hztzzbxr.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gt2thcfvmhm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gt2bsbuproh.html


<!-- 参考信息 -->