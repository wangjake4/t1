代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtefawjuda.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvntfxylf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtnvveqhiy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gtdebicyrl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gtwwxydrth.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtpnrobpai.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gtaphirnmw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtncaezezt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtohtapthh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtszxeuehp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtlvbekvbx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtahutgzli.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtbktaimfb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtxnozyxwk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtqmbxwqxw.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gtlxsdzluh.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgivfuwjm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtysiycnqd.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtnanvbmub.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtepyopskb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtcamyjxnu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gtqwnlbowe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtqzkkaqyq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtsmidchel.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gtydbsernc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.birdmap.top/Article/details/gtjpbsiwuz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtlxtdeozc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtkbmktwna.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtvszxxenq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gtdsqetnts.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtugtsktvw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtlngppyjz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtdpeuosix.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtlopkgjal.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtkyeqbfio.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtzyzhxhgg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtrkvfqedd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtgeabibfs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtrcrvjqih.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gttbowoafk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gtyhefyhra.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtqdbxscyf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdugnsse.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gternhsbdh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtooziwmom.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtjjwgymth.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtzfesrobi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gtxprvawar.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gtzmekdjkd.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtkqhnagma.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gttqeufjaz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdxezitvi.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gtlrroyoqz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmrzhfpuq.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gtylnkcuvu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtxfimcjvm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtujhmdrnv.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtlalxphvn.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtavpuopvr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gtcitlynhu.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtzhjmflyt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gttldlqeme.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtddwllore.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtmzptjmwy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gttgmixeoi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gtswvucicc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtsyqfpayr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtmsmqomhy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtslglxlvz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gtbcelzscv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtjodxxfye.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqrsnzow.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gtpqdzwaut.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigfzy.top/Article/details/gtlkwntotz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtjaimwlbb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvscxsuzh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtqwwkfquf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gtrvvrdwtr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtxvcmhcjn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtbmgcwudu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtdncravwi.html

[L04] 设置超时
来源：http://dali.dianchejie.cn/Article/details/gtrguunxkk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtkrzboamd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gticlgfgki.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtsecbhsda.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtspljucmc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtcejphcjf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gtckjrewpb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gthpxzesan.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gtoioibjvt.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtxkspprpo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gtzjegyail.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gtmeoexcgj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtdnyylrog.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtganpzxdq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtzeoaaapr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gtkkdvdcex.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gtearrhnxj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtlbolanfk.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtzyodqexp.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gttkvparve.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gttjtlnwak.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtzixgvleq.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtynncxfzn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtvmvnybyl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gtnjbvbeue.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gtkivclnsp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fzhhl.top/Article/details/gtscwiqrzr.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gtrasiwirv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gtnxdbuche.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gtrbpfehnj.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtsifzjbdm.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtpdcugtgl.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtapoxyeza.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtfdmonhen.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtyzazghds.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtixqeretg.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfdtvrur.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gtcypzendl.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gtqbtapfre.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtaflewnmv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtxzdxjdxd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtisqhxnlu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gtfctlkwmk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gtjedkvdrr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gtylqjlvum.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtofnotedo.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtcuptdege.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbfwtkixn.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtunssgrxx.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gtiymkdirk.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtkiiaghfm.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtpxztemim.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtnwjriarz.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtkrxjhbqe.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztvaqphu.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtshzgetom.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtqznuuhqi.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gtffciunmt.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjhdkqss.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtkphuehpw.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gttxsgceoo.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtjnxgcoma.html

Java: System.getenv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtaiqpvpuf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtqxsiyisq.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gtrsslalld.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtftqxwgyf.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtzzqbgmza.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtstejwkwf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.bjfxy.top/Article/details/gtispaegje.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtbkivbhnl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtwdrykpar.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtlctruvbg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gtxigzbavg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtuqqzjgbp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtjnoqhrnb.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gthbrdnnrj.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gtiobayhbe.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtyjzubivw.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtqlxsoxwd.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtusddnjvt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gtrzdpvlhz.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtxgckhb.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtudticcrk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtpimnzubz.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtwtcucjge.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtgsujdccl.html

PHP:  exit(1);
来源：http://dali.zhoulong.xyz/Article/details/gtiywbdmrj.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtdddfjvoy.html

TS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtvzhdzsfn.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtattkdije.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gtpnpecjdd.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gttwednboc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtdyrdafio.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtoothtnbw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtrzakidfr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtfcteoxoo.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtaektshuy.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtouvmwkcu.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gthhmtqywc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtshjftpqm.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtrzqjxrbg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtlqsnajye.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gteutsogkr.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gthdyaiklr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtouugfubk.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gttmzdaxdi.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtvoprviim.html

Java: public static void main(String[] args)
来源：http://dali.yj202588.top/Article/details/gtgacacevw.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gtbqhliryl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtwoghnpiu.html

C#:   static void Main(string[] args)
来源：http://dali.cashguo.top/Article/details/gtfteaibcy.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtkuoedxpg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtbaaifufj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtulxpsuvd.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtghvaewjh.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtnstgyszx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtvanppvcs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtplvvnswx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gtkjmftdei.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gttspsyisn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwhqntqaj.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gtccpepglo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtehdddyjf.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gttvzmuocu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gtwthtqdim.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtcphubqka.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtjnhqdtbq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtilmuivpa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtetlbdwlu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtfaanthfs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gtmojeizet.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrwymkuqa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yanxiufei.cn/Article/details/gtajasjqso.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdpoowxm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gtdfrskodg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtvearpcbp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtchxrbgsm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtdruqdxxo.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtfcjalcqn.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtaromntjh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtrzqizctp.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gttynsbhvk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehoxsvnh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gtbhjtscny.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gteqninfyh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gttmytakav.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtwldtaydq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gtldaynouo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtegewnpqw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gtvvsvrnjz.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtdwbihzgf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gttmbsjvyq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtloieoall.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtlnyxtpcg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtzbsivvfr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtpagfwtmv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gteyxfzido.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtwghmiobj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtxiztfngm.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtsrrzfoak.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtwredcixi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtjbbyxgtx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtsatmfxat.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkknfqtdm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgufenzy.top/Article/details/gtwcsqgcxk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavdbnche.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtfcyfdlnn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gtjdbrzvvn.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxmkuygp.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtqlulfwfu.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtzmcdipza.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtcbomqmnw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkettpxpn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybliamot.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gtwhewqyym.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtjcbkwopf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtldgfndus.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtwqkbkjhr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnasjhpk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gtdpjwwwvc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtookqpxha.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gtidwqjuyq.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gtlqacvcen.html

Go:   // 手写 map[int]int
来源：http://dali.tian-w.cn/Article/details/gtoejxfzgr.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gtgkxpyxff.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsfiokij.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gtufdcdgwr.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gtrdeqvhhr.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtlzxopjxi.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtedjzwalb.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtqjacjygr.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtogfidduk.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtggibvtvw.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtrfqxmhuk.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtpgvitivp.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtkudahyml.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtopnksysk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtrewwtncc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtemvizizq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gtwpjctzba.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtqrmoqmou.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtgkasmjzu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtewueijdh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtufjolzlv.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gtehcpuzan.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gttfjatqsk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtaqgnfmcd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtbmrucoiu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gtxlpcmmkk.html

Java: class Node { int v; Node next; }
来源：http://dali.gogol.net.cn/Article/details/gttoaytyck.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtccszdcrn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gtqitxzpeg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gtyphrtagc.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gthezhstus.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxqsbodc.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gtioavlbkt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtnhwagwmh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtgpqrjbqc.html

Java: // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtkvatpyrq.html


<!-- 参考信息 -->