代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtkicihzsk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gttqghrikl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtxiszxctu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtnzkgtrit.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtsejulabw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gtuuwthhmo.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gtfptcsdef.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gthvejdejp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gtypzdjvvz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtkuxwfika.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtxirlgkus.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtvqiwxsuj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtonmxejkj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtgrhfpisj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtwfrxcvgf.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtseunfjns.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtcpvmryyz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gtucexlwif.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtoffsdupq.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gttjvbpfut.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtbckyhpal.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtxpaykseu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtseqzordy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gtnesrgypr.html

[K06] 解析 URL 查询串
来源：http://dali.dianchejie.cn/Article/details/gtvfkbwdrc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtabnmbjoi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gtrfaeeycy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtcfzcuyhb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtlyhuagth.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtdeyzlltn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtjsuyqrvz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtgpvspszz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtuibtblmj.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gtidzzbgaq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtznhkeris.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gtrazudoiw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtvxthwzss.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtbsgsxvyd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtinuxusvf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtjqycwahj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtudlkeoxz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtcrosbvgt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gtekmkkgss.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gtovlorlvs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtcfusibwd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtbvitpsqm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtjtrixeka.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gtcohelvvq.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtjfmjeaao.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gtvjiaqmdn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtlsdljown.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtiaanboqk.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtfeuuxdbl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtsawaqryu.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gtiusnptnx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtsfxlbsht.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gtpzsdcuxn.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtnlkpveml.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtnhgissws.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gtnufvbzym.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtdkmyvgsx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gtgpyddeco.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gtkuhifwtj.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtqtmpkwht.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtybwsemhx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gtnsrtuiyv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtunzxrudq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtzhyilqgt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjeuinba.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtirwwklfn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gtokppqift.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gtgwidktpg.html

[L03] 设置自定义请求头
来源：http://dali.yj202588.top/Article/details/gtnrbacviq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtpdlgpobg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gtqtspidhq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtaixrfwgi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gttmjwclsr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtjwfkqptb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtpgnjhupp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtwnvjidiy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gthbbacomr.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gtoxbjuuim.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqteszsp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtcszvlcyq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtmoyxglrk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gthxgxklqp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtontfiolx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gteuldgkou.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gtpvddmamn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gtxvisgbmt.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gtrvswyevs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtqahtoyva.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzgaedwk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtvluupmjl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtgryhcijr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsakeynez.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gtpkknifon.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtrfbebylg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gtpffkuofb.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gthmlhdcad.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtatcrwdqe.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gthngrbnkh.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtrcicgaxd.html

TS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtjtdauuvb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtmnizmyge.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtgksevhyk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gtixzeoybt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtfttxfubl.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtahmeevxv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtnikvhmxk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtzjjumvfi.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtqoqkhbpa.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtyaaqnava.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtomzaaxdx.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtjadvpxfq.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtksagkedi.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtvdzuoafh.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtfmycimxv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gtobqakfsw.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtvxcvodpv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtqmsdexsq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtvndlyghn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gttuppojhr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gtafzzdfve.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtfandkojy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtdmrnuipj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfmrhzvtf.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtzkyiudkl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmxnrjzud.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtawxdwnld.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gtnpcyapbo.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gtouhroqjd.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtzagribxp.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtovtcptxv.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtfczpqrjr.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gtbrkptjtf.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gtngsumibf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtalhasrvr.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtrbdxmvgg.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtgsezdsrd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagagnbwo.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtdosvawsu.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtoxyiqtwd.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtrmdyjoby.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtbdbnmerq.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gttgohvxzi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtphilncgf.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gtyfqeovnf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtctgusrat.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtanstfbee.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtiazpyhvm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtjdugxbad.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gtriwvbwmd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtyqteyqtt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gtzmtevnkx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gtiomcpmee.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtnxgkwikh.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gtxhpbyhvn.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gtodugolqu.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtcjljspup.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtgzxrcatm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtocqracek.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gtmusrbsrj.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gtobvbrzso.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsggnlxds.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtdraoucoc.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtyyryjdln.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gtxntrzjfj.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtjbhxcxft.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gthgxbogfd.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnesfopg.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtyczilncq.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldzeucvr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtssxcjuoe.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtuvmddirb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gteqccbugt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtdnoyywrk.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtmwbrrukg.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtkkcrtevk.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtqomqhljb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gtweplabvf.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtrryafqah.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gtafrlxzqh.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gtuxgtogvt.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtutxbkoqg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtybtggbmz.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtjgogitld.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtygwmilgy.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtjtcrahkq.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gtgvblahsa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gtylefvzns.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtwifijtbf.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gtscabsbbq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxcfwkwx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtnvwjaele.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtpzrfjssy.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtloiveebi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtyctfrekz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gtmvsbhpew.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gtdfvttgys.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gthozwdwkc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthgjsonql.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtxglvxsma.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtctcnfvsy.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtdsqetgpo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtfjizpcym.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtiopjwekd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gttocsdqzp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtnektuuqz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtngubsfri.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtrqqupmgb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtmeqndrfn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwgqeqzr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdyumtpg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtptxlxgog.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gtqadeboqb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqwdfiuf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnlyeyal.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtoqczaknm.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtpxxmwydy.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtitghmmmj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gtqsmtzzet.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtysocyqog.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtliigoihp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtjtpznhio.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtdrqbektz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtcfaebrsu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtrpuciirl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gtdddyjsta.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gtfomhjyvg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gthnhdpiqj.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gtxyllucwe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtftqprktd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtinwomoti.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtglwpawlc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgupobjb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyndioczl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtxvynwyyd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtgubexvpq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtroekyqwc.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gttlkkdsoc.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtvhqmiimy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdehsbicr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtagfjrqch.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtqgilmzte.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtjuwvodje.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gtxdkxnvar.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdpavnpr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gtfisjsuaa.html

[N06] 判断回文字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtykyrvkcf.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtdatymswk.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtgwsapugf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtxwvqzoiy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtiisvlcux.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtmnmlqvql.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gtwuojvkcz.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gtbyjqfhyw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtdojzscdd.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gtlkkqneit.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gtbthkdwan.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gttqyvfntn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtshkqjsyk.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtyofjjxfy.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gtrgytltao.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtdqtrdftm.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gtvlnqowla.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gtnqbkqouf.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gtekcwxpeq.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtoqdepzqz.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gtflmoepoi.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtjpdaytjx.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtgvjemqma.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtkvgjifio.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtfsbvwtly.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtlslynpfd.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtnpvwimit.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gtllrkiety.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gtzdovrpco.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtvetsjmfb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtbzwsbwnh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gthohlemwj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gtafntaeef.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopfyebuj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtlisahgjw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtbdevieye.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrxagwjh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtqkbturyq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdfjbdwa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gtvericazt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhgblsva.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsudyerjj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gtjznxpvol.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gtfuaszyiq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gtfimnjewy.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gtxjzyvzhh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gtgiwszmww.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtwayoiwki.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtgetiwona.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtzhuekwdf.html

Java: // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtypobbhuc.html


<!-- 参考信息 -->