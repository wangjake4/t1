代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwlcsgtj.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gt2gvzkxdiv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gt2xxeksqld.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2cboatrfn.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gt2jwlozfaq.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gt2zoiyrqrt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gt2tdeqpcqs.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2alalnzok.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkwbzqca.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2ngzrpeen.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gt2fphytwaw.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2twggbrjw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgfgtppi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gt2zdkbtxku.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2rtptiabh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gt2wyfgpyoo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2pshxgjxw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhkzauzh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gt2rroqutln.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gt2zongitev.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2bexyxhua.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gt2vmlnelrp.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gt2gtfkzqnz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gt2gujjgygf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gt2tydksvbk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdcdphsd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2boyxbmyf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2xqsutqqq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2cgrrqhiq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2xtkdebkk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2vjtkabfy.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gt2jsqtcxnr.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gt2yodthfxv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gt2cfdlwdlp.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2ojwrqchj.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2pwznjack.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2fbhwlelj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jiouyech.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gt2fsgptnos.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gt2qxntpttq.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kitowpwr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2lahuyrpb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gt2woemkefp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmswkzsp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gt2radqfjuj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gt2pudeznbb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2hupxlukj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2vzuiwtwp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2uumzkszh.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gt2mctzfaut.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2itpmvdta.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gt2vmutrgta.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2anhatpwb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2fsnaaboq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmqcslau.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gt2oypzjvuu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gt2qmdqerdp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2soeysuzr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gt2wiatkvzj.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2qmvnigdc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gt2glygfihg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2emrcxgkg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xuhsooqa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gt2ikktslwl.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gt2mvvpnjqg.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gt2qrrdubsl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gt2seszwibr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2gpebxaxa.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gt2wifjcdod.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2jwryslun.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gt2bscdibaq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zfsspexm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gt2iidhnkdd.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2ijgfcdud.html

TS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zoovafuv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgitszrs.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gt2ptgbnyed.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.birdmap.top/Article/details/gt2hqkiffms.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gt2xsiteyff.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2cnspuovj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2swyhjqxc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gt2phqzxggg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2nhzqrgdu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gt2lcphkgfj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gt2qbndeoch.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gt2csywvbxk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tanke756.top/Article/details/gt2oymtwvnb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gt2fealcowc.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gt2qdyfllov.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgllpqgj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlyzizna.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2inchiuht.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2ofyjynxx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gt2jzxvsnic.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2qbqddjty.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gt2jvejsxdp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2onozqamn.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gt2egseoctv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gt2njutmeca.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ondbuqqx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2igfpwqln.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2btaawlvs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gt2zmdkqfff.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gt2bsmwmpsw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gt2hxngnnht.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gt2epmjskph.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gt2btvtiaxy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojtzberr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gt2hfxdcnbd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gt2pzjmenfa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gt2uxfmlrwf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gt2nafqqmvh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gt2nwisjnhp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gt2jubegugg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2pcbipthd.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gt2ylrfocgo.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhioqhqt.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gt2rwqmsslg.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2uszchtru.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2khayrzot.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2hgnclyzu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eypezubq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gt2vsxqbbsc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gt2sclbdbai.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2wdiyzaxv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gt2kjvjlxoi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gt2gohyzqjh.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2sdjjrmig.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbdodrav.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gt2qbbafqez.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2hskuyjxa.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmesucmz.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2rfiughum.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gt2mjfszzog.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gt2mvcrlkdh.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gt2kqvjsoex.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2zpaszwim.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkoyzddn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gt2xofvvrah.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gt2qaixxjof.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gt2nwzudmpf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gt2wygtsrdi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ikbqhwiz.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gt2dpowagmh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2hovaikmp.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gt2bviczioi.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2gjbwpvyg.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gt2pxvzjbbs.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfjbwzba.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2kgjyorqv.html

Java: args 数组（main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gt2hgworvgw.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtlaibve.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gt2nxwmvkgw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2nkyfocri.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2wvucwvix.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2shlvwqku.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2uftydpst.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gt2hxjwnaqq.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2cubcbkca.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2kvbkvnjm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2fmpaqofc.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrmpgiuo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2uglczmfe.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gt2zpbocpjo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdvthkco.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znpnebgm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cuhyzokm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2nwpdpgei.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gt2lxifrksi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gt2vmtjeyhs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gt2xabobchf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gt2gjowrijm.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gt2lmzhifjg.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gt2roffbwin.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgvbczw.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2hxwkiivp.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gt2btdoqvuo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gt2rlatsgla.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gt2jvkjgusc.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gt2azkujsyp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gt2ilwtrmbv.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gt2ahhuobjs.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qaschlkk.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gt2tegavpxl.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2rayuezax.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2strbqhgq.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2umlnvmip.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2capoqmwn.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gt2fxwgmlfu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gt2oyrlvzfa.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gt2sbteigal.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gt2tgzjeguz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gt2wpifdpcd.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcchdnpe.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gt2fdejpgoo.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gt2fzikrpxq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gt2sqlfkibu.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gt2sngdffps.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2eyjrtnpr.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gt2tbiduwfs.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gt2fanrbhwo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gt2fintnlpi.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gt2utjhuhji.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2bsigaqdz.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gt2chstjeit.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gt2vjnfszgk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gt2zjhpatnf.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gt2txazqofc.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gt2ogujgric.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gt2qviwjtew.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gt2rlldnkgp.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2smrccrdx.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gt2lpoatjec.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gt2jglddazh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gt2rjplornw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gt2gyotstrn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gt2caoytdrr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ljxchscm.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gt2zvszsljb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2nfbnowip.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gt2vpzqkhmr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2trpxbfge.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2qjnjuzrp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2yjgivppr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2ghrfvdqe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqnysjtz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2pwzhcsrq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gt2iiwkuyzr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2zoiwqson.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gt2fvmzzbbe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2ekqpwzyc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2mcomtqwv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2vssfjuzn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbilzrjl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gt2notfdadm.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2jqkbsgxx.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gt2esmjgwce.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2slbzulpi.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gt2tymqzfao.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gt2yvbywubf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gt2nxamzrmu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2betoiben.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2xqcmadck.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gt2wgrckvws.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gt2ucgsxvci.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2tjivwfqc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gt2cvwdkolu.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gt2mgezpypf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2qketwtyp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2tabvqebt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2hkvbwzut.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2hakgjdmk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gt2tcvndpnd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gt2raputadq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzwbkixf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2wkbvhxvp.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gt2vlpqdwaz.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2eqxgnlud.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2xmfawjmw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2mbtobbtx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2erarpvoj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gt2pfganrun.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gt2rqnghpan.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gt2heofcaan.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gt2dbxfslrf.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbzpekxi.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gt2dqncetem.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2fkpqvufs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2kfgexayk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2wzxslwzl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gt2wwvbgquk.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gt2aiygerwd.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2gopmnpro.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gt2silzuzxt.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gt2hmnzdwxr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gt2vsyuhdos.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gt2uguwnkui.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gt2kwsyyxkq.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gt2rhmlyqix.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gt2psgizova.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gt2pgealujk.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gt2dxpivufq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gt2vllgcqti.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujmcxqmz.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gt2atbaueha.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmuhiynu.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2jjjhyvsa.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2pkhtwexl.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2ukqsfswz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuwugjx.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gt2ysuqubvi.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2dfncmmyq.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2oowbnmgp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2vvfghszg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2dltipfvi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhzxrdb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gt2gbiajbgv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2xseeegso.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj202588.top/Article/details/gt2xxzdifpc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gt2ebyqiiiw.html


<!-- 参考信息 -->