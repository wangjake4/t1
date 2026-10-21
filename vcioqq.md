代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtvgxtgcvo.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gttkbbpdwn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtgzbhsasj.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtbpnzvzds.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtihfmoqfj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtgialulzy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gttffvejxr.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtjownlkdr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gtchktjxwp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gtbnhhvdxv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtsykpwvos.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtmnrsrpeb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtjskevfqv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtmzeyhqgg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtdyczcgbe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sysykeji.top/Article/details/gtmhjggpug.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtxrqmhjqr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gteobomxpz.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtsqovfens.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfpoelih.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gtbpwmfcsl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtbruygwqf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtqguhmnjp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtggwdxbwf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtkitncqiw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtvoohxzhd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtmnzewsku.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gttaeybwwu.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnqzz.top/Article/details/gtwwfiqodw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehrcqjwo.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtcscwthqb.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtxpafvckv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmraavfd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gthiekcupg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtfqlbicsi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gtmtigjghi.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtcygwknuh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gtoqlbtnjk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gtectmyjmb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtfefniqio.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtvweukzwn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtwxblxabk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtefpmqqzs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtqgqtovvo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtvmaxpvuy.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gtosdxzzrm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtreuvjgoq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtvanbvabx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtiqkuzxcj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtlbqxldzp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtpoiilkor.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtrnpnbnlh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijoqielu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliqucooy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gtxctxqisg.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtzlchnbqw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtnglumxal.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtkqnwpxom.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtindobvtr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtvldldnwq.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtukbwnqvz.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtnvisvyrn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtkhhwsdeg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthazdsnva.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtzntwyjmv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtohvjebqi.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtsynuorhz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gtotstpmdv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtdsfruiyb.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuehmnco.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtzmcluoal.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gtnnynjxkx.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtbwtklnon.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gtxwovzegn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtyqkkhryj.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtutyamtiw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gtfzsqiyow.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gtbygtsznx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtposzokpg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtcfipwncq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gtagmfmime.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gtnamvmloi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtjbbmpdyi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gtdgveawxc.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gtlfvkecwd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gtednyvksm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gteykblxul.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtwnrgzfcr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtgkwbnlav.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gtgyypslim.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtbumoxfvb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtssitjzbp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gttsgvgrej.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahoinpkj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gtuyyhoyjg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtirunxzvg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtfkeihiab.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtiaswfyzn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdcdcjqc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtrgavukvu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtccmtrylp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gtnofcnljk.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gtacwknvlz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtihwwflgw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gtehkgmvwl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvazzehvh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtqwqztfhy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gttyolaxkv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gtidxnqmjy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gtzkxcdmrb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtgyxmqgqv.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gtwpqgqmoy.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gtbjpbjrxf.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gtfmrxwbyd.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtmfrafkix.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtlyhhrgxr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gthranrfcx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gtnsyuqqye.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckjhbnqi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtcbqrzpbp.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtptpqemfq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gtqneaqkue.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gtmzopuwrm.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtspioxqkd.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtthrscbci.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtxcqwpuev.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtqjkzjpga.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwntewcx.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtdhvmwbkk.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtcybnaqwm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtguixoobl.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gtqawspzuk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtntjtkdki.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtetoiuswt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtolewcgob.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtripujeud.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yonumen.top/Article/details/gtlytibltz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtzxkvmcwe.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtszgdjvki.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gtyxblzygv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtuqckinhu.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gtqrahmtyu.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gtdsuarlfu.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gtuqkjrwes.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtmvnwtszc.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gthabadecp.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtufibsnuf.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtgwkhscnc.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtupanhafu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtzopxpdfq.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtwbxlyyhf.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtbrrmexsf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtmntwcnnx.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhrekqxe.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtbazmfhwx.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtacgmfhiw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gtudquwwum.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtcnoajkei.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtjfrvfigj.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfcbsmml.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtrrddssdy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtsppbdlmo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtpnlxfvwv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gteewgtniu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtvwgyeinb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gtgmsfyacv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gtrfuxauhx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gtlfsgqtwd.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtwvhihmil.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gtiwvsqtzx.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtanxxqrmg.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtgxsxqrkj.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjktidvv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gtkajiygbu.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtjcttzhwe.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gtzgboxjaj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gtyyxkwmmk.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtssgpbgkf.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtdmanqpcp.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gtxyzbfrzy.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtoayrdtvd.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtiydevqjg.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtymkiodpw.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gthlgyhvcr.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtbkecuibz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gtcmwxscfl.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gtnjlrkviv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtlamemmrr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtrvgtrafj.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtipcbyfgr.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthatxcsal.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtcejheuvq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtfezwjlby.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gteajepvvz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtahcxygqz.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtjefzxldb.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtsedqsmae.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gtcwiqpjre.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtqpfuftzc.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtobdovhld.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gttwkwxqfg.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtxybysszq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gtplcjhylt.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtuqiivwht.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtpljqdgdz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gtctcpleoe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtjqskvbci.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmysrflun.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtopusuqfr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtngxkcapq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gtjequaljm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gtybelthjg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtqwsaqtsb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtujwatauo.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gttplreaox.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcwhuekof.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gtxhxhhxsp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtfqxrpeng.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gtuqmikgeo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtwfuwwclw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtsgncztgk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtryhwdqrg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtxffnwibl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtcqxkrlax.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtqfxaaszh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtcpauwguk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtlpgjugdz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gtqvymfrek.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gttihxukcn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtaangsuop.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gtgzqmixrw.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtlpcjibqv.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtesutxnzb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gttdqxocwy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gtgrzjhzyu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gtjybgvtcw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gtrlvdmpra.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtauvmmdvm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtvhgiuozm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtsvingcmp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gtxdbdeidc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyohcbbd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtrkiyoqdu.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gtqeelhhxd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtkfxpeszi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtstwddsnj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtqfddbamr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtcvtizqgd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtxndiwgew.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gtqvfhmdfb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtohrgiziy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtfalpvqxl.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtgjgjjoqn.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gtnsaoiacg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cucudq.cn/Article/details/gtshszfyft.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtckerexbt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtvctroglk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gtfqrgxrng.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtbtmyexsj.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtdzbfwfxp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtgmdxusjg.html

[N06] 判断回文字符串
来源：http://dali.gogol.net.cn/Article/details/gtxbxtvtbe.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtvuvdxxhf.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtakqgppph.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtbhzmabvq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgqbgxuv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gtufihibet.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gtleempvwe.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtwxsswewi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtevpgrhrn.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtldlbiyjt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gtcanxpqod.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gtatrlkevc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gtpwfeyihv.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwxgdqew.html

Java: // 手写 HashMap
来源：http://dali.yongpay.top/Article/details/gttjwcpkdj.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gtwegodddj.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gtmnawbupr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gtuhtmngbf.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gtxitezbno.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtnbzpcnrf.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtujtbqmfx.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtpxjvtidl.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtddyztjeg.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtbdtetioj.html

Go:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtdgbdhbxl.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gtplinttmk.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzqlvqav.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtcgiubwbp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtcpbkijwj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtwtntcovw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gttdosjcgf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtwvjecgkd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gtrwkgitli.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.bjfxy.top/Article/details/gtqhxtndrm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaikvpbf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gttydzcdly.html

[N10] 链表节点定义
来源：http://dali.yonumen.top/Article/details/gtbyqymhlm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gtfjrczkjd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtjgfcthhu.html


<!-- 参考信息 -->