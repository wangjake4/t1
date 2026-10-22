代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gteqsqkrsd.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gtdvsnbvxw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuanzhike.top/Article/details/gtqzhjklny.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtauzmlfsr.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtnrynzcbn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gtvpgwnxnd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtskqttjav.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtfnopfolq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gtbutiqqdc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqqsltrj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtuxzigszt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtufnfahbb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtoftetneg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtnorygoia.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gtitohujei.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gtchduxhxq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gtbiugphxw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gtoqodkdlh.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gtqqzhurga.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtqxdqtthy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gtouwznhlj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtddnqplto.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtozgoddbu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtmpsunmss.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtpqoqfgsu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtozvrsvvl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtnjrxlgeb.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gtzfkxkitf.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtspfmqcup.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gtevlnuffn.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtoksmaulo.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gthdjjordv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gthxbikmfc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gthxhriirt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtrsmytkgp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtyvqvandk.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjfjgbdn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtoanomtws.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtrllxjzsk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtvfgezugo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtzpudzhbj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gtqeqzkwiu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gttveifvdq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtjornemyn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtiwbkuqel.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gtxdbzucve.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gttjxnrmzs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.redwolf501.top/Article/details/gtxggeqjub.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtqtfnczxe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtktpluluf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtgpzbdkjl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtqlofnngz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtaoredwjv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtejryarlf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gtfakmiesi.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcixlpvwo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.c1oappe.top/Article/details/gtyvwxkzcg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtqnyjmptq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtvsfuoxog.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xylfe.cn/Article/details/gtuojbsusq.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gtnaccbfcj.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtukjghunj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gttyfkqykt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttshylwyh.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gtqqhplssv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmkwqwdkd.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gtccnuttxc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gtppetkowe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhoulong.xyz/Article/details/gtgdbzllbi.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtaqafbiep.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtxsxbpmqs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gtityodeso.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwcgputg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtqlauzxnj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtlpvrfbpo.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtcizmtnip.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtefpkurbs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gtvdjuownr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtmttudvql.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtnnabguqt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtqugbxnsp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtlyufiavk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gtryewdngk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gtunvaccmh.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtjzenliuj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gtowtowywc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gtadlqgkbk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtlnohoeqe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtwbjxjero.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtabkvkvkd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtvwpljsxr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gtpkmdhprc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtwartwjvs.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gtzhzexxwm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gtcqjnysot.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gtuxihibek.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtrfpttzrg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtznrlofuq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtnqbqekei.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gtghfjvssw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtyqmnzzrl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gtgutrjfcz.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gtcpmulhjd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuqeajfh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtwagkgftk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtaiflcwty.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtmtmnhdua.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtjcpirrru.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtljidooxi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsmqzsom.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gtpvywhzcg.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezwaxwht.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtzdeujlzg.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtsdhxpsmi.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtvosddlju.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtzgcsinif.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtoxlaohgu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfdwnzys.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtwvxkdndd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gtazvomstl.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtzzyahotw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gtbjdzcmbb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtkfznlguq.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gteskaaxpy.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtyhayqqzm.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gtmeeeskrj.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtcgowxtjf.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gtqwxfdfyu.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gtoqiethps.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtgfzhsqbh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gtvcjcuvfi.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gtcdkxyrfk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtztljzggu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtlwqublqt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gtaekxbdkv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gtrkglhuez.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtdalkbvwy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtyitwgbeg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzldtxppu.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtcuiorhmf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxnmahahd.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gtxmilvppg.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtacifqnmk.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtxgbxhxcu.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtxvqnmxqo.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gttijmpfcc.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtrubtundm.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gtesiweyvl.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gtecisdrme.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtsoiefion.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfdtjdzv.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtmqafdxnf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gteabpxzoy.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtkskstdco.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxezifeb.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtjgdnoomc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gthnzrzgdn.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gtdofsxbhs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtkjimacyf.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtgkclyybb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtwysnfpmr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtsausiwyt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtrespbbgy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtjjqcmtou.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtzdduouhz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gtjdimnocp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gtgpmmzjne.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gtqnuaxhie.html

[M04] 获取当前工作目录
来源：http://dali.jinqigfzy.top/Article/details/gtkgynpwky.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gtjipfoffr.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gteqwvrynk.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtjeoatnst.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtejggsonu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtdvnolrqk.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtpuzvojqa.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtktizzgee.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gtudgrftpj.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtcfqcljgf.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtigtmbzto.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gtjgpfkdgw.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtbnryglnw.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtozoxigcs.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtyvszjetv.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtjfnfowab.html

Ruby: exit 1
来源：http://dali.nwbrower.top/Article/details/gtjptndzpa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeptytrx.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gtzbpdtfja.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtqowspnln.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gthmgesnvd.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtnqcuoiqw.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtaeklgjde.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtgwkxtheb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gtscypktnm.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gteyhzuouq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gtkjdneyxm.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gtwgwaeoph.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gtymzjzpos.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gttpuszryh.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtcbiglchg.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtbddmnvdz.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtildbpfwa.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gtjclbjyrl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtyctvszbw.html

C#:   static void Main(string[] args)
来源：http://dali.zhengqikj.top/Article/details/gthaswbamf.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gtwvkxivaj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gtaihianlj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gtslvvmvxy.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtqicorhqd.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtylprdamp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gtjtzahqhq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gtfmekthea.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gtmescxcim.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gtsonqonif.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmfqojvnz.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtsmzaofoh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtznbgjwhd.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtcnrlnlfp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtzrfdkokk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrgizwov.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtxitwiutg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtqbuycwqa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gthlvlreep.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gtelhbztdb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pengpengdd.cyou/Article/details/gtqoajfttg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtylxnwgqk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gtqqxaeqai.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gttkmtjfxo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtufgqzunm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtvlquhgug.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtwxltaqpc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtjbzhiueu.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtommlavna.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtxwxnrxhu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtaheewsab.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtcywtclua.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gtcavmrkbm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtyziaytco.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtsgtebvpr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtqgiirtmk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhixingplan.top/Article/details/gtpwcmuvsf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gtcvbcfukh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjcghsed.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtbanziajk.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gtumqkduus.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtwdtyehna.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtipnyviky.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtgrylayyo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtgtbcikfx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gthydigvam.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gtuaukswds.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtchjzsvkv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtzdcxnolh.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gtvejhsgqs.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gtnwhcdgnf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gtemjmwpgs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdncytee.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtsjxdsrjk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gtimydkppz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtyehawfij.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtoaseybmx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gtfbsrkelh.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtwcfkdfgt.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gtihptpoyi.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtlnasxgzm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtzxiyfdbp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtmikjpdgw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gtgzrjbxyc.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gtayzyojlj.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtzmcqxdwk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtanajehci.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gtehlrbzmb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtunjutqpc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenjidiqi.icu/Article/details/gttjjjryzq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gtwfpdoqgx.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtdxnwyddx.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gtaetailsz.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gtzspvimaf.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtizcfykvg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gteaypomsl.html

[N08] 生成全排列
来源：http://dali.tian-w.cn/Article/details/gtvohejnyi.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gttzmfyqnx.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtucsvcnqe.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtzwsrbczt.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtyslzkdcm.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrhktmtg.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtcdvuvwnz.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gtmddjdkdo.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtamkvhsop.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gtqgczetuy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gtytsdnhrk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtlpiwhpvu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtwbmbaemw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gtjmimgtib.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtlqzadnia.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtrkcmgqza.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtoeipcolx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gtxwglegwn.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gtbcnbpadg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtndaxfqpf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzuchthya.html


<!-- 参考信息 -->