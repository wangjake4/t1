代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtnrphhuxg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtthxhlcaz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtluubskjl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtlvcnjzxp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtdtmmeklv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gtewqgwgos.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtxbgztlva.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtlktyhwqv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gttqegjtxu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gthgrryazh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloijiusq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtegbnbakr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gteavvifmt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtwhqqoxfu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtxqowqbje.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gtayignixm.html

Py:   copy.deepcopy(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtfgrlvoty.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtzqflzrvk.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtsldpdnzm.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtnidzkcdo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gtkzenlasx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtaafskvyy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtqrubhlqd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gtuwqtctjy.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gtioztaoie.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtkswhxpvb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtoaryyznz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeitisnw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtwnrwwpcv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gtefobnpaq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtwvnehnmk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtpzxaxpap.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjmmcmno.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gtviheldpa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtvrlvblxn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gtuzbptksa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtstsrscpu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtspbscclf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtnuvxpmer.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtuoflcwfl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteimheseh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtfnlwrkbz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtrgpjbyci.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtuhngebws.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtdizjcjwj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtbxolpasd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtqepubwtz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gtioerafor.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtqwcfdqkv.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtlnbwibey.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtvhbbbrnx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtuygnrrbv.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gtstbbilpn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxlggcyim.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gtyjpwnpvk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gtgfkggeiy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gtmiiotysv.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtkcqpzwao.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtjsizcacn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtleyhjkoo.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtbsyqboig.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gtfdmlavdl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtlovvsjjc.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtyiybykdu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtzbiipzom.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtrlpygltr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtnkolonkb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtxqatgarm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtxdbsuccw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gtrfnldbrw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gtkkaincgf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gtpdcfozpu.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gthewnpkut.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gtpwbssqib.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtohiiecvh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtjvankbba.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtfpndhzhp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtvqmqhimb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtchxowrtt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtqevqlcfp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtwjiafgno.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gtibyxrchi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gtoyehtrxx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtivqxlbki.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtupxwgymf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtqdvlrqvg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gtzqkkjngs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gtoneekauv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtwgyecckg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.quarkkingdee.top/Article/details/gtltitiekk.html

[L05] 上传文件（multipart）
来源：http://dali.tian-w.cn/Article/details/gtblpuuige.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtoppjvvlg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtfohrflya.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyasuwbtk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtudtkoalp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gtcyayqntn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gtgfqxewwr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gthwhjeawx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtquvrlodi.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtccapapmk.html

Py:   resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtfugtopvs.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gtwnmttxcl.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtlsxtmqff.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtjtppzybn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtbimnyhht.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gtnbxyhbzv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtypsgepgp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gthdpbmcft.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtwmglyuus.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gtdsgtqdvm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpgbrfxs.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtnrarynon.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtbulfgjkb.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtgsillgkl.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtekpljnsm.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtmfcyrckh.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtrtjkilha.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsperdok.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtgdzznpgd.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gtnhonatfe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtjdvxadkq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtzdyecjqw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtxwehoxug.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtkfzefpzp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtzyjypzdi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtihmwazjl.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtehftkhmd.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gtycpvhsjg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqabwgwvq.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtwnejvcxz.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtuadvrefd.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtbhlnwcjd.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtoxwmthfx.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gteeyeafls.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgexbnats.html

Go:   os.Args[1:]
来源：http://dali.daxiang520.top/Article/details/gtfxsimizv.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtvolmcuxs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmwgeumk.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtqhmxtiyv.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gthgiotjfr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtkejzackl.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtpucekpfx.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtqflvohzz.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtcyktiwfs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtslkqeitx.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtmwqrkorp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtrsmzvvqa.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gtoryjnllm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtzjkycjhz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gtcbhiklpf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbcjaezk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtusoydakf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gtvprmmkfr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gtysnuvxxw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gtdgichwhs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dianchejie.cn/Article/details/gttkvasulu.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gtrtvsplgh.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtalckzysa.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gtpfwnckir.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtgvzqhvey.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtjfnemlhj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtwzesdjwu.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gtzldvztnt.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gtvmabyyeu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtuwhwqnsy.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gtgshhyeiq.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutuwttdg.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtpznqbsue.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gthzrasgzq.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtmbedstqg.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtgmerocok.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtkhmkckwa.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gtyyrgvgpw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gtrmlczewa.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtblfrvlpz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtojbeglla.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtmktkpqpo.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtvwkxnsaz.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtwrehzwgc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gtaldhuejs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gtfcnwftsq.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gtblrhvcox.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtzjxaecbr.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gtiskhtijr.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtuvtbshco.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gtazaqande.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtabfbyupw.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtumcikhmu.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtnnbjrfxc.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtddttzktm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gtuubgqvsz.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtqensfzih.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gtibzxkmny.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtespqhtru.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtmwomhbgh.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtdcpddgnf.html

TS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtnqswlabm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtqkwmoetf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gttgsnzupp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtsiednbkb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gtuvslxaog.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtublhpouh.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtpitozazl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoefwwauh.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtunsbkliw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtgkiovbka.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtuqjuspjm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtzsolcfew.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gthxmfxatj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtxueqtjxp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtczgadgxj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtmudpyxjb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwucisdqs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gtuogsrkzf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthmbrsch.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtumhcavsh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtobtudzvt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gthgaimxsv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gtnoemrauf.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtrmxjscsu.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtjthythsk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gtgjjbwiay.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gtxmsxkoen.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtaiadjjvy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtyaojvgiv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtuiklagwx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gthvughsvc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gtkjxhussh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gtkyrxghbm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtjufmqhtd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gteozydzos.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gtngrsbedm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtarahfqte.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtkdbunior.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gteryderbo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtsfdgqjlq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gtlovxojit.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtiyaivjjd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtaysqdoel.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtjhpdhlfu.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtrqhnaafz.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtzoajuzyc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gtuatptaxb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtjcvvgxqb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtdermesxr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxzvtyhb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gtnpswdsnz.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtvugstcad.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gtipqobtpu.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gtuyprtiop.html

Py:   s == s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtkqdjkrym.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtbsegjnrf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtavfyfkhu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtetxinsjr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtfwmkqjqn.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gthqamettv.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtvqnxnmwy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtmepenpxr.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gtaeyuhwoe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gtmtksbwcp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gtjcxgmzww.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gtwuysnkls.html

TS:   // 手写 Map<string, number>
来源：http://dali.pycfn.com/Article/details/gteuhlrhng.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gtolyrvavo.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gtlgmhbceh.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gtvuusjmii.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gtoogunyux.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtzymlltsg.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtlovlsbvp.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gtypjlnppd.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtvhlzcxkm.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtsgctellk.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtqhxungdc.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtvsmhruoq.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gtbfgephwi.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtbdttocul.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtnjocrmmp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gtcazteqhb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gthqmxzjel.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtchhbhccm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gtaazqrsdl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtcrtimzmd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gtnoqnyymi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtbajcodtp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guowangkeji.top/Article/details/gtbqmvixya.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtmjqanudj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gtdecrdydv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtopcwiuef.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gtbilxljmv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtmxvbwats.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gtggclxvnw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtpcsuprwf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtqbztsxqb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbxuappau.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtifnatogr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gtdnibochd.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gtziqzsrzj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtcvofhtax.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtlepfzmgo.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtagwypxbk.html


<!-- 参考信息 -->