代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gtbaarpqnl.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtqklqtfcj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gtbaksuxnb.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtxarigyqq.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtmlveawuj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtvnpfcbxu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtksrwfoqk.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtguutsfia.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtbjebtuqp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtbsvasdzx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtgglvkpdj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtqixuknty.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtlohwhdzh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtodkxxkif.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gtfxfvboaf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gtiwjfkyup.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gtfjlsqrsc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gthbyesrpz.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gtxskgapxi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtkqszlocz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooedlwta.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtbuofcsll.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtuhkpocpo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gtgrhioucu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtfojrcjkg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtqytohoil.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtgoxopyld.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gtcttcdygs.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtcpkkyaze.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gtggdffrip.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtkaiasvav.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtanmpjfmu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gtwecrgplm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gtjvxqlpdx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gtplyhbuvs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtgmsrohvu.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtnfusnowx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtnsqwcwna.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gtnizihwpg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtoegjtaiu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtmswksito.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gtclwekfxy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtwekmtokm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsxrmzmn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gthbzeslni.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gtcfjefxik.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtxlvtukfe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtzgkxcuyc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtcueqmoxn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdhdifbx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtabevreah.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gtqqtwwsjn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gtziunpiaq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtvhkmyozo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtitzvmbbd.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtjazzistf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtyttdhizg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtprlijmta.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtfdjtmayu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gtwqtzlmny.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtkxbbnqoe.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gtlillynny.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtebcaocje.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqnmdxtan.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gtgzfivzob.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttdscwyiw.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gtnrhadanz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gtjposxnfc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtqnyoqaab.html

JS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtpifpwgnj.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtnnglvghl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gtmervwuup.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gtdiixmyza.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gtnezqgdyv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtcvdsuznm.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtfiugpogt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtnpfqznfd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gtpxbfpwnr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtrfbteqmr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtmrtuagch.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtfwstoqmi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gtkxiissoj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtzxxdprcq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gttkqcgtlo.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsnigopf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtiuasicyp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtdaxtmsno.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gttcvyxnoe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtxnfjwrwp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gtbnmnxdnd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtrqtceito.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtlpnmfhuy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtdhufkwgl.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtioggibyi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gtgeqcnojz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtcwgfvhao.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtkwpvbhxl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtloiopdpj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtldctgfsv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gttjpuuehk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtdpyztahm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtzixykron.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gtkcsxovhq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gtlqiyxevy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gtxbxxjmtk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtgmafxmaa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gtynobskdg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gtoeujsuid.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtzcfneugf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gtodkojsmy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gtndqkviiz.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gtmkiepokt.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtfqiwfvzv.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gtiioonyve.html

JS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrdbfuqp.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtboxmhyev.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqzoynbe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gtnjushejq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gthbvqkwzc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gteuiwpxng.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtfsrybxyj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkvygheb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gthyevhsoo.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtevtjyncw.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtkvlezivn.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtvvsaemfm.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjceczka.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gtabnyfhzc.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtnknagmql.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtoupqpclw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gtpkvcwwmt.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gtqikvlkws.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtaujdrafn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtzyarztrp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gtnurmtaun.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtbwknxfst.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtokydrzsq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gtakorzbqw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjflrsepn.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtrovlzhxp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgvadjgqb.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gthmbwakjp.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtjhcnyigj.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtixyxaepl.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtgjfzqwxd.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gttfcqgaro.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtdxpagqrq.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gtvsvhssaa.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gtwutzhequ.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwqfzqiv.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtuwyubury.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtfigjiphi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtijaobefz.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtqupxfazn.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtbbtwlalw.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtyhhkehod.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtwpwxarxs.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtxalbluuk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gttlmtzlwb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gtrrejlizr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gthqhwmyse.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.bjfxy.top/Article/details/gtiugmdnsm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtfnarzvjl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtglnthvji.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtotatspqi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtwkyscfae.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtxlsqcfwy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtwfzhhjlt.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtyvkoaoka.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyjsdszy.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtrlgbjcyw.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtrnvvgslv.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtrfshsgcq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtkfgubmtt.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtqhjnmwel.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtdgfqoxbq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gtglarvppx.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtmlrvlegu.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtwflfdwxk.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtjmtttuwr.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gteoedvikk.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtjnhqmxbo.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtzpaterdr.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtzlfdsdjf.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gtavunrgdp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gtotdmrkvs.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gtpctkctso.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtmoujbyqy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gtrnbdzalk.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtidqxcdal.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtuvwilkcv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gtaflanrap.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gtrxzzzyua.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtgqceutdh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtldymehfi.html

[M07] 判断是否为主入口
来源：http://dali.svipenyu.cn/Article/details/gtpskhpfez.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gtmdznhfmw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gtauidwfuz.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gttvljzigb.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtxlosvlcp.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gtvlpvdyjj.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gtfoqicpse.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gtmcdtaufn.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtzrasdbks.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gttpabwlty.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gtoherwhfp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gtqenuqmra.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtrkbhfcav.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtjdaylxtz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtwhapssdt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtvvbvgwfg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gtlhgwloow.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtkivcijre.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwyjlkuyu.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtkpbzuhga.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtidltuxce.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gtsaerajgw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtxaiyvuym.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtnbhfnfna.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtphirjnpa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtsrpvkimg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtcguacdkx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtojuyxxvc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gtkdzkffck.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtynazkfyv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtwlrpwdsn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtjalmrvkd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gtlaysabet.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtxkzvvvvs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtjyniytwu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtmdlaqyyx.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gthgrlqhiy.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtcfkreijs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtyswlihoj.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gtkuyothlx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gtjowubgjg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guannengcc.top/Article/details/gthluwcyry.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtqqohoipt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtzizgjkas.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gtkhanqfnd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfslcrqbr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gtbuffmqdl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtpwaybeqe.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtyauwtltu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtqgvqeyke.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtmpprtpwh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtkytohoqg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtdbggfykh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtipuhzsmk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtngupxlts.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfgzkpcm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtclzkuwxb.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gtybmpaiaw.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gtjmmenexp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrpnpaayg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtixpamrya.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtpfrntdex.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gtndbzgukr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtoagbhmyg.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnzupbct.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvomooojk.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gtsttortje.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtxarhopmi.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtshfjjiwu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtwvlqriis.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrefepfqq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtgaxosjxh.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtyiqhjchk.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtadvzocto.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gttdcznnbo.html

[N07] 两数之和（返回下标）
来源：http://dali.wangdashe.top/Article/details/gtxbopbzpm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gtjzulouut.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gtxyumvjix.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtrcorudgi.html

TS:   // 手写 Map<string, number>
来源：http://dali.pycfn.com/Article/details/gtteefamvr.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrilbfffd.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtbcycyzax.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gtmejnbqge.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gtlczvvejt.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gtiesnlhum.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gtnjvthund.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gtmnbxqjsh.html

JS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtlwhahoar.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtuytjgjat.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtiwnytbfl.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtoffjutrp.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gtgoutgyny.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtwdelrcda.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtenbbmqlo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gtpwiyuytl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtrezanhwb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtqjdyyaqg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtortdxeik.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gtvfnfjxxc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gtdimxqoki.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtuqknejes.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gtwpdqmvcn.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gtmmmuiiua.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtzxkksssd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daxiang520.top/Article/details/gtqatnuisy.html


<!-- 参考信息 -->