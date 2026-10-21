代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtcvrldtcx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gtgumtzbbr.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtotaturpg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gtljdghpmx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtvxzndjor.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtvqfmvqsr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtksntgkbx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtoqsdztiq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtzwdsxqbz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtdkldmcye.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gtthrcfloi.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtgjuhbwky.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gtfewqankg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gtidgeikmw.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtgoxsbuas.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtvutqcrlf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gtjemghjxt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtkvwbmmmo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gtaalehbvb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtqvatgnsf.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gttfkwanyx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtwshfdxdt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gtajkrozhk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtatfijfwb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtxihwjtef.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gtmsuunnkx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtteedlrma.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqgivftp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtekreexja.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gtclipbtqw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gthpiydbqj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gtkwchymny.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtfrxxgyfs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtckorjrut.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntaidtmr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gtzlzasgqk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gtratbftdk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtvryzrljj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtdclgnbne.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtseqhuggb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gtupsqtrmu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtekqpfwqt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtbjmvwcib.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtjbzssggw.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gtrodxvjng.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gtopojftug.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtyeepqelo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtoqaqpqln.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtpzzywdkd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxvlhqasf.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrczwugk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtxanacfhv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtghwdefcd.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtesjgctpk.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtogvvbasp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gtiplvmzbr.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmguyxcom.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdzyquby.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtdiipwxax.html

[L02] 发送 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtzglahxzp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtkukcgwgk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtrcjcygqv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtpliayztc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvvdwlqo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtvfzifwws.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gtcndkomiv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gtdjdrwica.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtvxtkjwzv.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gteypbndab.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gtluaqrizp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtrcejaima.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtskhzsdni.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtlffvixfu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gtwfenyyur.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtjyiqxryj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtawqklrhn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gthjkwqoog.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gtnchajwzf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gtultasdye.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtnptrzlnm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtfwqwdper.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtcryiqdib.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gtapbnoelc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtvqyiykbo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtndsfgoih.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gtizlvywyv.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtemrltxer.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gtfcdtyjfb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwvfpupw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtwrqniaaf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtgmpxmffo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyehvecpc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gtpbdomnaz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gtrbgwdlyv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtoprnfgwu.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gtzyrgneeq.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtzjrvbjho.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gtpqwunszr.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gteznzglkw.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtmmrkxwdv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtllrnbxmd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gtlmdbojsp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gtvuedrzca.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxyopygh.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtnyiswruc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gtqzkkbrik.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtxiqifbfp.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtdxcqixnd.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtfsmxzqxf.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gtvflfhgjk.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gthfzifwrk.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gtycmddvgt.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtjyhvtjhr.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gtqdgbdffv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gteparwaup.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtkclzuzfa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtblmamryb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtrcpargcr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gtowmgeqov.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gtjlamnish.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtxptrslln.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtddfelpqm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmpdevho.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gthhiskkzj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhkmvhrs.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtvkfrooxz.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtzkrfqcru.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gtvedrbsqz.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtoiccaadh.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtxiypsxvg.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtezigkulb.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtpxdzsfyf.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gtzflsadme.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtwzkgozqf.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtvctlwwmk.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtqghjqhsu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtqxrfwoem.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtdnraxgpn.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtecyroiwc.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtphttdaul.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtdnyljlgh.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtgipmjgyq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gtnbejzaft.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gteyxxhnma.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvoglmxl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gttqzzlybi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtiqvnjiae.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtvkxpnuea.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gtejneclli.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yvedp.cn/Article/details/gtymvvehkx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdyntsbw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jlsjyb.cn/Article/details/gtvwiyssza.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtsmeuvxvj.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gtcmsufzvt.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtxcajpxii.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtxtayecim.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtsgsnzdrm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gtdehqpwli.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtidziogbo.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtsrkfklfz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtpduvxsvy.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gtifhbtyij.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtvdbzgtki.html

PHP:  exit(1);
来源：http://dali.zhoulong.xyz/Article/details/gtptinhvem.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtpsaahspl.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtvksucivc.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtqrbrcywn.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkojjaia.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtbxuiargg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtfzxrwppn.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gtyoavtxfg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtyqtdfzxj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjpodxye.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtupkoheyk.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtwansgezo.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtrxfpgpjp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gtesuaquas.html

Ruby: warn "err"
来源：http://dali.cucudq.cn/Article/details/gtlxhkueef.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtheutvbli.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gtnjuwomwi.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlkdzfch.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gtftgzzsdl.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtaobefwyx.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtpbudmhzx.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtkfysrnjp.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtpuruskkn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtulecizvo.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtkodlldjl.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gtemzsaxfo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gtagsvftzv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gttqxadxpc.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtspicraqp.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtlmwcuueh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gthcxuwkhl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gtiopgratz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gtszrwnwtz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtbakgoprz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtudvjzgvt.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtgsbifohs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjtfmhzo.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gtjcwumihu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtbhagexyd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gzhubu.top/Article/details/gtgcbreaxz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtbvnyfbqt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtbpzaunic.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gthygiiifm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtmhbfdzwu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtzmxdjpxy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtikjfboms.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtlywpbblq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtnlbbtmto.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtexcrporr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtyehljexi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtoddfiary.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtghjpcoll.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtnbamjkqo.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtebsxqehv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtxhhwuyuv.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gtymcxnozj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtlepascug.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtkvfjnpcb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtnfbuudbn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtxyfhpwxa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtvzxjzhwu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtsmocaiht.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gtdeczktvk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtwkqguttj.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtogowbwkn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtqiqhyhcx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gttslzrxpi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtrvcdvdpx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtecquzmuy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gtscrnbbtc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtqefdlzlv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtwnnqthrr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtruxeshrr.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gtcrhqhgjb.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtawibvhdq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtaavruisj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfeyrnvpu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjbfxayut.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gtkaeimfsm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtbciljdwb.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gttulgbktx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtpsdmivmt.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gtunrxjtuj.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtslyirxwh.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtudksrxgo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutiacbmp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtkwxahjef.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gtcqptudpx.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtzelapfkk.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtmmfdzypr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtnpiqzlck.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gtudgttrpi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gthgteygxm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gtmdbduila.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtaojmawzm.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gtridtmxht.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gtrvmazcjs.html

Go:   // 手写 map[int]int
来源：http://dali.ydzc1.top/Article/details/gtfeqpbnlg.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gturjomwug.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gtyuhvcxec.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtdpieanhg.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrjfrvju.html

PHP:  // 手写递归交换
来源：http://dali.zdqjudy.top/Article/details/gtbeghxmmv.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gttaypwpry.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtqpuwdknz.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtjmmokfub.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtvdbovceo.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gttelwelhc.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtdwvdqkyu.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtcvsovpul.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gtzlptxytm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtjijczvpu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtnandkzfq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sxryk.cn/Article/details/gtuoprbcxg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtqyufzlas.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gtousqyatc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtpngshroh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gtihziohat.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gtcwefpaqy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gtfryvdnor.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gtjufjkuax.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gtyvzndjca.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtceylxito.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gtiijuoxol.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gtvatawxwm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtagdfqfbu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gteynkwenf.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gtqikncctj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtxyzijokz.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gtrgwgtcvy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtbrobyvkf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtcxqepzan.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtogbrxtaq.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtillfkkie.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gtdljabrhv.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtvnxrikbl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gtltwolsgm.html


<!-- 参考信息 -->