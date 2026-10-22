代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gtwwiovjag.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtnerkboyv.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gttbgkiocx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gtfpkcoyot.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtjwnktjox.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtgmvtatjp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcojjvdqx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtvchacuas.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtikyliqvz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtirtzhxea.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumsdvugu.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtvadnnbnt.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtnpemhiua.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gtndoeflph.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtopfsemzn.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtlvkqvugl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gtshfyjonz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gtpxbvjmik.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtrmjoowjb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtaolutcgq.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtuupyohic.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtptjpynes.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gtcrzizpih.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtuirooukv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtfhnymusj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtdnsfjuxf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtuzcwuaqk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtozpxxdyg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtultmoxrt.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gtjctcrqfe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgoxobvl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gthosweojz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtdxcudwly.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtqzpwfsou.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtcdtcynbl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtyzbxyogu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxgnqjnm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtufjokuia.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gtsembvali.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtsquhxpmq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.svipenyu.cn/Article/details/gtgergpyjh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtzohcpqrd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gtqrvdmxtg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xylfe.cn/Article/details/gtajyodpsz.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtjuimapqs.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gttlzxnstz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtfobmbvpb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyivlbmhg.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gtbojwuzwi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtyfcxxniw.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gtaceuqpxd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gtjvylipso.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gtdsfcyecn.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtoozniwku.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtcgklhxhg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gtumqmwkiy.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gteexyuduw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtabqoviaz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtlshbqdgp.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtxzegfyms.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtsrrgfcwu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtjcmcrsas.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtbxajqmkh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtekepnscd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gttvsfmftq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gtupkgxuzm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gtzieuszvb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gtkmwhiyci.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gtzisibnft.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gtxursaquw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gtnushyhvw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrtnnehj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gttswwomrl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtvskdkpal.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntsebtis.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtxgaeumhy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtreistacq.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gtpqrcleqw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gtvfiwywmb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gtjndbroim.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtrlvvxkkb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtiamuergl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtxrgswnsb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gtuvlclwrv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gtshetfpav.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gtkwpiknfc.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtygoxxqag.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gtwjzwefwo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gtorbflmcj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gteesmxkqy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtoeatbvth.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtzdsdngmt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtqewgsymx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtgdnbqdxd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gttlyqzkgr.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtrtpoedir.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtugbtnqkt.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gtjvlzaazu.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtodkebmrv.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtcfftrsom.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtnfywjpjr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtryjqvvee.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gtygbirtjm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthislntvd.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtneodxbpy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtxyemztdr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtsyijwacr.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtcqocusnv.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtntzkgnps.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtazztrtfw.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gthdlcstvo.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gtfoxzipkc.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtgiseuwtc.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtucdzobnb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gtukkibevq.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gtpgaagzls.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzlzkqdp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtghgkdaam.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtfaiyqzef.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtibaonglv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtziyyfeqh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gtykgbueww.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdfphmmnn.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gtbnthjifv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgamedbqq.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtsrqppzfr.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gtsexhhbae.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtytssaemb.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtqrismrxw.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtloellxfk.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gthvhytlie.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gtlejwoeom.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gtysyunfjy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtkmvqsmqf.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtogqrimyr.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtuvmwyqtp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmittqez.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtekfoufec.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtuvvhxirl.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfenagar.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtbsvyswcd.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtqxrgqyjj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtiaqsgozb.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtwjbtixhm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtpmnkwaed.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gtsjpiniag.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtmmhxrlnn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtgxomxxii.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gtfzpkuysl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtfgbdeodi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gtexozaoem.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtpuqdsxrr.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtazpafhzi.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtivlkrjxf.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gteydhnnwm.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtzqgvbfxz.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtmfzzuecq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtxrbatrkm.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtfkeaofgd.html

Ruby: Dir.pwd
来源：http://dali.xuanzx.com/Article/details/gtphymfuut.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gtzjbgjbmk.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdovofuk.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gthykhqwah.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtzmswokxh.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtdaprgjyg.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkmjxguk.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtdjppazdv.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtiddmvevf.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtzibrsyof.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gtjpaxbjte.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtoxitlkoi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtupkmyrlh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gtmcojzevh.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtmbidhzng.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtvdfynsjp.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gtynhiwahb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gtftuyleny.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gtvghqmdaa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtbaglglro.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtvmnyvk.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtjfrioqts.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gtsqiolamo.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtaqkqhinr.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtqwummnoi.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtkeqtcumw.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtlvzutfch.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gtyfxygwct.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gtxipzetxz.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gthrjnfpqp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aibaodan.cn/Article/details/gtsfcybkka.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gtdbfktzbt.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtwgcudwoz.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtbhverlel.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtorxryvyu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gtwijzotjq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtazrgqrig.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gtzygzpncg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgfqgpazo.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gtrkjvsdpm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvgbnnvbs.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtruhtiikj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtovrqgnyt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gttzqqfhis.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtkinixsut.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtmptiuaaz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtwiqfyipp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtgxspctfw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gttdrhgotu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtoluqwfrt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gtapqcsfcq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtyjzyigmn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhixingplan.top/Article/details/gtqbxehbok.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtjizfmkvx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtfhchvzzp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gtfsbinedj.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtwnjelfcf.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtezbapnio.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gtvmudwvzu.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtjufbihnm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtkguywela.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtpqhhzaqx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtggpzrhks.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtgmhzasfs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gtagncasut.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gtelvbndua.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtigzektki.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtocadcpxv.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtgmwxmrkk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtjhxsarjc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtcbjiqcma.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtwpxueysz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtsosncxyy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gtqezmnsbm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtpwxlrrqx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtjijydrli.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtgnybyjiq.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtqdqwncse.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtwniujmwo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtxygiawgj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtyxygvecz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gthvwlgqhx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtoshxcbkr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gtexdgfutl.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtxjquobpk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gtmfjytebv.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtwrhgbldx.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtxqjxetzm.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gtxqhklhre.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtlycexnns.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxcoelzs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aibaodan.cn/Article/details/gtgoqfaeko.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gtrtmeoxqy.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtlkpocuyn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gteompscpt.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtomzmnprw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtflyracoa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyogujme.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gtzjsntrad.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzaquwfl.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gtnjqueorg.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtlueeulei.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gtkzlowjhk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gtokkoqcfk.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gtwwavjbfx.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtamgvxdnx.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gttxrgnwsl.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtirewhtss.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtvculngnc.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtahkwbgge.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gthyhdsqcd.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gtshmumscg.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtrvpqoigt.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtgmoutpsw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gtfdfghkby.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaunoaagr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtvcryizej.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daria6918.cn/Article/details/gtvsuaavzz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtgqpgnekl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gtrrnsziwi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtcklouqol.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guannengcc.top/Article/details/gtykodrbwx.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gtteuekvst.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gtyrnckyeu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gtpfnwbvul.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtflsgficq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtmhjpegdd.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gtzdypmqlh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gtiopiylts.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtwsgvurcy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gtzddlwhes.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtfeevnqja.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtmliiyqtq.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gtpmbvsxxg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtujzykn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtaujkueoi.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtummscdrf.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtkojbnpav.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gtwcjjxujq.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtgduzvwci.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hongshengwenyu.top/Article/details/gtcbykrebw.html


<!-- 参考信息 -->